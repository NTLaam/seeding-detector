# seeding-detector
Show quá trình làm việc
Project Proposal: Nhận Dạng Nội Dung Seeding

1. Introduction

Trong thời đại số, nội dung trên mạng xã hội ngày càng đa dạng và phức tạp. Một trong những chiến lược phổ biến trong marketing là "seeding content" - nội dung được tạo ra nhằm định hướng dư luận hoặc quảng bá một sản phẩm/dịch vụ. Việc phát hiện và phân loại nội dung seeding là một vấn đề quan trọng trong lĩnh vực xử lý ngôn ngữ tự nhiên (NLP) và an ninh thông tin.

2. Problem statement

- Người dùng bị thao túng bởi các bài đăng có nội dung quảng bá trá hình.
- Các doanh nghiệp khó đánh giá hiệu quả chiến dịch truyền thông, do không thể phân biệt giữa nội dung thực sự có tác động và nội dung được tạo ra nhân tạo.
- Công tác kiểm duyệt nội dung gặp khó khăn, đặc biệt trong các nền tảng có số lượng lớn bài viết hàng ngày.

3. Objectives

- Xây dựng một phần  mềm có khả năng nhận diện tự động các nội dung “seeding” trên các nền tảng trực tuyến.
- Áp dụng các thuật toán ML và NLP để phân loại và nhận diện nội dung.
- Đánh giá độ chính xác của mô hình nhận diện và đề xuất cải tiến.

4. Methodology

3.1. Dữ Liệu

Sử dụng bộ dữ liệu ViSPAM.

Tiền xử lý dữ liệu bao gồm làm sạch văn bản, loại bỏ stopwords, tách từ tiếng Việt.

3.2. Mô Hình Học Máy

Thử nghiệm các mô hình như Naïve Bayes, SVM, Random Forest.

Áp dụng mô hình deep learning như LSTM, Transformer để tăng độ chính xác.

3.3. Đánh Giá

Sử dụng các chỉ số như Accuracy, F1-score, Precision, Recall để đánh giá mô hình.

So sánh giữa các phương pháp khác nhau.

4. Research scope

- Đối tượng nghiên cứu: Tập trung vào việc nhận diện các nội dung tiếp thị "seeding" trên các nền tảng trực tuyến phổ biến như mạng xã hội (Facebook, Instagram), và các trang thương mại điện tử. Các bình luận, bài viết và đánh giá của người dùng trên các nền tảng này sẽ là nguồn dữ liệu chính cho nghiên cứu.
- Công nghệ sử dụng: Sử dụng các kỹ thuật ML, NLP và khai thác dữ liệu (data mining). Các công cụ như Python, TensorFlow, và các thư viện NLP như NLTK, SpaCy sẽ được ứng dụng trong quá trình phát triển phần mềm.
- Thời gian thực hiện: Nghiên cứu sẽ được tiến hành trong vòng 15 tuần, bao gồm các giai đoạn: thu thập dữ liệu, xây dựng mô hình, phát triển phần mềm, và thử nghiệm đánh giá kết quả.

5. Expected outcome 

- Một hệ thống phát hiện nội dung seeding có độ chính xác cao.

6. Planning

| Giai Đoạn     | Công Việc Chính                         | Thời Gian (Tuần) | Kết Quả Kỳ Vọng |
|--------------|--------------------------------------|-----------------|----------------|
| **5** | Tìm hiểu đề tài nghiên cứu      | 2 tuần          | Báo cáo hoàn chỉnh |
| **5** | Xây dựng kế hoạch nghiên cứu     | 2 tuần          | Báo cáo hoàn chỉnh |
| **5** | Xây dựng đề cương nghiên cứu       | 2 tuần          | Báo cáo hoàn chỉnh |
| **5** | Khảo sát vấn đề nghiên cứu       | 2 tuần          | Báo cáo hoàn chỉnh |

| **1** | Nghiên cứu lí thuyết và tổng quan vấn đề       | 2 tuần          | Lí thuyết chuẩn, không sai vấn đề |
| **2** | Thu thập và tiền xử lý dữ liệu        | 1 tuần          | Bộ dữ liệu sạch, có nhãn |
| **3** | Xây dựng mô hình phân loại          | 1 tuần          | Mô hình baseline chạy được |
| **4** | Tinh chỉnh và tối ưu mô hình       | 2 tuần          | Mô hình chính xác cao hơn |
| **5** | Đánh giá kết quả và phân tích       | 2 tuần          | Báo cáo đánh giá chi tiết |
| **6** | Viết báo cáo và tổng kết dự án      | 2 tuần          | Báo cáo hoàn chỉnh |


7. Resources & Budget

7.1. Tài Nguyên 

| Hạng Mục                     | Mô Tả |  
|------------------------------|----------------------------------|  
| **Dữ liệu (Dataset)**        | VisPAM |  
| **Phần cứng (Compute)**      | Google Colab |  
| **Phần mềm (Software)**      | Python, Github, Zotero |  
| **Lưu trữ (Storage)**        | Google Drive, Cloud Storage |  

7.2. Nhân lực 

| Hạng Mục                     | số lượng |  
|------------------------------|----------------------------------| 
| **Nghiên cứu và phát triển**          | 2 người | 
| **Mentor** | 1 người |

8. Kết Luận

Dự án này hướng đến việc phát triển một hệ thống tự động nhận dạng nội dung seeding, góp phần hỗ trợ phát hiện nội dung quảng bá ngầm trên mạng xã hội. Nếu thành công, mô hình có thể được ứng dụng vào nhiều lĩnh vực như kiểm duyệt nội dung, phân tích truyền thông, và nghiên cứu hành vi người dùng.

