# PTYC — DocGenie — Cây đèn thần dữ liệu (Alakathon 2026)

## [TC_DMGS_01] Danh mục dự án — Danh sách / tìm kiếm dự án

*Hiển thị danh sách dự án theo phạm vi quyền kèm chỉ số tổng quan danh mục; hỗ trợ tìm kiếm, lọc, sắp xếp và phân trang.*

**Mục đích**
Cho phép người dùng thực hiện danh mục dự án — danh sách / tìm kiếm dự án thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý danh mục dự án — danh sách / tìm kiếm dự án và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện danh mục dự án — danh sách / tìm kiếm dự án. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện danh mục dự án — danh sách / tìm kiếm dự án thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_DMGS_02] Danh mục dự án — Thêm mới dự án

*Khởi tạo dự án mới hoặc tạo từ hồ sơ thẩm định đã chốt; khai báo thông tin dự án, nhân sự và cấu hình kết nối.*

**Mục đích**
Cho phép người dùng thực hiện danh mục dự án — thêm mới dự án thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý danh mục dự án — thêm mới dự án và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện danh mục dự án — thêm mới dự án. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện danh mục dự án — thêm mới dự án thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_DMGS_03] Danh mục dự án — Chỉnh sửa dự án

*Cập nhật thông tin dự án, danh sách nhân sự và cấu hình kết nối; ghi vết thay đổi.*

**Mục đích**
Cho phép người dùng thực hiện danh mục dự án — chỉnh sửa dự án thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý danh mục dự án — chỉnh sửa dự án và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện danh mục dự án — chỉnh sửa dự án. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện danh mục dự án — chỉnh sửa dự án thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_DMGS_04] Danh mục dự án — Xóa dự án

*Xóa dự án khỏi danh mục qua bước xác nhận; ghi vết người thực hiện và thời điểm.*

**Mục đích**
Cho phép người dùng thực hiện danh mục dự án — xóa dự án thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý danh mục dự án — xóa dự án và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện danh mục dự án — xóa dự án. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện danh mục dự án — xóa dự án thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_DMGS_05] Danh mục dự án — Xem dự án cụ thể

*Mở dự án được chọn và chuyển phạm vi làm việc xuống dự án đó.*

**Mục đích**
Cho phép người dùng thực hiện danh mục dự án — xem dự án cụ thể thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý danh mục dự án — xem dự án cụ thể và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện danh mục dự án — xem dự án cụ thể. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện danh mục dự án — xem dự án cụ thể thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_DMGS_06] Dashboard tổ chức — Xem tổng quan danh mục

*Hiển thị tiến độ, nguồn lực, PNL và rủi ro tổng hợp trên toàn danh mục dự án trong phạm vi quyền.*

**Mục đích**
Cho phép người dùng thực hiện dashboard tổ chức — xem tổng quan danh mục thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý dashboard tổ chức — xem tổng quan danh mục và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện dashboard tổ chức — xem tổng quan danh mục. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện dashboard tổ chức — xem tổng quan danh mục thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_DMGS_07] Dashboard tổ chức — Lọc theo tiêu chí

*Lọc số liệu theo khoảng thời gian, trạng thái dự án, khách hàng và nhóm nhân sự.*

**Mục đích**
Cho phép người dùng thực hiện dashboard tổ chức — lọc theo tiêu chí thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý dashboard tổ chức — lọc theo tiêu chí và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện dashboard tổ chức — lọc theo tiêu chí. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện dashboard tổ chức — lọc theo tiêu chí thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_DMGS_08] Dashboard tổ chức — Xem chi tiết chỉ số

*Mở nguồn số của một chỉ số, dẫn về dự án và mốc thời gian tương ứng.*

**Mục đích**
Cho phép người dùng thực hiện dashboard tổ chức — xem chi tiết chỉ số thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý dashboard tổ chức — xem chi tiết chỉ số và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện dashboard tổ chức — xem chi tiết chỉ số. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện dashboard tổ chức — xem chi tiết chỉ số thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_DMGS_09] Dashboard tổ chức — Xuất báo cáo

*Kết xuất số liệu đang hiển thị thành tệp để mang đi làm việc.*

**Mục đích**
Cho phép người dùng thực hiện dashboard tổ chức — xuất báo cáo thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý dashboard tổ chức — xuất báo cáo và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện dashboard tổ chức — xuất báo cáo. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện dashboard tổ chức — xuất báo cáo thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HCB_01] Hỏi toàn hệ thống — Đặt câu hỏi

*Nhận câu hỏi bằng ngôn ngữ tự nhiên trên toàn danh mục dự án; xác định phạm vi được phép theo vai trò trước khi truy vấn.*

**Mục đích**
Cho phép người dùng thực hiện hỏi toàn hệ thống — đặt câu hỏi thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hỏi toàn hệ thống — đặt câu hỏi và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hỏi toàn hệ thống — đặt câu hỏi. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hỏi toàn hệ thống — đặt câu hỏi thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HCB_02] Hỏi toàn hệ thống — Xem câu trả lời và nguồn số

*Hiển thị kết quả tổng hợp kèm dẫn nguồn và mốc thời gian; nêu rõ khi thiếu dữ liệu thay vì suy đoán.*

**Mục đích**
Cho phép người dùng thực hiện hỏi toàn hệ thống — xem câu trả lời và nguồn số thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hỏi toàn hệ thống — xem câu trả lời và nguồn số và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hỏi toàn hệ thống — xem câu trả lời và nguồn số. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hỏi toàn hệ thống — xem câu trả lời và nguồn số thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HCB_03] Hỏi toàn hệ thống — Danh sách / tìm kiếm phiên hỏi

*Liệt kê các phiên hỏi đã thực hiện; tìm kiếm và mở lại nội dung phiên.*

**Mục đích**
Cho phép người dùng thực hiện hỏi toàn hệ thống — danh sách / tìm kiếm phiên hỏi thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hỏi toàn hệ thống — danh sách / tìm kiếm phiên hỏi và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hỏi toàn hệ thống — danh sách / tìm kiếm phiên hỏi. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hỏi toàn hệ thống — danh sách / tìm kiếm phiên hỏi thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HCB_04] Hỏi toàn hệ thống — Xóa phiên hỏi

*Xóa phiên hỏi của chính người dùng qua bước xác nhận.*

**Mục đích**
Cho phép người dùng thực hiện hỏi toàn hệ thống — xóa phiên hỏi thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hỏi toàn hệ thống — xóa phiên hỏi và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hỏi toàn hệ thống — xóa phiên hỏi. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hỏi toàn hệ thống — xóa phiên hỏi thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HCB_05] Hỏi toàn hệ thống — Xuất kết quả

*Kết xuất câu trả lời kèm nguồn số thành báo cáo.*

**Mục đích**
Cho phép người dùng thực hiện hỏi toàn hệ thống — xuất kết quả thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hỏi toàn hệ thống — xuất kết quả và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hỏi toàn hệ thống — xuất kết quả. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hỏi toàn hệ thống — xuất kết quả thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HCB_06] Hộp cảnh báo chủ động — Danh sách / tìm kiếm cảnh báo

*Liệt kê cảnh báo đẩy tới vai trò đang đăng nhập; lọc theo loại cảnh báo, dự án và trạng thái đọc.*

**Mục đích**
Cho phép người dùng thực hiện hộp cảnh báo chủ động — danh sách / tìm kiếm cảnh báo thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hộp cảnh báo chủ động — danh sách / tìm kiếm cảnh báo và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hộp cảnh báo chủ động — danh sách / tìm kiếm cảnh báo. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hộp cảnh báo chủ động — danh sách / tìm kiếm cảnh báo thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HCB_07] Hộp cảnh báo chủ động — Xem chi tiết cảnh báo

*Hiển thị hiện tượng quan sát được, con số và ngưỡng đã chạm, kèm đường dẫn tới dự án liên quan.*

**Mục đích**
Cho phép người dùng thực hiện hộp cảnh báo chủ động — xem chi tiết cảnh báo thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hộp cảnh báo chủ động — xem chi tiết cảnh báo và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hộp cảnh báo chủ động — xem chi tiết cảnh báo. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hộp cảnh báo chủ động — xem chi tiết cảnh báo thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HCB_08] Hộp cảnh báo chủ động — Đánh dấu đã xử lý

*Chuyển trạng thái cảnh báo sang đã đọc hoặc đã xử lý; ghi vết người thực hiện.*

**Mục đích**
Cho phép người dùng thực hiện hộp cảnh báo chủ động — đánh dấu đã xử lý thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hộp cảnh báo chủ động — đánh dấu đã xử lý và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hộp cảnh báo chủ động — đánh dấu đã xử lý. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hộp cảnh báo chủ động — đánh dấu đã xử lý thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HCB_09] Hộp cảnh báo chủ động — Cấu hình nhận cảnh báo

*Bật/tắt từng loại cảnh báo trong giới hạn vai trò cho phép.*

**Mục đích**
Cho phép người dùng thực hiện hộp cảnh báo chủ động — cấu hình nhận cảnh báo thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hộp cảnh báo chủ động — cấu hình nhận cảnh báo và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hộp cảnh báo chủ động — cấu hình nhận cảnh báo. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hộp cảnh báo chủ động — cấu hình nhận cảnh báo thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_01] Thẩm định hợp đồng mới — Tạo phiên thẩm định

*Tiếp nhận yêu cầu/RFP qua nhập liệu hoặc tải tệp và giá trị hợp đồng đang chào để bắt đầu thẩm định.*

**Mục đích**
Cho phép người dùng thực hiện thẩm định hợp đồng mới — tạo phiên thẩm định thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý thẩm định hợp đồng mới — tạo phiên thẩm định và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện thẩm định hợp đồng mới — tạo phiên thẩm định. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện thẩm định hợp đồng mới — tạo phiên thẩm định thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_02] Thẩm định hợp đồng mới — Soát DSCN nháp và ULNL ước lượng

*Xem và điều chỉnh DSCN nháp cùng bảng ULNL ước lượng do hệ thống dựng từ yêu cầu.*

**Mục đích**
Cho phép người dùng thực hiện thẩm định hợp đồng mới — soát dscn nháp và ulnl ước lượng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý thẩm định hợp đồng mới — soát dscn nháp và ulnl ước lượng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện thẩm định hợp đồng mới — soát dscn nháp và ulnl ước lượng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện thẩm định hợp đồng mới — soát dscn nháp và ulnl ước lượng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_03] Thẩm định hợp đồng mới — Xem phần tái sử dụng

*Hiển thị các chức năng đã từng làm ở dự án cũ, dẫn được về dự án nguồn và giờ tiêu thật.*

**Mục đích**
Cho phép người dùng thực hiện thẩm định hợp đồng mới — xem phần tái sử dụng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý thẩm định hợp đồng mới — xem phần tái sử dụng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện thẩm định hợp đồng mới — xem phần tái sử dụng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện thẩm định hợp đồng mới — xem phần tái sử dụng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_04] Thẩm định hợp đồng mới — Chọn phương án nguồn lực

*Xem các phương án bố trí nhân sự đối chiếu nguồn lực toàn danh mục và chọn phương án áp dụng.*

**Mục đích**
Cho phép người dùng thực hiện thẩm định hợp đồng mới — chọn phương án nguồn lực thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý thẩm định hợp đồng mới — chọn phương án nguồn lực và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện thẩm định hợp đồng mới — chọn phương án nguồn lực. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện thẩm định hợp đồng mới — chọn phương án nguồn lực thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_05] Thẩm định hợp đồng mới — Ghi nhận kết luận

*Ghi quyết định nhận / đàm phán lại giá / từ chối kèm giả định đã dùng và lưu thành hồ sơ thẩm định.*

**Mục đích**
Cho phép người dùng thực hiện thẩm định hợp đồng mới — ghi nhận kết luận thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý thẩm định hợp đồng mới — ghi nhận kết luận và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện thẩm định hợp đồng mới — ghi nhận kết luận. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện thẩm định hợp đồng mới — ghi nhận kết luận thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_06] Hồ sơ thẩm định — Danh sách / tìm kiếm hồ sơ

*Liệt kê hồ sơ thẩm định đã lập; tìm kiếm theo khách hàng, thời điểm và kết luận.*

**Mục đích**
Cho phép người dùng thực hiện hồ sơ thẩm định — danh sách / tìm kiếm hồ sơ thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hồ sơ thẩm định — danh sách / tìm kiếm hồ sơ và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hồ sơ thẩm định — danh sách / tìm kiếm hồ sơ. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hồ sơ thẩm định — danh sách / tìm kiếm hồ sơ thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_07] Hồ sơ thẩm định — Xem chi tiết hồ sơ

*Mở nội dung hồ sơ: DSCN nháp, ULNL, phần tái sử dụng, phương án nguồn lực và kết luận.*

**Mục đích**
Cho phép người dùng thực hiện hồ sơ thẩm định — xem chi tiết hồ sơ thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hồ sơ thẩm định — xem chi tiết hồ sơ và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hồ sơ thẩm định — xem chi tiết hồ sơ. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hồ sơ thẩm định — xem chi tiết hồ sơ thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_08] Hồ sơ thẩm định — Chỉnh sửa hồ sơ

*Cập nhật hồ sơ chưa chuyển thành dự án; ghi vết thay đổi.*

**Mục đích**
Cho phép người dùng thực hiện hồ sơ thẩm định — chỉnh sửa hồ sơ thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hồ sơ thẩm định — chỉnh sửa hồ sơ và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hồ sơ thẩm định — chỉnh sửa hồ sơ. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hồ sơ thẩm định — chỉnh sửa hồ sơ thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_09] Hồ sơ thẩm định — Xóa hồ sơ

*Xóa hồ sơ thẩm định qua bước xác nhận; ghi vết người thực hiện.*

**Mục đích**
Cho phép người dùng thực hiện hồ sơ thẩm định — xóa hồ sơ thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hồ sơ thẩm định — xóa hồ sơ và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hồ sơ thẩm định — xóa hồ sơ. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hồ sơ thẩm định — xóa hồ sơ thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_10] Hồ sơ thẩm định — Xuất hồ sơ

*Kết xuất hồ sơ thẩm định thành tệp để trình duyệt và đàm phán.*

**Mục đích**
Cho phép người dùng thực hiện hồ sơ thẩm định — xuất hồ sơ thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hồ sơ thẩm định — xuất hồ sơ và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hồ sơ thẩm định — xuất hồ sơ. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hồ sơ thẩm định — xuất hồ sơ thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_11] PNL & báo cáo tổng hợp — Xem PNL theo kỳ

*Tổng hợp PNL nhân sự theo tháng và theo dự án trong phạm vi quyền.*

**Mục đích**
Cho phép người dùng thực hiện pnl & báo cáo tổng hợp — xem pnl theo kỳ thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý pnl & báo cáo tổng hợp — xem pnl theo kỳ và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện pnl & báo cáo tổng hợp — xem pnl theo kỳ. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện pnl & báo cáo tổng hợp — xem pnl theo kỳ thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_12] PNL & báo cáo tổng hợp — Xem MM phát sinh

*Tổng hợp MM đã tiêu và MM phát sinh do thay đổi trên toàn danh mục.*

**Mục đích**
Cho phép người dùng thực hiện pnl & báo cáo tổng hợp — xem mm phát sinh thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý pnl & báo cáo tổng hợp — xem mm phát sinh và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện pnl & báo cáo tổng hợp — xem mm phát sinh. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện pnl & báo cáo tổng hợp — xem mm phát sinh thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_13] PNL & báo cáo tổng hợp — Lọc theo tiêu chí

*Lọc báo cáo theo kỳ, dự án, phòng ban và nhân sự.*

**Mục đích**
Cho phép người dùng thực hiện pnl & báo cáo tổng hợp — lọc theo tiêu chí thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý pnl & báo cáo tổng hợp — lọc theo tiêu chí và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện pnl & báo cáo tổng hợp — lọc theo tiêu chí. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện pnl & báo cáo tổng hợp — lọc theo tiêu chí thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HDT_14] PNL & báo cáo tổng hợp — Xuất báo cáo

*Kết xuất báo cáo tổng hợp thành tệp.*

**Mục đích**
Cho phép người dùng thực hiện pnl & báo cáo tổng hợp — xuất báo cáo thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý pnl & báo cáo tổng hợp — xuất báo cáo và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện pnl & báo cáo tổng hợp — xuất báo cáo. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện pnl & báo cáo tổng hợp — xuất báo cáo thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_TTTL_01] Kho tri thức liên dự án — Danh sách / tìm kiếm tri thức

*Tra cứu luồng nghiệp vụ, ULNL và giờ tiêu thật của các dự án đã đóng; lọc theo loại hình dự án và khách hàng.*

**Mục đích**
Cho phép người dùng thực hiện kho tri thức liên dự án — danh sách / tìm kiếm tri thức thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho tri thức liên dự án — danh sách / tìm kiếm tri thức và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho tri thức liên dự án — danh sách / tìm kiếm tri thức. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho tri thức liên dự án — danh sách / tìm kiếm tri thức thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_TTTL_02] Kho tri thức liên dự án — Xem chi tiết chức năng đã làm

*Mở thông tin một chức năng: dự án nguồn, mức ULNL đã chấm, giờ tiêu thật và độ lệch ước lượng.*

**Mục đích**
Cho phép người dùng thực hiện kho tri thức liên dự án — xem chi tiết chức năng đã làm thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho tri thức liên dự án — xem chi tiết chức năng đã làm và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho tri thức liên dự án — xem chi tiết chức năng đã làm. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho tri thức liên dự án — xem chi tiết chức năng đã làm thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_TTTL_03] Kho tri thức liên dự án — Chọn tái sử dụng

*Chọn chức năng để đưa sang dự án mới; hệ thống cấp mã ID mới và giữ trường nguồn tái sử dụng.*

**Mục đích**
Cho phép người dùng thực hiện kho tri thức liên dự án — chọn tái sử dụng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho tri thức liên dự án — chọn tái sử dụng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho tri thức liên dự án — chọn tái sử dụng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho tri thức liên dự án — chọn tái sử dụng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_TTTL_04] Kho tri thức liên dự án — Kiểm soát truy cập theo quyền

*Với dự án ngoài phạm vi quyền, chỉ trả về có hay không có luồng tương tự, không trả nội dung.*

**Mục đích**
Cho phép người dùng thực hiện kho tri thức liên dự án — kiểm soát truy cập theo quyền thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho tri thức liên dự án — kiểm soát truy cập theo quyền và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho tri thức liên dự án — kiểm soát truy cập theo quyền. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho tri thức liên dự án — kiểm soát truy cập theo quyền thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_TTTL_05] Kho biên bản họp — Danh sách / tìm kiếm biên bản

*Liệt kê biên bản họp toàn tổ chức trong phạm vi quyền; tìm kiếm theo tên, dự án, khách hàng và thời gian.*

**Mục đích**
Cho phép người dùng thực hiện kho biên bản họp — danh sách / tìm kiếm biên bản thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho biên bản họp — danh sách / tìm kiếm biên bản và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho biên bản họp — danh sách / tìm kiếm biên bản. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho biên bản họp — danh sách / tìm kiếm biên bản thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_TTTL_06] Kho biên bản họp — Xem chi tiết biên bản

*Mở nội dung biên bản có cấu trúc: nội dung trao đổi, yêu cầu nghe được và điểm chưa rõ.*

**Mục đích**
Cho phép người dùng thực hiện kho biên bản họp — xem chi tiết biên bản thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho biên bản họp — xem chi tiết biên bản và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho biên bản họp — xem chi tiết biên bản. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho biên bản họp — xem chi tiết biên bản thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_TTTL_07] Kho biên bản họp — Xóa biên bản

*Xóa biên bản qua bước xác nhận; ghi vết người thực hiện.*

**Mục đích**
Cho phép người dùng thực hiện kho biên bản họp — xóa biên bản thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho biên bản họp — xóa biên bản và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho biên bản họp — xóa biên bản. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho biên bản họp — xóa biên bản thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_NS_01] Danh bạ nhân sự — Danh sách / tìm kiếm nhân sự

*Liệt kê nhân sự dùng chung toàn tổ chức kèm tổng tải hiện tại; tìm kiếm theo tên, phòng ban và vai trò.*

**Mục đích**
Cho phép người dùng thực hiện danh bạ nhân sự — danh sách / tìm kiếm nhân sự thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý danh bạ nhân sự — danh sách / tìm kiếm nhân sự và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện danh bạ nhân sự — danh sách / tìm kiếm nhân sự. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện danh bạ nhân sự — danh sách / tìm kiếm nhân sự thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_NS_02] Danh bạ nhân sự — Thêm mới nhân sự

*Khai báo nhân sự mới với các trường dùng chung: tên, phòng ban, vai trò, email và định mức PNL tháng.*

**Mục đích**
Cho phép người dùng thực hiện danh bạ nhân sự — thêm mới nhân sự thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý danh bạ nhân sự — thêm mới nhân sự và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện danh bạ nhân sự — thêm mới nhân sự. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện danh bạ nhân sự — thêm mới nhân sự thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_NS_03] Danh bạ nhân sự — Chỉnh sửa nhân sự

*Cập nhật thông tin nhân sự; ghi vết thay đổi.*

**Mục đích**
Cho phép người dùng thực hiện danh bạ nhân sự — chỉnh sửa nhân sự thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý danh bạ nhân sự — chỉnh sửa nhân sự và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện danh bạ nhân sự — chỉnh sửa nhân sự. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện danh bạ nhân sự — chỉnh sửa nhân sự thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_NS_04] Danh bạ nhân sự — Xóa nhân sự

*Xóa nhân sự khỏi danh bạ qua bước xác nhận; chặn xóa khi đang tham gia dự án chưa đóng.*

**Mục đích**
Cho phép người dùng thực hiện danh bạ nhân sự — xóa nhân sự thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý danh bạ nhân sự — xóa nhân sự và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện danh bạ nhân sự — xóa nhân sự. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện danh bạ nhân sự — xóa nhân sự thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_NS_05] Danh bạ nhân sự — Xem chi tiết nhân sự

*Hiển thị các dự án đang tham gia, %tham gia, thời gian tham gia và tổng tải liên dự án.*

**Mục đích**
Cho phép người dùng thực hiện danh bạ nhân sự — xem chi tiết nhân sự thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý danh bạ nhân sự — xem chi tiết nhân sự và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện danh bạ nhân sự — xem chi tiết nhân sự. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện danh bạ nhân sự — xem chi tiết nhân sự thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_01] Quản trị người dùng — Danh sách / tìm kiếm người dùng

*Liệt kê tài khoản người dùng trong tổ chức; tìm kiếm theo tên, email, phòng ban và vai trò; lọc theo trạng thái hoạt động.*

**Mục đích**
Cho phép người dùng thực hiện quản trị người dùng — danh sách / tìm kiếm người dùng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý quản trị người dùng — danh sách / tìm kiếm người dùng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện quản trị người dùng — danh sách / tìm kiếm người dùng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện quản trị người dùng — danh sách / tìm kiếm người dùng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_02] Quản trị người dùng — Thêm mới người dùng

*Khai báo tài khoản mới, liên kết với bản ghi trong Danh bạ nhân sự và gán vai trò ban đầu.*

**Mục đích**
Cho phép người dùng thực hiện quản trị người dùng — thêm mới người dùng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý quản trị người dùng — thêm mới người dùng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện quản trị người dùng — thêm mới người dùng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện quản trị người dùng — thêm mới người dùng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_03] Quản trị người dùng — Chỉnh sửa người dùng

*Cập nhật thông tin tài khoản và vai trò được gán; ghi vết thay đổi.*

**Mục đích**
Cho phép người dùng thực hiện quản trị người dùng — chỉnh sửa người dùng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý quản trị người dùng — chỉnh sửa người dùng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện quản trị người dùng — chỉnh sửa người dùng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện quản trị người dùng — chỉnh sửa người dùng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_04] Quản trị người dùng — Khóa / mở khóa người dùng

*Ngừng hoặc khôi phục quyền truy cập của tài khoản mà không xóa dữ liệu lịch sử.*

**Mục đích**
Cho phép người dùng thực hiện quản trị người dùng — khóa / mở khóa người dùng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý quản trị người dùng — khóa / mở khóa người dùng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện quản trị người dùng — khóa / mở khóa người dùng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện quản trị người dùng — khóa / mở khóa người dùng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_05] Quản trị người dùng — Xóa người dùng

*Xóa tài khoản qua bước xác nhận; ghi vết người thực hiện và thời điểm.*

**Mục đích**
Cho phép người dùng thực hiện quản trị người dùng — xóa người dùng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý quản trị người dùng — xóa người dùng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện quản trị người dùng — xóa người dùng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện quản trị người dùng — xóa người dùng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_06] Quản trị vai trò — Danh sách / tìm kiếm vai trò

*Liệt kê các vai trò của hệ thống: Giám đốc, PM, BA, QA, Dev, HR, BD, Kế toán, Quản trị hệ thống.*

**Mục đích**
Cho phép người dùng thực hiện quản trị vai trò — danh sách / tìm kiếm vai trò thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý quản trị vai trò — danh sách / tìm kiếm vai trò và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện quản trị vai trò — danh sách / tìm kiếm vai trò. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện quản trị vai trò — danh sách / tìm kiếm vai trò thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_07] Quản trị vai trò — Thêm mới vai trò

*Tạo vai trò mới và khai báo nhóm quyền tương ứng.*

**Mục đích**
Cho phép người dùng thực hiện quản trị vai trò — thêm mới vai trò thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý quản trị vai trò — thêm mới vai trò và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện quản trị vai trò — thêm mới vai trò. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện quản trị vai trò — thêm mới vai trò thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_08] Quản trị vai trò — Chỉnh sửa vai trò

*Cập nhật tên vai trò và nhóm quyền; ghi vết thay đổi.*

**Mục đích**
Cho phép người dùng thực hiện quản trị vai trò — chỉnh sửa vai trò thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý quản trị vai trò — chỉnh sửa vai trò và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện quản trị vai trò — chỉnh sửa vai trò. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện quản trị vai trò — chỉnh sửa vai trò thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_09] Quản trị vai trò — Xóa vai trò

*Xóa vai trò qua bước xác nhận; chặn xóa khi còn người dùng đang được gán.*

**Mục đích**
Cho phép người dùng thực hiện quản trị vai trò — xóa vai trò thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý quản trị vai trò — xóa vai trò và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện quản trị vai trò — xóa vai trò. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện quản trị vai trò — xóa vai trò thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_10] Phạm vi dữ liệu — Cấu hình phạm vi theo vai trò

*Khai báo vùng dữ liệu của từng vai trò theo hai trục: theo dự án và theo loại dữ liệu (tài liệu / tiến độ / nhân sự / chi phí / hiệu suất cá nhân).*

**Mục đích**
Cho phép người dùng thực hiện phạm vi dữ liệu — cấu hình phạm vi theo vai trò thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phạm vi dữ liệu — cấu hình phạm vi theo vai trò và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phạm vi dữ liệu — cấu hình phạm vi theo vai trò. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phạm vi dữ liệu — cấu hình phạm vi theo vai trò thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_11] Phạm vi dữ liệu — Xem ma trận phân quyền

*Hiển thị bảng đối chiếu vai trò ↔ vùng dữ liệu để rà soát trước khi áp dụng.*

**Mục đích**
Cho phép người dùng thực hiện phạm vi dữ liệu — xem ma trận phân quyền thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phạm vi dữ liệu — xem ma trận phân quyền và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phạm vi dữ liệu — xem ma trận phân quyền. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phạm vi dữ liệu — xem ma trận phân quyền thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_12] Phạm vi dữ liệu — Ghi vết thay đổi phân quyền

*Lưu vết mọi thay đổi cấu hình phân quyền: người thực hiện, thời điểm và nội dung thay đổi.*

**Mục đích**
Cho phép người dùng thực hiện phạm vi dữ liệu — ghi vết thay đổi phân quyền thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phạm vi dữ liệu — ghi vết thay đổi phân quyền và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phạm vi dữ liệu — ghi vết thay đổi phân quyền. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phạm vi dữ liệu — ghi vết thay đổi phân quyền thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_13] Tham số ngưỡng — Danh sách tham số ngưỡng

*Liệt kê toàn bộ ngưỡng cảnh báo cấu hình ở tầng hệ thống: ngưỡng lãi/lỗ, ngưỡng lệch logwork, ngưỡng tổng tải nhân sự, ngưỡng burn rate.*

**Mục đích**
Cho phép người dùng thực hiện tham số ngưỡng — danh sách tham số ngưỡng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý tham số ngưỡng — danh sách tham số ngưỡng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện tham số ngưỡng — danh sách tham số ngưỡng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện tham số ngưỡng — danh sách tham số ngưỡng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_14] Tham số ngưỡng — Chỉnh sửa tham số ngưỡng

*Cập nhật giá trị ngưỡng; hiển thị giá trị mặc định và giá trị đang áp dụng; ghi vết thay đổi.*

**Mục đích**
Cho phép người dùng thực hiện tham số ngưỡng — chỉnh sửa tham số ngưỡng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý tham số ngưỡng — chỉnh sửa tham số ngưỡng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện tham số ngưỡng — chỉnh sửa tham số ngưỡng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện tham số ngưỡng — chỉnh sửa tham số ngưỡng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_15] Tham số ngưỡng — Khôi phục giá trị mặc định

*Đưa một hoặc nhiều tham số về giá trị khởi điểm.*

**Mục đích**
Cho phép người dùng thực hiện tham số ngưỡng — khôi phục giá trị mặc định thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý tham số ngưỡng — khôi phục giá trị mặc định và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện tham số ngưỡng — khôi phục giá trị mặc định. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện tham số ngưỡng — khôi phục giá trị mặc định thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_16] Kết nối dùng chung — Danh sách kết nối

*Liệt kê các kết nối dùng chung toàn tổ chức: Git, Jira, Figma, kênh mail và model AI.*

**Mục đích**
Cho phép người dùng thực hiện kết nối dùng chung — danh sách kết nối thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kết nối dùng chung — danh sách kết nối và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kết nối dùng chung — danh sách kết nối. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kết nối dùng chung — danh sách kết nối thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_17] Kết nối dùng chung — Thêm mới kết nối

*Khai báo kết nối mới kèm thông tin xác thực tương ứng.*

**Mục đích**
Cho phép người dùng thực hiện kết nối dùng chung — thêm mới kết nối thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kết nối dùng chung — thêm mới kết nối và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kết nối dùng chung — thêm mới kết nối. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kết nối dùng chung — thêm mới kết nối thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_18] Kết nối dùng chung — Chỉnh sửa kết nối

*Cập nhật cấu hình kết nối; ghi vết thay đổi.*

**Mục đích**
Cho phép người dùng thực hiện kết nối dùng chung — chỉnh sửa kết nối thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kết nối dùng chung — chỉnh sửa kết nối và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kết nối dùng chung — chỉnh sửa kết nối. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kết nối dùng chung — chỉnh sửa kết nối thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_19] Kết nối dùng chung — Kiểm tra kết nối

*Thực hiện Test connection và báo trạng thái kết nối sống/chết.*

**Mục đích**
Cho phép người dùng thực hiện kết nối dùng chung — kiểm tra kết nối thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kết nối dùng chung — kiểm tra kết nối và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kết nối dùng chung — kiểm tra kết nối. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kết nối dùng chung — kiểm tra kết nối thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_20] Kết nối dùng chung — Xóa kết nối

*Xóa kết nối qua bước xác nhận; cảnh báo các dự án đang sử dụng.*

**Mục đích**
Cho phép người dùng thực hiện kết nối dùng chung — xóa kết nối thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kết nối dùng chung — xóa kết nối và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kết nối dùng chung — xóa kết nối. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kết nối dùng chung — xóa kết nối thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_21] Kho Skill & Rule — Danh sách / tìm kiếm skill

*Liệt kê bộ skill sinh nội dung theo từng loại tài liệu 01–12; tìm kiếm theo tên và loại tài liệu.*

**Mục đích**
Cho phép người dùng thực hiện kho skill & rule — danh sách / tìm kiếm skill thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho skill & rule — danh sách / tìm kiếm skill và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho skill & rule — danh sách / tìm kiếm skill. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho skill & rule — danh sách / tìm kiếm skill thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_22] Kho Skill & Rule — Xem chi tiết skill

*Mở nội dung skill: template, rule áp dụng và phiên bản đang hoạt động.*

**Mục đích**
Cho phép người dùng thực hiện kho skill & rule — xem chi tiết skill thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho skill & rule — xem chi tiết skill và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho skill & rule — xem chi tiết skill. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho skill & rule — xem chi tiết skill thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_23] Kho Skill & Rule — Thêm mới skill

*Khai báo skill mới cho một loại tài liệu hoặc một nghiệp vụ sinh nội dung.*

**Mục đích**
Cho phép người dùng thực hiện kho skill & rule — thêm mới skill thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho skill & rule — thêm mới skill và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho skill & rule — thêm mới skill. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho skill & rule — thêm mới skill thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_24] Kho Skill & Rule — Chỉnh sửa skill

*Cập nhật template và rule của skill; sinh phiên bản mới, giữ lịch sử phiên bản cũ.*

**Mục đích**
Cho phép người dùng thực hiện kho skill & rule — chỉnh sửa skill thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho skill & rule — chỉnh sửa skill và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho skill & rule — chỉnh sửa skill. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho skill & rule — chỉnh sửa skill thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_25] Kho Skill & Rule — Xóa skill

*Xóa skill qua bước xác nhận; chặn xóa khi là skill bắt buộc của một loại tài liệu.*

**Mục đích**
Cho phép người dùng thực hiện kho skill & rule — xóa skill thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho skill & rule — xóa skill và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho skill & rule — xóa skill. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho skill & rule — xóa skill thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_26] Kho Skill & Rule — Quản lý bảng tham chiếu ULNL

*Khai báo và cập nhật bảng tham chiếu mã/mức, danh sách task chuẩn và quy đổi giờ → MD → MM.*

**Mục đích**
Cho phép người dùng thực hiện kho skill & rule — quản lý bảng tham chiếu ulnl thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho skill & rule — quản lý bảng tham chiếu ulnl và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho skill & rule — quản lý bảng tham chiếu ulnl. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho skill & rule — quản lý bảng tham chiếu ulnl thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_27] Kho Skill & Rule — Quản lý rule kiểm tra

*Khai báo các rule tự kiểm ở tầng hệ thống, gồm rule đối chiếu MH_ULNL_Total với tổng Original Estimate.*

**Mục đích**
Cho phép người dùng thực hiện kho skill & rule — quản lý rule kiểm tra thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý kho skill & rule — quản lý rule kiểm tra và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện kho skill & rule — quản lý rule kiểm tra. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện kho skill & rule — quản lý rule kiểm tra thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_28] Log truy vết — Danh sách / tìm kiếm log

*Liệt kê toàn bộ vết thao tác có hậu quả trong hệ thống; tìm kiếm và lọc theo người thực hiện, dự án, loại thao tác và khoảng thời gian.*

**Mục đích**
Cho phép người dùng thực hiện log truy vết — danh sách / tìm kiếm log thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý log truy vết — danh sách / tìm kiếm log và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện log truy vết — danh sách / tìm kiếm log. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện log truy vết — danh sách / tìm kiếm log thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_29] Log truy vết — Xem chi tiết log

*Hiển thị nội dung một vết: người thực hiện, thời điểm, đối tượng tác động và nội dung thay đổi.*

**Mục đích**
Cho phép người dùng thực hiện log truy vết — xem chi tiết log thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý log truy vết — xem chi tiết log và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện log truy vết — xem chi tiết log. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện log truy vết — xem chi tiết log thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [TC_HT_30] Log truy vết — Xuất log

*Kết xuất danh sách log theo bộ lọc đang áp dụng thành tệp.*

**Mục đích**
Cho phép người dùng thực hiện log truy vết — xuất log thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý log truy vết — xuất log và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện log truy vết — xuất log. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện log truy vết — xuất log thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_CH_01] Thông tin dự án — Xem thông tin dự án

*Hiển thị tên, mô tả, giá trị hợp đồng (MM) và thời gian phát triển của dự án.*

**Mục đích**
Cho phép người dùng thực hiện thông tin dự án — xem thông tin dự án thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý thông tin dự án — xem thông tin dự án và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện thông tin dự án — xem thông tin dự án. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện thông tin dự án — xem thông tin dự án thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_CH_02] Thông tin dự án — Chỉnh sửa thông tin dự án

*Cập nhật thông tin dự án; ghi vết người thực hiện và thời điểm.*

**Mục đích**
Cho phép người dùng thực hiện thông tin dự án — chỉnh sửa thông tin dự án thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý thông tin dự án — chỉnh sửa thông tin dự án và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện thông tin dự án — chỉnh sửa thông tin dự án. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện thông tin dự án — chỉnh sửa thông tin dự án thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_CH_03] Nhân sự dự án — Danh sách / tìm kiếm nhân sự dự án

*Liệt kê nhân sự tham gia dự án kèm vai trò, %tham gia và thời gian tham gia.*

**Mục đích**
Cho phép người dùng thực hiện nhân sự dự án — danh sách / tìm kiếm nhân sự dự án thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý nhân sự dự án — danh sách / tìm kiếm nhân sự dự án và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện nhân sự dự án — danh sách / tìm kiếm nhân sự dự án. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện nhân sự dự án — danh sách / tìm kiếm nhân sự dự án thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_CH_04] Nhân sự dự án — Thêm nhân sự vào dự án

*Chọn nhân sự từ Danh bạ nhân sự và khai %tham gia cùng thời gian tham gia trong dự án.*

**Mục đích**
Cho phép người dùng thực hiện nhân sự dự án — thêm nhân sự vào dự án thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý nhân sự dự án — thêm nhân sự vào dự án và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện nhân sự dự án — thêm nhân sự vào dự án. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện nhân sự dự án — thêm nhân sự vào dự án thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_CH_05] Nhân sự dự án — Chỉnh sửa phân bổ nhân sự

*Cập nhật %tham gia và thời gian tham gia của nhân sự trong dự án.*

**Mục đích**
Cho phép người dùng thực hiện nhân sự dự án — chỉnh sửa phân bổ nhân sự thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý nhân sự dự án — chỉnh sửa phân bổ nhân sự và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện nhân sự dự án — chỉnh sửa phân bổ nhân sự. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện nhân sự dự án — chỉnh sửa phân bổ nhân sự thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_CH_06] Nhân sự dự án — Gỡ nhân sự khỏi dự án

*Loại nhân sự khỏi dự án qua bước xác nhận; giữ nguyên logwork đã ghi nhận.*

**Mục đích**
Cho phép người dùng thực hiện nhân sự dự án — gỡ nhân sự khỏi dự án thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý nhân sự dự án — gỡ nhân sự khỏi dự án và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện nhân sự dự án — gỡ nhân sự khỏi dự án. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện nhân sự dự án — gỡ nhân sự khỏi dự án thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_CH_07] Nhân sự dự án — Cảnh báo trùng lịch liên dự án

*Cộng %tham gia của nhân sự trên mọi dự án có thời gian giao nhau; cảnh báo khi vượt ngưỡng và ghi nhận trường hợp được chấp nhận.*

**Mục đích**
Cho phép người dùng thực hiện nhân sự dự án — cảnh báo trùng lịch liên dự án thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý nhân sự dự án — cảnh báo trùng lịch liên dự án và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện nhân sự dự án — cảnh báo trùng lịch liên dự án. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện nhân sự dự án — cảnh báo trùng lịch liên dự án thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_CH_08] Cấu hình kết nối — Khai báo kết nối Git / Jira / Figma

*Khai báo repo Git duy nhất, tên miền và token Jira, kết nối Figma cho dự án.*

**Mục đích**
Cho phép người dùng thực hiện cấu hình kết nối — khai báo kết nối git / jira / figma thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý cấu hình kết nối — khai báo kết nối git / jira / figma và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện cấu hình kết nối — khai báo kết nối git / jira / figma. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện cấu hình kết nối — khai báo kết nối git / jira / figma thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_CH_09] Cấu hình kết nối — Kiểm tra kết nối và đối chiếu email Jira

*Chạy Test connection, đối chiếu email nhân sự với user Jira và báo các dòng không map được.*

**Mục đích**
Cho phép người dùng thực hiện cấu hình kết nối — kiểm tra kết nối và đối chiếu email jira thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý cấu hình kết nối — kiểm tra kết nối và đối chiếu email jira và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện cấu hình kết nối — kiểm tra kết nối và đối chiếu email jira. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện cấu hình kết nối — kiểm tra kết nối và đối chiếu email jira thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_CH_10] Cảnh báo khả thi — Xem cảnh báo khả thi lãi/lỗ

*Hiển thị chi phí đội, margin và nhãn lãi/lỗ theo công thức, kèm mốc so sánh từ dự án cũ cùng loại hình.*

**Mục đích**
Cho phép người dùng thực hiện cảnh báo khả thi — xem cảnh báo khả thi lãi/lỗ thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý cảnh báo khả thi — xem cảnh báo khả thi lãi/lỗ và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện cảnh báo khả thi — xem cảnh báo khả thi lãi/lỗ. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện cảnh báo khả thi — xem cảnh báo khả thi lãi/lỗ thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_CH_11] Cảnh báo khả thi — Xem vai trò được quyền đọc dự án

*Hiển thị danh sách vai trò ngoài đội đang có quyền đọc dự án theo cấu hình phân quyền.*

**Mục đích**
Cho phép người dùng thực hiện cảnh báo khả thi — xem vai trò được quyền đọc dự án thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý cảnh báo khả thi — xem vai trò được quyền đọc dự án và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện cảnh báo khả thi — xem vai trò được quyền đọc dự án. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện cảnh báo khả thi — xem vai trò được quyền đọc dự án thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TL_01] Phiên chat dự án — Danh sách / tìm kiếm phiên chat

*Liệt kê các phiên chat của dự án; tìm kiếm và mở lại nội dung phiên.*

**Mục đích**
Cho phép người dùng thực hiện phiên chat dự án — danh sách / tìm kiếm phiên chat thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phiên chat dự án — danh sách / tìm kiếm phiên chat và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phiên chat dự án — danh sách / tìm kiếm phiên chat. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phiên chat dự án — danh sách / tìm kiếm phiên chat thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TL_02] Phiên chat dự án — Khai thác yêu cầu qua chat

*Nêu yêu cầu bằng ngôn ngữ tự nhiên để hệ thống dựng nội dung; xem kết quả trực tiếp trong phiên.*

**Mục đích**
Cho phép người dùng thực hiện phiên chat dự án — khai thác yêu cầu qua chat thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phiên chat dự án — khai thác yêu cầu qua chat và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phiên chat dự án — khai thác yêu cầu qua chat. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phiên chat dự án — khai thác yêu cầu qua chat thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TL_03] Phiên chat dự án — Gọi biên bản họp vào ngữ cảnh

*Nạp nội dung một biên bản trong Kho biên bản họp vào phiên khi được gọi đúng tên.*

**Mục đích**
Cho phép người dùng thực hiện phiên chat dự án — gọi biên bản họp vào ngữ cảnh thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phiên chat dự án — gọi biên bản họp vào ngữ cảnh và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phiên chat dự án — gọi biên bản họp vào ngữ cảnh. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phiên chat dự án — gọi biên bản họp vào ngữ cảnh thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TL_04] Danh sách chức năng (Bản 01) — Chốt DSCN

*Chốt danh sách chức năng theo ba cách: import tệp, tương tác chat hoặc tái sử dụng từ dự án cũ; gán mã ID cố định cho từng chức năng.*

**Mục đích**
Cho phép người dùng thực hiện danh sách chức năng (bản 01) — chốt dscn thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý danh sách chức năng (bản 01) — chốt dscn và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện danh sách chức năng (bản 01) — chốt dscn. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện danh sách chức năng (bản 01) — chốt dscn thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TL_05] Danh sách chức năng (Bản 01) — Tái sử dụng chức năng từ dự án cũ

*Chọn chức năng từ dự án đã làm; cấp mã ID mới, giữ trường nguồn tái sử dụng và hiển thị giờ tiêu thật ở dự án gốc.*

**Mục đích**
Cho phép người dùng thực hiện danh sách chức năng (bản 01) — tái sử dụng chức năng từ dự án cũ thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý danh sách chức năng (bản 01) — tái sử dụng chức năng từ dự án cũ và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện danh sách chức năng (bản 01) — tái sử dụng chức năng từ dự án cũ. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện danh sách chức năng (bản 01) — tái sử dụng chức năng từ dự án cũ thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TL_06] Danh sách chức năng (Bản 01) — Kiểm tra rule DSCN

*Chuẩn hóa mã ID và kiểm rule trước khi ghi: không trùng mã, không sót quan hệ cha/con.*

**Mục đích**
Cho phép người dùng thực hiện danh sách chức năng (bản 01) — kiểm tra rule dscn thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý danh sách chức năng (bản 01) — kiểm tra rule dscn và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện danh sách chức năng (bản 01) — kiểm tra rule dscn. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện danh sách chức năng (bản 01) — kiểm tra rule dscn thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TL_07] Tài liệu phái sinh (Bản 02–12) — Sinh tài liệu phái sinh

*Sinh nháp PTYC, chi tiết màn hình, TKCT, Plan, Testcase, ULNL, TKCSDL, TKTT và HDSD từ các bản trước theo skill của từng loại.*

**Mục đích**
Cho phép người dùng thực hiện tài liệu phái sinh (bản 02–12) — sinh tài liệu phái sinh thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý tài liệu phái sinh (bản 02–12) — sinh tài liệu phái sinh và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện tài liệu phái sinh (bản 02–12) — sinh tài liệu phái sinh. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện tài liệu phái sinh (bản 02–12) — sinh tài liệu phái sinh thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TL_08] Tài liệu phái sinh (Bản 02–12) — Chọn nhịp sinh tài liệu

*Chọn sinh trọn bộ hoặc theo từng chức năng/nhóm; hệ thống gợi ý lựa chọn khi khối lượng lớn.*

**Mục đích**
Cho phép người dùng thực hiện tài liệu phái sinh (bản 02–12) — chọn nhịp sinh tài liệu thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý tài liệu phái sinh (bản 02–12) — chọn nhịp sinh tài liệu và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện tài liệu phái sinh (bản 02–12) — chọn nhịp sinh tài liệu. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện tài liệu phái sinh (bản 02–12) — chọn nhịp sinh tài liệu thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TL_09] Tài liệu phái sinh (Bản 02–12) — Soát và chỉnh nội dung trong phiên

*Xem nội dung sinh ra ngay trong phiên chat và yêu cầu chỉnh sửa trước khi ghi vào hệ thống.*

**Mục đích**
Cho phép người dùng thực hiện tài liệu phái sinh (bản 02–12) — soát và chỉnh nội dung trong phiên thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý tài liệu phái sinh (bản 02–12) — soát và chỉnh nội dung trong phiên và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện tài liệu phái sinh (bản 02–12) — soát và chỉnh nội dung trong phiên. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện tài liệu phái sinh (bản 02–12) — soát và chỉnh nội dung trong phiên thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TL_10] Tài liệu phái sinh (Bản 02–12) — Hỏi đáp trên bộ tài liệu

*Đặt câu hỏi về một chức năng và nhận câu trả lời có trích dẫn đúng bản và mục tài liệu.*

**Mục đích**
Cho phép người dùng thực hiện tài liệu phái sinh (bản 02–12) — hỏi đáp trên bộ tài liệu thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý tài liệu phái sinh (bản 02–12) — hỏi đáp trên bộ tài liệu và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện tài liệu phái sinh (bản 02–12) — hỏi đáp trên bộ tài liệu. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện tài liệu phái sinh (bản 02–12) — hỏi đáp trên bộ tài liệu thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TK_01] Prototype — Xem prototype bấm được

*Mở prototype HTML và thao tác thử theo luồng màn hình của chức năng.*

**Mục đích**
Cho phép người dùng thực hiện prototype — xem prototype bấm được thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý prototype — xem prototype bấm được và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện prototype — xem prototype bấm được. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện prototype — xem prototype bấm được thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TK_02] Prototype — Đồng bộ thiết kế Figma

*Dựng màn theo bộ component và lưu link Figma của dự án.*

**Mục đích**
Cho phép người dùng thực hiện prototype — đồng bộ thiết kế figma thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý prototype — đồng bộ thiết kế figma và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện prototype — đồng bộ thiết kế figma. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện prototype — đồng bộ thiết kế figma thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TK_03] Góp ý thiết kế — Đặt comment

*Đặt comment neo theo phần tử hoặc khối màn hình trên prototype.*

**Mục đích**
Cho phép người dùng thực hiện góp ý thiết kế — đặt comment thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý góp ý thiết kế — đặt comment và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện góp ý thiết kế — đặt comment. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện góp ý thiết kế — đặt comment thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TK_04] Góp ý thiết kế — Đồng ý xử lý comment

*Đánh dấu comment cần xử lý; hệ thống chỉ sửa thiết kế theo comment ở trạng thái này.*

**Mục đích**
Cho phép người dùng thực hiện góp ý thiết kế — đồng ý xử lý comment thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý góp ý thiết kế — đồng ý xử lý comment và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện góp ý thiết kế — đồng ý xử lý comment. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện góp ý thiết kế — đồng ý xử lý comment thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TK_05] Góp ý thiết kế — Xác nhận đóng comment

*Người dùng xác nhận kết quả xử lý để đóng comment; hệ thống không tự đóng.*

**Mục đích**
Cho phép người dùng thực hiện góp ý thiết kế — xác nhận đóng comment thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý góp ý thiết kế — xác nhận đóng comment và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện góp ý thiết kế — xác nhận đóng comment. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện góp ý thiết kế — xác nhận đóng comment thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TK_06] Góp ý thiết kế — Xem lịch sử vòng sửa

*Đối chiếu thiết kế trước và sau của từng vòng xử lý comment.*

**Mục đích**
Cho phép người dùng thực hiện góp ý thiết kế — xem lịch sử vòng sửa thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý góp ý thiết kế — xem lịch sử vòng sửa và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện góp ý thiết kế — xem lịch sử vòng sửa. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện góp ý thiết kế — xem lịch sử vòng sửa thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BT_01] Bộ tài liệu — Danh sách / tìm kiếm bộ tài liệu

*Liệt kê các bộ tài liệu của dự án kèm trạng thái, tiến độ x/12 và phần đã thay đổi so với bộ trước.*

**Mục đích**
Cho phép người dùng thực hiện bộ tài liệu — danh sách / tìm kiếm bộ tài liệu thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý bộ tài liệu — danh sách / tìm kiếm bộ tài liệu và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện bộ tài liệu — danh sách / tìm kiếm bộ tài liệu. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện bộ tài liệu — danh sách / tìm kiếm bộ tài liệu thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BT_02] Bộ tài liệu — Tạo bộ tài liệu mới

*Khởi tạo bộ mới kế thừa bản hoạt động của từng loại từ bộ vừa đóng; chọn các loại đánh N/A.*

**Mục đích**
Cho phép người dùng thực hiện bộ tài liệu — tạo bộ tài liệu mới thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý bộ tài liệu — tạo bộ tài liệu mới và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện bộ tài liệu — tạo bộ tài liệu mới. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện bộ tài liệu — tạo bộ tài liệu mới thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BT_03] Bộ tài liệu — Xem chi tiết bộ tài liệu

*Hiển thị từng loại tài liệu trong bộ: tên tệp, định dạng, dung lượng, thời gian xuất, người tạo và trạng thái Done/Null/N/A.*

**Mục đích**
Cho phép người dùng thực hiện bộ tài liệu — xem chi tiết bộ tài liệu thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý bộ tài liệu — xem chi tiết bộ tài liệu và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện bộ tài liệu — xem chi tiết bộ tài liệu. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện bộ tài liệu — xem chi tiết bộ tài liệu thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BT_04] Phiên bản tài liệu — Export tài liệu

*Sinh tệp mang ra ngoài để gửi khách hàng; không tạo phiên bản và không mở khóa bước sau.*

**Mục đích**
Cho phép người dùng thực hiện phiên bản tài liệu — export tài liệu thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phiên bản tài liệu — export tài liệu và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phiên bản tài liệu — export tài liệu. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phiên bản tài liệu — export tài liệu thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BT_05] Phiên bản tài liệu — Xuất phiên bản tài liệu

*Sinh một phiên bản mới của một loại vào bộ đang mở; phiên bản mới trở thành bản hoạt động.*

**Mục đích**
Cho phép người dùng thực hiện phiên bản tài liệu — xuất phiên bản tài liệu thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phiên bản tài liệu — xuất phiên bản tài liệu và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phiên bản tài liệu — xuất phiên bản tài liệu. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phiên bản tài liệu — xuất phiên bản tài liệu thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BT_06] Phiên bản tài liệu — Chọn bản hoạt động

*Chọn phiên bản của một loại làm bản sẽ được commit; mặc định là bản mới nhất.*

**Mục đích**
Cho phép người dùng thực hiện phiên bản tài liệu — chọn bản hoạt động thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phiên bản tài liệu — chọn bản hoạt động và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phiên bản tài liệu — chọn bản hoạt động. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phiên bản tài liệu — chọn bản hoạt động thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BT_07] Phiên bản tài liệu — So sánh phiên bản

*Đối chiếu nội dung giữa hai phiên bản của một loại tài liệu.*

**Mục đích**
Cho phép người dùng thực hiện phiên bản tài liệu — so sánh phiên bản thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phiên bản tài liệu — so sánh phiên bản và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phiên bản tài liệu — so sánh phiên bản. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phiên bản tài liệu — so sánh phiên bản thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BT_08] Commit & khôi phục — Commit bộ lên Git

*Chụp bản hoạt động của từng loại thành mốc verXX và đóng bộ; chặn commit khi còn loại áp dụng chưa có phiên bản.*

**Mục đích**
Cho phép người dùng thực hiện commit & khôi phục — commit bộ lên git thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý commit & khôi phục — commit bộ lên git và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện commit & khôi phục — commit bộ lên git. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện commit & khôi phục — commit bộ lên git thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BT_09] Commit & khôi phục — Khôi phục bộ

*Đưa đồng loạt cả bộ về một mốc verXX đã commit.*

**Mục đích**
Cho phép người dùng thực hiện commit & khôi phục — khôi phục bộ thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý commit & khôi phục — khôi phục bộ và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện commit & khôi phục — khôi phục bộ. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện commit & khôi phục — khôi phục bộ thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_UL_01] ULNL — Xem bảng ước lượng nỗ lực

*Hiển thị nỗ lực theo chức năng và ba nhóm task Giải pháp / Phát triển / Kiểm thử, quy đổi giờ → MD → MM.*

**Mục đích**
Cho phép người dùng thực hiện ulnl — xem bảng ước lượng nỗ lực thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý ulnl — xem bảng ước lượng nỗ lực và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện ulnl — xem bảng ước lượng nỗ lực. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện ulnl — xem bảng ước lượng nỗ lực thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_UL_02] ULNL — Điều chỉnh nỗ lực qua phiên chat

*PM yêu cầu chỉnh nỗ lực của một dòng qua chat; dòng đã chỉnh mang dấu nguồn PM điều chỉnh.*

**Mục đích**
Cho phép người dùng thực hiện ulnl — điều chỉnh nỗ lực qua phiên chat thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý ulnl — điều chỉnh nỗ lực qua phiên chat và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện ulnl — điều chỉnh nỗ lực qua phiên chat. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện ulnl — điều chỉnh nỗ lực qua phiên chat thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_UL_03] ULNL — Đối chiếu MM ULNL với MM hợp đồng

*So MM thực tế theo chức năng với MM hợp đồng đã khai để xác định mức khớp hay vượt.*

**Mục đích**
Cho phép người dùng thực hiện ulnl — đối chiếu mm ulnl với mm hợp đồng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý ulnl — đối chiếu mm ulnl với mm hợp đồng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện ulnl — đối chiếu mm ulnl với mm hợp đồng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện ulnl — đối chiếu mm ulnl với mm hợp đồng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_UL_04] Task Jira — Sinh cây task Jira

*Sinh Epic / Story / Sub-task theo chức năng và loại man-hour, gắn mã chức năng và bộ tài liệu.*

**Mục đích**
Cho phép người dùng thực hiện task jira — sinh cây task jira thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý task jira — sinh cây task jira và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện task jira — sinh cây task jira. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện task jira — sinh cây task jira thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_UL_05] Task Jira — Đồng bộ man-hour sang Jira

*Cập nhật Original Estimate vào sub-task theo cặp khóa mã chức năng và loại man-hour.*

**Mục đích**
Cho phép người dùng thực hiện task jira — đồng bộ man-hour sang jira thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý task jira — đồng bộ man-hour sang jira và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện task jira — đồng bộ man-hour sang jira. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện task jira — đồng bộ man-hour sang jira thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_UL_06] Task Jira — Kiểm tra đối chiếu man-hour

*Chạy rule đối chiếu MH_ULNL_Total với tổng Original Estimate và báo lỗi khi sinh task thiếu, thừa hoặc sai.*

**Mục đích**
Cho phép người dùng thực hiện task jira — kiểm tra đối chiếu man-hour thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý task jira — kiểm tra đối chiếu man-hour và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện task jira — kiểm tra đối chiếu man-hour. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện task jira — kiểm tra đối chiếu man-hour thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TD_01] Yêu cầu thay đổi — Danh sách / tìm kiếm yêu cầu

*Liệt kê yêu cầu nghiệp vụ cần trao đổi theo hai tab; lọc theo trạng thái, chức năng và người chốt.*

**Mục đích**
Cho phép người dùng thực hiện yêu cầu thay đổi — danh sách / tìm kiếm yêu cầu thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý yêu cầu thay đổi — danh sách / tìm kiếm yêu cầu và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện yêu cầu thay đổi — danh sách / tìm kiếm yêu cầu. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện yêu cầu thay đổi — danh sách / tìm kiếm yêu cầu thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TD_02] Yêu cầu thay đổi — Tạo yêu cầu thay đổi

*Tạo yêu cầu với chức năng liên quan, người chốt, người liên quan và nội dung thay đổi.*

**Mục đích**
Cho phép người dùng thực hiện yêu cầu thay đổi — tạo yêu cầu thay đổi thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý yêu cầu thay đổi — tạo yêu cầu thay đổi và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện yêu cầu thay đổi — tạo yêu cầu thay đổi. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện yêu cầu thay đổi — tạo yêu cầu thay đổi thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TD_03] Yêu cầu thay đổi — Trao đổi trong phiên

*Trao đổi nội dung thay đổi trong phiên chat nhóm cho tới khi chốt.*

**Mục đích**
Cho phép người dùng thực hiện yêu cầu thay đổi — trao đổi trong phiên thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý yêu cầu thay đổi — trao đổi trong phiên và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện yêu cầu thay đổi — trao đổi trong phiên. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện yêu cầu thay đổi — trao đổi trong phiên thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TD_04] Yêu cầu thay đổi — Hủy yêu cầu thay đổi

*Người tạo hủy yêu cầu đang chờ xử lý kèm lý do; ghi vết sự kiện.*

**Mục đích**
Cho phép người dùng thực hiện yêu cầu thay đổi — hủy yêu cầu thay đổi thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý yêu cầu thay đổi — hủy yêu cầu thay đổi và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện yêu cầu thay đổi — hủy yêu cầu thay đổi. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện yêu cầu thay đổi — hủy yêu cầu thay đổi thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TD_05] Yêu cầu thay đổi — Chốt hoặc từ chối yêu cầu

*Người chốt chấp nhận hoặc từ chối yêu cầu kèm lý do; phiên đóng sau khi chốt.*

**Mục đích**
Cho phép người dùng thực hiện yêu cầu thay đổi — chốt hoặc từ chối yêu cầu thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý yêu cầu thay đổi — chốt hoặc từ chối yêu cầu và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện yêu cầu thay đổi — chốt hoặc từ chối yêu cầu. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện yêu cầu thay đổi — chốt hoặc từ chối yêu cầu thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TD_06] Lan tỏa thay đổi — Xác nhận phạm vi ảnh hưởng

*Tick chọn các bản tài liệu và task Jira bị ảnh hưởng theo đề xuất kèm mức tác động, lý do và hệ quả MM; ghi vết lần bấm.*

**Mục đích**
Cho phép người dùng thực hiện lan tỏa thay đổi — xác nhận phạm vi ảnh hưởng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý lan tỏa thay đổi — xác nhận phạm vi ảnh hưởng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện lan tỏa thay đổi — xác nhận phạm vi ảnh hưởng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện lan tỏa thay đổi — xác nhận phạm vi ảnh hưởng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TD_07] Lan tỏa thay đổi — Gửi mail thông báo thay đổi

*Gửi mail tới toàn đội theo hai nhịp: chốt phạm vi và công bố bộ mới.*

**Mục đích**
Cho phép người dùng thực hiện lan tỏa thay đổi — gửi mail thông báo thay đổi thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý lan tỏa thay đổi — gửi mail thông báo thay đổi và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện lan tỏa thay đổi — gửi mail thông báo thay đổi. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện lan tỏa thay đổi — gửi mail thông báo thay đổi thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TD_08] Phát sinh MM — Xem báo cáo phát sinh MM

*Hiển thị phạm vi ban đầu, danh sách thay đổi, MM phát sinh theo từng thay đổi và ba con số MM tổng hợp.*

**Mục đích**
Cho phép người dùng thực hiện phát sinh mm — xem báo cáo phát sinh mm thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phát sinh mm — xem báo cáo phát sinh mm và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phát sinh mm — xem báo cáo phát sinh mm. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phát sinh mm — xem báo cáo phát sinh mm thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_TD_09] Phát sinh MM — Xuất báo cáo phát sinh MM

*Kết xuất báo cáo giải trình để đề xuất bổ sung MM với khách hàng.*

**Mục đích**
Cho phép người dùng thực hiện phát sinh mm — xuất báo cáo phát sinh mm thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phát sinh mm — xuất báo cáo phát sinh mm và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phát sinh mm — xuất báo cáo phát sinh mm. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phát sinh mm — xuất báo cáo phát sinh mm thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_KT_01] Phiên kiểm thử — Danh sách / tìm kiếm phiên kiểm thử

*Liệt kê các phiên kiểm thử của dự án; lọc theo phạm vi, trạng thái và thời gian chạy.*

**Mục đích**
Cho phép người dùng thực hiện phiên kiểm thử — danh sách / tìm kiếm phiên kiểm thử thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phiên kiểm thử — danh sách / tìm kiếm phiên kiểm thử và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phiên kiểm thử — danh sách / tìm kiếm phiên kiểm thử. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phiên kiểm thử — danh sách / tìm kiếm phiên kiểm thử thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_KT_02] Phiên kiểm thử — Tạo phiên kiểm thử

*Tạo phiên và cấu hình phạm vi kiểm thử cùng thông số môi trường.*

**Mục đích**
Cho phép người dùng thực hiện phiên kiểm thử — tạo phiên kiểm thử thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phiên kiểm thử — tạo phiên kiểm thử và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phiên kiểm thử — tạo phiên kiểm thử. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phiên kiểm thử — tạo phiên kiểm thử thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_KT_03] Phiên kiểm thử — Chạy kiểm thử

*Sinh ma trận test từ Testcase và thực thi trên commit mới nhất của chức năng.*

**Mục đích**
Cho phép người dùng thực hiện phiên kiểm thử — chạy kiểm thử thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phiên kiểm thử — chạy kiểm thử và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phiên kiểm thử — chạy kiểm thử. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phiên kiểm thử — chạy kiểm thử thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_KT_04] Phiên kiểm thử — Xem kết quả theo case

*Hiển thị kết quả từng case ở ba trạng thái Pass / Fail / Không kiểm được tự động.*

**Mục đích**
Cho phép người dùng thực hiện phiên kiểm thử — xem kết quả theo case thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phiên kiểm thử — xem kết quả theo case và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phiên kiểm thử — xem kết quả theo case. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phiên kiểm thử — xem kết quả theo case thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_KT_05] Phiên kiểm thử — Xuất kết quả kiểm thử

*Kết xuất kết quả phiên kiểm thử thành tệp.*

**Mục đích**
Cho phép người dùng thực hiện phiên kiểm thử — xuất kết quả kiểm thử thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phiên kiểm thử — xuất kết quả kiểm thử và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phiên kiểm thử — xuất kết quả kiểm thử. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phiên kiểm thử — xuất kết quả kiểm thử thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_KT_06] Phiên kiểm thử — Xóa phiên kiểm thử

*Xóa phiên kiểm thử qua bước xác nhận; ghi vết người thực hiện.*

**Mục đích**
Cho phép người dùng thực hiện phiên kiểm thử — xóa phiên kiểm thử thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý phiên kiểm thử — xóa phiên kiểm thử và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện phiên kiểm thử — xóa phiên kiểm thử. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện phiên kiểm thử — xóa phiên kiểm thử thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_KT_07] Quản lý lỗi — Log bug lên Jira

*Dựng nội dung bug từ case fail, chọn người xử lý và gắn bug về task của chức năng; chống trùng theo cặp chức năng và mã case.*

**Mục đích**
Cho phép người dùng thực hiện quản lý lỗi — log bug lên jira thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý quản lý lỗi — log bug lên jira và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện quản lý lỗi — log bug lên jira. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện quản lý lỗi — log bug lên jira thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_DB_01] Dashboard dự án — Xem khu Tiến độ

*Hiển thị tiến độ ba tuyến BA/Dev/QA theo số task và theo trọng số giờ, kèm mốc phạm vi đổi và dự báo trễ.*

**Mục đích**
Cho phép người dùng thực hiện dashboard dự án — xem khu tiến độ thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý dashboard dự án — xem khu tiến độ và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện dashboard dự án — xem khu tiến độ. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện dashboard dự án — xem khu tiến độ thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_DB_02] Dashboard dự án — Xem khu Nguồn lực

*Hiển thị MM phạm vi hiện hành, MM sunk, MM tổng tiêu so MM hợp đồng và nhân sự đang vượt tổng tải.*

**Mục đích**
Cho phép người dùng thực hiện dashboard dự án — xem khu nguồn lực thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý dashboard dự án — xem khu nguồn lực và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện dashboard dự án — xem khu nguồn lực. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện dashboard dự án — xem khu nguồn lực thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_DB_03] Dashboard dự án — Xem khu Hiệu suất

*Hiển thị độ lệch giữa logwork và ULNL kèm cảnh báo làm lố; phân quyền theo người.*

**Mục đích**
Cho phép người dùng thực hiện dashboard dự án — xem khu hiệu suất thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý dashboard dự án — xem khu hiệu suất và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện dashboard dự án — xem khu hiệu suất. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện dashboard dự án — xem khu hiệu suất thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_DB_04] Dashboard dự án — Xem khu Chất lượng

*Hiển thị bug mở/đóng, regression, số case không kiểm được tự động và độ phủ HDSD.*

**Mục đích**
Cho phép người dùng thực hiện dashboard dự án — xem khu chất lượng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý dashboard dự án — xem khu chất lượng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện dashboard dự án — xem khu chất lượng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện dashboard dự án — xem khu chất lượng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_DB_05] Dashboard dự án — Xem khu Phát sinh MM

*Hiển thị báo cáo giải trình thay đổi và đề xuất bổ sung MM.*

**Mục đích**
Cho phép người dùng thực hiện dashboard dự án — xem khu phát sinh mm thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý dashboard dự án — xem khu phát sinh mm và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện dashboard dự án — xem khu phát sinh mm. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện dashboard dự án — xem khu phát sinh mm thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_DB_06] Dashboard dự án — Chỉnh Plan đề xuất

*PM chỉnh kế hoạch đè lên bản hệ thống đề xuất; lưu tách hai bản để đối chiếu.*

**Mục đích**
Cho phép người dùng thực hiện dashboard dự án — chỉnh plan đề xuất thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý dashboard dự án — chỉnh plan đề xuất và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện dashboard dự án — chỉnh plan đề xuất. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện dashboard dự án — chỉnh plan đề xuất thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_DB_07] Dashboard dự án — Xuất báo cáo dashboard

*Kết xuất số liệu đang hiển thị thành tệp.*

**Mục đích**
Cho phép người dùng thực hiện dashboard dự án — xuất báo cáo dashboard thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý dashboard dự án — xuất báo cáo dashboard và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện dashboard dự án — xuất báo cáo dashboard. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện dashboard dự án — xuất báo cáo dashboard thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BB_01] Biên bản họp dự án — Danh sách / tìm kiếm biên bản

*Liệt kê biên bản họp của dự án kèm trạng thái Nháp / Đã gửi / Đã xác nhận.*

**Mục đích**
Cho phép người dùng thực hiện biên bản họp dự án — danh sách / tìm kiếm biên bản thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý biên bản họp dự án — danh sách / tìm kiếm biên bản và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện biên bản họp dự án — danh sách / tìm kiếm biên bản. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện biên bản họp dự án — danh sách / tìm kiếm biên bản thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BB_02] Biên bản họp dự án — Ghi âm hoặc tải bản ghi

*Ghi trực tiếp hoặc tải tệp bản ghi cuộc họp để hệ thống dựng biên bản có cấu trúc.*

**Mục đích**
Cho phép người dùng thực hiện biên bản họp dự án — ghi âm hoặc tải bản ghi thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý biên bản họp dự án — ghi âm hoặc tải bản ghi và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện biên bản họp dự án — ghi âm hoặc tải bản ghi. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện biên bản họp dự án — ghi âm hoặc tải bản ghi thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BB_03] Biên bản họp dự án — Soát và chỉnh biên bản

*Xem và chỉnh nội dung trao đổi, yêu cầu nghe được và điểm chưa rõ trước khi lưu.*

**Mục đích**
Cho phép người dùng thực hiện biên bản họp dự án — soát và chỉnh biên bản thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý biên bản họp dự án — soát và chỉnh biên bản và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện biên bản họp dự án — soát và chỉnh biên bản. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện biên bản họp dự án — soát và chỉnh biên bản thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BB_04] Biên bản họp dự án — Gửi mail xác nhận

*Soát nội dung mail nháp và gửi xác nhận biên bản tới người tham dự.*

**Mục đích**
Cho phép người dùng thực hiện biên bản họp dự án — gửi mail xác nhận thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý biên bản họp dự án — gửi mail xác nhận và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện biên bản họp dự án — gửi mail xác nhận. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện biên bản họp dự án — gửi mail xác nhận thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BB_05] Biên bản họp dự án — Cập nhật trạng thái biên bản

*Chuyển trạng thái biên bản theo tiến trình xác nhận.*

**Mục đích**
Cho phép người dùng thực hiện biên bản họp dự án — cập nhật trạng thái biên bản thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý biên bản họp dự án — cập nhật trạng thái biên bản và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện biên bản họp dự án — cập nhật trạng thái biên bản. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện biên bản họp dự án — cập nhật trạng thái biên bản thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [DA_BB_06] Biên bản họp dự án — Xóa biên bản

*Xóa biên bản qua bước xác nhận; ghi vết người thực hiện.*

**Mục đích**
Cho phép người dùng thực hiện biên bản họp dự án — xóa biên bản thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý biên bản họp dự án — xóa biên bản và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện biên bản họp dự án — xóa biên bản. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện biên bản họp dự án — xóa biên bản thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [CC_XT_01] Xác thực — Đăng nhập

*Xác thực người dùng bằng tài khoản được cấp và khởi tạo phiên làm việc theo vai trò mặc định.*

**Mục đích**
Cho phép người dùng thực hiện xác thực — đăng nhập thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý xác thực — đăng nhập và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện xác thực — đăng nhập. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện xác thực — đăng nhập thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [CC_XT_02] Xác thực — Đăng xuất

*Kết thúc phiên làm việc và trả người dùng về màn đăng nhập.*

**Mục đích**
Cho phép người dùng thực hiện xác thực — đăng xuất thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý xác thực — đăng xuất và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện xác thực — đăng xuất. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện xác thực — đăng xuất thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [CC_XT_03] Xác thực — Quên mật khẩu

*Gửi đường dẫn đặt lại mật khẩu tới email đã đăng ký của người dùng.*

**Mục đích**
Cho phép người dùng thực hiện xác thực — quên mật khẩu thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý xác thực — quên mật khẩu và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện xác thực — quên mật khẩu. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện xác thực — quên mật khẩu thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [CC_XT_04] Xác thực — Đổi mật khẩu

*Cho phép người dùng đổi mật khẩu hiện tại; ghi vết thời điểm thay đổi.*

**Mục đích**
Cho phép người dùng thực hiện xác thực — đổi mật khẩu thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý xác thực — đổi mật khẩu và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện xác thực — đổi mật khẩu. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện xác thực — đổi mật khẩu thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [CC_XT_05] Tài khoản — Chuyển tài khoản

*Chuyển sang tài khoản khác mà không cần đăng xuất thủ công; ghi vết lần chuyển.*

**Mục đích**
Cho phép người dùng thực hiện tài khoản — chuyển tài khoản thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý tài khoản — chuyển tài khoản và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện tài khoản — chuyển tài khoản. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện tài khoản — chuyển tài khoản thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [CC_XT_06] Tài khoản — Chuyển vai trò đang đóng

*Chuyển vai trò trong giới hạn quyền được cấp; menu và vùng dữ liệu cập nhật lại theo vai trò mới.*

**Mục đích**
Cho phép người dùng thực hiện tài khoản — chuyển vai trò đang đóng thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý tài khoản — chuyển vai trò đang đóng và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện tài khoản — chuyển vai trò đang đóng. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện tài khoản — chuyển vai trò đang đóng thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [CC_XT_07] Tài khoản — Xem và chỉnh hồ sơ cá nhân

*Hiển thị và cập nhật thông tin cá nhân, ảnh đại diện và thông tin liên hệ.*

**Mục đích**
Cho phép người dùng thực hiện tài khoản — xem và chỉnh hồ sơ cá nhân thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý tài khoản — xem và chỉnh hồ sơ cá nhân và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện tài khoản — xem và chỉnh hồ sơ cá nhân. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện tài khoản — xem và chỉnh hồ sơ cá nhân thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [CC_GD_01] Hiển thị — Chế độ sáng / tối

*Chuyển giao diện giữa chế độ sáng và tối; lưu thiết lập theo người dùng.*

**Mục đích**
Cho phép người dùng thực hiện hiển thị — chế độ sáng / tối thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hiển thị — chế độ sáng / tối và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hiển thị — chế độ sáng / tối. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hiển thị — chế độ sáng / tối thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [CC_GD_02] Hiển thị — Thu gọn / mở rộng menu

*Ẩn hoặc hiện thanh điều hướng trái; ghi nhớ trạng thái theo người dùng.*

**Mục đích**
Cho phép người dùng thực hiện hiển thị — thu gọn / mở rộng menu thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý hiển thị — thu gọn / mở rộng menu và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện hiển thị — thu gọn / mở rộng menu. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện hiển thị — thu gọn / mở rộng menu thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [CC_GD_03] Ngữ cảnh làm việc — Chuyển phạm vi làm việc

*Chuyển ngữ cảnh giữa Toàn tổ chức và một dự án cụ thể; vùng dữ liệu truy vấn đổi theo phạm vi.*

**Mục đích**
Cho phép người dùng thực hiện ngữ cảnh làm việc — chuyển phạm vi làm việc thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý ngữ cảnh làm việc — chuyển phạm vi làm việc và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện ngữ cảnh làm việc — chuyển phạm vi làm việc. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện ngữ cảnh làm việc — chuyển phạm vi làm việc thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [CC_GD_04] Ngữ cảnh làm việc — Chọn model AI cho phiên

*Chọn model dùng cho phiên sinh nội dung; áp dụng cho toàn phiên.*

**Mục đích**
Cho phép người dùng thực hiện ngữ cảnh làm việc — chọn model ai cho phiên thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý ngữ cảnh làm việc — chọn model ai cho phiên và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện ngữ cảnh làm việc — chọn model ai cho phiên. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện ngữ cảnh làm việc — chọn model ai cho phiên thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [CC_TB_01] Thông báo — Xem danh sách thông báo

*Hiển thị thông báo gửi tới người dùng kèm số lượng chưa đọc.*

**Mục đích**
Cho phép người dùng thực hiện thông báo — xem danh sách thông báo thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý thông báo — xem danh sách thông báo và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện thông báo — xem danh sách thông báo. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện thông báo — xem danh sách thông báo thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

## [CC_TB_02] Thông báo — Cấu hình nhận thông báo

*Bật/tắt từng loại thông báo trong giới hạn vai trò cho phép.*

**Mục đích**
Cho phép người dùng thực hiện thông báo — cấu hình nhận thông báo thuận tiện và chính xác.

**Đối tượng sử dụng**
Người dùng cuối đã đăng nhập và được phân quyền truy cập.

**Luồng nghiệp vụ chính**
Người dùng mở màn hình, nhập thông tin cần thiết, hệ thống kiểm tra hợp lệ, xử lý thông báo — cấu hình nhận thông báo và phản hồi kết quả.

**Quy tắc nghiệp vụ**
Mọi trường bắt buộc phải hợp lệ trước khi thực hiện thông báo — cấu hình nhận thông báo. Ghi vết kiểm toán (audit log) đầy đủ.

**Trường hợp ngoại lệ**
Dữ liệu nhập không hợp lệ; mất kết nối mạng; phiên làm việc hết hạn.

**Tiêu chí chấp nhận**
Thực hiện thông báo — cấu hình nhận thông báo thành công, dữ liệu được lưu vết chính xác và thông báo phản hồi rõ ràng.

