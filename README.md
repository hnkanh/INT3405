# INT3405 - Sentiment Analysis Problem
**Group:** K65CACLC-Gojo
## Overview
**Bài toán:** *Từ nhận xét của người dùng, dự đoán xếp hạng của họ dành cho sản phẩm.*

Từ tập dữ liệu, bài toán được đưa về bài toán *Phân loại văn bản*. Ý tưởng chính để giải quyết bài toán:
![This is an image](https://github.com/hnkanh/INT3405/blob/d0440d2170b8b1d1190b372f68f3f97be4800ecd/text_classification.png)
## Dataset
- Dữ liệu được lấy từ đánh giá của người dùng trên Foody, lưu dưới dạng file .csv, gồm các trường:
  + RevID: ID của đánh giá.
  + UserID: ID của người dùng.
  + Comment: Nhận xét của người dùng.
  + image_urls: Địa chỉ URL của hình ảnh liên quan đến bài đánh giá.
  + Rating: Xếp hạng của bài đánh giá.
- Tiền xử lý dữ liệu:
![This is an image](https://github.com/hnkanh/INT3405/blob/a1a4f3518246b23010c22e585c6a18791f264cc6/Preprocessing.png)
## Result
Kết quả chạy trên Kaggle: accuracy 0.77
