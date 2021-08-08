# trinhduyet
Thử nghiệm Vps (Desktop VNC) Eu trên trình duyệt Sử dụng katacoda
# Cách cài đặt và sử dụng
đây là tool hoàn toàn miễn phí. Không phải đăng ký hay abc... việc bạn cần làm là copy và paste là done.
1. Đăng nhập vào: https://katacoda.com/openshift/courses/subsystems/container-internals-lab-2-0-part-1
2. Click vào "Start Scenario" 
3. Đợi cho máy chủ tải file vài phút.
4. Nhập lệnh sau:
```
docker run -p 6070:80 dorowu/ubuntu-desktop-lxde-vnc
```
Với lệnh trên bạn có thể truy cập Vnc bằng Cổng 6070.
Nếu bạn muốn truy cập các cổng khác thì chỉnh sang cổng bạn muốn ví dụ:
```
docker run -p 6080:80 -p 5900:5900 -v /dev/shm:/dev/shm dorowu/ubuntu-desktop-lxde-vnc
```
Đó là port 6080
....

Sau khi kết thúc setup.
