# JPX_Tokyo_Stock_Exchange_Prediction
Building stock price prediction models on the Tokyo exchange to help investors make future financial decisions
Xây dựng mô hình dự đoán sự thay đổi giá cổ phiếu giao dịch trên sàn chứng khoán Nhật Bản JPX Tokyo
## Dataset
Bộ dữ liệu được sử dụng trong cuộc thi trên web Kaggle https://www.kaggle.com/competitions/jpx-tokyo-stock-exchange-prediction.
Bộ dữ liệu chứa thông tin giao dịch của nhiều loại cổ phiếu trên sàn JPX Tokyo.
Tập dữ liệu huấn luận bao gồm thông tin của các loại cổ phiếu mỗi ngày như: giá mở cửa, giá đóng cửa, giá cao, giá thấp, khối lượng giao dịch,...
Mục tiêu dự đoán của mô hình là tỷ lệ thay đổi giá đóng cửa của mỗi loại cổ phiếu vào ngày hôm sau (T+1) và ngày hôm sau nữa (T+2)
## Model
Sử dụng các mô hình chuỗi thời gian phổ biến như MA, Arima, LightGBMs,...
