# XỬ LÝ ẢNH TỪ VIDEO ĐỂ PHÁT HIỆN TÌNH HUỐNG VIỆT VỊ TRONG BÓNG ĐÁ

## I. Giới thiệu
Đề tài "Xử lí ảnh từ video phát hiện tình huống việt vị trong bóng đá" nhằm mục đích tìm hiểu về cách sử dụng ngôn ngữ Python, thư viện opencv và công cụ YOLO. Từ đó phát hiện các vật thể, người hoặc các tình huống cụ thể.
### 1.1 Dữ liệu
Đề tài sử dụng các hình ảnh được lấy từ trận "Việt Nam - Trung Quốc | Vòng loại World Cup 2022"
### 1.2 Công cụ
Đề tài sử dụng:
- Python IDE: Pycharm
- Công cụ Train và Detect: [Yolov8](https://github.com/ultralytics/ultralytics.git).
- Môi trường Train dữ liệu [Google Colaboratory](https://colab.research.google.com/).
## II. Custom data training
### 2.1 Chuẩn bị dữ liệu
Snapshot các hình ảnh từ video, đổi tên các ảnh theo thứ tự nhất định. Sau đó, truy cập trang web [Make Sense AI](https://www.makesense.ai/) upload hình ảnh và tiến hành gắn các label vào ảnh. Tải file sau khi gắn label. File dữ liệu mẫu: `Sample_data`.
