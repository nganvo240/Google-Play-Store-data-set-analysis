# Google-Play-Store-data-set-analysis
Phân tích các yếu tố ảnh hưởng đến xếp hạng của ứng dụng trên google play store bằng R

  Tập dữ liệu đầu vào được tìm thấy trên Kaggle và thông tin được thu thập thông qua việc tìm kiếm trên web khoảng 10.000 ứng dụng Cửa hàng Play. Vì Google Play sử dụng các kỹ thuật hiện đại như tải trang động bằng JQuery, điều này khiến việc tìm kiếm khó khăn hơn. Mỗi ứng dụng có các giá trị cho danh mục, xếp hạng, kích thước, lượt cài đặt và các thông số kỹ thuật ứng dụng khác. Mặc dù Google Play cũng hoạt động như một cửa hàng phương tiện kỹ thuật số,nhưng trong phạm vi bài phân tích này chúng ta chỉ quan tâm đến ứng dụng Android vì thế dữ liệu chỉ bao gồm các ứng dụng di động.
- Hướng dẫn sử dụng: Để chạy được file báo cáo và thuyết trình yêu cầu cài 3 thư viện, tidyverse, ggplot2 và revealjs



# Giới thiệu
Dữ liệu ứng dụng trên Cửa hàng Play (Google Play) có tiềm năng to lớn để thúc đẩy các doanh nghiệp sản xuất ứng dụng thành công. Thông tin chi tiết hữu ích có thể được rút ra để các nhà phát triển như chúng ta làm việc và nắm bắt thị trường Android! Chính vì thế, với project này, chúng ta sẽ cùng thực hiện một số phân tích thống kê về dữ liệu thu thập được từ CH Play để tìm ra các xu hướng và mẫu liên quan đến thị trường nhằm mục đích giúp các nhà phát triển định hướng cũng như tìm ra con đường đúng đăn để phát triển các ứng dụng Android.
