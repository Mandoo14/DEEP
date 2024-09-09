# Tên dự án: Nhận diện món ăn với DeepLearning
## Giới thiệu dự án:

### Mục tiêu: 
    Bài toán này nhằm xây dựng một phần mềm có khả năng nhận dạng 5 món ăn (Táo, 
    chuối, cam, cà chua, dưa hấu). Mục tiêu là tạo ra một hệ thống tự động có khả năng 
    nhận diện các món ăn và xác định vị trí. 
    Trong đó input là hình ảnh chứa các món ăn như là:  - - - - - 
      Táo 
      Chuối 
      Cam 
      Cà chua 
      Dưa hấu 

### Dữ liêu:

#### Nguồn:
      Roboflow

#### Kích thước: 
      Train (2167 ảnh), Test (310 ảnh), Valid (619 ảnh). Kích thước dữ liệu 121MB.

#### Nội dung: 
      Hình ảnh của các món ăn (Táo, chuối, cam, cà chua, dưa hấu) đã được gắn nhãn  

### Công cụ thực hiện:
      Sử dụng 3 mô hình CNN, MLP, ResNet50 tiến hành phân lớp và xác định vị trí hình ảnh.

### Các bước thực hiện:

#### - - - 
    Thu thập dữ liệu
    Phân lớp các đối tượng và xác định vị trí đối tượng trong ảnh : sử dụng 3 mô hình CNN, MLP, ResNet50
    Triển khai mô hình 
    Kết quả

### Kết quả: 
    Triển khai được những mô hình học sâu cần thiết và huấn 
    luyện những mô hình sau đó sử dụng để nhận dạng và xác định vị trí của các món ăn. 

### Cần cải thiện:
    Dữ liệu để train mô hình còn hạn chế với kích thước dữ liệu chỉ 121MB. 
    Chưa áp dụng được xác định vị trí khi dùng streamlit để nhận diện. 

### Hướng phát triển:
    Có thể sử dụng camera để xác định vị trí món ăn  
    Xây dựng một ứng dụng như web hay mobile để upload ảnh hay video mà 
    người dùng muốn nhận diện món ăn. 


### Liên hệ:
#### Email: khuean14112003@gmail.com
    
        
      

