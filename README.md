# KIỂM THỬ PHẦN MỀM – MANUAL TESTING

## 1. 📌 Giới thiệu
Dự án nhằm thực hành **kiểm thử phần mềm thủ công (Manual Testing)** cho Website E-commerce giả lập.  
Mục tiêu là áp dụng quy trình kiểm thử gồm **Test Plan → Test Case → Bug Report → RTM → Test Report → Metrics** để đánh giá chất lượng phần mềm trước khi phát hành.

---

## 2. 🎯 Mục tiêu kiểm thử
- Kiểm tra các chức năng nghiệp vụ chính của hệ thống
- Phát hiện và ghi nhận lỗi phát sinh
- Đánh giá mức độ ổn định của website
- Đưa ra quyết định **Release / No-Release**

---

## 3. 📂 Cấu trúc thư mục dự án

📦 Ecommerce-Manual-Testing  
├── README.md  
├── Test_Plan  
│   └── Test_Plan_Ecommerce.docx  
├── Test_Cases  
│   └── Test_Cases_Ecommerce.xlsx  
├── Bug_Report  
│   └── Bug_Report.xlsx  
├── RTM  
│   └── RTM_Ecommerce.xlsx  
├── Test_Metrics  
│   └── Test_Metrics.xlsx  
└── Test_Report  
    └── Test_Report.docx  

---

## 4. 📄 Mô tả thư mục & tài liệu

### 📁 Test_Plan
- **Test_Plan_Ecommerce.docx**  
  Mô tả kế hoạch kiểm thử, phạm vi, phương pháp, môi trường, rủi ro và lịch trình kiểm thử.

### 📁 Test_Cases
- **Test_Cases_Ecommerce.xlsx**  
  Danh sách test case chi tiết cho các module:
  - Authentication
  - Product & Cart
  - Checkout  
  Bao gồm: Positive, Negative, Boundary, Validation test case.

### 📁 Bug_Report
- **Bug_Report.xlsx**  
  Ghi nhận các lỗi phát hiện trong quá trình kiểm thử (Bug ID, mô tả, severity, trạng thái).

### 📁 RTM (Requirement Traceability Matrix)
- **RTM_Ecommerce.xlsx**  
  Ma trận truy vết yêu cầu giữa Requirement và Test Case.

### 📁 Test_Metrics
- **Test_Metrics.xlsx**  
  Thống kê số lượng test case, tỷ lệ pass/fail, số bug theo mức độ nghiêm trọng.

### 📁 Test_Report
- **Test_Report.docx**  
  Báo cáo tổng hợp kết quả kiểm thử và quyết định phát hành hệ thống.

---

## 5. 🧪 Phạm vi kiểm thử

### In-scope
- Authentication (Đăng ký, đăng nhập, quên mật khẩu, đăng xuất)
- Product & Cart (Xem sản phẩm, giỏ hàng)
- Checkout (Thanh toán, đặt hàng, lịch sử đơn hàng)

### Out-of-scope
- Performance Testing
- Automation Testing
- Security Testing chuyên sâu

---

## 6. ⚙️ Môi trường kiểm thử
- OS: Windows 11  
- Browser: Google Chrome  
- Device: Laptop  
- Test Data: Giả lập  

---

## 7. 📊 Kết quả kiểm thử (Tóm tắt)
- 100% test case đã được thực thi
- Phát hiện lỗi mức **Critical** và **Major**
- Hệ thống **chưa đủ điều kiện phát hành (No-Release)**

---

## 8. 📌 Kết luận
Dự án giúp áp dụng đầy đủ quy trình kiểm thử phần mềm thủ công, nâng cao kỹ năng thiết kế test case, quản lý bug và đánh giá chất lượng phần mềm.

---

## 9. 👨‍🎓 Thông tin sinh viên
- Môn học: Kiểm thử phần mềm  
- Hình thức: Manual Testing  
- Dự án: Website E-commerce giả lập
