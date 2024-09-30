## The application about recognizing emotions through videos, images and voice

1. Folder stucture
emotion_recognition_app/
│
├── data/                  # Dữ liệu mẫu và mô hình
│   ├── images/            # Ảnh mẫu để thử nghiệm
│   ├── videos/            # Video mẫu để thử nghiệm
│   ├── audio/             # Audio mẫu để thử nghiệm
│   └── models/            # Lưu trữ các mô hình đã train
│
├── notebooks/             # Các notebook Jupyter để thử nghiệm và phân tích mô hình
│   └── emotion_detection.ipynb
│
├── src/                   # Thư mục chứa code chính của ứng dụng
│   ├── gui/               # Giao diện người dùng (Tkinter, PyQt, v.v.)
│   │   ├── main_window.py # Mã giao diện chính
│   │   └── ...
│   ├── processing/        # Xử lý hình ảnh, video, giọng nói
│   │   ├── video_processor.py  # Xử lý video
│   │   ├── image_processor.py  # Xử lý hình ảnh
│   │   └── audio_processor.py  # Xử lý giọng nói
│   ├── models/            # Mã liên quan đến mô hình deep learning
│   │   ├── image_model.py  # Mô hình nhận diện cảm xúc qua hình ảnh
│   │   ├── video_model.py  # Mô hình nhận diện cảm xúc qua video
│   │   └── audio_model.py  # Mô hình nhận diện cảm xúc qua giọng nói
│   ├── utils/             # Các hàm tiện ích chung
│   │   ├── file_loader.py  # Hàm load dữ liệu
│   │   └── ...
│   └── main.py            # Chạy ứng dụng chính
│
├── requirements.txt       # Liệt kê các thư viện cần thiết
├── README.md              # Hướng dẫn sử dụng
└── setup.py               # File cài đặt nếu cần
