

<h5>📅<em>~ Tháng 5 năm 2025 ~</em></h5>

<h3>TÊN ĐỀ TÀI: ỨNG DỤNG HỌC MÁY PHÁT HIỆN ẢNH GIẢ TRONG LĨNH VỰC BẢO HIỂM Ô TÔ 🚗</h3>

<p> 🔬<strong>Lĩnh vực:</strong> Khoa học tự nhiên</p>
<p> 💻<strong>Chuyên ngành:</strong> Công nghệ thông tin</p>

<p> 👥 Thành viên nhóm</p>

| STT | Họ và tên             
|-----|-----------------------
| 1   | Đinh Thị Quỳnh Anh    
| 2   | Vũ Phương Anh    
| 3   | Nguyễn Hoàng Long        
| 4   | Lê Thị Thùy Linh        
| 5   | Vũ Thị Khánh Linh    
---
<p>🌐 <strong>Giới thiệu dự án</strong></p>

Dự án này nhằm nghiên cứu và ứng dụng các mô hình học máy để **tự động phát hiện hình ảnh giả mạo** trong quy trình xử lý bồi thường bảo hiểm ô tô. Nhóm tập trung triển khai các **kiến trúc học sâu hiện đại**, cụ thể là **ResNet50** và **ResNet50V2**, nhằm nâng cao độ chính xác và hiệu quả trong việc phát hiện các trường hợp gian lận thông qua hình ảnh. Bên cạnh việc tối ưu hóa mô hình, đề tài cũng chú trọng đến việc xử lý **bài toán mất cân bằng dữ liệu** – một thách thức phổ biến trong các hệ thống phát hiện gian lận, nơi số lượng hình ảnh gian lận thường rất ít so với dữ liệu hợp lệ.


<p>📂 <strong>Bộ dữ liệu:</strong> Nhóm nghiên cứu đã chọn ra <strong>3.087 hình ảnh</strong> từ tập dữ liệu 
<a href="https://www.kaggle.com/datasets/pacificrm/car-insurance-fraud-detection" target="_blank">“Car Insurance Fraud Detection”</a> trên nền tảng Kaggle.</p>

<p> 🗂<strong>Cấu trúc của tập dữ liệu:</strong></p>
<pre>
Insurance-Fraud-Detection/
│
├── train/
│   ├── Fake/
│   └── Real/
│
└── test/
    ├── Fake/
    └── Real/
</pre>

<p>🧠 <strong>Các mô hình được triển khai:</strong></p>
<ul>
  <li> Mô hình sử dụng <em>ResNet50 cổ điển</em> kết hợp với <em>Class_weights</em></li>
  <li> Mô hình kết hợp <em>trích xuất đặc trưng từ ResNet50</em> với <em>Random Forest</em> và <em>SMOTE</em></li>
  <li> Mô hình sử dụng <em>ResNet50V2 cải tiến</em></li>
</ul>
