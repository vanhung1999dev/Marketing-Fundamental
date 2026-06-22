## CHECKLIST: Cải Tiến Liên Tục — Nhịp Điệu Đánh Giá Và Cải Thiện

Cải tiến liên tục không xảy ra vì ai đó "muốn tốt hơn" — nó xảy ra vì có cadence cụ thể: thời điểm cố định để dừng lại, nhìn lại, và commit một improvement. Không có cadence = improvement chỉ xảy ra khi có sự cố. Có cadence = improvement là thứ xảy ra bất kể có sự cố hay không.

Dưới đây là 3-tier review system — từ tactical (hàng tuần) đến strategic (hàng quý). Chọn tier phù hợp với quy mô team và dùng nhất quán.

---

### TIER 1: WEEKLY FRICTION REVIEW (15–20 phút, mỗi thứ Sáu)

*Mục tiêu: Bắt những vấn đề nhỏ trước khi chúng thành lớn*

**Câu hỏi cho cả team (async, qua form hoặc channel Slack):**
- [ ] Có quy trình nào gây friction cho bạn trong tuần này không? *(Cụ thể: bước nào, tại sao bất tiện)*
- [ ] Có mistake nào xảy ra mà có thể prevent bằng system change không? *(Không blame người — blame process)*
- [ ] Có bước nào trong quy trình bạn thường skip vì "mất thời gian"? *(Đây là signal của over-engineered process)*
- [ ] Có tool/công cụ nào đang làm chậm work hơn là giúp không?
- [ ] Có thông tin nào bạn cần nhưng không biết tìm ở đâu không?

**Output mong đợi:** 1 danh sách friction points của tuần. Không cần fix ngay — chỉ capture.

**Ai làm:** Toàn team tự báo cáo. Manager tổng hợp.

---

### TIER 2: MONTHLY IMPROVEMENT MEETING (60–90 phút, cuối tháng)

*Mục tiêu: Review friction points tích lũy, pick và commit 1 improvement*

**Agenda:**
1. **(10 phút)** Review friction points từ 4 tuần qua — nhóm theo chủ đề
2. **(15 phút)** Review top 3 complaints từ team về quy trình nội bộ
3. **(15 phút)** Review top 3 complaints từ khách hàng về delivery/quality
4. **(20 phút)** Vote và chọn 1 improvement để pilot tháng tới *(không phải 5 — chọn 1)*
5. **(15 phút)** Define rõ improvement đó: ai làm gì, deadline, cách đo kết quả
6. **(5 phút)** Review improvement đã commit tháng trước: có work không? Tiếp tục, adjust, hay dừng?

**Checklist trước buổi họp:**
- [ ] Đã tổng hợp weekly friction points chưa?
- [ ] Đã có data về complaints từ khách chưa? (email, NPS feedback, review)
- [ ] Đã review status của improvement tháng trước chưa?

**Output mong đợi:** 1 improvement được assign owner + deadline + success metric.

**Ai tham gia:** Team lead + 1-2 người liên quan trực tiếp đến quy trình cần improve.

---

### TIER 3: QUARTERLY PROCESS AUDIT (Half-day, cuối mỗi quý)

*Mục tiêu: Nhìn toàn cảnh, đánh giá health của hệ thống vận hành*

**Checklist chuẩn bị:**
- [ ] Tổng hợp tất cả improvements đã thực hiện trong quý → cái nào work, cái nào không
- [ ] Pull metrics vận hành của quý: tỷ lệ lỗi, thời gian xử lý, customer satisfaction
- [ ] Hỏi mỗi team lead: "Quy trình nào đang tốn nhiều effort nhất mà ít giá trị nhất?"
- [ ] Benchmark: so sánh với best practices ngành nếu có thể

**Nội dung audit:**
- [ ] 3 Core processes có còn phản ánh cách tốt nhất để làm việc không?
- [ ] Có Core process nào mới nổi lên cần được document không?
- [ ] Có SOP nào đã lỗi thời vì tool/sản phẩm/team thay đổi không?
- [ ] Mức độ adoption của SOP hiện tại — team có thực sự follow không?
- [ ] Bottleneck của quý là ở đâu? (người? tool? quy trình?)

**Output mong đợi:** Danh sách 3–5 changes ưu tiên cho quý tới, được approve và assign owner.

---

### TRACKING IMPROVEMENTS

Dùng bảng đơn giản này để track tất cả improvements đã commit:

| Improvement | Owner | Deadline | Metric đo | Status | Kết quả |
|---|---|---|---|---|---|
| Thêm template email xử lý khiếu nại | Chị Lan | 15/7 | Thời gian xử lý giảm từ 4h → 2h | In progress | - |
| Document quy trình onboard khách mới | Anh Hùng | 30/7 | NPS week-1 tăng | Done | NPS tăng 8 điểm |

---

> **Bài học:** Khi muốn improve operations, đừng hỏi "Làm sao để tăng gấp đôi output?" — hỏi "Có thể loại bỏ bước nào trong quy trình này không? Có thể giảm thời gian chuyển đổi giữa bước A và B không? Có thể standardize quyết định nhỏ này không?" Những cải tiến nhỏ cộng dồn lại. Và cadence review là cơ chế đảm bảo điều đó xảy ra đều đặn, không phụ thuộc vào cảm hứng.

> **Phân tích sâu:** 3-tier review system này dựa trên nguyên tắc "Inspect and Adapt" của Agile — nhưng được áp dụng cho operations, không chỉ software development. Tier ngắn (weekly) bắt noise; Tier trung (monthly) xử lý signal; Tier dài (quarterly) điều chỉnh direction. Không có tier nào thay thế được tier kia — cần đủ cả 3 để hệ thống cải tiến thực sự hoạt động.

> **Sai lầm phổ biến #1:** Chỉ có quarterly review, bỏ qua weekly và monthly. Kết quả: dồn tích quá nhiều vấn đề, buổi quarterly review thành một buổi "than vãn" thay vì "cải tiến". Weekly friction capture giúp vấn đề không tích lũy quá lâu.

> **Sai lầm phổ biến #2:** Commit quá nhiều improvements một lúc. Tháng commit 5 cải tiến → không cái nào được làm đến nơi → tháng sau cũng vậy. Rule: commit 1 improvement per month, làm cho đến khi xong và đo được kết quả, rồi mới pick cái tiếp theo.

> **Cạm bẫy:** Weekly review trở thành buổi blame. Thiết kế ngay từ đầu là "blame process, not people" — khi ai đó báo cáo friction, câu hỏi ngay là "quy trình nào cần thay đổi?" chứ không phải "ai đã làm sai?". Nếu culture không safe để báo cáo friction, weekly review sẽ chỉ thu thập "mọi thứ đều ổn" — useless data.

---
