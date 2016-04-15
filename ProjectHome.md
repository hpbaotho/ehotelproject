eHotel's project is a project of asp.net mvc.This is developed by Trung doan and Van thien in An giang University.I hope this useful for you!.
Thank for visiting!.



Quản lý eHotel:

+Nhiệm vụ ưu tiên cho Quản lý đặt Phòng,Quản lý thuê Phòng.Đây là 2 chức năng quan trọng nhất trong Quản lý Khách sạn.
+Đối với Quản lý Đặt phòng được chia thành 2 mảng:Đặt phòng online và đặt Phòng offline.
+Đặt Phòng Online là mảng của site Main(site chính của Khách sạn chỉ cho phép đặt Phòng online mà thôi),Đặt phòng ofline thuộc Site admin.
+Site admin: Phân quyền use truy cập vào,ứng với từng user(role) sẽ được sử dụng những chức năng riêng của Website.(Tạo user,role,membership).Và trong site admin sẽ cho phép quản lý các chức năng như: Quản lý Phòng:Quản lý trạng thái Phòng,Quản lý thuê Phòng:Quản lý nghiệp vụ thuê Phòng (thông tin Phòng,thông tin Khách hàng..),Quản lý đặt Phòng trực tiếp(điện thoại..) tất cả đều kế thừa Quản lý Phòng.
+Quản lý Phòng:Thêm,xóa,sửa Phòng,loại,trạng thái.....
+Quản lý thuê Phòng:Kiểm tra trạng thái Phòng-->Nhập thông tin Nhân viên ,thông tin Phòng vào Table HiringRoom và lưu lại,đồng thời Refresh(cập nhật lại trạng thái Phòng cho lần thuê,đặt tiếp theo..).
+Quản lý đặt Phòng:Đặt phòng trực tiếp-->Kiểm tra trạng thái Phòng-->lưu thông tin Khách hàng,thông tin Phòng,Cập nhật trạng thái Phòng vào Hệ thống!.
+Quản lý Nhân viên:CRUD ,cấp tài khoản cho Nhân viên đăng nhập Hệ thống


--->OK đó là kế hoạch phát triển, users nào có ý kiến hay thì comment dùm,Thiện coi lại,có gì thì cho ý kiến!.

--->Chú ý:Các bạn nào vào Project của mình down tài liệu,source ,khi về cần chỉnh sửa lại một số thông số mới chạy đc.Một số tài khoản mail của các bạn phải tự cấu hình để chạy(nếu là đặt Phòng online) trong eHotelProject của mình.Các phiên bản trước mình cấu hình cho các bạn,nhưng đều này không an toàn cho account của mình,nên các bạn thông cảm!.

/**Các bạn nào cần ebook ASP.net MVC full thì vào http://code.google.com/p/desperado-coding/downloads/list để down nhé, ở đó tha hồ mà nghiên cứu,chúc tất cả vui:)**/