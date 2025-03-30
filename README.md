# seeding-detector
Show quá trình làm việc
Project Proposal: Nhận Dạng Nội Dung Seeding

## 📌 Giới Thiệu
Trong thời đại số, nội dung trên mạng xã hội ngày càng đa dạng và phức tạp. Một trong những chiến lược phổ biến trong marketing là **seeding content** – nội dung được tạo ra nhằm định hướng dư luận hoặc quảng bá sản phẩm/dịch vụ. Việc phát hiện và phân loại nội dung seeding là một vấn đề quan trọng trong **Xử Lý Ngôn Ngữ Tự Nhiên (NLP)** và **An Ninh Thông Tin**.

---

## 🚨 Problem Statement
- Người dùng bị thao túng bởi các bài đăng có nội dung quảng bá trá hình.
- Doanh nghiệp khó đánh giá hiệu quả chiến dịch truyền thông do không thể phân biệt giữa nội dung tự nhiên và nội dung nhân tạo.
- Công tác kiểm duyệt nội dung gặp khó khăn, đặc biệt trên các nền tảng có lượng bài viết lớn.

---

## 🎯 Objectives
- Xây dựng một phần mềm tự động nhận diện nội dung **seeding** trên các nền tảng trực tuyến.
- Áp dụng các thuật toán **Machine Learning (ML)** và **NLP** để phân loại và nhận diện nội dung.
- Đánh giá độ chính xác của mô hình và đề xuất cải tiến.

---

## 🔬 Methodology
### 📌 1. Dữ Liệu
- Sử dụng bộ dữ liệu **ViSPAM**.
- Tiền xử lý dữ liệu: làm sạch văn bản, loại bỏ stopwords, tách từ tiếng Việt.

### 📌 2. Mô Hình Học Máy
- Thử nghiệm các mô hình truyền thống: **Naïve Bayes, SVM, Random Forest**.
- Ứng dụng **Deep Learning (LSTM, Transformer)** để cải thiện độ chính xác.

### 📌 3. Đánh Giá
- Sử dụng các chỉ số: **Accuracy, F1-score, Precision, Recall**.
- So sánh hiệu suất giữa các phương pháp.

---

## 📚 Research Scope
- **Đối tượng nghiên cứu:** Nhận diện nội dung tiếp thị "seeding" trên mạng xã hội (Facebook, Instagram) và các trang thương mại điện tử.
- **Công nghệ sử dụng:** Python, TensorFlow, NLTK, SpaCy, PhoBERT.
- **Thời gian thực hiện:** 15 tuần, bao gồm thu thập dữ liệu, xây dựng mô hình, phát triển phần mềm và thử nghiệm đánh giá.

---

## ✅ Expected Outcomes
- Xây dựng **một hệ thống phát hiện nội dung seeding** có độ chính xác cao.
- Cung cấp báo cáo phân tích về **đặc điểm của nội dung seeding**.
- Đề xuất các hướng phát triển tiếp theo trong việc kiểm duyệt và phân tích nội dung.

---

## 📅 Planning (Kế Hoạch Thực Hiện)
| Giai Đoạn  | Công Việc Chính                     | Thời Gian (Tuần) | Kết Quả Kỳ Vọng |
|------------|------------------------------------|-----------------|----------------|
| **1**      | Nghiên cứu lí thuyết và tổng quan đề tài nghiên cứu  | 2 tuần  | Đề cương chi tiết |
| **2**      | Thu thập và tiền xử lý dữ liệu                       | 2 tuần  | Bộ dữ liệu chất lượng. Dữ liệu sạch, sẵn sàng |
| **3**      | Xây dựng và huấn luyện mô hình phân loại             | 2 tuần  | Mô hình chính xác cao |
| **4**      | Đánh giá & cải tiến mô hình                          | 2 tuần  | Nâng cao hiệu suất |
| **5**      | Viết báo cáo & tổng kết dự án                        | 2 tuần  | Báo cáo hoàn chỉnh |

---

## 🛠 Resources & Budget
### 🔹 1. Tài Nguyên
| Hạng Mục              | Mô Tả |
|----------------------|----------------------------------|
| **Dữ liệu (Dataset)** | ViSPAM |
| **Phần cứng (Compute)** | Google Colab |
| **Phần mềm (Software)** | Python, GitHub, Zotero |
| **Lưu trữ (Storage)** | Google Drive, Cloud Storage |

### 🔹 2. Nhân Lực
| Vai Trò                   | Số Lượng |
|--------------------------|---------|
| **Nghiên cứu & phát triển** | 2 người |
| **Mentor/Hướng dẫn**       | 1 người |

---

## 🔚 Kết Luận
Dự án này hướng đến việc phát triển **một hệ thống tự động nhận dạng nội dung seeding**, hỗ trợ phát hiện nội dung quảng bá ngầm trên mạng xã hội. Nếu thành công, mô hình có thể ứng dụng vào **kiểm duyệt nội dung, phân tích truyền thông, và nghiên cứu hành vi người dùng**.

