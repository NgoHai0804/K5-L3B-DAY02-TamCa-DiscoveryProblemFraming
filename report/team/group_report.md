# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: TamCa
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Sinh viên IT năm cuối/mới ra trường mất nhiều thời gian (khoảng 16/30 phút mỗi CV) để đối chiếu và viết lại mô tả dự án trong CV cho khớp với từ khóa yêu cầu trong JD khi ứng tuyển Intern/Fresher.
- Quyết định cuối: Go / Not Yet / No-Go _(chốt ở CP6)_

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Trần Thị Nhài | Khi apply một vị trí mới, tôi muốn chỉnh CV cho khớp yêu cầu trong JD, để không bị loại ngay ở vòng lọc hồ sơ | Sinh viên năm cuối / mới ra trường ngành IT | Viết lại mô tả dự án/kinh nghiệm cho khớp từng yêu cầu JD (~16'/CV, hơn nửa tổng thời gian) | "Chuẩn bị sẵn CV master có 2–3 phiên bản mô tả (No AI) đã đủ chưa?" (Ngô Ngọc Hải) |
| 2 | Trần Thị Nhài | Khi lướt các trang tuyển dụng mỗi ngày, tôi muốn thấy nhanh tin Intern/Fresher đúng tech stack và khu vực, để không mất thời gian đọc tin không hợp | Sinh viên năm cuối / mới ra trường IT, theo dõi 4 nguồn (TopCV, ITviec, LinkedIn, group FB) | Đọc từng tin để kiểm stack/cấp độ/khu vực (~30'/ngày; 7/10 tin đọc xong mới biết không hợp) | "Bộ lọc / job alert có sẵn của TopCV/ITviec/LinkedIn đã đủ chưa?" (Trần Hữu Tài) |
| 3 | Trần Thị Nhài | Khi nhận đề lab mới gồm nhiều file hướng dẫn, tôi muốn nắm cần làm gì, nộp gì và phần nào bị giới hạn, để bắt tay làm ngay mà không sót/vi phạm | Học viên khóa học có lab mỗi buổi (6 lab/tuần) | Đọc chéo RULES/RUBRIC/SUBMISSION/template (~20'/lab; yêu cầu 1 checkpoint nằm rải ở 3–4 file) | "Bottleneck thật là do phải đọc chéo file hay do đề lab viết chưa rõ?" (Ngô Ngọc Hải) |
| 4 | Ngô Ngọc Hải | Khi bắt đầu ngày làm việc hoặc tìm hiểu công nghệ mới, tôi muốn nhanh chóng cập nhật thông tin & xu hướng mới nhất, để không tụt hậu và không dùng phương pháp lỗi thời | Bản thân, thành viên phụ trách công nghệ / R&D | Đọc chi tiết 2–3 bài viết dài để lọc nội dung thực chất (~25'/lần) | "Dùng RSS feed + newsletter (No AI) đã đủ lọc tin rác chưa?" (Trần Thị Nhài) |
| 5 | Ngô Ngọc Hải | Khi nhóm trưởng/đồng đội cần nắm tình hình các việc dở dang, tôi muốn có danh sách việc tồn và blocker, để cả nhóm phối hợp kịp thời mà không phải hỏi dồn dập | Thành viên nhóm đồ án, nhóm trưởng | Nhắn tin và chờ từng người trả lời nguyên nhân nghẽn (~25') | "Pain là do thiếu công cụ hay do thành viên không chịu tự cập nhật?" (Trần Thị Nhài) |
| 6 | Ngô Ngọc Hải | Khi chuẩn bị nộp lab AI20K trước 23h59, tôi muốn đối chiếu cấu trúc thư mục, tên file và link repo theo đúng barem, để không bị trừ điểm oan | Học viên AI20K, người nộp đại diện nhóm | Rà soát thủ công từng file báo cáo (~15'/lần) | "Một shell script kiểm rule đã đủ 95% chưa? Bõ công cả buổi lab?" (Trần Hữu Tài) |
| 7 | Trần Hữu Tài | Khi luyện trả lời xong, tôi muốn biết câu trả lời của mình tốt/dở ở điểm nào, để biết phải sửa gì trước buổi phỏng vấn thật | Ứng viên (sinh viên năm cuối / người mới đi làm) | Tự đánh giá câu trả lời, không tiêu chí, không người chuyên môn (~15–30') | "Ứng viên cần điểm số hay cần gợi ý sửa cụ thể?" (Trần Thị Nhài) |
| 8 | Trần Hữu Tài | Khi sắp có buổi phỏng vấn, tôi muốn luyện tập trong tình huống giống thật (có người hỏi, áp lực thời gian), để không bị run và bí ý | Ứng viên; người đóng vai (bạn bè, mentor) | Tìm và hẹn được người đóng vai phỏng vấn (chờ 1–3 ngày) | "Mock interview với bạn bè / Pramp đã đủ chưa?" (Ngô Ngọc Hải) |
| 9 | Trần Hữu Tài | Khi ứng tuyển một vị trí cụ thể, tôi muốn biết phỏng vấn mấy vòng và câu hỏi có khả năng được hỏi, để chuẩn bị đúng trọng tâm | Ứng viên | Tìm và đọc thông tin rời rạc từ nhiều nguồn (60–120'/công ty) | "Glassdoor/group cộng đồng đã đủ? Thông tin tổng hợp có đáng tin?" (Ngô Ngọc Hải) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung (Nỗi đau chung) |
|---|---|---|
| **A — Lọc tin từ nhiều nguồn** | • #2 (Nhài — Lọc tin tuyển dụng)<br>• #4 (Hải — Lọc tin công nghệ)<br>• #9 (Tài — Lọc review & câu hỏi phỏng vấn) | Phải mở nhiều trang, đọc lướt hàng chục bài viết/tin tức để nhặt ra vài thông tin đúng nhu cầu; tốn 30–60 phút mỗi ngày và dễ đọc phải tin rác/không hợp. |
| **B — So khớp & sửa theo barem** | • #1 (Nhài — Chỉnh CV theo JD)<br>• #6 (Hải — Soát bài nộp theo barem lab)<br>• #7 (Tài — Tự chấm câu trả lời PV theo rubric) | Đã có tiêu chuẩn sẵn (JD, barem lab, rubric), nhưng phải tự căng mắt đối chiếu từng dòng và sửa thủ công; rất dễ sót lỗi khiến hồ sơ bị loại hoặc bài thi bị trừ điểm. |
| **C — Chuẩn bị trước khi bắt tay vào làm** | • #3 (Nhài — Đọc chéo file đề lab để nắm việc)<br>• #5 (Hải — Hỏi từng người để nắm việc tồn & blocker)<br>• #8 (Tài — Chờ hẹn người để luyện phỏng vấn thử) | Trước khi bắt đầu việc chính (làm lab, họp nhóm, đi phỏng vấn), bị nghẽn ở khâu chuẩn bị vì thông tin bị xé nhỏ ở nhiều nơi hoặc phải phụ thuộc, chờ đợi người khác. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Sinh viên IT năm cuối/mới ra trường giảm thời gian chuẩn bị cho một lần ứng tuyển Intern/Fresher IT (từ lúc lọc tin đến lúc nộp CV), mà tỷ lệ hồ sơ vượt qua vòng lọc CV không giảm (baseline: 1/4 hồ sơ có phản hồi).
├── Opportunity A (từ Cluster A): Mất nhiều thời gian đọc lướt hàng chục tin tuyển dụng rải rác trên nhiều trang để nhặt ra tin đúng stack và khu vực.
├── Opportunity B (từ Cluster B - Trọng tâm nhóm chọn): Mất hơn một nửa thời gian để so từng yêu cầu trong JD và viết lại mô tả dự án trong CV cho khớp từ khóa.
└── Opportunity C (từ Cluster C): Mất nhiều thời gian tự chuẩn bị câu trả lời phỏng vấn mà không có tiêu chuẩn rõ ràng để tự đánh giá câu trả lời đã đạt hay chưa.
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- ✗ "Website/Tool tự động cào tin tuyển dụng và nộp CV hàng loạt" — Solution kỹ thuật, vi phạm boundary đạo đức (spam ứng tuyển), làm tăng tỷ lệ bị từ chối.
- ✗ "AI tự động viết lại toàn bộ CV từ đầu" — Solution trá hình, có nguy cơ nghiêm trọng về việc AI phóng đại hoặc bịa đặt kỹ năng không có thật.
- ✗ "Chatbot tư vấn phỏng vấn có AI chấm điểm" — Solution mơ hồ, chưa làm rõ tiêu chí chấm và giải quyết sai mắt xích (nghẽn chính nằm ở khâu chuẩn bị CV để qua vòng hồ sơ).

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| **1. Chỉnh CV theo JD (#1 — Nhài, Cluster B)** | 5 | 5 | 5 | 5 | 4 | 5 | 5 | **34** |
| **2. Barem & quy cách nộp lab AI20K (#6 — Hải, Cluster B)** | 5 | 5 | 5 | 5 | 5 | 3 | 5 | **33** |
| **3. Lọc tin tuyển dụng Intern/Fresher (#2 — Nhài, Cluster A)** | 4 | 4 | 4 | 4 | 4 | 4 | 4 | **28** |

**Candidate được chọn:**
Candidate #1 — Chỉnh CV theo JD khi ứng tuyển vị trí Intern/Fresher IT.

**Vì sao chọn:**
1. **Điểm đánh giá cao nhất (34/35):** Đạt điểm tối đa ở hầu hết các tiêu chí quan trọng.
2. **Bottleneck cực kỳ sắc nét:** Bước viết lại mô tả dự án/kinh nghiệm theo từ khóa của JD chiếm tới 16/30 phút của mỗi CV (hơn 50% thời gian) và lặp lại với mỗi JD mới.
3. **So sánh 4 mức can thiệp rất tự nhiên:**
   - *No AI:* Chuẩn bị sẵn "CV master" với nhiều phiên bản mô tả dự án theo các hướng (Backend, Frontend, Fullstack...) để copy-paste sửa nhẹ.
   - *Rule:* Trích xuất từ khóa bằng regex / text matching giữa CV và JD.
   - *Workflow:* Hệ thống trích xuất yêu cầu JD, map với dự án thật trong CV master, gợi ý viết lại mô tả theo keyword của JD và **bắt buộc người dùng duyệt từng dòng** (Human-in-the-loop).
   - *Agent:* Tự động viết lại và tự nộp CV (đây là rủi ro và nhóm đặt boundary cấm).
4. **Domain gần gũi, thuận lợi cho CP4:** Cả 3 thành viên và bạn học trong lớp đều đang là sinh viên năm cuối chuẩn bị xin việc, có thể phỏng vấn người thật (The Mom Test) để thu thập dữ liệu kiểm chứng ngay trong buổi học mà không phải phỏng vấn giả định.

**Vì sao loại các candidate còn lại:**
- **Loại Candidate #6 (Barem & quy cách nộp lab AI20K):** Dù đây là nỗi đau thật (đã từng bị trừ 5 điểm) và quy trình rất rõ, nhưng bản chất bài toán là logic cố định (deterministic rule) — chỉ cần một shell script bash hoặc checklist cố định là giải quyết được 95% vấn đề. Không có bài toán về ngôn ngữ hay độ mơ hồ để cần đến mức can thiệp Workflow/AI. Nếu chọn bài này, ở CP5–CP6 sẽ bị gượng ép khi đưa AI vào một bài toán mà Rule làm tốt hơn.
- **Loại Candidate #2 (Lọc tin tuyển dụng Intern/Fresher):** Các nền tảng tuyển dụng lớn (TopCV, ITviec, LinkedIn) đều đã có sẵn bộ lọc theo cấp độ/địa điểm và tính năng Job Alert gửi email hằng ngày (No AI). Điểm nghẽn nằm ở các bài đăng không cấu trúc trên Facebook group, nhưng việc thu thập dữ liệu này vướng rào cản kỹ thuật và pháp lý (scraping, API hạn chế), khó triển khai kiểm chứng thực tế trong thời gian lab.

**Xử lý bất đồng (nếu có):**
- Hải ban đầu muốn chọn bài Barem nộp lab (#6) vì bài học bị trừ 5 điểm ở bài lab trước còn rất mới và muốn có giải pháp dứt điểm. Tuy nhiên, sau khi cả nhóm thảo luận tiêu chí "So sánh được 4 mức", Hải nhận thấy một script bash chạy local đã đủ giải quyết bài này và nhóm không nên "dùng dao mổ trâu để giết gà". Hải đồng ý chuyển sang chọn bài Chỉnh CV (#1) và đề xuất viết script kiểm barem lab như một công cụ nội bộ riêng của nhóm.
- Tài muốn giải bài toán Luyện phỏng vấn (#7, #8) vì thấy nhiều bạn gặp khó khăn khi trả lời câu hỏi hành vi. Nhưng Nhài và Hải phân tích: phỏng vấn cần xử lý âm thanh/video hoặc ngữ cảnh giao tiếp phức tạp, tiêu chí "câu trả lời hay" có độ mơ hồ quá cao để đánh giá trong phạm vi lab. Cả nhóm thống nhất: vượt qua vòng lọc hồ sơ (CV) là điều kiện tiên quyết trước khi đến vòng phỏng vấn, do đó giải quyết khâu CV (#1) là bước đi cấp thiết và vừa sức hơn. Tài hoàn toàn nhất trí.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Sinh viên IT khác (không chỉ mình Nhài) cũng mất trên 20 phút/CV để viết lại mô tả cho khớp JD | Value | 5 | 2 | ✅ |
| 2 | Bước tốn thời gian nhất là viết lại mô tả dự án cho khớp từ khóa JD, không phải khâu tìm việc hay lọc tin | Value | 5 | 2 | ✅ |
| 3 | Người dùng đã thử workaround (CV master / copy từ khóa JD / tool có sẵn) và vẫn thấy chưa đủ | Value / Feasibility | 4 | 1 | ✅ |
| 4 | AI gợi ý viết lại tiết kiệm thời gian nhiều hơn thời gian người dùng phải duyệt lại | Value / Usability | 4 | 1 | ✅ |
| 5 | Trích xuất yêu cầu/từ khóa từ JD đủ đáng tin (text/regex/AI) | Feasibility | 4 | 3 | — |
| 6 | Thị trường đã có công cụ làm việc này (Jobscan, Teal) nên không nên tự xây từ đầu | Feasibility / Viability | 4 | 4 | — |

Giả định nhóm kiểm chứng trong buổi này: **#1, #2, #3, #4** (quan trọng cao nhưng ít bằng chứng).

### 3.2. Kiểm chứng


Cách đã dùng: **Phỏng vấn nhanh 3 người (The Mom Test) + micro survey/poll 5–10 người trong lớp.**

> File hỗ trợ: bộ câu hỏi `report/assets/cp4-poll-cau-hoi.md` · mẫu snapshot `report/assets/cp4-interview-snapshot-template.md` · tin nhắn mời + poll `report/assets/cp4-tin-nhan-va-poll.md`.

- Đối tượng phỏng vấn: 2 bạn cùng lớp đang tìm Intern/Fresher IT + 1 anh/chị khóa trên đã đi làm. **Không phỏng vấn thành viên nhóm mình.**
- Nguyên tắc: hỏi về **chuyện đã xảy ra** và **cách họ đang xử lý**, tuyệt đối không hỏi dạng "Bạn có muốn…".

**Bộ câu hỏi phỏng vấn (The Mom Test):**

1. Lần gần nhất bạn chỉnh CV để ứng tuyển một vị trí là khi nào? Kể lại từng bước bạn đã làm.
2. Bước nào mất nhiều thời gian nhất? Khoảng bao lâu?
3. Bạn đã thử cách nào để CV khớp JD chưa (CV master, copy từ khóa, dùng tool)? Kết quả thế nào?
4. Bạn có đối chiếu CV với JD trước khi nộp không? Bằng cách nào?
5. Sau khi nộp, bạn có nhận được phản hồi nào không?

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | _(điền)_ |
| Câu nói đáng nhớ nhất (nguyên văn) | _(điền)_ |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | _(điền)_ |
| Hiện đang xử lý bằng cách nào (workaround)? | _(điền)_ |
| Mất bao lâu, bao lần? | _(điền)_ |
| Insight / opportunity rút ra | _(điền)_ |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn | _(3)_ | _(điền)_ | _(điền)_ |
| Poll trong lớp | _(5–10)_ | _(điền)_ | _(điền)_ |

**Nhóm đã sửa problem thế nào sau kiểm chứng:** _(điền sau khi có kết quả — ví dụ: thu hẹp actor, đổi metric, hoặc hạ mức can thiệp nếu workaround No AI đã đủ)_

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| **Jobscan** — ATS Resume Matcher | https://www.jobscan.co/resume-matcher | Bước 1+2: đọc JD, đối chiếu CV với JD, chỉ ra hard/soft skills còn thiếu | Có Match Score theo từng vị trí; quét 30+ tiêu chí; bản scan miễn phí; có AI Optimize | "AI Optimize"/"Predicted Skills" có thể thêm từ khóa không có thật trong kinh nghiệm; optimize là tính năng trả phí; chỉ tối ưu cho ATS, không đảm bảo nội dung đúng | Phần đối chiếu từ khóa đã có tool làm tốt → dùng để **gợi ý**, con người phải **duyệt từng từ khóa** |
| **Teal** — Resume Job Description Match | https://www.tealhq.com/tool/resume-job-description-match | Bước 2+3: so CV với JD ra Match Score, đánh dấu từ khóa Xanh/Vàng/Đỏ, gợi ý bullet | Trực quan (green/yellow/red); AI gợi ý bullet theo hành động; có bản free | AI bullet "có thể chứa số liệu giả định" (Teal tự cảnh báo); nhiều tính năng cần Teal+; chỉ xuất PDF | Đúng hướng **Workflow + người duyệt**: AI gợi ý, người sửa và xác nhận |
| **Pattern "CV master + bật/tắt bullet theo JD"** (No AI) | https://help.tealhq.com/en/articles/14435726-how-to-tailor-your-resume-for-a-specific-job | Bước 3: thay vì viết lại từ đầu, dựng 1 CV master rồi bật/tắt bullet phù hợp cho từng JD | Không cần AI; nhanh nếu CV master đủ; kiểm soát hoàn toàn nội dung | Mỗi JD "lạ" vẫn phải viết mới; CV master tốn công dựng ban đầu | Đây là **phương án No AI** cần kiểm chứng trước khi kết luận cần AI |

**Kết luận research:** bài toán "đối chiếu CV ↔ JD" đã có tool làm sẵn, **không nên tự xây từ đầu**. Hướng hợp lý: **Rule** trích từ khóa JD → **AI gợi ý** viết lại mô tả → **con người duyệt** → nộp. Điểm khác biệt so với tool có sẵn là nhấn mạnh bước người duyệt để tránh AI bịa kinh nghiệm.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text

```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |

**Bottleneck chính:**

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text

```

### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | | | |
| Tổng thời gian | | | |
| Số bước thủ công | | | |
| Bottleneck chính | | | |
| Rủi ro mới phát sinh | | | |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

-

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô:

Vì sao:

### 6.2. So sánh 4 mức

| Mức | Phương án cho bài của nhóm | Đủ khi nào | Rủi ro | Chọn? |
|---|---|---|---|---|
| **No AI** (sửa quy trình) | | | | |
| **Rule** | | | | |
| **Workflow** | | | | |
| **Agent** | | | | |

**Mức chọn:**

**Vì sao không chọn mức đơn giản hơn:**

### 6.3. AI Canvas rút gọn

| Thành phần | Nội dung |
|---|---|
| **Prediction** — AI dự đoán / tạo ra gì? | |
| **Judgment** — con người cân nhắc, quyết định gì? | |
| **Action** — hành động cuối cùng là gì, ai làm? | |
| **Outcome** — đo kết quả bằng gì? | |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | |
| **Feedback** — lấy phản hồi ở đâu để cải thiện? | |

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng:
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào:

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường | Nội dung |
|---|---|
| **Actor** | |
| **Quy trình** | |
| **Bottleneck** | |
| **Impact** | |
| **Success Metric** (baseline → target, cách đo) | |
| **Boundary** | |
| **AI intervention point** | |
| **Mức chọn** | No AI / Rule / Workflow / Agent |
| **Rủi ro & người kiểm tra** | |

**Thay đổi so với v0 và lý do:**

| Trường | v0 | v1 | Vì sao đổi |
|---|---|---|---|
| | | | |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

| # | Tiêu chí | Đạt khi | Không đạt khi |
|---:|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro | Câu hỏi | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng |
|---|---|---|---|
| **Value** | Người dùng có thật sự cần và sẽ dùng không? | | |
| **Usability** | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | | |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không? | | |
| **Viability** | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành? | | |

### 8.2. Kết luận

**Quyết định:** Go / Not Yet / No-Go

**Lý do:**

**Nếu Go — pilot nhỏ nhất:**

**Nếu Not Yet — cần kiểm chứng gì trước:**

**Nếu No-Go — nên làm gì thay AI:**

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

---

## 9. Hạn chế và hướng tiếp theo

-

## 10. Tài liệu tham khảo

-
