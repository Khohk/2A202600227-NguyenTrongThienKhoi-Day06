# Individual Reflection — Day 5 & 6
**Họ tên:** Ng Trọng thiên Khôi
**MSSV:** 2A202600227
**Nhóm:** 16 — Track B (Vinmec)
**Topic:** Vinmec AI Triage & Booking Chat

---

## 1. Role & Đóng góp cá nhân (10 điểm)

**Vai trò trong nhóm:** Người đưa ra ý tưởng,khung công việc, và chỉnh sửa các phần việc của mọi người 

**Các phần tôi trực tiếp làm:**

- Đưa ra khung và tham gia viết file spec final
- Viết code phần tools và chỉnh sửa system prompt
- Đưa ra hướng đi cho sản phẩm của team,chọn đề bài

**Commit trên repo nhóm:**
Link: 

[---
](https://github.com/ductiens/Nhom12-402-Day06-01)
## 2. Individual Reflection (15 điểm)

### Điều tôi học được từ Day 5–6

Trước hackathon, tôi nghĩ rằng build một sản phẩm AI chỉ cần có model chạy được là xong. Nhưng qua quá trình làm SPEC và prototype cho Vinmec, tôi nhận ra rằng phần khó nhất không phải là code — mà là **thiết kế cho uncertainty**.

Cụ thể, khi xây dựng phần triage triệu chứng, nhóm tôi phải quyết định: optimize precision hay recall? Đây không phải câu hỏi kỹ thuật — đây là product decision. Với red flag detection, recall phải là 100% vì bỏ sót 1 case nguy hiểm có thể ảnh hưởng đến tính mạng. Nhưng với gợi ý chuyên khoa thông thường, precision quan trọng hơn vì gợi ý sai khoa khiến bệnh nhân mất thời gian và tiền bạc — thiệt hại trực tiếp và cảm nhận được ngay. Cùng một sản phẩm, hai bài toán, hai metric khác nhau — điều này tôi chưa từng nghĩ đến trước đây.

Ngoài ra việc thiết kế ui/ux không phải thật fancy mà làm sao cho phù hợp,tiện lợi nhất cho người dùng và việc xây dựng spec cũng như prototype giúp t nhận ra rằng nếu xây dựng làm rõ bài toán trong thực tế yêu cầu những gì và việc biết những thứ đó giúp cho xây dựng sản phẩm sau dễ dàng hơn nhiều

### Điều tôi tự làm và tự debug

Chỉnh sửa system prompt để agent có thể hoạt động hiệu quả ,chính xác với nhiều case khác nhau

### Quyết định khó nhất trong hackathon

Phân công, chia việc và quản lý thời gian

### Nếu làm lại, tôi sẽ thay đổi gì

Chia việc rõ ràng và cụ thể hơn các thành viên trong team

### Kết nối với bản thân — AI product thinking áp dụng vào đâu tiếp theo

Với dự án nhóm đang làm
---

