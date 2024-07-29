# House Price Prediction in Ho Chi Minh city (2023)

Đây là project cuối kỳ nhóm 3 người môn "Nhập môn Khoa học dữ liệu" - HCMUS. Trong project này, bọn mình sẽ dự đoán giá nhà, căn hộ bằng các mô hình hồi quy (regression model) - Là mô hình phổ biến trong ngành khoa học dữ liệu.

Giá nhà, căn hộ luôn là chủ đề nóng trong BĐS, cho nên project này hi vọng sẽ cải thiện cho người bán, người mua và các nhà phân tích BĐS có góc nhìn phù hợp với giá nhà hiện tại và có thể chuẩn bị trong tương lai.

Project này chỉ lấy cụ thể nhà, căn hộ trong khu vực TP.HCM

**Các bước bọn mình làm trên project này:**

- Bước 1. Collecting Data bằng cách sử dụng Web Scrapping trên trang web batdongsan.vn

- Bước 2. Transforming Data - Chỉnh lại tên, giá nhà, phòng ngủ, phòng tắm,... sao cho hợp lý nếu bị sai.

- Bước 3. Explore Data Analysis (Thống kê căn bản, remove outliers,...)

- Bước 4. PCA để giảm số chiều dữ liệu

- Bước 5. Training và testing các regression model như linear, lasso, random forest, xgboost,...

Chi tiết hơn về project này, các bạn xem trong file House_Price_Prediction.ipynb nhé. Ngôn ngữ lập trình được sử dụng là python.

Về data gốc bọn mình đã web scrapping từ trang web: [batdongsan.vn](https://batdongsan.vn/ban-nha-ho-chi-minh)

Các bạn có thể tải file .ipynb về và chạy thử.
