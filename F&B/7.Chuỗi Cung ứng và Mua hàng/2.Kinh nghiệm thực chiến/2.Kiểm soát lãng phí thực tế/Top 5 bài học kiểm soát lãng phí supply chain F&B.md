### Top 5 Bài Học Kiểm Soát Lãng Phí Supply Chain F&B

Lãng phí trong supply chain F&B không giống lãng phí bạn có thể nhìn thấy hàng ngày — đó là tiền mất dần dần, từng phần nhỏ, qua rất nhiều điểm: trong cách mua hàng, trong kho, trong prep, trong service. Không có một drama lớn. Không có một khoảnh khắc "à, mình vừa mất X triệu." Nó chỉ hiển thị ở cuối tháng khi food cost percentage cao hơn target mà không ai biết tại sao.

Những bài học sau đây là những pattern xương máu được phát hiện sau khi đã mất tiền không cần thiết.

---

## Bài Học 1 — "Mua Nhiều Để Rẻ" Là Bẫy Tốn Kém Nhất Trong F&B

**Pattern phổ biến:**
Supplier offer giá tốt hơn khi mua quantity lớn. 20kg thay vì 10kg → giảm 15% giá đơn vị. Nghe logic. Thực tế: bạn dùng được 12kg trong shelf life, 8kg phải bỏ. Net result: không phải tiết kiệm, là lỗ.

**Math để check trước khi bulk buy:**

Break-even usage rate = 1 / (1 + discount rate)

Với 15% discount: break-even = 1 / 1.15 = 87%

Có nghĩa: phải use ít nhất 87% quantity trong shelf life để không lỗ hơn mua ít.

**Với perishable items, tự hỏi:**
- Shelf life của item là bao nhiêu ngày?
- Với usage rate hiện tại, mình dùng hết bao nhiêu % trong shelf life?
- Nếu dưới 87% → không worth it.

**Khi bulk buy THỰC SỰ sense:**
Dry goods và shelf-stable items với confirmed demand. Nếu dùng 50kg gạo/tháng và supplier offer discount cho 100kg — không có shelf life risk, storage space permitting → bulk buy sensible.

**Cạm bẫy tư duy:**
Nhà cung cấp có incentive để push volume — đó là cách họ move product và improve their own cash flow. Khi họ suggest "mua nhiều hơn để tiết kiệm", run your own math trước khi agree. Tiền của bạn bị giam trong inventory không generating return — đó là cost thực sự, dù không visible trên invoice.

---

## Bài Học 2 — Waste Không Được Đo Lường Sẽ Luôn Bị Underestimate

**Data gap:**
Nhiều owner F&B estimate food waste "khoảng 5-8%" nhưng khi đo thực tế, con số thường là 12-18%. Gap đó không phải vì owner thiếu kinh nghiệm — đó là vì waste accumulates invisibly qua nhiều điểm nhỏ.

**Hawthorne effect trong waste management:**
Chỉ việc tracking thường giảm waste 10-20% trong vài tuần đầu — không cần thay đổi gì khác. Nhân viên biết waste đang được measured → naturally become more careful. Không cần penalty, không cần incentive — measurement alone drives improvement.

**Waste tracking implementation:**

**Tuần 1 — Bucket test:**
Đặt bucket riêng trong bếp. Mọi thứ bỏ đi đều vào đó. Cuối ngày: cân và ghi số. Làm 7 ngày liên tục.

**Tuần 2-4 — Categorize:**
Add reason categories: expired, cooking error, over-production, prep waste, plate return. Mỗi ngày end-of-day: 5 phút estimate cost của waste theo category.

**Tháng 2+:**
Weekly waste cost dashboard. Share với team: "Tuần này waste của mình là X triệu. Tuần trước là Y. Giảm Z." Public acknowledgment khi waste giảm.

**Cạm bẫy lớn nhất — blame culture:**
Treat waste log như punishment ("ai làm hỏng phải ghi vào") thay vì learning tool. Blame culture → nhân viên hide waste → invisible waste → unmanageable waste. Reframe: "Chúng mình cần hiểu waste đến từ đâu để cải thiện process — không phải để phạt ai."

**Đừng measure một lần rồi stop:**
Waste reduction cần ongoing monitoring. Stop tracking sau tháng đầu → waste thường creep back up trong 60-90 ngày. Measurement phải be permanent practice.

---

## Bài Học 3 — Yield Ratio: Con Số Ít Quán F&B Biết Nhưng Ảnh Hưởng Lớn

**Điểm mù phổ biến:**
Một quán order 100kg cà rốt. Recipe cost được tính dựa trên 100kg. Nhưng sau khi trim, wash, và peel: actual usable yield chỉ 72kg. Nghĩa là recipe cost đã sai ngay từ đầu — và food cost percentage sẽ luôn appear higher than expected.

**Formula đúng:**

```
Effective cost per usable unit = As-purchased price / Yield ratio
```

Ví dụ:
- Tôm tươi: 250K/kg as-purchased
- Yield ratio sau khi bóc vỏ: 55%
- Effective cost per usable kg: 250K / 0.55 = **455K/kg usable**

Nếu recipe dùng 200g tôm usable per dish và recipe cost tính theo as-purchased price:
- Sai: 200g × 250K/kg = 50K per dish
- Đúng: 200g × 455K/kg = 91K per dish

Recipe cost sai gấp đôi.

**Benchmark yield ratios:**

| Nguyên liệu | Standard Yield | Ghi Chú |
|---|---|---|
| Tôm tươi (bóc vỏ, bỏ đầu) | 50-60% | Tùy size và head-on vs. headless |
| Thịt bò (trim, bỏ fat cap, sinew) | 80-90% | Tùy cut và spec |
| Cá fillet | 45-60% | Tùy loài |
| Rau củ (cắt tỉa) | 70-85% | Tùy loại |
| Hành tây (bỏ vỏ) | 88-92% | |
| Gà (bỏ nội tạng, cut) | 65-75% | |

**Yield varies theo supplier:**
Không assume yield ratio consistent khi switch supplier hoặc khi supplier's source changes. Re-measure sau mỗi significant supplier change. Supplier A với thịt 200K/kg và yield 85% vs. Supplier B 190K/kg và yield 75%: A có effective cost 235K/kg usable, B có 253K/kg usable. "Rẻ hơn" thực ra đắt hơn.

---

## Bài Học 4 — Menu Engineering Là Weapon Giảm Waste Mạnh Nhất

**Menu engineering trong supply chain context:**
Thường được dạy như pricing và profitability tool. Nhưng trong supply chain context, đây là waste reduction tool cực kỳ powerful: by designing menu để cross-utilize ingredients, waste từ một ingredient trở thành input cho món khác.

**Cross-utilization matrix:**
Liệt kê tất cả ingredients. Map ingredient nào appear trong bao nhiêu món.

Target: mỗi core ingredient nên appear trong ít nhất 2-3 món.

**Vấn đề của "single-use" ingredients:**
Ingredient chỉ dùng cho 1 món → nếu món đó slow day → ingredient expires. Ingredient dùng trong 3 món → usage spreads across demand, waste giảm dramatically.

**Ví dụ thực tế:**
- Thịt bò appear trong: phở bò, bún bò, cơm bò lúc lắc, bánh mì bò
- Trim từ thịt bò → ground beef cho burger special hoặc nhân gyoza
- Xương bò → pho broth, stock cho sauces

Mỗi gram purchased has multiple potential applications. Waste becomes nearly impossible khi every part of every ingredient has a destination.

**Menu size và waste correlation:**
40-item menu thường less profitable và higher waste than 15-item menu executed perfectly. Large menus require large ingredient variety → small quantities of many items → each item has higher individual waste risk. Small menu forces cross-utilization và concentration of volume per item.

**New item supply chain analysis:**
Trước khi add bất kỳ menu item mới: phân tích cross-utilization impact. Nguyên liệu mới nào cần? Cái nào đã có? Usage của mỗi ingredient đủ không để justify stock it? Item dùng nguyên liệu đã có = supply chain positive. Item cần 3 unique ingredients dùng cho chỉ 1 món = supply chain risk.

---

## Bài Học 5 — Rush Buying Là Symptom, Không Phải Chỉ Là Chi Phí

**Vòng xoáy không tốt:**
Hết hàng giữa service → driver rush đi mua ở siêu thị với retail price → cost 40-60% cao hơn supplier price → food cost spike → đổ lỗi cho chef → root cause không được fix → cycle repeats.

**Rush buying là tín hiệu mạnh nhất rằng ordering system cần được rebuild.**

**Post-mortem mỗi stockout:**

| Câu hỏi | Mục đích |
|---|---|
| Hết lúc mấy giờ? | Identify pattern (always afternoon? always weekend?) |
| Ngày nào trong tuần? | Demand pattern insight |
| Item nào? | High-risk items list |
| Tại sao hết? | Root cause classification |

**4 root causes của stockout — mỗi cái có different fix:**

1. **Par level quá thấp:** Fix = recalculate par level với better demand data
2. **Demand spike unexpected:** Fix = event ordering protocol, historical analysis
3. **Delivery không về:** Fix = backup supplier activated, delivery tracking
4. **Không check kịp thời:** Fix = daily spot check routine cho high-usage items

Mỗi root cause có different fix. Jump to "mua nhiều hơn" mà không understand root cause là patch, không phải solution.

**Chuẩn hóa pre-event ordering:**
Khi có promotion, event, hoặc holiday weekend → order thêm proactively. Quy tắc: biết 1 tuần trước → order 3 ngày trước → buffer đủ. Mỗi lần phải rush buy là data point về forecasting failure — add đó vào par level và event protocol.

---

## Xương Máu Từ Chiến Trường

> **Bài học #1 — Bulk Buy Thịt Đông Lạnh: 15% Tiết Kiệm Biến Thành 8% Lỗ**
>
> Một nhà hàng steak negotiated deal với importer: mua 50kg beef frozen thay vì 20kg/lần thường, được giảm 15%. Paper savings: 4-5 triệu so với buying 20kg twice.
>
> Thực tế: freezer space limited. 30kg đầu được thaw và served theo schedule. 20kg cuối bị left in freezer past optimal quality date. Khi finally used: texture và moisture không optimal, several customer complaints about steak quality.
>
> Bỏ 20kg không serve → waste 40% of bulk buy. Net cost: higher than buying 20kg twice at regular price.
>
> Lessons learned: (1) Freezer capacity phải be confirmed trước khi agree to bulk buy; (2) Usage rate calculation required; (3) Quality window of frozen items phải be considered — frozen doesn't mean infinite shelf life.
>
> **Phân tích sâu:** Bulk buy economics only work if: (a) Storage capacity exists, (b) Usage rate is sufficient to consume within quality window, (c) Cash flow can handle upfront investment. All three must be confirmed before committing. "15% discount" sounds compelling — but 40% waste rate eliminates the discount and then some. The supplier wins (moves more product); you lose. Always run the full calculation.

> **Bài học #2 — Waste Tracking Reveals Invisible 3 Triệu/Tháng: Kitchen Team Không Biết Mình Đang Lãng Phí Gì**
>
> Một nhà hàng casual dining, owner tự estimate waste 5-6% food cost. No formal tracking. After 3 months of profitability declining without obvious cause, implement bucket test và waste log.
>
> Week 1 bucket test: average 3.5kg food waste/day. Cost estimate: ~170K/day. Monthly: ~5.1 triệu.
>
> Breakdown by category after 2 weeks of tracking:
> - Over-production (batch too much): 45% of waste
> - Prep waste (trimming excess): 25%
> - Expired items: 20%
> - Cooking errors: 10%
>
> Action: reduce batch sizes (prep to 80% of expected vs. "prep everything"), implement yield standards for top 5 trimmed items, weekly FIFO audit.
>
> 3 months later: waste reduced to ~2 triệu/month. Monthly savings: ~3 triệu. P&L impact: food cost down 2.5%.
>
> **Phân tích sâu:** The team wasn't being careless — they had no information about waste patterns. When the data appeared, they were surprised by over-production being 45% of waste (they thought it was "unavoidable to have some buffer"). Reducing batch size felt risky to them — what if we run out? Implement data showed: in 3 months of reduced batches, only 2 stockout incidents (both managed easily). The "buffer" was waste in disguise. Data changes perception; perception changes behavior.

> **Bài học #3 — Rush Buy Tháng Này Là Symptom: Không Có Par Level System**
>
> Một café tracked expenses và thấy pattern: mỗi tháng có 3-5 emergency purchases ở Circle K hoặc siêu thị vì hết syrup, milk, hoặc coffee supplies mid-service. Chi phí từng lần: nhỏ (100-300K). Tháng: 500K-1.5 triệu in overprice.
>
> Nhưng real cost cao hơn nhiều: mỗi emergency buy mất 30-45 phút cho nhân viên đi mua (labor cost) + disruption cho service (sometimes had to tell customers "sold out" on certain drinks for 30 min) + inconsistency trong ingredient quality (retail vs. supplier grade different).
>
> Root cause investigation: không có par level cho any supplies. Ordering done "when someone notices we're low." Different staff had different thresholds for what "low" meant.
>
> Fix: par level system cho top 20 supplies. Physical kanban-style trigger: sticky note at par level mark in storage. When visible: reorder. Anyone can trigger reorder without management involvement.
>
> Result: zero emergency retail purchases trong 4 months after implementation. Monthly savings: 500K direct + estimated 2-3 triệu in avoided disruption.
>
> **Phân tích sâu:** Emergency retail purchases are embarrassing to track because each one seems trivial. The accumulation is not. More importantly, each purchase signals a system failure — not individual carelessness. Par level system removes judgment and memory from reordering. The mark on the shelf is the system; the person who sees it is just the trigger. This is the power of physical kanban: makes the invisible (inventory level) visible, and makes the action (reorder) obvious and immediate.

---

*Tóm lại từ người trong nghề: Waste control trong supply chain F&B không phải là about being perfect — đó là về being honest với what's actually happening và systematically addressing root causes. Bucket test reveal reality. Yield calculation reveal where food cost math is wrong. Cross-utilization menu design eliminate structural waste. Par levels eliminate stockouts và emergency buy. Mỗi thứ này là independent improvement with compounding effect. Implement một, thấy improvement. Implement tất cả, thấy transformation trong food cost.*

---
