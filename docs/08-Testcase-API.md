# Testcase API — DocGenie — Cây đèn thần dữ liệu (Alakathon 2026)

## [TC_DMGS_01] Danh mục dự án — Danh sách / tìm kiếm dự án

*Hiển thị danh sách dự án theo phạm vi quyền kèm chỉ số tổng quan danh mục; hỗ trợ tìm kiếm, lọc, sắp xếp và phân trang.*

**Endpoint**
`POST /api/v2/tc_dmgs_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Danh mục dự án — Danh sách / tìm kiếm dự án.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_DMGS_02] Danh mục dự án — Thêm mới dự án

*Khởi tạo dự án mới hoặc tạo từ hồ sơ thẩm định đã chốt; khai báo thông tin dự án, nhân sự và cấu hình kết nối.*

**Endpoint**
`POST /api/v2/tc_dmgs_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Danh mục dự án — Thêm mới dự án.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_DMGS_03] Danh mục dự án — Chỉnh sửa dự án

*Cập nhật thông tin dự án, danh sách nhân sự và cấu hình kết nối; ghi vết thay đổi.*

**Endpoint**
`POST /api/v2/tc_dmgs_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Danh mục dự án — Chỉnh sửa dự án.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_DMGS_04] Danh mục dự án — Xóa dự án

*Xóa dự án khỏi danh mục qua bước xác nhận; ghi vết người thực hiện và thời điểm.*

**Endpoint**
`POST /api/v2/tc_dmgs_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Danh mục dự án — Xóa dự án.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_DMGS_05] Danh mục dự án — Xem dự án cụ thể

*Mở dự án được chọn và chuyển phạm vi làm việc xuống dự án đó.*

**Endpoint**
`POST /api/v2/tc_dmgs_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Danh mục dự án — Xem dự án cụ thể.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_DMGS_06] Dashboard tổ chức — Xem tổng quan danh mục

*Hiển thị tiến độ, nguồn lực, PNL và rủi ro tổng hợp trên toàn danh mục dự án trong phạm vi quyền.*

**Endpoint**
`POST /api/v2/tc_dmgs_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Dashboard tổ chức — Xem tổng quan danh mục.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_DMGS_07] Dashboard tổ chức — Lọc theo tiêu chí

*Lọc số liệu theo khoảng thời gian, trạng thái dự án, khách hàng và nhóm nhân sự.*

**Endpoint**
`POST /api/v2/tc_dmgs_07`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Dashboard tổ chức — Lọc theo tiêu chí.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_DMGS_08] Dashboard tổ chức — Xem chi tiết chỉ số

*Mở nguồn số của một chỉ số, dẫn về dự án và mốc thời gian tương ứng.*

**Endpoint**
`POST /api/v2/tc_dmgs_08`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Dashboard tổ chức — Xem chi tiết chỉ số.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_DMGS_09] Dashboard tổ chức — Xuất báo cáo

*Kết xuất số liệu đang hiển thị thành tệp để mang đi làm việc.*

**Endpoint**
`POST /api/v2/tc_dmgs_09`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Dashboard tổ chức — Xuất báo cáo.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HCB_01] Hỏi toàn hệ thống — Đặt câu hỏi

*Nhận câu hỏi bằng ngôn ngữ tự nhiên trên toàn danh mục dự án; xác định phạm vi được phép theo vai trò trước khi truy vấn.*

**Endpoint**
`POST /api/v2/tc_hcb_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hỏi toàn hệ thống — Đặt câu hỏi.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HCB_02] Hỏi toàn hệ thống — Xem câu trả lời và nguồn số

*Hiển thị kết quả tổng hợp kèm dẫn nguồn và mốc thời gian; nêu rõ khi thiếu dữ liệu thay vì suy đoán.*

**Endpoint**
`POST /api/v2/tc_hcb_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hỏi toàn hệ thống — Xem câu trả lời và nguồn số.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HCB_03] Hỏi toàn hệ thống — Danh sách / tìm kiếm phiên hỏi

*Liệt kê các phiên hỏi đã thực hiện; tìm kiếm và mở lại nội dung phiên.*

**Endpoint**
`POST /api/v2/tc_hcb_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hỏi toàn hệ thống — Danh sách / tìm kiếm phiên hỏi.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HCB_04] Hỏi toàn hệ thống — Xóa phiên hỏi

*Xóa phiên hỏi của chính người dùng qua bước xác nhận.*

**Endpoint**
`POST /api/v2/tc_hcb_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hỏi toàn hệ thống — Xóa phiên hỏi.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HCB_05] Hỏi toàn hệ thống — Xuất kết quả

*Kết xuất câu trả lời kèm nguồn số thành báo cáo.*

**Endpoint**
`POST /api/v2/tc_hcb_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hỏi toàn hệ thống — Xuất kết quả.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HCB_06] Hộp cảnh báo chủ động — Danh sách / tìm kiếm cảnh báo

*Liệt kê cảnh báo đẩy tới vai trò đang đăng nhập; lọc theo loại cảnh báo, dự án và trạng thái đọc.*

**Endpoint**
`POST /api/v2/tc_hcb_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hộp cảnh báo chủ động — Danh sách / tìm kiếm cảnh báo.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HCB_07] Hộp cảnh báo chủ động — Xem chi tiết cảnh báo

*Hiển thị hiện tượng quan sát được, con số và ngưỡng đã chạm, kèm đường dẫn tới dự án liên quan.*

**Endpoint**
`POST /api/v2/tc_hcb_07`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hộp cảnh báo chủ động — Xem chi tiết cảnh báo.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HCB_08] Hộp cảnh báo chủ động — Đánh dấu đã xử lý

*Chuyển trạng thái cảnh báo sang đã đọc hoặc đã xử lý; ghi vết người thực hiện.*

**Endpoint**
`POST /api/v2/tc_hcb_08`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hộp cảnh báo chủ động — Đánh dấu đã xử lý.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HCB_09] Hộp cảnh báo chủ động — Cấu hình nhận cảnh báo

*Bật/tắt từng loại cảnh báo trong giới hạn vai trò cho phép.*

**Endpoint**
`POST /api/v2/tc_hcb_09`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hộp cảnh báo chủ động — Cấu hình nhận cảnh báo.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_01] Thẩm định hợp đồng mới — Tạo phiên thẩm định

*Tiếp nhận yêu cầu/RFP qua nhập liệu hoặc tải tệp và giá trị hợp đồng đang chào để bắt đầu thẩm định.*

**Endpoint**
`POST /api/v2/tc_hdt_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Thẩm định hợp đồng mới — Tạo phiên thẩm định.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_02] Thẩm định hợp đồng mới — Soát DSCN nháp và ULNL ước lượng

*Xem và điều chỉnh DSCN nháp cùng bảng ULNL ước lượng do hệ thống dựng từ yêu cầu.*

**Endpoint**
`POST /api/v2/tc_hdt_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Thẩm định hợp đồng mới — Soát DSCN nháp và ULNL ước lượng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_03] Thẩm định hợp đồng mới — Xem phần tái sử dụng

*Hiển thị các chức năng đã từng làm ở dự án cũ, dẫn được về dự án nguồn và giờ tiêu thật.*

**Endpoint**
`POST /api/v2/tc_hdt_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Thẩm định hợp đồng mới — Xem phần tái sử dụng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_04] Thẩm định hợp đồng mới — Chọn phương án nguồn lực

*Xem các phương án bố trí nhân sự đối chiếu nguồn lực toàn danh mục và chọn phương án áp dụng.*

**Endpoint**
`POST /api/v2/tc_hdt_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Thẩm định hợp đồng mới — Chọn phương án nguồn lực.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_05] Thẩm định hợp đồng mới — Ghi nhận kết luận

*Ghi quyết định nhận / đàm phán lại giá / từ chối kèm giả định đã dùng và lưu thành hồ sơ thẩm định.*

**Endpoint**
`POST /api/v2/tc_hdt_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Thẩm định hợp đồng mới — Ghi nhận kết luận.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_06] Hồ sơ thẩm định — Danh sách / tìm kiếm hồ sơ

*Liệt kê hồ sơ thẩm định đã lập; tìm kiếm theo khách hàng, thời điểm và kết luận.*

**Endpoint**
`POST /api/v2/tc_hdt_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hồ sơ thẩm định — Danh sách / tìm kiếm hồ sơ.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_07] Hồ sơ thẩm định — Xem chi tiết hồ sơ

*Mở nội dung hồ sơ: DSCN nháp, ULNL, phần tái sử dụng, phương án nguồn lực và kết luận.*

**Endpoint**
`POST /api/v2/tc_hdt_07`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hồ sơ thẩm định — Xem chi tiết hồ sơ.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_08] Hồ sơ thẩm định — Chỉnh sửa hồ sơ

*Cập nhật hồ sơ chưa chuyển thành dự án; ghi vết thay đổi.*

**Endpoint**
`POST /api/v2/tc_hdt_08`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hồ sơ thẩm định — Chỉnh sửa hồ sơ.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_09] Hồ sơ thẩm định — Xóa hồ sơ

*Xóa hồ sơ thẩm định qua bước xác nhận; ghi vết người thực hiện.*

**Endpoint**
`POST /api/v2/tc_hdt_09`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hồ sơ thẩm định — Xóa hồ sơ.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_10] Hồ sơ thẩm định — Xuất hồ sơ

*Kết xuất hồ sơ thẩm định thành tệp để trình duyệt và đàm phán.*

**Endpoint**
`POST /api/v2/tc_hdt_10`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hồ sơ thẩm định — Xuất hồ sơ.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_11] PNL & báo cáo tổng hợp — Xem PNL theo kỳ

*Tổng hợp PNL nhân sự theo tháng và theo dự án trong phạm vi quyền.*

**Endpoint**
`POST /api/v2/tc_hdt_11`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của PNL & báo cáo tổng hợp — Xem PNL theo kỳ.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_12] PNL & báo cáo tổng hợp — Xem MM phát sinh

*Tổng hợp MM đã tiêu và MM phát sinh do thay đổi trên toàn danh mục.*

**Endpoint**
`POST /api/v2/tc_hdt_12`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của PNL & báo cáo tổng hợp — Xem MM phát sinh.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_13] PNL & báo cáo tổng hợp — Lọc theo tiêu chí

*Lọc báo cáo theo kỳ, dự án, phòng ban và nhân sự.*

**Endpoint**
`POST /api/v2/tc_hdt_13`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của PNL & báo cáo tổng hợp — Lọc theo tiêu chí.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HDT_14] PNL & báo cáo tổng hợp — Xuất báo cáo

*Kết xuất báo cáo tổng hợp thành tệp.*

**Endpoint**
`POST /api/v2/tc_hdt_14`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của PNL & báo cáo tổng hợp — Xuất báo cáo.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_TTTL_01] Kho tri thức liên dự án — Danh sách / tìm kiếm tri thức

*Tra cứu luồng nghiệp vụ, ULNL và giờ tiêu thật của các dự án đã đóng; lọc theo loại hình dự án và khách hàng.*

**Endpoint**
`POST /api/v2/tc_tttl_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho tri thức liên dự án — Danh sách / tìm kiếm tri thức.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_TTTL_02] Kho tri thức liên dự án — Xem chi tiết chức năng đã làm

*Mở thông tin một chức năng: dự án nguồn, mức ULNL đã chấm, giờ tiêu thật và độ lệch ước lượng.*

**Endpoint**
`POST /api/v2/tc_tttl_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho tri thức liên dự án — Xem chi tiết chức năng đã làm.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_TTTL_03] Kho tri thức liên dự án — Chọn tái sử dụng

*Chọn chức năng để đưa sang dự án mới; hệ thống cấp mã ID mới và giữ trường nguồn tái sử dụng.*

**Endpoint**
`POST /api/v2/tc_tttl_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho tri thức liên dự án — Chọn tái sử dụng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_TTTL_04] Kho tri thức liên dự án — Kiểm soát truy cập theo quyền

*Với dự án ngoài phạm vi quyền, chỉ trả về có hay không có luồng tương tự, không trả nội dung.*

**Endpoint**
`POST /api/v2/tc_tttl_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho tri thức liên dự án — Kiểm soát truy cập theo quyền.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_TTTL_05] Kho biên bản họp — Danh sách / tìm kiếm biên bản

*Liệt kê biên bản họp toàn tổ chức trong phạm vi quyền; tìm kiếm theo tên, dự án, khách hàng và thời gian.*

**Endpoint**
`POST /api/v2/tc_tttl_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho biên bản họp — Danh sách / tìm kiếm biên bản.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_TTTL_06] Kho biên bản họp — Xem chi tiết biên bản

*Mở nội dung biên bản có cấu trúc: nội dung trao đổi, yêu cầu nghe được và điểm chưa rõ.*

**Endpoint**
`POST /api/v2/tc_tttl_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho biên bản họp — Xem chi tiết biên bản.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_TTTL_07] Kho biên bản họp — Xóa biên bản

*Xóa biên bản qua bước xác nhận; ghi vết người thực hiện.*

**Endpoint**
`POST /api/v2/tc_tttl_07`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho biên bản họp — Xóa biên bản.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_NS_01] Danh bạ nhân sự — Danh sách / tìm kiếm nhân sự

*Liệt kê nhân sự dùng chung toàn tổ chức kèm tổng tải hiện tại; tìm kiếm theo tên, phòng ban và vai trò.*

**Endpoint**
`POST /api/v2/tc_ns_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Danh bạ nhân sự — Danh sách / tìm kiếm nhân sự.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_NS_02] Danh bạ nhân sự — Thêm mới nhân sự

*Khai báo nhân sự mới với các trường dùng chung: tên, phòng ban, vai trò, email và định mức PNL tháng.*

**Endpoint**
`POST /api/v2/tc_ns_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Danh bạ nhân sự — Thêm mới nhân sự.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_NS_03] Danh bạ nhân sự — Chỉnh sửa nhân sự

*Cập nhật thông tin nhân sự; ghi vết thay đổi.*

**Endpoint**
`POST /api/v2/tc_ns_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Danh bạ nhân sự — Chỉnh sửa nhân sự.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_NS_04] Danh bạ nhân sự — Xóa nhân sự

*Xóa nhân sự khỏi danh bạ qua bước xác nhận; chặn xóa khi đang tham gia dự án chưa đóng.*

**Endpoint**
`POST /api/v2/tc_ns_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Danh bạ nhân sự — Xóa nhân sự.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_NS_05] Danh bạ nhân sự — Xem chi tiết nhân sự

*Hiển thị các dự án đang tham gia, %tham gia, thời gian tham gia và tổng tải liên dự án.*

**Endpoint**
`POST /api/v2/tc_ns_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Danh bạ nhân sự — Xem chi tiết nhân sự.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_01] Quản trị người dùng — Danh sách / tìm kiếm người dùng

*Liệt kê tài khoản người dùng trong tổ chức; tìm kiếm theo tên, email, phòng ban và vai trò; lọc theo trạng thái hoạt động.*

**Endpoint**
`POST /api/v2/tc_ht_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Quản trị người dùng — Danh sách / tìm kiếm người dùng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_02] Quản trị người dùng — Thêm mới người dùng

*Khai báo tài khoản mới, liên kết với bản ghi trong Danh bạ nhân sự và gán vai trò ban đầu.*

**Endpoint**
`POST /api/v2/tc_ht_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Quản trị người dùng — Thêm mới người dùng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_03] Quản trị người dùng — Chỉnh sửa người dùng

*Cập nhật thông tin tài khoản và vai trò được gán; ghi vết thay đổi.*

**Endpoint**
`POST /api/v2/tc_ht_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Quản trị người dùng — Chỉnh sửa người dùng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_04] Quản trị người dùng — Khóa / mở khóa người dùng

*Ngừng hoặc khôi phục quyền truy cập của tài khoản mà không xóa dữ liệu lịch sử.*

**Endpoint**
`POST /api/v2/tc_ht_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Quản trị người dùng — Khóa / mở khóa người dùng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_05] Quản trị người dùng — Xóa người dùng

*Xóa tài khoản qua bước xác nhận; ghi vết người thực hiện và thời điểm.*

**Endpoint**
`POST /api/v2/tc_ht_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Quản trị người dùng — Xóa người dùng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_06] Quản trị vai trò — Danh sách / tìm kiếm vai trò

*Liệt kê các vai trò của hệ thống: Giám đốc, PM, BA, QA, Dev, HR, BD, Kế toán, Quản trị hệ thống.*

**Endpoint**
`POST /api/v2/tc_ht_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Quản trị vai trò — Danh sách / tìm kiếm vai trò.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_07] Quản trị vai trò — Thêm mới vai trò

*Tạo vai trò mới và khai báo nhóm quyền tương ứng.*

**Endpoint**
`POST /api/v2/tc_ht_07`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Quản trị vai trò — Thêm mới vai trò.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_08] Quản trị vai trò — Chỉnh sửa vai trò

*Cập nhật tên vai trò và nhóm quyền; ghi vết thay đổi.*

**Endpoint**
`POST /api/v2/tc_ht_08`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Quản trị vai trò — Chỉnh sửa vai trò.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_09] Quản trị vai trò — Xóa vai trò

*Xóa vai trò qua bước xác nhận; chặn xóa khi còn người dùng đang được gán.*

**Endpoint**
`POST /api/v2/tc_ht_09`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Quản trị vai trò — Xóa vai trò.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_10] Phạm vi dữ liệu — Cấu hình phạm vi theo vai trò

*Khai báo vùng dữ liệu của từng vai trò theo hai trục: theo dự án và theo loại dữ liệu (tài liệu / tiến độ / nhân sự / chi phí / hiệu suất cá nhân).*

**Endpoint**
`POST /api/v2/tc_ht_10`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phạm vi dữ liệu — Cấu hình phạm vi theo vai trò.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_11] Phạm vi dữ liệu — Xem ma trận phân quyền

*Hiển thị bảng đối chiếu vai trò ↔ vùng dữ liệu để rà soát trước khi áp dụng.*

**Endpoint**
`POST /api/v2/tc_ht_11`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phạm vi dữ liệu — Xem ma trận phân quyền.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_12] Phạm vi dữ liệu — Ghi vết thay đổi phân quyền

*Lưu vết mọi thay đổi cấu hình phân quyền: người thực hiện, thời điểm và nội dung thay đổi.*

**Endpoint**
`POST /api/v2/tc_ht_12`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phạm vi dữ liệu — Ghi vết thay đổi phân quyền.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_13] Tham số ngưỡng — Danh sách tham số ngưỡng

*Liệt kê toàn bộ ngưỡng cảnh báo cấu hình ở tầng hệ thống: ngưỡng lãi/lỗ, ngưỡng lệch logwork, ngưỡng tổng tải nhân sự, ngưỡng burn rate.*

**Endpoint**
`POST /api/v2/tc_ht_13`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Tham số ngưỡng — Danh sách tham số ngưỡng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_14] Tham số ngưỡng — Chỉnh sửa tham số ngưỡng

*Cập nhật giá trị ngưỡng; hiển thị giá trị mặc định và giá trị đang áp dụng; ghi vết thay đổi.*

**Endpoint**
`POST /api/v2/tc_ht_14`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Tham số ngưỡng — Chỉnh sửa tham số ngưỡng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_15] Tham số ngưỡng — Khôi phục giá trị mặc định

*Đưa một hoặc nhiều tham số về giá trị khởi điểm.*

**Endpoint**
`POST /api/v2/tc_ht_15`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Tham số ngưỡng — Khôi phục giá trị mặc định.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_16] Kết nối dùng chung — Danh sách kết nối

*Liệt kê các kết nối dùng chung toàn tổ chức: Git, Jira, Figma, kênh mail và model AI.*

**Endpoint**
`POST /api/v2/tc_ht_16`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kết nối dùng chung — Danh sách kết nối.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_17] Kết nối dùng chung — Thêm mới kết nối

*Khai báo kết nối mới kèm thông tin xác thực tương ứng.*

**Endpoint**
`POST /api/v2/tc_ht_17`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kết nối dùng chung — Thêm mới kết nối.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_18] Kết nối dùng chung — Chỉnh sửa kết nối

*Cập nhật cấu hình kết nối; ghi vết thay đổi.*

**Endpoint**
`POST /api/v2/tc_ht_18`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kết nối dùng chung — Chỉnh sửa kết nối.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_19] Kết nối dùng chung — Kiểm tra kết nối

*Thực hiện Test connection và báo trạng thái kết nối sống/chết.*

**Endpoint**
`POST /api/v2/tc_ht_19`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kết nối dùng chung — Kiểm tra kết nối.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_20] Kết nối dùng chung — Xóa kết nối

*Xóa kết nối qua bước xác nhận; cảnh báo các dự án đang sử dụng.*

**Endpoint**
`POST /api/v2/tc_ht_20`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kết nối dùng chung — Xóa kết nối.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_21] Kho Skill & Rule — Danh sách / tìm kiếm skill

*Liệt kê bộ skill sinh nội dung theo từng loại tài liệu 01–12; tìm kiếm theo tên và loại tài liệu.*

**Endpoint**
`POST /api/v2/tc_ht_21`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho Skill & Rule — Danh sách / tìm kiếm skill.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_22] Kho Skill & Rule — Xem chi tiết skill

*Mở nội dung skill: template, rule áp dụng và phiên bản đang hoạt động.*

**Endpoint**
`POST /api/v2/tc_ht_22`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho Skill & Rule — Xem chi tiết skill.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_23] Kho Skill & Rule — Thêm mới skill

*Khai báo skill mới cho một loại tài liệu hoặc một nghiệp vụ sinh nội dung.*

**Endpoint**
`POST /api/v2/tc_ht_23`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho Skill & Rule — Thêm mới skill.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_24] Kho Skill & Rule — Chỉnh sửa skill

*Cập nhật template và rule của skill; sinh phiên bản mới, giữ lịch sử phiên bản cũ.*

**Endpoint**
`POST /api/v2/tc_ht_24`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho Skill & Rule — Chỉnh sửa skill.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_25] Kho Skill & Rule — Xóa skill

*Xóa skill qua bước xác nhận; chặn xóa khi là skill bắt buộc của một loại tài liệu.*

**Endpoint**
`POST /api/v2/tc_ht_25`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho Skill & Rule — Xóa skill.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_26] Kho Skill & Rule — Quản lý bảng tham chiếu ULNL

*Khai báo và cập nhật bảng tham chiếu mã/mức, danh sách task chuẩn và quy đổi giờ → MD → MM.*

**Endpoint**
`POST /api/v2/tc_ht_26`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho Skill & Rule — Quản lý bảng tham chiếu ULNL.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_27] Kho Skill & Rule — Quản lý rule kiểm tra

*Khai báo các rule tự kiểm ở tầng hệ thống, gồm rule đối chiếu MH_ULNL_Total với tổng Original Estimate.*

**Endpoint**
`POST /api/v2/tc_ht_27`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Kho Skill & Rule — Quản lý rule kiểm tra.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_28] Log truy vết — Danh sách / tìm kiếm log

*Liệt kê toàn bộ vết thao tác có hậu quả trong hệ thống; tìm kiếm và lọc theo người thực hiện, dự án, loại thao tác và khoảng thời gian.*

**Endpoint**
`POST /api/v2/tc_ht_28`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Log truy vết — Danh sách / tìm kiếm log.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_29] Log truy vết — Xem chi tiết log

*Hiển thị nội dung một vết: người thực hiện, thời điểm, đối tượng tác động và nội dung thay đổi.*

**Endpoint**
`POST /api/v2/tc_ht_29`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Log truy vết — Xem chi tiết log.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [TC_HT_30] Log truy vết — Xuất log

*Kết xuất danh sách log theo bộ lọc đang áp dụng thành tệp.*

**Endpoint**
`POST /api/v2/tc_ht_30`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Log truy vết — Xuất log.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_CH_01] Thông tin dự án — Xem thông tin dự án

*Hiển thị tên, mô tả, giá trị hợp đồng (MM) và thời gian phát triển của dự án.*

**Endpoint**
`POST /api/v2/da_ch_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Thông tin dự án — Xem thông tin dự án.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_CH_02] Thông tin dự án — Chỉnh sửa thông tin dự án

*Cập nhật thông tin dự án; ghi vết người thực hiện và thời điểm.*

**Endpoint**
`POST /api/v2/da_ch_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Thông tin dự án — Chỉnh sửa thông tin dự án.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_CH_03] Nhân sự dự án — Danh sách / tìm kiếm nhân sự dự án

*Liệt kê nhân sự tham gia dự án kèm vai trò, %tham gia và thời gian tham gia.*

**Endpoint**
`POST /api/v2/da_ch_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Nhân sự dự án — Danh sách / tìm kiếm nhân sự dự án.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_CH_04] Nhân sự dự án — Thêm nhân sự vào dự án

*Chọn nhân sự từ Danh bạ nhân sự và khai %tham gia cùng thời gian tham gia trong dự án.*

**Endpoint**
`POST /api/v2/da_ch_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Nhân sự dự án — Thêm nhân sự vào dự án.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_CH_05] Nhân sự dự án — Chỉnh sửa phân bổ nhân sự

*Cập nhật %tham gia và thời gian tham gia của nhân sự trong dự án.*

**Endpoint**
`POST /api/v2/da_ch_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Nhân sự dự án — Chỉnh sửa phân bổ nhân sự.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_CH_06] Nhân sự dự án — Gỡ nhân sự khỏi dự án

*Loại nhân sự khỏi dự án qua bước xác nhận; giữ nguyên logwork đã ghi nhận.*

**Endpoint**
`POST /api/v2/da_ch_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Nhân sự dự án — Gỡ nhân sự khỏi dự án.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_CH_07] Nhân sự dự án — Cảnh báo trùng lịch liên dự án

*Cộng %tham gia của nhân sự trên mọi dự án có thời gian giao nhau; cảnh báo khi vượt ngưỡng và ghi nhận trường hợp được chấp nhận.*

**Endpoint**
`POST /api/v2/da_ch_07`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Nhân sự dự án — Cảnh báo trùng lịch liên dự án.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_CH_08] Cấu hình kết nối — Khai báo kết nối Git / Jira / Figma

*Khai báo repo Git duy nhất, tên miền và token Jira, kết nối Figma cho dự án.*

**Endpoint**
`POST /api/v2/da_ch_08`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Cấu hình kết nối — Khai báo kết nối Git / Jira / Figma.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_CH_09] Cấu hình kết nối — Kiểm tra kết nối và đối chiếu email Jira

*Chạy Test connection, đối chiếu email nhân sự với user Jira và báo các dòng không map được.*

**Endpoint**
`POST /api/v2/da_ch_09`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Cấu hình kết nối — Kiểm tra kết nối và đối chiếu email Jira.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_CH_10] Cảnh báo khả thi — Xem cảnh báo khả thi lãi/lỗ

*Hiển thị chi phí đội, margin và nhãn lãi/lỗ theo công thức, kèm mốc so sánh từ dự án cũ cùng loại hình.*

**Endpoint**
`POST /api/v2/da_ch_10`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Cảnh báo khả thi — Xem cảnh báo khả thi lãi/lỗ.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_CH_11] Cảnh báo khả thi — Xem vai trò được quyền đọc dự án

*Hiển thị danh sách vai trò ngoài đội đang có quyền đọc dự án theo cấu hình phân quyền.*

**Endpoint**
`POST /api/v2/da_ch_11`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Cảnh báo khả thi — Xem vai trò được quyền đọc dự án.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TL_01] Phiên chat dự án — Danh sách / tìm kiếm phiên chat

*Liệt kê các phiên chat của dự án; tìm kiếm và mở lại nội dung phiên.*

**Endpoint**
`POST /api/v2/da_tl_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phiên chat dự án — Danh sách / tìm kiếm phiên chat.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TL_02] Phiên chat dự án — Khai thác yêu cầu qua chat

*Nêu yêu cầu bằng ngôn ngữ tự nhiên để hệ thống dựng nội dung; xem kết quả trực tiếp trong phiên.*

**Endpoint**
`POST /api/v2/da_tl_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phiên chat dự án — Khai thác yêu cầu qua chat.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TL_03] Phiên chat dự án — Gọi biên bản họp vào ngữ cảnh

*Nạp nội dung một biên bản trong Kho biên bản họp vào phiên khi được gọi đúng tên.*

**Endpoint**
`POST /api/v2/da_tl_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phiên chat dự án — Gọi biên bản họp vào ngữ cảnh.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TL_04] Danh sách chức năng (Bản 01) — Chốt DSCN

*Chốt danh sách chức năng theo ba cách: import tệp, tương tác chat hoặc tái sử dụng từ dự án cũ; gán mã ID cố định cho từng chức năng.*

**Endpoint**
`POST /api/v2/da_tl_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Danh sách chức năng (Bản 01) — Chốt DSCN.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TL_05] Danh sách chức năng (Bản 01) — Tái sử dụng chức năng từ dự án cũ

*Chọn chức năng từ dự án đã làm; cấp mã ID mới, giữ trường nguồn tái sử dụng và hiển thị giờ tiêu thật ở dự án gốc.*

**Endpoint**
`POST /api/v2/da_tl_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Danh sách chức năng (Bản 01) — Tái sử dụng chức năng từ dự án cũ.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TL_06] Danh sách chức năng (Bản 01) — Kiểm tra rule DSCN

*Chuẩn hóa mã ID và kiểm rule trước khi ghi: không trùng mã, không sót quan hệ cha/con.*

**Endpoint**
`POST /api/v2/da_tl_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Danh sách chức năng (Bản 01) — Kiểm tra rule DSCN.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TL_07] Tài liệu phái sinh (Bản 02–12) — Sinh tài liệu phái sinh

*Sinh nháp PTYC, chi tiết màn hình, TKCT, Plan, Testcase, ULNL, TKCSDL, TKTT và HDSD từ các bản trước theo skill của từng loại.*

**Endpoint**
`POST /api/v2/da_tl_07`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Tài liệu phái sinh (Bản 02–12) — Sinh tài liệu phái sinh.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TL_08] Tài liệu phái sinh (Bản 02–12) — Chọn nhịp sinh tài liệu

*Chọn sinh trọn bộ hoặc theo từng chức năng/nhóm; hệ thống gợi ý lựa chọn khi khối lượng lớn.*

**Endpoint**
`POST /api/v2/da_tl_08`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Tài liệu phái sinh (Bản 02–12) — Chọn nhịp sinh tài liệu.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TL_09] Tài liệu phái sinh (Bản 02–12) — Soát và chỉnh nội dung trong phiên

*Xem nội dung sinh ra ngay trong phiên chat và yêu cầu chỉnh sửa trước khi ghi vào hệ thống.*

**Endpoint**
`POST /api/v2/da_tl_09`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Tài liệu phái sinh (Bản 02–12) — Soát và chỉnh nội dung trong phiên.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TL_10] Tài liệu phái sinh (Bản 02–12) — Hỏi đáp trên bộ tài liệu

*Đặt câu hỏi về một chức năng và nhận câu trả lời có trích dẫn đúng bản và mục tài liệu.*

**Endpoint**
`POST /api/v2/da_tl_10`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Tài liệu phái sinh (Bản 02–12) — Hỏi đáp trên bộ tài liệu.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TK_01] Prototype — Xem prototype bấm được

*Mở prototype HTML và thao tác thử theo luồng màn hình của chức năng.*

**Endpoint**
`POST /api/v2/da_tk_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Prototype — Xem prototype bấm được.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TK_02] Prototype — Đồng bộ thiết kế Figma

*Dựng màn theo bộ component và lưu link Figma của dự án.*

**Endpoint**
`POST /api/v2/da_tk_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Prototype — Đồng bộ thiết kế Figma.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TK_03] Góp ý thiết kế — Đặt comment

*Đặt comment neo theo phần tử hoặc khối màn hình trên prototype.*

**Endpoint**
`POST /api/v2/da_tk_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Góp ý thiết kế — Đặt comment.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TK_04] Góp ý thiết kế — Đồng ý xử lý comment

*Đánh dấu comment cần xử lý; hệ thống chỉ sửa thiết kế theo comment ở trạng thái này.*

**Endpoint**
`POST /api/v2/da_tk_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Góp ý thiết kế — Đồng ý xử lý comment.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TK_05] Góp ý thiết kế — Xác nhận đóng comment

*Người dùng xác nhận kết quả xử lý để đóng comment; hệ thống không tự đóng.*

**Endpoint**
`POST /api/v2/da_tk_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Góp ý thiết kế — Xác nhận đóng comment.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TK_06] Góp ý thiết kế — Xem lịch sử vòng sửa

*Đối chiếu thiết kế trước và sau của từng vòng xử lý comment.*

**Endpoint**
`POST /api/v2/da_tk_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Góp ý thiết kế — Xem lịch sử vòng sửa.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BT_01] Bộ tài liệu — Danh sách / tìm kiếm bộ tài liệu

*Liệt kê các bộ tài liệu của dự án kèm trạng thái, tiến độ x/12 và phần đã thay đổi so với bộ trước.*

**Endpoint**
`POST /api/v2/da_bt_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Bộ tài liệu — Danh sách / tìm kiếm bộ tài liệu.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BT_02] Bộ tài liệu — Tạo bộ tài liệu mới

*Khởi tạo bộ mới kế thừa bản hoạt động của từng loại từ bộ vừa đóng; chọn các loại đánh N/A.*

**Endpoint**
`POST /api/v2/da_bt_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Bộ tài liệu — Tạo bộ tài liệu mới.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BT_03] Bộ tài liệu — Xem chi tiết bộ tài liệu

*Hiển thị từng loại tài liệu trong bộ: tên tệp, định dạng, dung lượng, thời gian xuất, người tạo và trạng thái Done/Null/N/A.*

**Endpoint**
`POST /api/v2/da_bt_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Bộ tài liệu — Xem chi tiết bộ tài liệu.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BT_04] Phiên bản tài liệu — Export tài liệu

*Sinh tệp mang ra ngoài để gửi khách hàng; không tạo phiên bản và không mở khóa bước sau.*

**Endpoint**
`POST /api/v2/da_bt_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phiên bản tài liệu — Export tài liệu.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BT_05] Phiên bản tài liệu — Xuất phiên bản tài liệu

*Sinh một phiên bản mới của một loại vào bộ đang mở; phiên bản mới trở thành bản hoạt động.*

**Endpoint**
`POST /api/v2/da_bt_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phiên bản tài liệu — Xuất phiên bản tài liệu.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BT_06] Phiên bản tài liệu — Chọn bản hoạt động

*Chọn phiên bản của một loại làm bản sẽ được commit; mặc định là bản mới nhất.*

**Endpoint**
`POST /api/v2/da_bt_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phiên bản tài liệu — Chọn bản hoạt động.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BT_07] Phiên bản tài liệu — So sánh phiên bản

*Đối chiếu nội dung giữa hai phiên bản của một loại tài liệu.*

**Endpoint**
`POST /api/v2/da_bt_07`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phiên bản tài liệu — So sánh phiên bản.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BT_08] Commit & khôi phục — Commit bộ lên Git

*Chụp bản hoạt động của từng loại thành mốc verXX và đóng bộ; chặn commit khi còn loại áp dụng chưa có phiên bản.*

**Endpoint**
`POST /api/v2/da_bt_08`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Commit & khôi phục — Commit bộ lên Git.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BT_09] Commit & khôi phục — Khôi phục bộ

*Đưa đồng loạt cả bộ về một mốc verXX đã commit.*

**Endpoint**
`POST /api/v2/da_bt_09`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Commit & khôi phục — Khôi phục bộ.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_UL_01] ULNL — Xem bảng ước lượng nỗ lực

*Hiển thị nỗ lực theo chức năng và ba nhóm task Giải pháp / Phát triển / Kiểm thử, quy đổi giờ → MD → MM.*

**Endpoint**
`POST /api/v2/da_ul_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của ULNL — Xem bảng ước lượng nỗ lực.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_UL_02] ULNL — Điều chỉnh nỗ lực qua phiên chat

*PM yêu cầu chỉnh nỗ lực của một dòng qua chat; dòng đã chỉnh mang dấu nguồn PM điều chỉnh.*

**Endpoint**
`POST /api/v2/da_ul_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của ULNL — Điều chỉnh nỗ lực qua phiên chat.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_UL_03] ULNL — Đối chiếu MM ULNL với MM hợp đồng

*So MM thực tế theo chức năng với MM hợp đồng đã khai để xác định mức khớp hay vượt.*

**Endpoint**
`POST /api/v2/da_ul_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của ULNL — Đối chiếu MM ULNL với MM hợp đồng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_UL_04] Task Jira — Sinh cây task Jira

*Sinh Epic / Story / Sub-task theo chức năng và loại man-hour, gắn mã chức năng và bộ tài liệu.*

**Endpoint**
`POST /api/v2/da_ul_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Task Jira — Sinh cây task Jira.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_UL_05] Task Jira — Đồng bộ man-hour sang Jira

*Cập nhật Original Estimate vào sub-task theo cặp khóa mã chức năng và loại man-hour.*

**Endpoint**
`POST /api/v2/da_ul_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Task Jira — Đồng bộ man-hour sang Jira.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_UL_06] Task Jira — Kiểm tra đối chiếu man-hour

*Chạy rule đối chiếu MH_ULNL_Total với tổng Original Estimate và báo lỗi khi sinh task thiếu, thừa hoặc sai.*

**Endpoint**
`POST /api/v2/da_ul_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Task Jira — Kiểm tra đối chiếu man-hour.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TD_01] Yêu cầu thay đổi — Danh sách / tìm kiếm yêu cầu

*Liệt kê yêu cầu nghiệp vụ cần trao đổi theo hai tab; lọc theo trạng thái, chức năng và người chốt.*

**Endpoint**
`POST /api/v2/da_td_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Yêu cầu thay đổi — Danh sách / tìm kiếm yêu cầu.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TD_02] Yêu cầu thay đổi — Tạo yêu cầu thay đổi

*Tạo yêu cầu với chức năng liên quan, người chốt, người liên quan và nội dung thay đổi.*

**Endpoint**
`POST /api/v2/da_td_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Yêu cầu thay đổi — Tạo yêu cầu thay đổi.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TD_03] Yêu cầu thay đổi — Trao đổi trong phiên

*Trao đổi nội dung thay đổi trong phiên chat nhóm cho tới khi chốt.*

**Endpoint**
`POST /api/v2/da_td_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Yêu cầu thay đổi — Trao đổi trong phiên.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TD_04] Yêu cầu thay đổi — Hủy yêu cầu thay đổi

*Người tạo hủy yêu cầu đang chờ xử lý kèm lý do; ghi vết sự kiện.*

**Endpoint**
`POST /api/v2/da_td_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Yêu cầu thay đổi — Hủy yêu cầu thay đổi.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TD_05] Yêu cầu thay đổi — Chốt hoặc từ chối yêu cầu

*Người chốt chấp nhận hoặc từ chối yêu cầu kèm lý do; phiên đóng sau khi chốt.*

**Endpoint**
`POST /api/v2/da_td_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Yêu cầu thay đổi — Chốt hoặc từ chối yêu cầu.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TD_06] Lan tỏa thay đổi — Xác nhận phạm vi ảnh hưởng

*Tick chọn các bản tài liệu và task Jira bị ảnh hưởng theo đề xuất kèm mức tác động, lý do và hệ quả MM; ghi vết lần bấm.*

**Endpoint**
`POST /api/v2/da_td_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Lan tỏa thay đổi — Xác nhận phạm vi ảnh hưởng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TD_07] Lan tỏa thay đổi — Gửi mail thông báo thay đổi

*Gửi mail tới toàn đội theo hai nhịp: chốt phạm vi và công bố bộ mới.*

**Endpoint**
`POST /api/v2/da_td_07`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Lan tỏa thay đổi — Gửi mail thông báo thay đổi.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TD_08] Phát sinh MM — Xem báo cáo phát sinh MM

*Hiển thị phạm vi ban đầu, danh sách thay đổi, MM phát sinh theo từng thay đổi và ba con số MM tổng hợp.*

**Endpoint**
`POST /api/v2/da_td_08`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phát sinh MM — Xem báo cáo phát sinh MM.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_TD_09] Phát sinh MM — Xuất báo cáo phát sinh MM

*Kết xuất báo cáo giải trình để đề xuất bổ sung MM với khách hàng.*

**Endpoint**
`POST /api/v2/da_td_09`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phát sinh MM — Xuất báo cáo phát sinh MM.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_KT_01] Phiên kiểm thử — Danh sách / tìm kiếm phiên kiểm thử

*Liệt kê các phiên kiểm thử của dự án; lọc theo phạm vi, trạng thái và thời gian chạy.*

**Endpoint**
`POST /api/v2/da_kt_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phiên kiểm thử — Danh sách / tìm kiếm phiên kiểm thử.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_KT_02] Phiên kiểm thử — Tạo phiên kiểm thử

*Tạo phiên và cấu hình phạm vi kiểm thử cùng thông số môi trường.*

**Endpoint**
`POST /api/v2/da_kt_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phiên kiểm thử — Tạo phiên kiểm thử.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_KT_03] Phiên kiểm thử — Chạy kiểm thử

*Sinh ma trận test từ Testcase và thực thi trên commit mới nhất của chức năng.*

**Endpoint**
`POST /api/v2/da_kt_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phiên kiểm thử — Chạy kiểm thử.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_KT_04] Phiên kiểm thử — Xem kết quả theo case

*Hiển thị kết quả từng case ở ba trạng thái Pass / Fail / Không kiểm được tự động.*

**Endpoint**
`POST /api/v2/da_kt_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phiên kiểm thử — Xem kết quả theo case.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_KT_05] Phiên kiểm thử — Xuất kết quả kiểm thử

*Kết xuất kết quả phiên kiểm thử thành tệp.*

**Endpoint**
`POST /api/v2/da_kt_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phiên kiểm thử — Xuất kết quả kiểm thử.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_KT_06] Phiên kiểm thử — Xóa phiên kiểm thử

*Xóa phiên kiểm thử qua bước xác nhận; ghi vết người thực hiện.*

**Endpoint**
`POST /api/v2/da_kt_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Phiên kiểm thử — Xóa phiên kiểm thử.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_KT_07] Quản lý lỗi — Log bug lên Jira

*Dựng nội dung bug từ case fail, chọn người xử lý và gắn bug về task của chức năng; chống trùng theo cặp chức năng và mã case.*

**Endpoint**
`POST /api/v2/da_kt_07`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Quản lý lỗi — Log bug lên Jira.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_DB_01] Dashboard dự án — Xem khu Tiến độ

*Hiển thị tiến độ ba tuyến BA/Dev/QA theo số task và theo trọng số giờ, kèm mốc phạm vi đổi và dự báo trễ.*

**Endpoint**
`POST /api/v2/da_db_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Dashboard dự án — Xem khu Tiến độ.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_DB_02] Dashboard dự án — Xem khu Nguồn lực

*Hiển thị MM phạm vi hiện hành, MM sunk, MM tổng tiêu so MM hợp đồng và nhân sự đang vượt tổng tải.*

**Endpoint**
`POST /api/v2/da_db_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Dashboard dự án — Xem khu Nguồn lực.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_DB_03] Dashboard dự án — Xem khu Hiệu suất

*Hiển thị độ lệch giữa logwork và ULNL kèm cảnh báo làm lố; phân quyền theo người.*

**Endpoint**
`POST /api/v2/da_db_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Dashboard dự án — Xem khu Hiệu suất.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_DB_04] Dashboard dự án — Xem khu Chất lượng

*Hiển thị bug mở/đóng, regression, số case không kiểm được tự động và độ phủ HDSD.*

**Endpoint**
`POST /api/v2/da_db_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Dashboard dự án — Xem khu Chất lượng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_DB_05] Dashboard dự án — Xem khu Phát sinh MM

*Hiển thị báo cáo giải trình thay đổi và đề xuất bổ sung MM.*

**Endpoint**
`POST /api/v2/da_db_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Dashboard dự án — Xem khu Phát sinh MM.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_DB_06] Dashboard dự án — Chỉnh Plan đề xuất

*PM chỉnh kế hoạch đè lên bản hệ thống đề xuất; lưu tách hai bản để đối chiếu.*

**Endpoint**
`POST /api/v2/da_db_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Dashboard dự án — Chỉnh Plan đề xuất.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_DB_07] Dashboard dự án — Xuất báo cáo dashboard

*Kết xuất số liệu đang hiển thị thành tệp.*

**Endpoint**
`POST /api/v2/da_db_07`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Dashboard dự án — Xuất báo cáo dashboard.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BB_01] Biên bản họp dự án — Danh sách / tìm kiếm biên bản

*Liệt kê biên bản họp của dự án kèm trạng thái Nháp / Đã gửi / Đã xác nhận.*

**Endpoint**
`POST /api/v2/da_bb_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Biên bản họp dự án — Danh sách / tìm kiếm biên bản.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BB_02] Biên bản họp dự án — Ghi âm hoặc tải bản ghi

*Ghi trực tiếp hoặc tải tệp bản ghi cuộc họp để hệ thống dựng biên bản có cấu trúc.*

**Endpoint**
`POST /api/v2/da_bb_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Biên bản họp dự án — Ghi âm hoặc tải bản ghi.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BB_03] Biên bản họp dự án — Soát và chỉnh biên bản

*Xem và chỉnh nội dung trao đổi, yêu cầu nghe được và điểm chưa rõ trước khi lưu.*

**Endpoint**
`POST /api/v2/da_bb_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Biên bản họp dự án — Soát và chỉnh biên bản.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BB_04] Biên bản họp dự án — Gửi mail xác nhận

*Soát nội dung mail nháp và gửi xác nhận biên bản tới người tham dự.*

**Endpoint**
`POST /api/v2/da_bb_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Biên bản họp dự án — Gửi mail xác nhận.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BB_05] Biên bản họp dự án — Cập nhật trạng thái biên bản

*Chuyển trạng thái biên bản theo tiến trình xác nhận.*

**Endpoint**
`POST /api/v2/da_bb_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Biên bản họp dự án — Cập nhật trạng thái biên bản.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [DA_BB_06] Biên bản họp dự án — Xóa biên bản

*Xóa biên bản qua bước xác nhận; ghi vết người thực hiện.*

**Endpoint**
`POST /api/v2/da_bb_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Biên bản họp dự án — Xóa biên bản.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [CC_XT_01] Xác thực — Đăng nhập

*Xác thực người dùng bằng tài khoản được cấp và khởi tạo phiên làm việc theo vai trò mặc định.*

**Endpoint**
`POST /api/v2/cc_xt_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Xác thực — Đăng nhập.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [CC_XT_02] Xác thực — Đăng xuất

*Kết thúc phiên làm việc và trả người dùng về màn đăng nhập.*

**Endpoint**
`POST /api/v2/cc_xt_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Xác thực — Đăng xuất.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [CC_XT_03] Xác thực — Quên mật khẩu

*Gửi đường dẫn đặt lại mật khẩu tới email đã đăng ký của người dùng.*

**Endpoint**
`POST /api/v2/cc_xt_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Xác thực — Quên mật khẩu.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [CC_XT_04] Xác thực — Đổi mật khẩu

*Cho phép người dùng đổi mật khẩu hiện tại; ghi vết thời điểm thay đổi.*

**Endpoint**
`POST /api/v2/cc_xt_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Xác thực — Đổi mật khẩu.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [CC_XT_05] Tài khoản — Chuyển tài khoản

*Chuyển sang tài khoản khác mà không cần đăng xuất thủ công; ghi vết lần chuyển.*

**Endpoint**
`POST /api/v2/cc_xt_05`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Tài khoản — Chuyển tài khoản.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [CC_XT_06] Tài khoản — Chuyển vai trò đang đóng

*Chuyển vai trò trong giới hạn quyền được cấp; menu và vùng dữ liệu cập nhật lại theo vai trò mới.*

**Endpoint**
`POST /api/v2/cc_xt_06`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Tài khoản — Chuyển vai trò đang đóng.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [CC_XT_07] Tài khoản — Xem và chỉnh hồ sơ cá nhân

*Hiển thị và cập nhật thông tin cá nhân, ảnh đại diện và thông tin liên hệ.*

**Endpoint**
`POST /api/v2/cc_xt_07`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Tài khoản — Xem và chỉnh hồ sơ cá nhân.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [CC_GD_01] Hiển thị — Chế độ sáng / tối

*Chuyển giao diện giữa chế độ sáng và tối; lưu thiết lập theo người dùng.*

**Endpoint**
`POST /api/v2/cc_gd_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hiển thị — Chế độ sáng / tối.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [CC_GD_02] Hiển thị — Thu gọn / mở rộng menu

*Ẩn hoặc hiện thanh điều hướng trái; ghi nhớ trạng thái theo người dùng.*

**Endpoint**
`POST /api/v2/cc_gd_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Hiển thị — Thu gọn / mở rộng menu.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [CC_GD_03] Ngữ cảnh làm việc — Chuyển phạm vi làm việc

*Chuyển ngữ cảnh giữa Toàn tổ chức và một dự án cụ thể; vùng dữ liệu truy vấn đổi theo phạm vi.*

**Endpoint**
`POST /api/v2/cc_gd_03`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Ngữ cảnh làm việc — Chuyển phạm vi làm việc.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [CC_GD_04] Ngữ cảnh làm việc — Chọn model AI cho phiên

*Chọn model dùng cho phiên sinh nội dung; áp dụng cho toàn phiên.*

**Endpoint**
`POST /api/v2/cc_gd_04`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Ngữ cảnh làm việc — Chọn model AI cho phiên.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [CC_TB_01] Thông báo — Xem danh sách thông báo

*Hiển thị thông báo gửi tới người dùng kèm số lượng chưa đọc.*

**Endpoint**
`POST /api/v2/cc_tb_01`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Thông báo — Xem danh sách thông báo.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

## [CC_TB_02] Thông báo — Cấu hình nhận thông báo

*Bật/tắt từng loại thông báo trong giới hạn vai trò cho phép.*

**Endpoint**
`POST /api/v2/cc_tb_02`

**Tham số đầu vào**
Header Authorization: Bearer <token>. Body JSON chứa các trường dữ liệu của Thông báo — Cấu hình nhận thông báo.

**Phản hồi mong đợi**
HTTP 200 OK kèm payload JSON kết quả xử lý thành công.

**Mã lỗi**
HTTP 400 (Bad Request), HTTP 401 (Unauthorized), HTTP 403 (Forbidden), HTTP 500 (Internal Error).

