Chào bạn! Đây là một ứng dụng web đơn giản nhưng mạnh mẽ, được xây dựng bằng Python Flask ở backend và HTML/CSS/JavaScript ở frontend, giúp bạn hiểu và trải nghiệm quá trình truyền file dữ liệu có kí số sử dụng thuật toán RSA.

Ứng dụng này làm được gì?
Ứng dụng này mô phỏng một quy trình an toàn để chứng thực nguồn gốc và đảm bảo tính toàn vẹn của file dữ liệu thông qua chữ ký số. Cụ thể, nó cho phép bạn:

Tạo cặp khóa RSA: Bạn có thể tạo ra một cặp khóa RSA mới (khóa riêng tư và khóa công khai). Khóa riêng tư sẽ được dùng để ký, còn khóa công khai sẽ được dùng để xác minh. Bạn có thể đặt tên cho các cặp khóa để dễ dàng quản lý.
Tải lên và ký số file:
Bạn chọn một file bất kỳ từ máy tính của mình.
Ứng dụng sẽ sử dụng khóa riêng tư mà bạn chọn để tạo ra một chữ ký số duy nhất cho file đó.
Cả file gốc và file chữ ký số sẽ được lưu trữ trên server.
Tải xuống file và chữ ký: Sau khi ký, bạn có thể tải về cả file gốc và file chữ ký số riêng biệt.
Xác minh chữ ký số:
Bạn có thể tải lên lại file gốc và file chữ ký số tương ứng.
Ứng dụng sẽ sử dụng khóa công khai (tương ứng với khóa riêng tư dùng để ký) để kiểm tra xem chữ ký có hợp lệ hay không.
Nếu chữ ký hợp lệ, điều đó có nghĩa là file chưa bị thay đổi kể từ khi được ký và đúng là do người sở hữu khóa riêng tư đã ký. Nếu không, file có thể đã bị can thiệp.
