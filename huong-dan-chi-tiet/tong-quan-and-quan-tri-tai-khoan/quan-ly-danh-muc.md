---
description: >-
  Phân hệ này cho phép quản trị viên khởi tạo, phân loại và tổ chức cây dữ liệu
  dùng chung cho toàn hệ thống.
---

# Quản lý danh mục

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption></figcaption></figure>

<p align="center"><em>Màn hình tổng quan dữ liệu danh mục</em></p>

### 1. Tìm kiếm, Bộ lọc và Điều hướng Danh sách

Để tra cứu dữ liệu danh mục trên hệ thống, bạn sử dụng công cụ bộ lọc kết hợp thanh phân trang:

* **Tìm kiếm nâng cao:**
  * **Từ khóa:** Nhập tên hoặc mô tả danh mục cần tìm kiếm vào ô _**Từ khóa**_.
  * **Loại danh mục:** Sử dụng bộ lọc xổ xuống để phân loại theo mục đích sử dụng (_Đơn vị, Khóa học, Bài thi, Câu hỏi, Khung đề thi_).
  * **Trạng thái:** Lọc theo trạng thái vận hành (_Chỉ đang hoạt động_ hoặc _Chỉ tạm khóa_).
  * **Thao tác:** Nhấn \[**Áp dụng**] để hiển thị kết quả hoặc \[**Xóa lọc**] để làm mới bộ tìm kiếm.

<figure><img src="../../.gitbook/assets/image (16).png" alt=""><figcaption></figcaption></figure>

<p align="center"><em>Thanh bộ lọc tìm kiếm dữ liệu</em></p>

* **Cấu hình hiển thị và Phân trang:**
  * **Số lượng bản ghi (Cỡ trang):** Hệ thống mặc định hiển thị 10 bản ghi trên mỗi trang. Bạn có thể thay đổi số lượng hiển thị bằng cách chọn ô tùy chọn Cỡ trang ở góc dưới bên phải (Hỗ trợ hiển thị: _5, 10, 20, 50_ bản ghi).
  * **Chuyển trang:** Sử dụng các nút mũi tên \[**< Trước**], số trang \[1], \[2]... và \[**Sau >**] ở cuối trang để chuyển trang xem dữ liệu.

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption></figcaption></figure>

<p align="center"><em>Thanh phân trang dữ liệu</em></p>

### 2. Thao tác Khởi tạo Danh mục mới

Để thêm mới một danh mục hoặc phòng ban vào hệ thống, bạn thực hiện theo các bước sau:

* Bước 1: Nhấn nút \[Thêm danh mục] ở góc bên phải.
* Bước 2: Điền các trường thông tin bắt buộc trong Form:
  * Tên danh mục: Tên phòng ban hoặc nhóm nội dung (Ví dụ: _Tổng công ty, IT, Ban lãnh đạo_).
  * Loại danh mục: Chọn đúng phân loại phù hợp (Ví dụ: Chọn _Đơn vị_ nếu là cấu trúc phòng ban).
  * Danh mục cha: Nếu là phòng ban con, chọn đơn vị cấp trên trực tiếp (Ví dụ: Chọn danh mục cha là _Tổng công ty_, danh mục con là _IT_ để tạo cấu trúc phân cấp thụt lề `└─`).
* Bước 3: Nhấn \[Lưu] để hoàn tất.

> \[_Giao diện Form Thêm mới Danh mục_] _Ý nghĩa ảnh: Chụp màn hình pop-up Form khi bấm nút Thêm danh mục._

***

### 3. Quản lý và Hiệu chỉnh Danh sách

Tại bảng hiển thị Danh sách danh mục, Quản trị viên có thể theo dõi nhanh cơ cấu cây thư mục và thực hiện thay đổi trạng thái vận hành:

* Cấu trúc cây (Thụt lề): Hệ thống ký hiệu các danh mục con bằng biểu tượng `└─` phía dưới danh mục cha để biểu thị sơ đồ tổ chức trực quan.
* Chỉnh sửa / Khóa: Tại cột THAO TÁC, click vào nút \[Thao tác] tương ứng với bản ghi để:
  * Chọn \[Chỉnh sửa] nếu cần cập nhật lại tên hoặc mô tả.
  * Chọn \[Đổi trạng thái] sang _Tạm khóa_ nếu muốn ngừng sử dụng danh mục này trên hệ thống mà không làm mất dữ liệu lịch sử.

> \[_Bảng danh sách dữ liệu danh mục_] _Ý nghĩa ảnh: Chụp bảng danh sách hiển thị các bản ghi thực tế (Tổng công ty, Ban lãnh đạo, IT...)._
