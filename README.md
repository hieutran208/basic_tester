**A. Hiểu cơ bản về kiểm thử phần mềm**

*1. Các loại kiểm thử phần mềm*
- Kiểm thử thủ công (Manual Testing): Tester thực hiện kiểm thử bằng tay, không sử dụng công cụ tự động. Thường được dùng trong giai đoạn đầu để phát hiện lỗi và kiểm tra giao diện, trải nghiệm người dùng (Ví dụ: Tester kiểm tra xem nút "Đăng nhập" có hoạt động đúng không khi nhập đúng/sai mật khẩu)
- Kiểm thử tự động (Automation Testing): Sử dụng các công cụ như Selenium, Pytest, Robot Framework để tự động kiểm tra phần mềm. Dùng khi cần kiểm thử lặp lại nhiều lần (Regression Testing) giúp tiết kiệm thời gian so với Manual Testing. (Ví dụ: Dùng Selenium để kiểm tra đăng nhập trên nhiều trình duyệt khác nhau (Chrome, Firefox, Edge)).

*2. Quy trình kiểm thử phần mềm theo mô hình Agile/Scrum*
- Mô hình hoạt động: Dự án chia thành các Sprint (chu kỳ phát triển, thường kéo dài 2 tuần). Trong mỗi Sprint, nhóm phát triển và Tester làm việc cùng nhau. Tester kiểm thử ngay khi Dev hoàn thành một tính năng thay vì đợi đến cuối dự án. Tester báo lỗi (bug), Dev sửa lỗi, Tester kiểm tra lại.
- Vai trò của Tester:
  - Hiểu rõ yêu cầu sản phẩm, thực hiện kiểm thử thủ công hoặc tự động.
  - Viết Test Case để kiểm tra từng chức năng, báo lỗi nếu có vấn đề.

*3. Test case*: Là tập hợp các bước để kiểm tra xem tính năng có hoạt động đúng hay không. Test case phải có dữ liệu đầu vào (input), kết quả mong đợi để đối chiếu

![image](https://github.com/user-attachments/assets/c6617705-faab-4e0b-bb96-da6180548c8b)

*4. Test plan*: Là tài liệu mô tả kế hoạch kiểm thử cho dự án

*5. Bug report*: Báo cáo lỗi trong quá trình kiểm thử

![image](https://github.com/user-attachments/assets/9f7109c3-9361-47ea-a295-2bef39b5d182)


