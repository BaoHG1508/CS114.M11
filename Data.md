# Thu thập dữ liệu

Dùng các video để thu thập dữ liệu nhóm mỗi thành viên sẽ tự quay các video theo từng kí tự có trong bài toán.
Nhóm sẽ dùng các video này để thu thập dữ liệu bằng cách vẽ landmark của tay theo từng kí tự đã thu thập được sau đó lưu các landmark đó về theo từng kí tự riêng biệt để dùng cho việc huấn luyện mô hình. Trong quá trình thu thập dữ liệu nhóm gặp khó khăn như: Thiếu ánh sáng, nhận diện hand để lấy landmark chưa mượt do camera thiếu chất lượng (giải pháp là phải mua thêm đèn đặt trước mặt).

  * Để mô phỏng cho 2 người đang nói chuyện với nhau nhóm sẽ chuẩn bị 1 chiếc laptop có sẵn camera để trước mặt.
   * Đưa tay lên xuống theo kí hiệu đang thu thập(chữ A thì phải để tay chữ A lên camera).
   * Sử dụng thư viện Mediapipe và openCV để xác định ví trị của bàn tay  sau đó vẽ ra landmark trên tay.
  * Lưu lại toạ độ landmark trong frame ảnh.
   * Lưu theo từng folder ứng với kí hiệu đó (Đồng thời gán nhãn xong dữ liệu).
