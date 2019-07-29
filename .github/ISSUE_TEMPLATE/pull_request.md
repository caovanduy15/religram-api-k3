## Checklist cho PR
Tick vào trong checklist các mục đã làm. PM xác nhận pass hết các điều kiện dưới đây thì nhấn approve

   - [ ] Đã xác nhận source code không có các thay đổi không cần thiết, như là 
      - Khoảng trắng thừa 
      - File thừa, hoặc thay đổi trong code không liên quan tới task 
  - [ ] Đã đặt Title MR và commit message theo định dạng `Task #{ISSUE_NUMBER} {ISSUE_CONTENTS}`
    - Trong đó :
      - `#{ISSUE_NUMBER}` là Redmine ID.
      - `#{ISSUE_CONTENTS}` là nội dung ngắn gọn mô tả task
    - V/d: `Task #1234 Hôm nay trời nhẹ lên cao`
  - [ ] Đã sefl review và điền đầy đủ http://bit.ly/2JUceHq
  - [ ] Đã self-test và điền kết quả vào checklist 
  - [ ] Đã viết đầy đủ thông tin trong Redmine. Mục nào không có thì ghi "Không", không để giá trị mặc định
  - [ ] Đã viết Release Notes. Đảm bảo release khi có lỗi xảy ra có thể rollback ngay lập tức 
  - [ ] Đã chuyển Redmine issue sang trạng thái Resolved (Coding done)
