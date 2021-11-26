# Learn_to_the_world
Ansible for automation

I. Khái niệm 
- Ansible là một giải pháp tự động hóa CNTT,được ứng dụng rộng rãi để tối ưu, tự động hóa các bài toán thuộc các lĩnh vực CNTT cấp phát tài nguyên cloud, quản lý cấu hình thiết bị, triển khai ứng dụng,... và một vài ứng dụng khác.

- Ansible cho phép triển khai đồng thời nhiều hệ thống nhiều hạ tầng CNTT trong cùng 1 thời điểm 
- Là giải pháp no agents ==> dễ dàng trong việc triển khai 
- Được định nghĩa bằng ngôn ngữ (YAML) cho phép mô tả các tác vụ một cách clear 

II. Các bước cài đặt 

1. Control Machine Requirement
Hiện tại Ansible có thể chạy trên bất kỳ machine nào cài được cài đặt mội trường Python2 (Version 2.6 hoặc 2.7) hoặc Python3 (version 3.5 hoặc cao hơn). 
* Chú ý: 
  + Đối máy chủ windows không hỗ trợ control machine
  + Các hệ điều hành có thể làm control host: Red hat Debian, OS X, BSDs, ..

2. Managed Node Requirement:

Đối với các node dược quản lý, cần đảm bảo đường kết nối, thông thường qua giao thức ssh. Mặc định sử dụng giai thức sftp. Nếu 2 giao thức kia không đảm bảo có thể chuyển qua giao thức scp được cấu hình trong file ansible.cfg. Môi trường của managed node thì cũng cần môi trường python2.6 hoặc hơn 

3. Install ansible on Control machine trên server chạy hệ điều hành CenOS 



