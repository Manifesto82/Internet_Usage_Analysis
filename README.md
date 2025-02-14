# Internet Usage Analysis
# Mục tiêu
Mục tiêu project là xây dựng một mô hình dự đoán tỷ lệ người dùng có nhấn vào quảng cáo khi đang sử dụng website và internet không dựa trên những yếu tố liên quan. Dự án sử dụng bộ dữ liệu chứa thông tin người dùng sử dụng website và internet, bao gồm các thuộc tính đặc trưng và biến mục tiêu Clicked_on_Ad (người dùng có click quảng cáo hay không).

# Dữ liệu
Bộ dữ liệu: Chứa các thông tin lâm sàng về bệnh nhân suy tim, bao gồm các thuộc tính như Daily Time Spent On Site, Age, Area Income, Daily Internet Usage, Ad Topic Line, City, Country, Gender, Timestamp.

Biến mục tiêu: Clicked on Ad (1: Có click, 0: không click).

# Tiền xử lý dữ liệu

Dữ liệu được đọc từ file CSV và kiểm tra các giá trị đặc biệt, trùng lặp.

Các bước tiền xử lý bao gồm:

Kiểm tra và xóa các giá trị trùng lặp.

Đếm số lượng giá trị riêng biệt trong từng cột.

Chuyển đổi các dữ liệu sang số hóa để thuận tiện cho việc dùng Machine Learning để dự đoán.

# Trực quan hóa dữ liệu

Dùng các thư viện Python như Scikit-learn, Seaborn, Matplotlib.pyplot để trực quan.

# Các thuật toán sử dụng

Logistic Regression:

Chia dữ liệu thành tập huấn luyện (70%) và tập kiểm tra (30%).

Huấn luyện mô hình và tính toán độ chính xác (accuracy).

Sử dụng Confusion Matrix và Classification Report để đánh giá hiệu suất mô hình.

K-Nearest Neighbors:

Sử dụng K-Neighbors và các tham số k ban đầu mặc định = 3 và thêm một k tối ưu (lấy k mang lại giá trị accuracy cũng như các chỉ số khác tối ưu nhất).

Huấn luyện mô hình và tính toán độ chính xác.

Đánh giá mô hình thông qua Confusion Matrix và Classification Report.
