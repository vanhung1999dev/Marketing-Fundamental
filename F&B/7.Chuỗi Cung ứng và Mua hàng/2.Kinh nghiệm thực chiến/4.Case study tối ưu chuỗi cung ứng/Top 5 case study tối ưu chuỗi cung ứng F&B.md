### Top 5 Case Study Tối Ưu Chuỗi Cung Ứng F&B

Supply chain optimization trong F&B không phải là abstract concept — đó là chuỗi quyết định rất cụ thể về supplier nào, mua bao nhiêu, lưu trữ thế nào, và quản lý thế nào. Những case studies sau đây là những tình huống thực tế, với numbers thực sự và lessons được học qua real cost — không phải qua classroom.

---

## Case Study 1 — Cắt Giảm Food Cost 9 Percentage Points Không Thay Menu

**Tình huống:**
Nhà hàng pasta tại TP.HCM. Food cost 38% — cao hơn đáng kể so với target 30-32% cho casual dining. Owner không biết tại sao vì recipe có vẻ đúng, giá bán hợp lý, không thấy waste nhiều. Sau 3 tháng investigation và supply chain fix — không thay 1 món nào — food cost xuống 29%.

**4 root causes được phát hiện:**

**Root cause 1 — Yield ratio không được tính:**
Pasta fresh yield 68% sau cooking loss (pasta absorbs water, increases weight → menu says "250g pasta" nhưng thực chất cần 165g dry pasta). Recipe cost được tính trên dry pasta weight nhưng portion size based on cooked weight.

Re-computation: 5 món pasta đang được underpriced vì food cost calculation sai fundamentally.

**Root cause 2 — Over-production batch:**
Batch quá nhiều mỗi sáng "để chắc." 25-30% batch không sell trong ngày, became next-day quality issue. Kitchen lead practice: "prep better safe than sorry." 

Fix: demand-based batch sizing using rolling 7-day average by day-of-week.

**Root cause 3 — Portioning inconsistency:**
No kitchen scale. Visual portioning. Random audit: actual portions ranged from 220g to 310g for 250g spec dish. Average over-portion: 17-18%.

Fix: scale at every station. Visual portioning guides with before/after photos.

**Root cause 4 — Inventory shrinkage:**
Weekly stocktake revealed: 4% unexplained variance. Investigation: 2% from receiving shortfall (not weighing), 1.5% from unauthorized "tasting" during prep (more than recipe calls for), 0.5% miscounting.

Fix: weigh all deliveries, implement tasting protocol, two-person count.

**Results timeline:**

| Month | Food Cost % | Primary Fix Applied |
|---|---|---|
| Baseline | 38% | — |
| Month 1 | 35% | Correct recipe costing + yield calculation |
| Month 2 | 32% | Portion control + demand-based batch |
| Month 3 | 29% | Receiving controls + shrinkage reduction |

**Key lesson:** 9 percentage points food cost improvement không đến từ cutting corners hay reducing quality. Đến từ: measurement, accountability, và operational discipline. Food cost cao thường là ops problem, không phải pricing problem. Jump to "tăng giá bán" khi food cost high là move sai — identify và fix ops issues trước.

---

## Case Study 2 — Supplier "Bạn Bè" Và 25% Price Premium: Business Vs. Friendship

**Tình huống:**
Chủ nhà hàng mua rau củ từ người quen 2 năm. Không bao giờ so sánh giá — "mua của người quen vừa tin vừa ủng hộ nhau." Tình cờ hỏi một quán bạn về supplier của họ và phát hiện: cùng chất lượng, cùng volume, giá thấp hơn 22-25%.

**Impact calculation:**

Rau củ = 3% of revenue. 25% premium = 0.75% margin lost per year.
Restaurant revenue: 500 triệu/năm.
Actual overpayment: 0.75% × 500 triệu = 3.75 triệu/năm.
2 năm: ~7-8 triệu total overpaid.

**Approach đúng cách:**
"Mình cần review lại chi phí vì margin đang bị squeeze. Có quotes từ market cho thấy rau củ hiện tại mình đang trả cao hơn average. Anh có thể xem xét điều chỉnh giá về [X] không? Nếu được mình muốn tiếp tục với anh vì đã quen và tin nhau rồi."

Không confront. Không accusation. Data-backed, relationship-respecting.

**Result:**
Người quen match price vì không muốn mất business. Relationship intact. Business now at market rate.

**Framework: Annual Price Audit**

Mỗi 12 tháng, với tất cả major suppliers:
1. Request quotes từ 2-3 alternatives cho cùng spec
2. Compare với current supplier pricing
3. Gap < 5%: maintain current relationship
4. Gap 5-15%: renegotiate với data
5. Gap > 15%: switch hoặc renegotiate aggressively with pilot test alternative

Set calendar reminder — không để này fall through the cracks.

---

## Case Study 3 — Cloud Kitchen "Hết Nguyên Liệu" Và 23 Cancelled Orders Trong 1 Chiều

**Tình huống:**
Cloud kitchen bán trên 3 platform đồng thời (Grab, Shopee Food, Baemin). Thứ 7 peak time, hết chicken vào lúc 1pm. POS không update inventory vào delivery platforms. Platforms vẫn nhận orders. Nhân viên manually cancel 23 orders và deal với complaints.

**Cost of 23 cancelled orders:**

| Component | Impact |
|---|---|
| Lost revenue (23 orders × 150K average) | 3.45 triệu |
| Platform penalty fees | Variable |
| Customer reviews (30-40% để 1-2 sao sau cancellation) | 7-9 negative reviews |
| Customer churn (60-70% không order lại trong 30 ngày) | Future revenue loss |
| Staff stress và time (handling complaints) | Labor cost |

**Real cost estimate of one cancellation incident: 5-10 triệu total value** khi tính đủ.

**Root cause và fix:**

Root cause: inventory không connected với POS, POS không connected với delivery platforms. Manual process required khi 86 an item — which failed under pressure.

**Fix options (từ simple đến complex):**

| Solution | Cost | Complexity | Effectiveness |
|---|---|---|---|
| Dedicated person monitor & manual update during service | 0 hardware | High labor | Fails when busy |
| POS with multi-platform integration | Medium investment | Medium setup | High — automatic |
| Middleware tool (e.g., BEE System, iPos) | Monthly subscription | Low-medium | High — automatic |
| Build custom integration | High | High | Depends on quality |

**Recommended for most cloud kitchens:** POS system với inventory tracking + platform integration. Investment payback in 2-3 avoided cancellation incidents.

**Principle:** Manual process fails under pressure — that's exactly when you need it most. System phải be designed to prevent failure, not expect human vigilance to prevent it during peak hours.

---

## Case Study 4 — Mùa Mưa Đà Lạt, 3 Ngày Không Rau — Quán Xoay Xở Thế Nào

**Tình huống:**
Đợt mưa lớn làm tắc đường từ Đà Lạt xuống TP.HCM — con đường phổ biến của rau củ về thành phố. Supplier của nhà hàng không giao được trong 3 ngày.

**Năm 1 — Caught off-guard:**
Không có backup supplier. Không có safety stock đủ. Chỉ có rau cho ngày hôm đó khi nhận được thông báo. Phải 86 nhiều món, improvise với supermarket price (gấp 3). Revenue drop ~40% trong 3 ngày.

**Năm 2 — Prepared:**
Sau lần đầu, họ implement 4 layers of preparation:

**Layer 1 — Backup suppliers maintained:**
2 backup rau suppliers được test qua small weekly orders (dù không cần). Relationship và familiarity đã built. Contact updated. Emergency order capability confirmed.

**Layer 2 — Survival menu:**
8 món core không cần leafy greens — chỉ cần root vegetables (shelf life dài hơn), protein, và pantry staples. Pre-planned. Printed và in kitchen binder.

**Layer 3 — Emergency safety stock:**
2-day buffer của most critical vegetables (root veg, nhờ longer shelf life).

**Layer 4 — Early warning protocol:**
Khi weather forecast show heavy rain period → order 3 ngày trước thay vì 1 ngày. Weather apps monitored proactively.

**Năm 2 result:**
Khi disruption hit: switched to backup supplier trong 4 giờ. Served survival menu với clear communication to customers. Revenue impact: ~10% reduction (vs. 40% in year 1). Customer reaction: largely understanding given transparent communication.

**Insurance logic:**
Cost of maintaining backup suppliers (small regular orders): ~500K-1 triệu/tháng.
Cost of one disruption without preparation: 15-25 triệu.
After first incident: preparation ROI is obvious.

---

## Case Study 5 — Từ 12 Suppliers Xuống 5: Kết Quả Thực Sự Sau Consolidation

**Tình huống:**
Nhà hàng mid-size (50-seat, 2 meals/day) manage 12 suppliers cho các nguyên liệu — 12 invoices/tháng, 12 delivery schedules, 12 relationships. Owner/manager spend ước tính 40% time trên supplier-related tasks: ordering, receiving, dispute resolution, invoice processing.

**Consolidation decision:**
Audit 12 suppliers → identify categories có thể consolidate:
- 3 rau củ suppliers → 1 primary + 1 backup
- 2 thịt bò suppliers → 1 main supplier (cả two types)
- 2 dry goods suppliers → 1 full-service distributor
- Kept separate: specialty seafood, alcohol, fresh herbs (cannot consolidate without quality compromise)

**Result: 12 → 5 suppliers.**

**Measured outcomes after 6 months:**

| Metric | Before | After | Change |
|---|---|---|---|
| Supplier admin time | ~20h/month | ~8h/month | -60% |
| Average unit cost | Baseline | Baseline -8% | -8% (higher volume per supplier) |
| Delivery disruptions | 4-5/month | 1-2/month | -60-75% |
| Receiving time | 8h/month | 4.5h/month | -44% |
| Relationship depth with key suppliers | Surface level | Deeper | Qualitative improvement |

**Critical tradeoffs:**

**Tradeoff 1 — Less diversification per category:**
Mitigated by keeping backup supplier for each critical category (not fully consolidated, just simplified).

**Tradeoff 2 — Dependency risk:**
Now more dependent on fewer suppliers. Managed by: better relationship with each, better contracts, better communication channel.

**What NOT to consolidate:**
Items with unique quality requirements that only 1-2 suppliers can meet. Don't sacrifice quality for admin convenience.

**Financial impact:**
8% cost reduction on ~30 triệu/month in supplier purchases = 2.4 triệu/month in direct savings.
60% admin time reduction: freed ~12 hours/month of manager time = estimated 2-3 triệu opportunity value.
Total monthly benefit: ~5 triệu.

---

## Xương Máu Từ Chiến Trường

> **Bài học #1 — "Giá Nguyên Liệu Tăng" Là Lời Giải Thích Dễ, Không Phải Lý Do Thật**
>
> Trong case pasta restaurant phía trên: khi food cost tăng từ 30% lên 38% trong 6 tháng, narrative trong team là "giá thị trường tăng." Owner partially believe này — nguyên liệu thực sự có đắt hơn một chút trong period đó.
>
> But: price increase trong period was ~5-8% across categories. That would account for roughly 1.5-2.5 percentage points increase in food cost if all else equal. The 8-point increase could not be explained by ingredient prices alone.
>
> Only when real stocktake + investigation happened did the actual 4 causes emerge. And 3 of 4 were completely within internal control (portioning, batch sizing, receiving controls) — totally unrelated to market prices.
>
> **Phân tích sâu:** "Giá nguyên liệu tăng" is the default narrative in F&B when food cost rises. It's often partially true — and that partial truth makes it an effective shield against deeper investigation. The real question is: "Is market price increase the FULL explanation, or is it covering for operational failures?" Full explanation requires reconciling theoretical vs. actual food cost. If the gap is larger than market price movement alone explains — there are internal factors to find and fix. Never accept partial explanation for full variance.

> **Bài học #2 — Backup Supplier Investment: 12 Tháng Không Cần, Rồi Cần Trong 4 Tiếng**
>
> Nhà hàng maintain backup seafood supplier với small monthly order (3kg/month, mostly unused) cho 12 tháng. Total "wasted" cost: ~1.8 triệu.
>
> Month 13: primary seafood supplier bị customs delay on import — no delivery for 3 days with short notice. Backup supplier activated immediately. Seamless transition. Revenue impact: minimal (backup quality acceptable at ~85% of primary).
>
> Estimated revenue protected over 3 days (Friday-Sunday): ~25 triệu.
>
> Insurance ROI: 1.8 triệu "premium" for 12 months → 25 triệu claim paid in month 13.
>
> **Phân tích sâu:** Backup supplier relationship requires regular maintenance to be actually useful — not just a name in your phone. The monthly small order serves multiple functions: (1) keeps the relationship warm, (2) gives you ongoing quality assessment of their product, (3) establishes a payment track record so they prioritize you in emergency, (4) gives your team familiarity with their product. A backup supplier you've never ordered from is an unknown quantity when you need them most. Think of small regular orders as relationship maintenance, not wasted procurement.

> **Bài học #3 — Supplier Consolidation Failure: Consolidating Quality Out Of Menu**
>
> Một nhà hàng specialty burgers attempt to consolidate beef supplier — going from 2 specialists (one for grass-fed premium, one for regular) to a single general meat distributor offering both grades from same source.
>
> 3 months after consolidation: customer comments about "beef taste different." Chef notice: grass-fed product from new supplier had different flavor profile than the dedicated grass-fed supplier (feeding regime, breed, and age at slaughter all different).
>
> Reverted to specialized grass-fed supplier. Lost 3 months of customer trust rebuilding.
>
> Lesson: consolidation should optimize admin and cost without compromising the product characteristics that differentiate your menu. Grass-fed beef flavor is core to this restaurant's value proposition — that's not the right place to consolidate for efficiency.
>
> **Phân tích sâu:** Supplier consolidation decision phải always ask: "What are we actually buying?" For commodity items (standard cleaning supplies, generic dry goods), supplier matters little — consolidate freely. For identity-defining ingredients (the coffee that defines your café, the beef that defines your burger, the bread from the specific bakery), supplier IS the product. Consolidating these away for efficiency destroys the thing that made you worth coming to. Map ingredients into: commodity (consolidate freely) vs. identity-defining (protect the supplier relationship). Never consolidate identity-defining ingredients solely for efficiency.

---

*Tóm lại từ người trong nghề: Supply chain optimization là work that compounds. Fix receiving → better inventory accuracy → better ordering → less waste → better food cost. Maintain backup suppliers → survive disruptions → protect peak revenue → build customer loyalty. Each improvement enables the next. The businesses that look like they "just have great food cost" typically started with unglamorous basics — counting inventory, weighing deliveries, maintaining backup relationships — and built from there. No single magic fix. Systematic improvement, consistently applied, year over year.*

---
