# Purchase-Behavior-Analysis
# 1. Giới thiệu (Overview)
Dự án tập trung vào việc khám phá dữ liệu giao dịch của 238 khách hàng để tìm ra mối liên hệ giữa nhân khẩu học (tuổi, khu vực) và thói quen chi tiêu. Mục tiêu cuối cùng là phân đoạn khách hàng và đề xuất chiến lược tối ưu hóa doanh thu cho bộ phận Marketing.

# 2. Kỹ năng & Công cụ sử dụng (Tech Stack)
Ngôn ngữ: Python (Pandas, Numpy), SQL (SQLite/pandasql).

Trực quan hóa: Seaborn, Matplotlib, Plotly (Treemap).

Kỹ thuật SQL nâng cao: CTEs, Window Functions, Case Statements, Grouping & Filtering.

# 3. Quy trình thực hiện (Action)
Làm sạch dữ liệu: Kiểm tra tính toàn vẹn, xử lý trùng lặp và định dạng lại các biến số.

Phân tích SQL:

Sử dụng CTEs để tạo bảng tạm giúp code sạch và dễ bảo trì.

Dùng Case Statements để phân loại khách hàng thành: Gen Z, Millennials, Gen X+ và các hạng VIP, Tiềm năng, Cần chăm sóc.

Lọc các khu vực tiềm năng bằng câu lệnh HAVING.

Trực quan hóa & Thống kê:

Vẽ Heatmap để so sánh mức chi tiêu theo Khu vực và Nhóm tuổi.

Sử dụng biểu đồ Pareto để kiểm chứng quy luật 80/20 trong doanh thu.

# 4. Kết quả & Insight (Results)
Nhóm khách hàng mục tiêu: Nhóm Millennials (30-45 tuổi) đóng góp doanh thu ổn định nhất với mức chi tiêu trung bình trên $450/đơn hàng.

Phân bổ khu vực: Xác định được 2 khu vực trọng điểm có tỷ lệ khách hàng VIP cao nhất, nơi cần tập trung ngân sách quảng cáo.

Quy luật chi tiêu: Qua biểu đồ Pareto, nhận thấy 20% khách hàng hàng đầu đóng góp gần 30% doanh thu, cho thấy cơ cấu doanh thu khá bền vững, không bị phụ thuộc quá mức vào một nhóm nhỏ.
