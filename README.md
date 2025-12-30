# Phân tích và thiết kế hệ thống QUẢN LÝ SIÊU THỊ
Ngày nay khoa học kỹ thuật phát triển nhanh chóng, lao động trí óc dần thay thế cho lao động chân tay bằng những ứng dụng khoa học kỹ thuật. Và góp phần đắc lực trong cuộc cách mạng khoa học này phải kể đến lĩnh vực công nghệ thông tin Công nghệ thông tin được ứng dụng trong nhiều lĩnh vực. Như chúng ta đã biết, việc quản lý siêu thị của rất nhiều công ty, doanh nghiệp nói chung và siêu thị mini nói riêng vẫn tiến hành rất thủ công, việc ghi chép thông qua sổ sách gặp rất nhiều trở ngại, gần khó khăn cho người quản lý khi muốn xem xét tình trạng các mặt hàng còn hay hết, nguồn hàng đến từ đâu cũng như việc xuất kho hàng như thế nào, tình trạng bán hàng ra sao. Từ thực tế như vậy mà nhóm chúng em đã tiến hành xây dựng một phần mềm quản lý siêu thị cho một siêu thị.
Phần mềm là một chương trình cho phép người sử dụng thực hiện một cách nhanh chóng, chính xác việc nhập dữ liệu, lưu trữ cập nhật thông tin cho các loại sản phẩm, thực hiện yêu cầu tìm kiếm thông tin thống kê bán hàng hay báo cáo tài chính của siêu thị, với giao diện làm việc thân thiện dễ sử dụng. 
Mong rằng với phần mềm này chúng em có thể đóng góp được một phần nào đó vào sự phát triển của các siêu thị.
* Mô tả bài toán như sau
## Đặc tả yêu cầu của khách hàng
- Quản lý bán hàng
- Quản lý chương trình khuyến mãi
- Quản lý khách hàng
- Quản lý nhập khi
- Quản lý xuất kho
- Quản lý đơn giao hàng
- Quản lý nhân viên
- Quản lý nhà cung cấp
- Quản lý loại sản phẩm
- Quản lý tồn kho
- Quản lý sản phẩm
- Quản lý đại lý
- Báo cáo
- Quản lý tài khoản
- Đăng nhập
- Đăng xuất
## Đặc tả yêu cầu chức năng
- Dối với nhân viên
- Đối với nhân viên quản lý
## Biểu đồ Usecase
## Biểu đồ hoạt động (AD)
## Biểu đồ tuần tự (SD)
## Biểu đồ trạng thái 
## Thiết kế CSDL
Với mô hình quan hệ như sau:
Hóa đơn ( mã hóa đơn, mã nhân viên, ngày lập hóa đơn, mã sản phẩm, số lượng, giá tiền giảm)
Chi tiết hóa đơn ( mã hóa đơn, mã sản phẩm, thành tiền, tổng tiền)
Phiếu nhập kho ( mã phiếu nhập, ngày nhập, mã nhà cung cấp, mã nhân viên, mã sản phẩm, số lượng)
Chi tiết phiếu nhập (mã phiếu nhập, mã sản phẩm, thành tiền, tổng tiền)
Phiếu xuất kho ( mã phiếu xuất, ngày xuất, mã đại lý, mã nhân viên, mã sản phẩm, số lượng)
Chi tiết phiếu xuất ( mã phiếu xuất, mã sản phẩm, thành tiền, tổng tiền)
Chương trình khuyến mãi ( mã chương trình, tên chương trình, loại khuyến mãi, đối tượng áp dụng)
Chương trình khuyến mãi_Sản phẩm ( mã chương trình, mã sản phẩm, ngày bắt đầu, ngày kết thúc, giá tiền giảm)
Sản phẩm ( mã sản phẩm,mã loại sản phẩm, tên sản phẩm, tên loại sản phẩm, giá bán, đơn vị)
Phiếu đổi (mã phiếu đổi, mã hóa đơn, mã thẻ thành viên, mã sản phẩm, số lượng đổi, ngày lập phiếu, lý do đổi)
Phiếu trả (mã phiếu trả, mã hóa đơn, mã thẻ thành viên, mã sản phẩm, số lượng trả, ngày lập phiếu trả, lý do trả, số tiền trả khách)
Tài khoản (mã tài khoản, mã nhân viên, tên đăng nhập, mật khẩu, phân quyền)
Đại lý ( mã đại lý, tên đại lý, số điện thoại, địa chỉ, ngày hợp tác, ngày hết hạn, mô tả)
Khách hàng (mã khách hàng, mã thẻ thành viên, tên khách hàng, ngày sinh, giới tính, địa chỉ, số điện thoại, điểm tích lũy, mô tả)
Nhân viên (mã nhân viên, tên nhân viên, chức vụ, giới tính, ngày sinh, số điện thoại, địa chỉ, mô tả)
Nhà cung cấp (mã nhà cung cấp, tên nhà cung cấp, ngày hợp tác, ngày kết thúc, địa chỉ, số điện thoại, mô tả)
Loại sản phẩm (mã loại sản phẩm, tên loại sản phẩm, mã nhà cung cấp, mô tả)
## Thiết kế giao diện
https://www.figma.com/design/cFo6AoE4nqF7tJ1XpiFZNa/PTTKHT?node-id=0-1&p=f&t=0CPE5olE5PcamkhF-0
