
<center>
  
# Lab 01: Thu thập dữ liệu và trực quan hóa dữ liệu
  
</center>

### 1. Giới thiệu đồ án

Hiện nay, các nền tảng nghe nhạc trực tuyến như **Spotify**, **Zing MP3**, **Nhaccuatui**, **SoundCloud**, ... là một trongnhững kênh để nghe nhạc và khám phá các xu hướng âm nhạc mới. Trên các nền tảng này chứa dữ liệu khổng lồ về các thông tin bài hát, nghệ sĩ, thể loại, .... Tuy nhiên, dữ liệu này thường phân tán và chưa được khai thác hiệu quả.

Đồ án của chúng ta sẽ tập trung vào việc thu thập, làm sạch và phân tích dữ liệu từ các nền tảng này. Chúng ta sẽ khám phá mối quan hệ giữa các yếu tố âm nhạc, xác định xu hướng thị trường và phát hiện những đặc điểm nổi bật trong hành vi nghe nhạc của người dùng bằng cách áp dụng các kỹ thuật xử lý dữ liệu, phân tích thống kê và trực quan hóa. Nhờ đó, xây dựng một bức tranh về thị trường âm nhạc trực tuyến tại Việt Nam.

### 2. Nhiệm vụ đồ án 

Trong đồ án này, các bạn sẽ thực hiện các nhiệm vụ sau:

**Thu nhập và tiền xử lý dữ liệu**
- Nhóm có thể chọn một hoặc nhiều nền tảng âm nhạc trực tuyến Zing MP3, Nhaccuatui, SoundCloud, .... để thu nhập dữ liệu (có thể sử dụng API, web crawling, .... để thu nhập dữ liệu)
- Dữ liệu sau khi thu nhập sẽ được qua các bước tiền xử lý (nếu cần) như làm sạch dữ liệu, chuẩn hóa, .... và được lưu dưới dạng .csv (có thể lưu thành nhiều file nếu cần)
- File dữ liệu sạch cần chứa ≈ 3000 records có ý nghĩa phân tích.

**Trực quan hóa dữ liệu**
- Phân tích cơ bản về dữ liệu: giới thiệu dữ liệu, cỡ mẫu, cấu trúc, phân tích thống kê, xử lý dữ liệu, ....
- Xác định mục tiêu phân tích và lựa chọn các trường dữ liệu
  - Xác định rõ mục tiêu phân tích và lựa chọn các trường dữ liệu phù hợp để trực quan hóa
  -  Cần xem xét các môí quan hệ giữa các trường để đưa ra lựa chọn phù hợp nhất.
  -  Mỗi nhóm cần xác định ít nhất [Số lượng thành viên] * 2 mục tiêu phân tích và trực quan.
- Lựa chọn biểu đồ thích hợp và giải thích lý do
  - Biểu đồ cần phải phù hợp với tính chất của trường dữ liệu.
  - Nhóm sử dụng đa dạng các biểu đồ để làm rõ mục tiêu đã đề ra.
  - Toàn bài phân tích cần bao phủ hết các biểu đồ đã được học.
- Nhận xét và đưa ra kết luận dựa trên các biểu đồ

**Yêu cầu đồ án**
- Nhóm thực hiện các nhiệm vụ trên trong môi trường lập trình **Python**, **không** sử dụng các phần mềm khác như **Tableau**, **PowerBI**, ... để minh họa; Các thư viện được sử dụng như **`numpy`**, **`pandas`**, **`seaborn`**, **`matplotlib`** được phép sử dụng; các thư viện ngoài thì cần ghi rõ trong báo cáo lý do sử dụng.
- Nhóm **tổ chức tất cả các code Python trên một file Jupyter Notebook (.ipynb)** và sử dụng **các cell Markdown** để mô tả rõ quá trình thực hiện.
- Nhóm **không được sử dụng dữ liệu có sẵn trên Kaggle**, .... mà phải tự thu nhập bằng các cách như web crawling, gọi api, ... Code để thu nhập cần có trong file Jupyter Notebook.
- Có thể sử dụng các thuật toán máy học trong việc phân tích và thể hiện trên biểu đồ.
- Trong quá trình phân tích, có thể dùng dữ liệu của nhóm khác nhưng cần ghi rõ lý do trong cả báo cáo và phần code (nếu mục đích phù hợp sẽ được cộng điểm, ngược lại sẽ trừ điểm tùy mức độ).
- Viết báo cáo ngắn gọn và đầy đủ toàn bộ quá trình thực hiện; kết quả và nhận xét. Báo cáo tối đa là 24 trang (không bao gồm trang bìa, mục lục và tài liệu tham khảo). Nội dung file code và báo cáo phải khớp với nhau. Nội dung báo cáo bao gồm:
  - Thông tin nhóm: tên nhóm, mssv...
  - Mức độ hoàn thành tổng thể của mỗi yêu cầu.
  - Mức độ hoàn thành của từng thành viên
  - Chi tiết các bước thực hiện (kèm hình ảnh), thuật toán, chạy ví dụ, nhận xét. Trình bày đơn giản, có hình minh họa.
