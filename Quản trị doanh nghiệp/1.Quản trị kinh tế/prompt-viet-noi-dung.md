# Prompt: Viết nội dung cho section 1.Quản trị kinh tế

## Bối cảnh

Knowledge base tiếng Việt về Quản trị doanh nghiệp. Section này là phần tài chính–kinh tế toàn diện nhất, gồm **8 module** với **201 stub files hoàn toàn rỗng (0 byte)** — phải viết nội dung từ đầu.

## Đối tượng đọc

Founders và CFO/Finance managers Việt Nam ở SME và mid-size company. Đã biết kế toán cơ bản — cần hiểu **cơ chế quản trị** (tại sao và làm gì), không phải hướng dẫn kế toán viên. Đọc để ra quyết định kinh doanh, không phải để làm kế toán.

## Format bắt buộc (áp dụng cho TẤT CẢ 201 files)

```
### [Tiêu đề theo tên file]

[Body: 3–5 đoạn + bảng/checklist/ví dụ. Kết hợp tiếng Việt với thuật ngữ tiếng Anh quan trọng giữ nguyên]

> **Bài học:** [ngắn gọn — takeaway chính]

> **Phân tích sâu:** [cơ chế, framework, research backing]

> **Sai lầm phổ biến #1:** [cụ thể, có thể xảy ra với VN SME]

> **Sai lầm phổ biến #2:** [cụ thể]

> **Cạm bẫy:** [risk tinh tế, ít người nhận ra]

---
```

- Target: **3–5KB per file**
- Ví dụ VN khi có thể: Vinamilk, Vinhomes, Masan, Thế Giới Di Động, Hòa Phát, FPT, Techcombank
- Dẫn chiếu luật/chuẩn mực khi có: VAS, Thông tư 200/2014/TT-BTC, Luật Thuế GTGT, Luật Thuế TNDN, Luật Thuế TNCN
- Mỗi file là **standalone** — đọc được mà không cần file khác

---

## Frameworks cần tham chiếu

### Phân tích tài chính
- **VAS** (Vietnamese Accounting Standards) + **Thông tư 200/2014/TT-BTC**
- **DuPont Analysis**: ROE = Net Margin × Asset Turnover × Equity Multiplier
- **Altman Z-Score**: công cụ dự báo phá sản
- **Cash Conversion Cycle (CCC)** = DIO + DSO − DPO

### Chi phí và Ngân sách
- **CVP (Cost-Volume-Profit)**: Break-even, contribution margin
- **Zero-Based Budgeting (ZBB)** vs Incremental Budgeting
- **BSC (Balanced Scorecard)**: Kaplan & Norton — 4 perspectives
- **Activity-Based Costing (ABC)**
- **RACI matrix** trong quy trình lập ngân sách

### Dữ liệu và Công nghệ
- **CRM / ERP / BI / DSS** — cấp vận hành và chiến thuật
- **OKR** (Objectives and Key Results)
- **Leading vs Lagging indicators**

### Vốn và Tài chính
- **WACC** (Weighted Average Cost of Capital)
- **Modigliani-Miller theorem**: capital structure irrelevance (và hạn chế khi có thuế)
- **DCF** (Discounted Cash Flow)
- **Markowitz portfolio theory**: efficient frontier, diversification

### Thuế VN
- Luật Thuế GTGT (VAT): Luật 13/2008, sửa đổi 2013, 2016
- Luật Thuế TNDN (CIT): Luật 14/2008, sửa đổi 2013 — thuế suất 20% chuẩn
- Luật Thuế TNCN (PIT): Luật 04/2007, sửa đổi 2012
- Thông tư 96/2015/TT-BTC: chi phí được trừ thuế TNDN
- Nghị định 123/2020/NĐ-CP: hóa đơn điện tử

---

## Module 1: Đọc hiểu và Phân tích BCTC
*Path: `1.Đọc hiểu và Phân tích BCTC/`*

### Phần 1 — Nền tảng

**`1.1.1 Quản trị dòng trong doanh nghiệp.md`**
- 3 dòng chính: dòng tiền (cash flow), dòng thông tin (data), dòng quyết định (decision)
- BCTC là ngôn ngữ chung của 3 dòng này
- Vì sao founder cần đọc BCTC thay vì chỉ xem dashboard

**`1.1.2 BCTC liên kết chiến lược và vận hành.md`**
- BCTC là "kết quả" của chiến lược được execute
- Cách đọc BCTC ngược từ kết quả → tìm nguyên nhân vận hành
- Ví dụ: Doanh thu tăng nhưng margin giảm → phân tích ngược

**`1.2.1 Tổng quan đối tượng và mục đích.md`**
- 4 nhóm đọc BCTC: nhà quản lý, nhà đầu tư, chủ nợ, cơ quan quản lý
- Mỗi nhóm quan tâm gì khác nhau
- Disclosure requirements (nghĩa vụ công bố) theo luật VN

**`1.2.2 Khía cạnh nhà quản lý và nhà đầu tư quan tâm.md`**
- Nhà quản lý: thanh khoản, cost structure, EBITDA, working capital
- Nhà đầu tư: ROE, EPS, P/E, tăng trưởng doanh thu và margin
- Ví dụ: Hòa Phát — nhà đầu tư và nhà quản lý đọc BCTC khác nhau thế nào

**`1.3.1 Tổng quan các cấu phần BCTC.md`**
- 5 báo cáo chính theo VAS + Thông tư 200
- Mối liên hệ giữa các báo cáo (profit ≠ cash)
- Tại sao đọc đủ 5, không chỉ đọc P&L

**`1.3.2 Báo cáo kết quả hoạt động kinh doanh.md`**
- Cấu trúc: Doanh thu → Lợi nhuận gộp → EBIT → EBT → EAT
- Phân biệt Revenue, Gross Profit, EBITDA, EBIT, Net Profit
- Gross Margin vs Net Margin — cái nào nói lên điều gì
- Ví dụ đọc P&L Vinamilk

**`1.3.3 Bảng cân đối kế toán.md`**
- Tài sản = Nợ phải trả + Vốn chủ sở hữu
- Ngắn hạn vs dài hạn (cả tài sản lẫn nợ)
- Chỉ số: D/E ratio, Current Ratio, Quick Ratio đọc từ BĐKT
- Ví dụ: đọc BĐKT Vinhomes — tại sao nhiều nợ vẫn healthy

**`1.3.4 Báo cáo lưu chuyển tiền tệ.md`**
- 3 hoạt động: vận hành (CFO), đầu tư (CFI), tài chính (CFF)
- Rule of thumb: CFO phải dương và tăng dần
- Tại sao "profit ≠ cash" — ví dụ công ty lãi mà hết tiền
- Free Cash Flow = CFO − CapEx

**`1.3.5 Báo cáo thay đổi vốn chủ sở hữu.md`**
- Equity thay đổi do: lợi nhuận, cổ tức, phát hành cổ phiếu, mua lại
- Retained earnings — ý nghĩa với tăng trưởng nội sinh
- Cách đọc khi công ty có cổ phần phát hành thêm

**`1.3.6 Thuyết minh báo cáo tài chính.md`**
- Tại sao notes là phần quan trọng nhất mà ít người đọc
- Các mục thường cần đọc kỹ: chính sách kế toán, contingent liabilities, related party transactions
- Red flags trong thuyết minh

**`1.3.7 Báo cáo tích hợp.md`**
- Integrated Reporting (IR) — xu hướng toàn cầu
- 6 loại vốn: tài chính, sản xuất, trí tuệ, nhân lực, xã hội, tự nhiên
- ESG reporting tại VN — xu hướng và yêu cầu

### Phần 2 — Tình huống Vinhomes

**`Tình huống Vinhomes.md`**
- Case study đọc BCTC Vinhomes (2019–2023)
- Điểm đặc thù ngành BĐS: recognition revenue theo % hoàn thành dự án
- Phân tích: Doanh thu → Margin → Cash flow → D/E
- Tại sao Vinhomes có nợ lớn nhưng vẫn được đánh giá healthy
- Bài học cho đọc BCTC ngành capital-intensive

### Phần 3 — Phân tích chỉ số tài chính

**`3.1 Định nghĩa và Phân loại.md`**
- 6 nhóm chỉ số: thanh khoản, thanh toán, đòn bẩy, hoạt động, sinh lời, thị trường
- Nguyên tắc đọc chỉ số: so sánh với ngành, so sánh qua thời gian
- Sai lầm: đọc chỉ số tuyệt đối mà không có benchmark

**`3.2.1 Định nghĩa chỉ số thanh khoản.md`**
- Liquidity = khả năng trả nợ ngắn hạn
- Vì sao cả công ty lãi vẫn có thể insolvency
- Thanh khoản vs khả năng sinh lời — trade-off

**`3.2.2 Bộ chỉ số thanh khoản.md`**
- Current Ratio = Tài sản ngắn hạn / Nợ ngắn hạn (benchmark: >1.5)
- Quick Ratio = (TSNH − Hàng tồn kho) / Nợ NH (benchmark: >1.0)
- Cash Ratio = Tiền & tương đương / Nợ NH
- Ngưỡng lý tưởng theo ngành (F&B, bán lẻ, sản xuất, BĐS khác nhau)

**`3.3.1 Định nghĩa chỉ số thanh toán.md`**
- Khả năng thanh toán dài hạn (solvency) vs ngắn hạn (liquidity)
- Interest Coverage Ratio = EBIT / Interest Expense
- Khi nào cần lo về solvency

**`3.3.2 Bộ chỉ số thanh toán.md`**
- Debt-to-Equity (D/E): benchmark theo ngành
- Debt-to-Assets
- Interest Coverage Ratio (ICR): <2 là danger zone
- Ví dụ: so sánh D/E Hòa Phát vs Vinamilk — ngành khác nhau, benchmark khác nhau

**`3.4 Chỉ số đòn bẩy.md`**
- Financial leverage = sử dụng nợ để amplify return
- Operating leverage = tỷ lệ fixed cost cao
- Combined leverage effect
- Đòn bẩy tốt vs đòn bẩy nguy hiểm — khi nào ROE tăng từ leverage

**`3.5.1 Bộ chỉ số hoạt động.md`**
- Asset Turnover = Doanh thu / Tổng tài sản
- Inventory Turnover = COGS / Tồn kho bình quân
- Receivable Turnover = Doanh thu / Công nợ phải thu bình quân
- Payable Turnover = COGS / Công nợ phải trả bình quân

**`3.5.2 Chu kỳ hoạt động và chu kỳ tiền.md`**
- Operating Cycle = DIO + DSO
- Cash Conversion Cycle = DIO + DSO − DPO
- Negative CCC là lợi thế cạnh tranh (ví dụ: Thế Giới Di Động)
- Cách rút ngắn CCC từng yếu tố

**`3.5.3 Mức lý tưởng chỉ số hoạt động.md`**
- Không có "mức lý tưởng" tuyệt đối — phụ thuộc ngành
- Bảng benchmark theo ngành VN: bán lẻ, F&B, sản xuất, dịch vụ
- Trend quan trọng hơn số tuyệt đối

**`3.6.1 Chỉ số hiệu quả sử dụng tài sản.md`**
- ROA = Net Income / Total Assets
- ROTA (Return on Total Assets excluding intangibles)
- Asset-light vs Asset-heavy business model

**`3.6.2 Chỉ số dọc theo BCKQHĐKD.md`**
- Vertical analysis: % của từng dòng so với Doanh thu
- Gross Margin, EBITDA Margin, EBIT Margin, Net Margin
- Đọc trend 3–5 năm để thấy structural shift

**`3.6.3 Chỉ số tỷ suất sinh lời.md`**
- ROE = Net Income / Equity (benchmark: >15% là tốt với VN SME)
- ROCE (Return on Capital Employed)
- ROIC (Return on Invested Capital) — metric quan trọng nhất về chất lượng business

**`3.6.4 Mô hình Dupont.md`**
- ROE = Net Margin × Asset Turnover × Equity Multiplier
- 3-factor DuPont → 5-factor DuPont
- Case study: phân tích ROE Vinamilk — nguồn gốc thay đổi
- Dùng DuPont để diagnose vấn đề

**`3.7.1 Bộ chỉ số đo lường thị trường.md`**
- P/E (Price-to-Earnings): benchmark theo ngành và giai đoạn tăng trưởng
- P/B (Price-to-Book): dưới 1 = undervalued hay value trap?
- EV/EBITDA: dùng khi so sánh companies có capital structure khác nhau
- Dividend Yield

**`3.7.2 Phương pháp định giá.md`**
- DCF (Discounted Cash Flow): công thức, assumptions quan trọng
- Comparable Company Analysis (CCA): P/E, EV/EBITDA multiples
- Precedent Transactions
- Asset-based valuation: khi nào dùng
- Ví dụ: định giá startup F&B VN

**`3.7.3 Quan điểm định giá của nhà đầu tư.md`**
- Growth investor vs Value investor: đọc gì khác nhau trong BCTC
- Private equity due diligence checklist
- Nhà đầu tư VN quan tâm gì khi xem BCTC SME

**`3.8 Nhận diện gian lận từ mâu thuẫn chỉ số.md`**
- Benford's Law: detect unusual number patterns
- Red flags: doanh thu tăng nhanh nhưng receivables tăng nhanh hơn
- Inventory vs COGS mâu thuẫn
- Cash flow từ hoạt động âm khi lợi nhuận dương
- Ví dụ: case gian lận BCTC tại VN

---

## Module 2: Quản trị Chi phí theo Chiến lược
*Path: `2.Quản trị Chi phí theo Chiến lược/`*

### Phần 1 — Quản trị chi phí cấp độ chiến lược

**`1.1 Tổng quan mô hình quản lý vận hành.md`**
- Operating model = cách tổ chức deliver value
- Chi phí là output của operating model choices
- Cost leadership vs differentiation: impact lên cost structure

**`1.2.1 Chính sách quản trị chi phí — Tổng quan.md`**
- Cost policy: quy tắc ra quyết định về chi phí
- 3 cấp: chiến lược (loại chi phí nào), tactic (mức chi), vận hành (quy trình phê duyệt)
- Vì sao policy cần gắn với strategy (không phải chỉ "cắt giảm")

**`1.2.2 Chi phí tiêu chuẩn (Standard Costing).md`**
- Standard cost = mức chi phí "nên là" cho một đơn vị sản phẩm/dịch vụ
- Standard Material + Standard Labour + Standard Overhead
- Variance analysis: Price variance vs Volume variance
- Khi nào standard costing phù hợp vs không phù hợp

**`1.2.3 Lập ngân sách chi phí.md`**
- Zero-Based Budgeting (ZBB) vs Incremental: pros/cons
- Rolling forecast: tại sao annual budget đang bị thay thế
- Driver-based budgeting: link cost với business drivers
- Process: bottom-up vs top-down

**`1.3.1 Hai tầng quản trị quy trình mua hàng.md`**
- Strategic procurement: supplier selection, negotiation, contracting
- Operational procurement: PO, receive, invoice, payment
- Tách biệt hai tầng để kiểm soát chi phí và rủi ro

**`1.3.2 Các phương thức tối ưu quy trình.md`**
- Lean thinking: eliminate waste (TIMWOOD: Transportation, Inventory, Motion, Waiting, Overproduction, Over-processing, Defects)
- Process mapping: as-is vs to-be
- Automation: khi nào nên automate một process
- Outsourcing decision: make vs buy framework

**`1.4.1 Vai trò công nghệ thông tin trong tối ưu chi phí.md`**
- IT giảm chi phí theo 3 cơ chế: automation, visibility, scale
- ERP vs best-of-breed: tradeoffs cho SME
- Data quality: garbage in, garbage out trong cost reporting

**`1.4.2 Số hóa quy trình.md`**
- Digitization (convert to digital) vs Digitalization (change process using digital)
- ROI của digital transformation: cách tính
- Common pitfalls: implement phần mềm mà không redesign process

**`1.5.1 Đo lường và báo cáo hiệu quả chi phí — Tổng quan.md`**
- Cost KPIs: Cost per unit, Cost as % of Revenue, Cost variance
- Frequency: daily operational vs monthly strategic
- Audience: operator (detail) vs executive (summary)

**`1.5.2 Nhất quán trong đo lường chi phí.md`**
- Same definition của cost items across departments
- Allocation methodology phải consistent
- Tại sao "cost" mỗi bộ phận tính khác nhau gây tranh cãi

**`1.5.3 KPI và Dữ liệu chi phí.md`**
- Leading KPI (input) vs Lagging KPI (output) trong quản lý chi phí
- Ví dụ: Employee productivity (leading) → Cost per output (lagging)
- Dashboard chi phí cho SME: 5 metrics cần thiết nhất

**`1.6.1 Mô hình 3 vòng phòng thủ (Three Lines of Defense).md`**
- Line 1: Business operations (người thực hiện có kiểm soát)
- Line 2: Risk & Compliance (giám sát độc lập)
- Line 3: Internal Audit (kiểm tra độc lập)
- Áp dụng cho cost control trong SME

**`1.6.2 Phương thức tổ chức doanh nghiệp.md`**
- Functional, Divisional, Matrix structure — impact lên cost allocation
- Shared Services Center (SSC): khi nào nên tập trung
- Cost center vs Profit center vs Investment center

**`1.6.3 Mô hình đơn vị kinh doanh (Business Unit Model).md`**
- BU as mini P&L: accountability và autonomy
- Transfer pricing giữa BUs
- Khi nào decentralize vs centralize — impact lên cost structure

### Phần 2 — Phân tích hiệu quả chi phí

**`2.1.1 Hành vi chi phí (Cost Behavior).md`**
- Fixed vs Variable vs Semi-variable (mixed) costs
- Relevant range: fixed cost chỉ fixed trong một phạm vi
- Contribution Margin = Revenue − Variable Costs
- High-Low Method để tách fixed vs variable

**`2.1.2 Biểu đồ phân tích CVP.md`**
- Break-even Point (BEP) = Fixed Costs / Contribution Margin per Unit
- Margin of Safety = Actual Sales − BEP Sales
- CVP chart: revenue line, total cost line, profit zone
- Sensitivity analysis: what if variable cost tăng 10%?

**`2.2.1 Chi phí nguyên vật liệu liên quan.md`**
- Relevant cost = future, incremental, cash cost
- Sunk cost: đã tốn, không liên quan đến quyết định tương lai
- Opportunity cost: chi phí của lựa chọn bị bỏ qua
- Ứng dụng: quyết định make vs buy NVL

**`2.2.2 Chi phí nhân công liên quan.md`**
- Direct labour: relevant khi thay đổi theo quyết định
- Idle time cost: relevant hay sunk?
- Overtime premium: relevant cost khi có capacity constraint
- Quyết định: thêm ca hay thuê ngoài?

**`2.2.3 Các chi phí không liên quan.md`**
- Allocated overhead: không liên quan với most short-term decisions
- Depreciation: sunk cost (đã committed), không relevant
- Common pitfall: include overhead trong relevant cost analysis → wrong decision

**`2.3.1 Chi phí nguyên vật liệu trực tiếp.md`**
- Direct material = NVL đi thẳng vào sản phẩm (traceable)
- Bill of Materials (BOM): danh mục NVL mỗi SKU
- Material price variance + Material usage variance
- Procurement strategy ảnh hưởng unit cost: bulk discount, long-term contract

**`2.3.2 Chi phí nhân công trực tiếp.md`**
- Direct labour = lao động trực tiếp tạo ra sản phẩm (traceable)
- Labour rate variance + Labour efficiency variance
- Labour cost per unit: time study, standard hours
- Automation threshold: khi nào machine < labour

**`2.3.3 Chi phí chung (Overhead).md`**
- Manufacturing overhead: indirect material, indirect labour, factory overhead
- Absorption costing vs Variable (Marginal) costing: difference và impact
- Overhead allocation: direct labour hours, machine hours, ABC
- Ví dụ: overhead allocation gây distorted product profitability

---

## Module 3: Ứng dụng Công nghệ và Dữ liệu trong Quản trị
*Path: `3.Ứng dụng Công nghệ và Dữ liệu trong Quản trị/`*

### Phần 1 — Chiến lược dữ liệu và công nghệ

**`1.1.1 Khung bản đồ chiến lược (Strategy Map).md`**
- Kaplan & Norton Strategy Map: 4 perspectives của BSC
- Financial → Customer → Internal Process → Learning & Growth
- Cách xây strategy map cho SME VN
- Link strategy map với KPIs

**`1.1.2.1 Tổng quan nhất quán trong đo lường.md`**
- Measurement consistency: tại sao critical
- Common problem: mỗi bộ phận tính doanh thu khác nhau
- Single source of truth (SSOT): nguyên tắc và implementation

**`1.1.2.2 Nhất quán theo độ sâu chiến lược và liên phòng.md`**
- Cascade: Strategic KPI → Department KPI → Individual KPI
- Cross-functional KPI: ai own khi KPI span nhiều bộ phận
- Alignment check: KPI bộ phận có support company objective không

**`1.1.2.3 Nhất quán theo quy trình kết quả.md`**
- Input → Process → Output → Outcome framework
- Leading indicators (process) → Lagging indicators (outcome)
- Ví dụ: số cuộc gọi sales (input) → conversion rate (process) → revenue (output) → margin (outcome)

**`1.1.2.4.1 Chỉ số tổng quan quy trình bán hàng.md`**
- Sales funnel metrics: Lead → Qualified → Proposal → Close
- Pipeline velocity = (# Deals × Win Rate × Average Deal Size) / Sales Cycle Length
- Pipeline coverage ratio: cần bao nhiêu pipeline để hit target

**`1.1.2.4.2 Chỉ số hiệu suất lao động đội bán hàng.md`**
- Revenue per salesperson
- Activity metrics: calls, meetings, demos per week
- Quota attainment distribution (50% ramp vs 80% ramp healthy)
- Leading vs lagging trong sales performance

**`1.1.2.4.3 Chỉ số tỷ lệ chuyển đổi.md`**
- Conversion rate tại mỗi stage của funnel
- Benchmark theo industry và channel (cold outbound vs warm inbound)
- Bottleneck analysis: stage nào conversion thấp nhất → focus improvement

**`1.1.2.4.4 Chỉ số phân tích doanh thu đa chiều.md`**
- Revenue by: product, channel, geography, customer segment, sales rep
- Cohort analysis: doanh thu theo cohort khách hàng
- Revenue concentration risk: top 3 customers chiếm bao nhiêu %

**`1.2.1 Hệ thống dữ liệu.md`**
- Data sources: transactional (ERP, CRM), operational (IoT, POS), external (market data)
- Data warehouse vs Data lake vs Data lakehouse
- SME data architecture: phù hợp quy mô nào

**`1.2.2 Thu thập dữ liệu.md`**
- Structured vs Unstructured data
- Data collection methods: automated (system logs) vs manual (surveys)
- Data governance: ai own data quality?
- GDPR/Nghị định 13/2023: compliance khi collect customer data

**`1.2.3 Quy trình xử lý dữ liệu.md`**
- ETL (Extract, Transform, Load) pipeline
- Data cleaning: missing values, outliers, inconsistencies
- Data validation: before và after transformation
- Frequency: real-time vs batch processing

**`1.3.1 Vai trò công nghệ trong quản trị hiệu quả.md`**
- Technology as enabler, not solution
- ROI of technology investment: productivity + decision quality
- Technology adoption curve trong SME VN

**`1.3.2.1 Cấp vận hành — CRM.md`**
- CRM functions: contact management, pipeline tracking, activity logging
- Data SME nên capture trong CRM
- CRM implementation failures và cách tránh
- Options VN SME: Salesforce, HubSpot, VN-made solutions

**`1.3.2.2 Cấp vận hành — HRMS.md`**
- HRMS functions: payroll, attendance, leave, performance
- Integration với kế toán (BHXH, thuế TNCN)
- Options VN: MISA, Base, 1C
- Data HR cần để ra quyết định (turnover, cost per hire, performance distribution)

**`1.3.2.3 Cấp chiến thuật — ERP.md`**
- ERP modules: Finance, Supply Chain, Manufacturing, HR
- Monolithic ERP (SAP, Oracle) vs Modular/Cloud (Odoo, MISA SME)
- ERP implementation: phạm vi, thời gian, rủi ro thực tế
- Khi nào SME VN sẵn sàng cho ERP

**`1.3.2.4 Cấp chiến thuật — DSS.md`**
- Decision Support System: tools giúp ra quyết định có cấu trúc
- BI tools: Power BI, Tableau, Looker Studio (free)
- Dashboard vs Report: khác nhau về mục đích và audience
- Self-service BI: democratize data analysis

**`1.4.1 Tư duy theo mô hình logic.md`**
- Logic model: If we do X, then Y happens, because Z mechanism
- Hypothesis-driven analysis: form hypothesis → test with data
- Correlation vs causation: phổ biến trong data analysis
- MECE (Mutually Exclusive, Collectively Exhaustive): McKinsey framework

**`1.4.2 Tình huống thực tế — Phân tích dữ liệu.md`**
- Case: SME F&B phân tích tại sao same-store sales giảm
- Approach: segment by store, time, product, customer
- Common analytical mistakes: confirmation bias, cherry-picking data
- Action: từ insight đến decision đến implementation

### Phần 2 — Thực hành phân tích dữ liệu

**`2.1.1 Case Vinamilk — Tổng quan.md`**
- Context: Vinamilk 2019–2023, dairy market leader VN
- Câu hỏi phân tích: Tại sao ROE giảm từ 40% xuống ~25%?
- Data sources: BCTC công khai, HOSE disclosures

**`2.1.2 Case Vinamilk — Phân tích lợi nhuận.md`**
- Gross Margin trend: input cost tăng (milk powder), pricing power limited
- EBITDA margin erosion: fixed cost deleverage khi growth slows
- Net margin: impact của lãi suất và đầu tư nước ngoài (Mochimilk, Driftwood)

**`2.1.3 Case Vinamilk — Phân tích vòng quay tài sản.md`**
- Asset Turnover giảm: capex tăng (nhà máy mới) trước khi revenue catch up
- Receivable days: bán lẻ (thấp) vs MT/GT channel mix change
- Working capital efficiency vs growth investment

**`2.1.4 Case Vinamilk — Phân tích đòn bẩy vốn chủ sở hữu.md`**
- Equity multiplier: Vinamilk low leverage (conservative)
- Share buyback: impact lên equity base và ROE
- Dividend policy: payout ratio cao → retained earnings thấp → equity growth thấp

**`2.1.5 Case Vinamilk — Phân tích lưu chuyển tiền tệ.md`**
- CFO vs Net Income: working capital changes
- CFI: capex cycle (dairy farm expansion, new plant)
- CFF: dividend payments, share buyback
- Free Cash Flow yield: so sánh với industry peers

**`2.1.6 Case Vinamilk — Tổng kết.md`**
- DuPont breakdown: ROE giảm chủ yếu từ Net Margin + Asset Turnover
- Growth dilemma: đầu tư để grow → drag on near-term ROE
- Bài học: đọc BCTC phải kết hợp với business context, không chỉ số thuần túy

**`2.2.1 Case Maison RMI — Tổng quan doanh nghiệp.md`**
- Context: luxury fashion retail chain VN
- Business model: multi-brand luxury distribution
- Key financial characteristics: high margin, high OpEx, inventory-heavy

**`2.2.2 Case Maison RMI — Chiến lược mở rộng quy mô.md`**
- Store expansion vs same-store growth: risk profile khác nhau
- Payback period per store
- Break-even phân tích: fixed cost per store vs contribution margin

**`2.2.3 Case Maison RMI — Chiến lược M&A.md`**
- M&A rationale: brand acquisition vs organic growth
- Valuation approach trong retail: EV/EBITDA, comparable transactions
- Integration risk: brand dilution, culture, systems

**`2.2.4 Case Maison RMI — Tối đa hóa biên lợi nhuận gộp.md`**
- Gross margin drivers: brand mix, markdown policy, shrinkage
- Inventory markdown: timing và magnitude
- Open-to-buy (OTB) planning

**`2.2.5 Case Maison RMI — Tối ưu chi phí bán hàng và phân phối.md`**
- Fixed vs variable SG&A trong retail
- Rent negotiation: % of revenue vs fixed
- Staff productivity: revenue per staff, revenue per sqm

**`2.2.6 Case Maison RMI — Ứng dụng công nghệ hiệu quả.md`**
- POS + CRM integration: single customer view
- Inventory management system: real-time stock across stores
- Analytics: sell-through rate, age of inventory, customer LTV

**`2.2.7 Case Maison RMI — Vận hành Camera AI.md`**
- AI camera use cases: foot traffic, dwell time, conversion rate per zone
- Data privacy considerations
- ROI calculation: cost of system vs incremental revenue from insights

---

## Module 4: Lập Ngân sách Chiến lược
*Path: `4.Lập Ngân sách Chiến lược/`*

### Phần 1 — Chiến lược và Ngân sách

**`1.1.1 Tổng quát quy trình phân tích chiến lược.md`**
- Strategy → Objectives → Initiatives → Budget
- Strategic planning cycle: thường xuyên nhưng không phải annual only
- Budget as resource allocation tool (không phải accounting exercise)

**`1.1.2 Mô hình BSC (Balanced Scorecard).md`**
- 4 perspectives: Financial, Customer, Internal Process, Learning & Growth
- Strategy Map: mối liên hệ nhân quả giữa objectives
- KPI theo từng perspective: ví dụ cho SME VN
- Pitfall: BSC trở thành KPI list mà không có cause-effect linkage

**`1.2.1 Khung bản đồ chiến lược.md`**
- Xây strategy map: bắt đầu từ financial goals, trace back đến enablers
- Ví dụ: "Tăng ROE 5 điểm" → cần gì từ Customer? Process? L&G?
- Communication tool: strategy map dễ communicate hơn spreadsheet

**`1.2.2 Từ chiến lược tới kế hoạch hành động.md`**
- Strategic initiative: project/program thực thi một phần strategy
- Initiative prioritization: impact vs effort matrix
- Resource allocation: ngân sách theo initiative, không chỉ theo department
- Tracking: milestone-based vs output-based

### Phần 2 — Quy trình lập ngân sách

**`2.1.1 Quy trình lập ngân sách theo mô hình RACI.md`**
- RACI: Responsible, Accountable, Consulted, Informed
- Budget calendar: timeline từ strategic guidance đến final approval
- Typical process: 8–12 tuần cho SME; 4–6 tháng cho mid-size
- Common bottleneck: data collection từ departments

**`2.1.2 Hai phương pháp chính lập ngân sách.md`**
- Top-down: CEO set target, departments plan to meet
- Bottom-up: departments build, consolidate, adjust
- Hybrid (most practical): top-down target + bottom-up detail
- Negotiation process: gaming the budget (sandbagging)

**`2.2.1 Cấu trúc ngân sách tổng thể.md`**
- Master budget: Revenue → COGS → Gross Profit → OpEx → EBIT → Interest → EBT → Tax → Net Income
- Supporting schedules: production, procurement, HR, capex
- Consolidated P&L, Balance Sheet, Cash Flow (projected)

**`2.2.2 Ngân sách vận hành.md`**
- Revenue budget: by product/channel/geography
- Cost of Goods Sold budget: unit cost × volume
- SG&A budget: by department and category
- Headcount plan: FTE count and average cost

**`2.2.3 Ngân sách đầu tư (CapEx Budget).md`**
- CapEx categories: maintenance, growth, transformation
- Approval thresholds: <X tự duyệt, >X lên CEO/Board
- NPV / IRR / Payback Period: cách evaluate CapEx request
- CapEx vs OpEx: trade-off và tax implications

**`2.2.4 Bộ báo cáo tài chính dự phóng.md`**
- Pro forma P&L: từ revenue assumptions đến bottom line
- Pro forma Balance Sheet: assets, liabilities, equity projected
- Pro forma Cash Flow: operating + investing + financing
- Sensitivity table: best/base/worst case scenarios

**`2.3.1 Các tiêu chí của thông số đầu vào chuẩn.md`**
- Budget assumptions: market growth, inflation, exchange rate, headcount
- Source of assumptions: internal data, industry reports, macro forecasts
- Documentation: every assumption phải có source và rationale
- Review cycle: assumptions phải được updated khi environment thay đổi

**`2.3.2 Quy trình thiết lập chi phí tiêu chuẩn.md`**
- Standard cost setting: historical analysis + efficiency targets
- Annual review: update standards khi input cost thay đổi
- Variance tracking: actual vs standard → investigate significant variances
- Integration với budgeting: standards là building blocks của budget

### Phần 3 — Kỹ thuật dự báo

**`3.1.1 Hai dạng tương quan (Hồi quy tuyến tính).md`**
- Positive correlation vs Negative correlation: ví dụ business
- Scatter plot: visualize relationship
- R² (coefficient of determination): strength of relationship
- Ứng dụng: forecast revenue từ marketing spend

**`3.1.2 Biểu mẫu dự báo hồi quy.md`**
- Simple linear regression: Y = a + bX
- Multiple regression: Y = a + b₁X₁ + b₂X₂ + ... 
- Excel / Google Sheets: LINEST function, FORECAST function
- Template: bảng dự báo với regression-based approach

**`3.1.3 Ưu nhược điểm hồi quy tuyến tính.md`**
- Pros: explainable, quantifies relationship, handles multiple variables
- Cons: assumes linear relationship (không phải lúc nào cũng đúng), sensitive to outliers
- Khi nào dùng: enough historical data, stable relationship, clear driver

**`3.2.1 Phương pháp chuỗi thời gian — Khái niệm và Cấu phần.md`**
- Time series components: Trend (T), Seasonality (S), Cyclicality (C), Irregular (I)
- Decomposition: tách 4 thành phần
- Ứng dụng: forecast retail sales theo season

**`3.2.2 Biểu mẫu dự báo chuỗi thời gian.md`**
- Moving average: simple và weighted
- Exponential smoothing: alpha parameter
- Seasonal index: tính và áp dụng
- Template Excel: 12-month seasonal forecast model

**`3.2.3 Ưu nhược điểm chuỗi thời gian.md`**
- Pros: captures patterns và seasonality, good for stable environments
- Cons: không capture structural change, needs sufficient history (>2 years lý tưởng)
- Khi nào dùng: mature business với stable patterns, seasonal business

**`3.3.1 Đường cong học tập — Cơ sở hình thành.md`**
- Learning curve effect: mỗi lần double cumulative output, unit cost giảm X%
- Wright's Law (1936): aviation manufacturing
- Ứng dụng: manufacturing, service delivery
- Ví dụ VN: nhà máy sản xuất TGDĐ, call center

**`3.3.2 Đường cong học tập — Khái niệm và Mô hình.md`**
- 80% learning curve: unit cost giảm 20% mỗi lần double output
- Cumulative average model vs Unit time model
- Tính toán: Y = aX^b (power function)

**`3.3.3 Điều kiện áp dụng đường cong học tập.md`**
- Applicable khi: high labour content, complex tasks, early in product lifecycle
- Not applicable khi: fully automated, commodity, mature stable process
- Key assumption: không disruption trong learning process

**`3.3.4 Biểu mẫu đường cong học tập.md`**
- Template: cumulative units → unit cost forecast
- Sensitivity: different learning rates (75%, 80%, 85%, 90%)
- Integration với budget: labour cost forecast cho new product launch

**`3.3.5 Ưu nhược điểm đường cong học tập.md`**
- Pros: forward-looking, captures efficiency gains, useful for pricing và bidding
- Cons: assumes continuous learning (disruption resets curve), hard to validate ex ante
- Pitfall: over-estimate learning rate → under-price contracts

---

## Module 5: Quản lý Vốn Lưu động
*Path: `5.Quản lý Vốn Lưu động/`*

### Phần 1 — Tư duy chiến lược

**`1.1.1.1 Tiền mặt và khả năng thanh khoản.md`**
- Cash là oxygen của business — không có cash = chết dù lợi nhuận dương
- Cash buffer rule: 3 tháng operating expenses minimum
- Liquidity management: cash pooling, sweep accounts
- Warning signs: line of credit drawdown tăng, late payments to suppliers

**`1.1.1.2 Công nợ phải thu và quản lý rủi ro khách hàng.md`**
- Accounts Receivable (AR) = tiền khách hàng đang nợ
- DSO (Days Sales Outstanding) = AR / (Revenue/365)
- Credit risk: customer tiered rating system
- Aging schedule: 0–30, 31–60, 61–90, >90 days

**`1.1.1.3 Công nợ phải trả và quan hệ nhà cung cấp.md`**
- Accounts Payable (AP) = tiền mình đang nợ supplier
- DPO (Days Payable Outstanding): kéo dài DPO = tốt hay xấu?
- Supplier relationship: balance giữa payment terms và relationship
- Early payment discount: nên take hay không?

**`1.1.2 Tăng trưởng và nhu cầu vốn lưu động.md`**
- Growth trap: tăng trưởng nhanh → cần more working capital
- Funded growth vs Unfunded growth: tại sao profitable company hết tiền khi grow
- Working capital intensity = Working Capital / Revenue
- Pre-funding growth: plan WC needs trước khi scale

**`1.1.3 Rào cản quản trị vốn lưu động trong SMEs.md`**
- Lack of visibility: không biết real-time cash position
- Informal processes: AR collection ad hoc, không systematic
- Relationship-based credit: extend credit vì friendship, không credit analysis
- Fix: weekly cash flow forecast, AR aging report, credit policy

**`1.2.1.1 Thời gian thu tiền và tốc độ luân chuyển công nợ.md`**
- DSO calculation + DIO calculation
- Receivable turnover ratio: mấy vòng/năm
- Target DSO: theo ngành và business model
- Collection process: invoice → reminder → escalation

**`1.2.1.2 Thời gian trả tiền và tín dụng thương mại.md`**
- Trade credit as financing: AP là nguồn vốn "free" ngắn hạn
- Optimal DPO: maximize without damaging supplier relationship
- 2/10 Net 30: annualized cost of NOT taking discount = 36%

**`1.2.1.3 Vòng quay tồn kho và chi phí cơ hội vốn.md`**
- DIO (Days Inventory Outstanding)
- Inventory holding costs: capital cost, storage, obsolescence, shrinkage
- Inventory turnover by SKU: find slow movers
- Just-in-Time vs safety stock: tradeoff

**`1.2.2.1 Ngưỡng thanh khoản tối thiểu an toàn.md`**
- Minimum cash buffer: 30–90 days operating expenses (ngành-dependent)
- Liquidity stress test: nếu top customer không trả 60 ngày, còn survive không?
- Credit facilities: establish before you need them
- Liquid asset buffer: cash + near-cash

**`1.2.2.2 Tác động dây chuyền khi thay đổi chính sách.md`**
- Policy change AR: giảm payment terms → cash improves nhưng có thể lose customers
- Policy change AP: extend DPO → cash improves nhưng damages supplier relations
- Policy change inventory: reduce stock → frees cash nhưng increases stockout risk
- Simulation: thay đổi một biến → impact lên CCC và cash

**`1.3.1 Ba định hướng quản trị vốn lưu động.md`**
- Conservative: high cash buffer, short AR, long inventory, pay suppliers early → safe nhưng expensive
- Aggressive: minimal cash, long AR, lean inventory, maximize DPO → efficient nhưng risky
- Balanced: optimize per component, driven by business model
- Chọn theo: industry, growth stage, risk appetite

**`1.3.2 Cơ chế phân bổ vốn theo ưu tiên chiến lược.md`**
- Capital allocation hierarchy: maintenance → growth → returns to shareholders
- WC investment vs CapEx: how to prioritize when capital scarce
- Seasonal business: WC needs spike pre-season → pre-fund

### Phần 2 — Dòng tiền và Công nợ

**`2.1.1.1 Các biến số trọng yếu ảnh hưởng đến dòng tiền.md`**
- Revenue timing: invoice date vs collection date
- Cost timing: accrual vs cash basis difference
- CapEx timing: lump sum vs installment
- Tax timing: estimated tax payments vs actual

**`2.1.1.2 Quy trình rà soát và cập nhật định kỳ.md`**
- Weekly cash flow forecast: 13-week rolling
- Monthly review: actual vs forecast, update assumptions
- Variance analysis: tại sao cash better/worse than expected
- Escalation: khi nào alert CFO/CEO

**`2.1.2 Quản trị dòng tiền theo chu kỳ vận hành.md`**
- Operating cycle cash flow map: từ raw material đến cash collected
- Seasonal patterns: peak seasons cần pre-funding
- Contract billing milestones: align với cash flow needs
- Progress billing vs. milestone billing

**`2.1.3 Cơ chế cảnh báo sớm rủi ro thanh khoản.md`**
- Early warning indicators: AR aging deterioration, DPO lengthening, inventory buildup
- Cash runway: tháng còn lại nếu không có revenue
- Trigger points: khi nào activate contingency plan
- Contingency options: credit facility, asset sale, equity injection

**`2.2.1.1 Tiêu chí phân loại khách hàng theo rủi ro.md`**
- Credit scoring: payment history, financial strength, industry risk
- ABC classification: A = pay on time + large, B = medium risk, C = high risk/slow pay
- Credit limit: based on risk tier
- Collateral: khi nào yêu cầu bảo đảm

**`2.2.1.2 Cơ chế giám sát và thu hồi công nợ hiệu quả.md`**
- AR aging weekly report: ai xem, ai action
- Collection script: soft reminder → firm reminder → escalation → legal
- Disputed invoices: separate process, resolve fast
- Incentive: sales team commission tied to collection (không chỉ booking)

**`2.2.2 Cấu trúc công nợ theo rủi ro và lợi nhuận.md`**
- High-margin customer with slow payment: profitable hay không?
- Net profit after cost of capital: adjust margin for WC cost
- Portfolio view: mix of customer risk profiles
- Concentration risk: >20% revenue from one customer → risky

**`2.2.3 Đàm phán và tái cấu trúc điều khoản thanh toán.md`**
- Renegotiate payment terms: khi nào và cách tiếp cận
- Factoring: bán AR cho factoring company để get cash immediately (cost: 1–3% discount)
- Supply chain financing: supplier gets paid early, buyer pays later (buyer's bank intermediary)
- Debt restructuring: extend repayment term when cash tight

### Phần 3 — Tồn kho và Tích hợp

**`3.1.1.1 Phân loại tồn kho theo giá trị và tần suất.md`**
- ABC analysis: A = 20% SKU tạo 80% value → monitor closely
- XYZ analysis: X = steady demand, Y = variable, Z = sporadic
- ABC-XYZ matrix: AX = most critical, CZ = candidates for discontinuation

**`3.1.1.2 Tồn kho chiến lược và tồn kho cần giải phóng vốn.md`**
- Strategic inventory: safety stock for critical components
- Dead stock: >6 months no movement → write-down plan
- Clearance pricing: recover some capital from dead stock
- Prevention: better demand forecasting, shorter order cycles

**`3.1.2.1 Cân bằng rủi ro đứt gãy và chi phí lưu kho.md`**
- Stockout cost: lost sales + customer dissatisfaction
- Holding cost: capital + storage + obsolescence + insurance
- Optimal safety stock formula: based on demand variability + lead time variability
- Service level target: 95% vs 99% — cost difference significant

**`3.1.2.2 Tối ưu chu kỳ đặt hàng theo dữ liệu thực tế.md`**
- EOQ (Economic Order Quantity): optimize order size
- Reorder point: when to place next order
- Lead time management: reduce lead time → reduce safety stock needed
- Vendor-managed inventory (VMI): supplier manages stock at your location

**`3.1.3 Chi phí cơ hội và chi phí lưu kho.md`**
- Total holding cost = capital cost + storage + handling + obsolescence + shrinkage
- Capital cost of inventory: WACC × inventory value (thường 8–15%/năm)
- Shrinkage: theft, damage, expiry — ước tính và control
- Obsolescence risk: technology products, fashion — model risk explicitly

**`3.2.1.1 Mô phỏng kịch bản thay đổi một cấu phần.md`**
- Scenario: reduce DSO by 10 days → impact on cash và P&L
- Scenario: increase DPO by 10 days → impact on supplier relationship và cash
- Scenario: reduce DIO by 5 days → impact on service level và cash
- Combined scenario: tất cả 3 optimize → tổng impact

**`3.2.1.2 Đánh giá hiệu quả sau tái cấu trúc chính sách.md`**
- Before/after comparison: CCC, cash balance, cost of working capital
- Unintended consequences: customer loss, supplier deterioration
- Monitoring: 3-month post-change review
- Adjust: nếu consequences bad → rollback hoặc modify

**`3.2.2 Hệ thống giám sát và dashboard vốn lưu động.md`**
- WC dashboard: Cash days, DSO, DPO, DIO, CCC — daily/weekly
- Traffic light system: green/yellow/red per metric
- Action protocol: yellow → investigate; red → escalate + intervene
- Data source: ERP output, không phải manual collection

**`3.2.3 Nguyên tắc ra quyết định ưu tiên sử dụng vốn ngắn hạn.md`**
- Priority waterfall: obligations first → operations → growth → opportunistic
- Opportunity cost framework: WC vs CapEx vs debt repayment
- Short-term vs long-term tradeoff: don't sacrifice long-term for short-term liquidity
- Decision criteria: marginal cost of WC vs return on use

---

## Module 6: Tối ưu Thuế và Quản trị Rủi ro Tuân thủ
*Path: `6.Tối ưu Thuế và Quản trị Rủi ro Tuân thủ/`*

**Lưu ý quan trọng:** Mọi file trong module này cần disclaimer:
*"Nội dung chỉ mang tính giáo dục — tham khảo chuyên gia thuế hoặc kế toán trước khi áp dụng."*

### Phần 1 — Quản trị thuế chiến lược

**`1.1.1.1 Tác động chính sách thuế đến lợi nhuận ròng.md`**
- Effective tax rate vs statutory rate: tại sao khác nhau
- Tax as % of EBIT: benchmark theo ngành VN
- Ví dụ: cùng EBIT 10 tỷ, ETR khác nhau → net profit khác nhau đáng kể

**`1.1.1.2 Liên kết thuế và dòng tiền hoạt động.md`**
- Cash tax paid vs tax expense (accrual): timing difference
- Deferred tax: asset (overpaid) vs liability (underpaid)
- Cash flow planning: estimated tax payments quarterly

**`1.1.2.1 Lợi ích lập kế hoạch thuế hợp pháp.md`**
- Tax planning vs Tax evasion: ranh giới rõ ràng
- Legitimate optimization: timing of income/expense, use of incentives
- Luật Thuế TNDN: ưu đãi cho high-tech, R&D, vùng khó khăn
- CIT incentives: 10% rate cho high-tech, 2-year tax holiday + 4 years 50% reduction

**`1.1.2.2 Giới hạn rủi ro pháp lý trong tối ưu thuế.md`**
- Substance over form: cơ quan thuế nhìn vào bản chất, không phải hình thức
- Transfer pricing risk: related-party transactions phải arm's length
- Anti-avoidance provisions: GAAR (General Anti-Avoidance Rule) VN
- Red flags: cơ quan thuế focus vào gì khi audit

**`1.2.1 Case study — SME tối ưu cấu trúc chi phí và thuế.md`**
- Scenario: SME tech 50 người, doanh thu 30 tỷ
- Opportunities: R&D expense deduction, training costs, depreciation acceleration
- Restructuring: when to use holding company structure
- Disclaimer: specific advice cần professional

### Phần 2 — Tối ưu các sắc thuế chủ yếu

**`2.1.1 Rủi ro thường gặp về hóa đơn và khấu trừ VAT.md`**
- Hóa đơn không hợp lệ: 8 lỗi phổ biến → bị loại khấu trừ VAT đầu vào
- Circular 78/2014, Thông tư 26/2015: điều kiện khấu trừ VAT
- Input VAT recovery: không claim đúng hạn → mất
- E-invoice (Nghị định 123/2020): yêu cầu và rủi ro

**`2.1.2.1 Kiểm soát hồ sơ chứng từ tránh bị loại chi phí.md`**
- Thông tư 96/2015/TT-BTC: điều kiện chi phí được trừ
- 3 điều kiện cốt lõi: thực tế phát sinh, phục vụ hoạt động kinh doanh, có đầy đủ hóa đơn chứng từ
- Checklist hồ sơ: hợp đồng + hóa đơn + biên bản nghiệm thu + chứng từ thanh toán
- Common mistakes: thanh toán tiền mặt >20 triệu, hóa đơn sai tên/địa chỉ

**`2.1.2.2 Tận dụng thuế GTGT đầu vào.md`**
- Timing: đẩy mua hàng trước kỳ khai báo để maximize input VAT
- Non-deductible VAT: xe ô tô >1.6 tỷ, một số entertainment expenses
- Pro-rata rule: nếu có cả taxable và non-taxable revenue
- Refund vs offset: khi nào request refund

**`2.2.1 Chi phí được trừ và không được trừ (CIT).md`**
- Deductible: thực tế + phục vụ KD + đủ chứng từ
- Non-deductible phổ biến: tiền phạt vi phạm hành chính, chi quảng cáo vượt 15% revenue, không hóa đơn
- Gray areas: entertainment, gifts, travel expenses → cần document
- Depreciation: straight-line, reduced balance, theo thông tư 45/2013

**`2.2.2.1 Cân đối lợi ích kế toán và thuế khi ghi nhận chi phí.md`**
- Book vs Tax difference: timing differences create deferred tax
- Accelerated depreciation (tax) vs straight-line (book)
- Provision expenses: book ngay khi probable, tax khi realized
- Impact lên ETR và cash taxes

**`2.2.2.2 Dự báo ảnh hưởng đến dòng tiền sau thuế.md`**
- After-tax cash flow = Pre-tax cash flow × (1 − ETR)
- Tax shield on interest expense: vì sao leverage reduce tax
- CapEx timing: depreciation tax shield value
- Working capital và thuế: accelerate deductions, defer income

**`2.3.1 Chính sách thuế TNCN theo các loại thu nhập.md`**
- Taxable income categories: tiền lương/công, kinh doanh, đầu tư, chuyển nhượng BĐS/chứng khoán
- Progressive tax rates: 5%–35% (lương) vs flat rates (khác)
- Personal deductions: bản thân 11 triệu/tháng, phụ thuộc 4.4 triệu/người/tháng
- Resident vs Non-resident: khác nhau về cách tính

**`2.3.2 Cân bằng phúc lợi thưởng và chi phí thuế.md`**
- Tax-efficient compensation: không phải tất cả thu nhập đều taxable như nhau
- Non-taxable benefits: nhà ở một nơi, vé máy bay về phép (nước ngoài), đồng phục, bữa ăn ca
- Stock options vs cash bonus: khác biệt về timing và rate
- Company car vs car allowance: taxability khác nhau

### Phần 3 — Kiểm soát rủi ro tuân thủ thuế

**`3.1.1 Điểm yếu trong quy trình kế toán và kê khai.md`**
- Common weaknesses: manual processes → transcription errors
- Month-end close process: nếu không structured → errors
- Reconciliation gaps: GTGT claim vs general ledger
- Internal control checklist cho SME: 10 controls quan trọng nhất

**`3.1.2 Cơ chế kiểm tra phê duyệt lưu trữ chứng từ.md`**
- 4-eyes principle: 2 người approve trước khi file tax return
- Document retention: hóa đơn/chứng từ 10 năm theo VN law
- Digital storage: e-invoice lưu thế nào, backup, access control
- Tax file room: organized by year, type, ready for audit

**`3.2.1 Đánh giá rủi ro bị truy thu và phạt chậm nộp.md`**
- Penalty regime: truy thu 100% + phạt 20% + lãi chậm nộp 0.03%/ngày
- Common audit triggers: high growth không matched với tax, unusual expense ratios
- Self-assessment: review mình trước khi cơ quan thuế review
- Statute of limitations: 5 năm (10 năm nếu trốn thuế)

**`3.2.2 Hồ sơ giải trình và cơ chế phản hồi cơ quan thuế.md`**
- Tax audit response: không panic, gather documentation first
- Written response: professional tone, factual, không defensive
- Negotiation: adjustments thường negotiable nếu good faith
- Appeal process: khi nào và cách thức

**`3.3.1 Tích hợp dữ liệu thuế điện tử và hóa đơn điện tử.md`**
- E-invoice system: kết nối với Tổng Cục Thuế
- Real-time reporting: hóa đơn phát hành → thuế biết ngay
- System requirements: phần mềm phát hành hóa đơn phải certified
- Transition risks: old system to new → data migration, reconciliation

**`3.3.2 Tác động quy định mới e-invoice đến vận hành SME.md`**
- Nghị định 123/2020: mandatory e-invoice từ 7/2022
- Operational changes: paper invoice process bị xóa bỏ
- Cost: phần mềm, training, connection fees
- Benefits: real-time tracking, automated reconciliation, fraud reduction

---

## Module 7: Huy động Vốn và Tái Cấu trúc Tài chính
*Path: `7.Huy động Vốn và Tái Cấu trúc Tài chính/`*

### Phần 1 — Đánh giá năng lực tài chính

**`1.1.1.1 Nhận diện rủi ro mất cân đối tài chính.md`**
- Financial distress signals: liquidity ratios deteriorating, covenant breach, supplier cutting credit
- Altman Z-Score: predict financial distress (Z < 1.81 = danger zone)
- Working capital trap: grow fast → WC negative → distress
- Early intervention: better outcomes if addressed early

**`1.1.1.2 Phân tích khả năng chịu đựng đòn bẩy tài chính.md`**
- Debt capacity: how much debt can the business service?
- DSCR (Debt Service Coverage Ratio) = EBITDA / (Principal + Interest): >1.25 comfortable
- Leverage limit: tùy ngành — F&B có thể 2x EBITDA, BĐS development 4–6x
- Stress test: nếu EBITDA giảm 30%, còn cover debt service không?

**`1.1.2.1 Dự báo dòng tiền thiếu hụt hoặc dư thừa.md`**
- 13-week cash flow forecast: weekly granularity
- Funding gap analysis: khi nào và bao nhiêu cần additional capital
- Excess cash deployment: không để idle — short-term instruments
- Scenario planning: base / downside / upside

**`1.1.2.2 Liên kết mục tiêu tăng trưởng với nhu cầu vốn.md`**
- Growth = more WC + more CapEx → more capital needed
- Sustainable growth rate = ROE × Retention Rate (no external capital)
- If target growth > sustainable rate → need external capital
- Capital planning: how much, when, what type

### Phần 2 — Lựa chọn kênh huy động vốn

**`2.1.1 Vốn nội bộ — lợi nhuận giữ lại và góp thêm.md`**
- Retained earnings: cheapest but limited
- Owner injection: dilutes personal liquidity
- ESOP / employee investment: align incentives
- Bootstrapping limits: growth capped by internal generation

**`2.1.2 Vốn bên ngoài — ngân hàng, nhà đầu tư, đối tác.md`**
- Bank debt: cheaper cost, requires collateral and cash flow
- Angel / VC / PE: expensive (equity dilution), provides expertise and network
- Strategic investor: smart money with strategic value
- Trade credit / supply chain financing: often underutilized

**`2.1.3 Chi phí vốn và rủi ro từng kênh.md`**
- Cost of debt: interest rate (8–12% VN 2024) − tax shield
- Cost of equity: CAPM hoặc private market premium (typically 15–25% for VN SME)
- WACC: blended cost
- Risk: debt → financial risk; equity → dilution + governance

**`2.2.1 Tỷ trọng vốn vay và vốn chủ theo chiến lược.md`**
- Capital structure: optimal D/E depends on business stability
- Tax shield benefit of debt vs financial distress cost
- Modigliani-Miller với thuế: levered firm value = unlevered + PV(tax shield)
- Practical guidelines by business type

**`2.2.2.1 Kịch bản biến động lãi suất và khả năng trả nợ.md`**
- Floating rate debt exposure: lãi suất VN biến động nhiều
- Sensitivity: nếu lãi suất tăng 2%, DSCR giảm bao nhiêu?
- Hedging options: fixed rate, interest rate swap (ít phổ biến ở VN SME)
- Refinancing risk: maturity wall — khi nhiều nợ đến hạn cùng lúc

**`2.2.2.2 Ngưỡng cảnh báo tài chính nội bộ.md`**
- Financial covenants: DSCR, leverage ratio, minimum liquidity
- Early warning dashboard: mỗi metric với green/yellow/red thresholds
- Response protocol: yellow → management review; red → board alert + remediation plan

**`2.3.1 Chuẩn hóa hồ sơ vay và năng lực tín dụng.md`**
- What banks look for: 5Cs — Character, Capacity, Capital, Collateral, Conditions
- Credit file: 3 years financial statements, management accounts, forecasts
- Collateral: real estate, equipment, AR assignment
- Credit score improvement: pay on time, reduce leverage, improve coverage

**`2.3.2 Trình bày kế hoạch kinh doanh và dòng tiền thuyết phục.md`**
- Business plan for bank: executive summary, market, business model, financials
- Cash flow projections: monthly, 3 scenarios
- Sensitivities: what if revenue is 20% lower?
- Management credibility: track record matters more than projections

**`2.3.3 Uy tín tín dụng và quan hệ tài chính dài hạn.md`**
- Build bank relationship before you need the money
- Regular communication: share financials proactively, not just at loan renewal
- Multiple banking relationships: không phụ thuộc một ngân hàng
- Trade credit history: pay suppliers on time → build credit reference

### Phần 3 — Tái cấu trúc và chiến lược vốn

**`3.1.1 Dấu hiệu mất cân đối tài chính và vòng xoáy nợ.md`**
- Debt spiral: borrow to pay interest → more debt → less coverage → more expensive debt
- Signs: bank lines fully drawn, aging AP lengthening, supplier demanding prepay
- Tipping point: khi nào cần professional restructuring advisor
- Prevention: monitor DSCR monthly, không để breach covenants

**`3.1.2 Đánh giá khả năng phục hồi dòng tiền.md`**
- Viability assessment: is the business fundamentally sound?
- Cash flow recovery plan: what actions can restore positive FCF?
- Time to recovery: 3/6/12 months — determines restructuring approach
- Stakeholder assessment: who can help / who will obstruct

**`3.2.1 Đàm phán giãn nợ, hoán đổi và tái cấp vốn.md`**
- Debt standstill: temporary halt on payments while restructuring
- Debt-to-equity swap: convert debt to equity (creditor becomes shareholder)
- Refinancing: new loan to repay old (better terms, longer tenor)
- Haircut negotiation: creditors accept less than face value
- Process: usually requires legal and financial advisor

**`3.2.2.1 Cân đối lợi nhuận tái đầu tư và cổ tức.md`**
- Dividend policy: financial performance, growth needs, shareholder expectations
- Payout ratio: sustainable range depends on capex needs and growth
- Stock dividend vs cash dividend: tax và signal differences
- Retained earnings strategy: fund growth or return capital?

**`3.2.2.2 Minh bạch tài chính để thu hút vốn mới.md`**
- Investor-ready financials: audited, IFRS or VAS clearly stated
- Related party transactions: disclosed, at arm's length
- Corporate governance: board composition, controls, reporting
- Due diligence readiness: data room with complete documentation

**`3.3.1 Đa dạng hóa nguồn vốn — ngân hàng, đối tác, quỹ đầu tư.md`**
- Single source dependency risk
- Bank + PE + strategic investor: different advantages
- Government programs: ưu đãi cho doanh nghiệp đổi mới sáng tạo, SME
- Timing: diversify during good times, not when desperate

**`3.3.2 Gắn quản trị vốn với tăng trưởng dài hạn.md`**
- Capital efficiency: growth rate / capital invested
- ROIC > WACC: value creation; ROIC < WACC: value destruction
- Capital recycling: sell underperforming assets, redeploy to higher-return uses
- Long-term capital strategy: 3-year rolling capital plan

---

## Module 8: Quản lý Tài chính Cá nhân
*Path: `8.Quản lý Tài chính Cá nhân/`*

### Phần 1 — Hoạch định đầu tư và tín dụng

**`5.1 Chu kỳ kinh tế và đặc điểm từng giai đoạn.md`**
- 4 phases: Expansion → Peak → Contraction → Trough
- Leading indicators: PMI, credit growth, bond yield curve
- VN economic cycle: đặc điểm riêng (liên kết với China, FDI-driven)
- Asset allocation theo chu kỳ: rotate sectors

**`5.2 Hiệu suất các lớp tài sản theo chu kỳ kinh tế.md`**
- Equities: outperform in early expansion
- Fixed income/bonds: outperform in contraction
- Real estate: lags cycle by 6–12 months
- Commodities: peak near economic peak
- Gold: safe haven in uncertainty
- VN context: BĐS và chứng khoán thống trị danh mục cá nhân VN

**`5.3 Các loại hình đầu tư và đặc tính từng loại.md`**
- Equities: high return, high volatility, liquid
- Fixed deposits/bonds: lower return, predictable, low risk
- Real estate: illiquid, leverage, tax advantaged
- Business investment: highest return potential, highest risk, illiquid
- Mutual funds: diversified, professional management, accessible
- Crypto: speculative, high volatility, not suitable for financial planning base

**`5.4 Đặc tính của một danh mục tài sản hiệu quả.md`**
- Markowitz efficient frontier: maximize return for given risk
- Diversification benefit: correlation between assets matters
- Practical VN portfolio: stocks + fixed income + real estate
- Rebalancing: tái cơ cấu định kỳ để maintain target allocation
- Time horizon: determines acceptable risk level

**`5.5 Các tình huống vay thiếu hiệu quả của doanh chủ.md`**
- Common mistake: mix business and personal finances
- Personal guarantee for business debt: personal exposure
- Borrow to invest in volatile assets: leverage on top of investment risk
- Real estate investment with 80% leverage: breakeven rent calculation
- Credit card debt for investment: 24–36% interest = very hard to beat

**`5.6 Sai lầm về quản trị dòng vốn của chủ DN SME.md`**
- Company profit ≠ owner wealth: retained earnings vs cash in pocket
- Drawing excessively: undercapitalize the business
- Not separating accounts: mix personal with business
- Not planning for tax on distributions: dividend tax, personal income
- No emergency fund: company cash = personal savings = dangerous

**`5.7 Xử lý khoản vay khi có biến động tài chính.md`**
- Review loan terms: fixed vs floating, prepayment penalties
- Priority payoff: highest interest rate first (avalanche method) or smallest balance (snowball method)
- Refinancing: lower rate or extend term for cash flow relief
- Communicating with lenders: proactive communication better than default

### Phần 2 — Hoạch định tài chính cá nhân toàn diện

**`6.1 Khái niệm và phạm vi kế hoạch hưu trí.md`**
- Retirement planning = ensuring financial independence at chosen retirement age
- Three pillars: social insurance (BHXH), corporate pension (ít phổ biến VN), personal savings
- Replacement ratio: cần bao nhiêu % income pre-retirement để maintain lifestyle?
- Vietnamese context: gia đình extended = một phần retirement support

**`6.2 Nghịch đảo cơ cấu dân số vàng và già hóa dân số.md`**
- Demographic dividend: VN đang ở giai đoạn cuối dân số vàng
- Aging society: tỷ lệ người già tăng → BHXH áp lực
- Implication cá nhân: không thể rely solely on state pension
- Timeline: VN dự kiến già hóa nhanh vào 2035–2050

**`6.3 Bối cảnh hệ thống hưu trí tại Việt Nam.md`**
- BHXH bắt buộc: mức hưởng, điều kiện, tính toán
- BHXH tự nguyện: cho informal sector
- Voluntary pension fund: Nghị định 88/2016 — ít người biết
- Gap: BHXH chỉ replace ~45–55% final salary → insufficient

**`6.4 Các bước xây dựng kế hoạch hưu trí.md`**
- Step 1: Determine retirement age và income needed
- Step 2: Calculate retirement corpus needed (using 4% rule hoặc annuity)
- Step 3: Calculate current savings trajectory
- Step 4: Identify the gap
- Step 5: Choose instruments to fill gap
- Step 6: Review annually

**`6.5 Các sản phẩm tài chính cho giai đoạn hưu trí.md`**
- Fixed deposits/savings: safe, liquid, low return
- Government bonds: safe, slightly higher yield
- Mutual funds (balanced/equity): long-term growth
- Life insurance savings (bảo hiểm nhân thọ tích lũy): guaranteed return, tax advantage
- Voluntary BHXH: government guarantee, limited flexibility
- Real estate income: rental yield 4–6% VN

**`7.1 Khái niệm di sản và tính chất pháp lý.md`**
- Estate = tất cả tài sản, quyền tài sản, nghĩa vụ tài sản của người mất
- Phân biệt: tài sản riêng vs tài sản chung vợ chồng
- Scope: bất động sản, tiền, chứng khoán, doanh nghiệp, IP, khoản nợ
- BLDS 2015: Phần IV — Thừa kế

**`7.2 Thừa kế theo pháp luật.md`**
- Khi không có di chúc: chia theo hàng thừa kế
- Hàng 1: vợ/chồng, con, cha mẹ
- Hàng 2: anh chị em ruột, ông bà
- Hàng 3: cô dì chú bác, cháu ruột
- Vấn đề: tài sản doanh nghiệp chia theo hàng thừa kế → disruption

**`7.3 Thừa kế theo di chúc.md`**
- Di chúc override hàng thừa kế (với một số hạn chế)
- Người không phụ thuộc vẫn được nhận phần bắt buộc
- Điều kiện di chúc hợp lệ
- Nên có di chúc nếu muốn control việc phân chia

**`7.4 Di chúc và các loại di chúc.md`**
- Di chúc bằng văn bản: có công chứng vs không công chứng
- Di chúc miệng: chỉ hợp lệ khi sắp chết, có 2 nhân chứng
- Di chúc có công chứng: strong evidentiary value
- Điều khoản cần có trong di chúc

**`7.5 Hoạch định di sản toàn diện.md`**
- Goals: minimize family conflict, minimize tax, continue business
- Tools: di chúc, tặng cho trong khi còn sống, tổ chức lại doanh nghiệp
- Business succession: ai kế thừa doanh nghiệp?
- Family trust: ít phổ biến VN nhưng đang phát triển
- Review: update sau major life events (marriage, children, divorce, death)

**`8.1 Các loại thu nhập chịu thuế và thuế suất.md`**
- Tiền lương/công: progressive 5%–35%
- Kinh doanh: 0.5%–2% on revenue (không thuộc hộ kinh doanh > ngưỡng)
- Đầu tư vốn: cổ tức 5%, lãi tiền gửi miễn thuế
- Chuyển nhượng chứng khoán: 0.1% trên giá bán
- Chuyển nhượng BĐS: 2% trên giá bán hoặc chênh lệch

**`8.2 Hoạch định tối ưu thuế TNCN.md`**
- Timing income: defer to lower-bracket year if possible
- Structure compensation: salary vs bonus vs benefits
- Use deductions fully: đăng ký giảm trừ gia cảnh đầy đủ
- Business owner: salary vs dividend decision

**`8.3 Các khoản thu nhập được miễn thuế.md`**
- Tiền lãi ngân hàng và trái phiếu chính phủ
- Lương làm thêm giờ vào ban đêm (phần vượt)
- Phụ cấp đặc thù: độc hại, thâm niên
- Thu nhập từ nhà ở duy nhất bán
- Quà tặng giữa người thân trong gia đình (một số loại)

**`8.4 Tối ưu quyền miễn thuế theo luật định.md`**
- Cách đăng ký người phụ thuộc: MST, đăng ký với HR
- Contribution to BHXH tự nguyện: một phần giảm trừ
- Insurance premium deduction: bảo hiểm nhân thọ có một phần giảm trừ
- Timing charitable donation: deductible nếu qua tổ chức được công nhận

**`8.5 Tối ưu thuế dành cho chủ doanh nghiệp.md`**
- Owner salary vs dividend: tax treatment khác nhau
- Legit business expenses: car, phone, training — khi nào deductible
- Holding company structure: tax planning opportunities (và rủi ro khi không có substance)
- Timing of income recognition: owner có nhiều flexibility hơn employee

**`8.6 Sai lầm thường gặp về hoạch định thuế.md`**
- Không quyết toán thuế TNCN hàng năm → miss refund hoặc bị truy thu
- Không đăng ký người phụ thuộc → miss deductions
- Mix business và personal → bị disallowed deductions
- Assume tax laws stable → thực ra thay đổi thường xuyên

**`8.7 Một số tình huống tối ưu thuế phổ biến.md`**
- Tình huống 1: nhân viên lương cao, muốn giảm TNCN → benefit structuring
- Tình huống 2: chủ DN nhận cổ tức vs lương → optimization
- Tình huống 3: bán BĐS — 2% vs chênh lệch, chọn cái nào?
- Tình huống 4: kiều hối và thu nhập nước ngoài của người VN

**`8.8 Pháp nhân và cá nhân trong hoạch định thuế.md`**
- Separate legal entity: company tax vs personal tax không pha trộn
- When to use company: khi income regular và CIT rate < personal marginal rate
- Flow-through risk: khi hộ kinh doanh phù hợp hơn công ty
- Anti-avoidance: cơ quan thuế nhìn vào economic substance

**`9.1 Ôn tập các kiến thức hoạch định tài chính cá nhân.md`**
- Summary framework: 6 pillars of personal finance (income, protection, savings, investment, tax, estate)
- Interconnections: how each pillar affects others
- Priority order: protection (insurance) first, then debt, then savings, then investment

**`9.2 Phân tích tình huống.md`**
- Scenario: Chủ DN 45 tuổi, doanh thu 50 tỷ, muốn retire at 60
- Analysis: current financial position, gap analysis, required actions
- Common profiles: early career, mid-career, pre-retirement, post-sale

**`9.3 Thực hành hoạch định tài chính cá nhân toàn diện.md`**
- Template: one-page financial plan
- Income & expense statement (personal)
- Net worth statement: assets − liabilities
- Goal-based planning: retirement, children education, home purchase
- Review cadence: annual full review, quarterly check-in
