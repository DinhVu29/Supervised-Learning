# Giới thiệu về dự án 
 Dự án sử dụng phương pháp một trong những phương pháp học máy (Machine Learning) phổ biến đó là Supervised Learning (Học có giám sát) để phân tích dự đoán mức độ hài lòng của hành khách đối với hãng hàng không. 
 Mục tiêu của bài phân tích là: 
- Việc phân tích phản hồi của khách hàng sẽ giúp ích rất nhiều cho các hãng hàng không hiểu chính xác hơn khách hàng của họ cần gì và họ có thể cải thiện tốt hơn ở đâu.
- Hơn nữa, việc dự đoán mức độ hài lòng của khách hàng cũng hỗ trợ CRM (Quản lý quan hệ khách hàng) trong các hãng hàng không


#### Dataset: 
- Bộ dữ liệu này bao gồm một cuộc khảo sát về sự hài lòng của hành khách đã đi máy bay của một hãng hàng không. 
- Bộ dữ liệu được chia thành 2 kiểu dữ liệu:
    - Dữ liệu đầu vào (X - Input): Các dữ liệu nhân khẩu, các dữ liệu dịch vụ hàng không, ...
    - Dữ liệu đầu ra (Y - Output): Hài lòng hoặc Không Hài Lòng (biến Nhị Phân)

#### Phân tích hồi quy (Regression): Dự đoán sự hài lòng của khách hàng
1. Phân tích khám phá dữ liệu (EDA):
    - Nhóm biến về khách hàng
    - Nhóm biến về tính chất chuyến bay
    - Nhóm biến về dịch vụ trong chuyến bay
    - Nhóm biến về dịch vụ trước chuyến bay
2. Xây dựng mô hình: 
    - Tiến hành mã hóa và chuẩn hóa dữ liệu
    - Corelation Matrix
    - Xây dựng mô hình
        1. Logistic Regression
        2. Gaussian Naive Bayes Classifier
        3. Decision Tree Classifer
        4. Random Forest Classifer
        5. KNeighbors Classifer
        6. LightGBM (Light Gradient Boosting Machine) 

 #### Nội dung chi tiết bài phân tích, trong file 'SupervisedLearning_Project.ipynb'
