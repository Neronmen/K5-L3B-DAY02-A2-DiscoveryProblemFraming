# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: A2
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): Lab coach phải trả lời lặp lại câu hỏi về cách nộp bài (tên repo, tên file, cách nộp) trước mỗi hạn deadline
- Quyết định cuối: *[điền sau CP6]*

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Phạm Nguyên Khoa | Khi khách hàng nhắn hỏi giá/size/màu/ship, tôi muốn trả lời nhanh mà không gõ lại nhiều lần, để không bỏ lỡ khách | Người bán hàng online nhỏ lẻ | Tra lại thông tin sản phẩm (chưa đo thời gian) | *[điền khi pitch thật]* |
| 2 | Phạm Nguyên Khoa | Khi tìm việc làm thêm/thực tập, tôi muốn tổng hợp tin tuyển dụng phù hợp tại một nơi, để không mất thời gian tìm trên nhiều nguồn | Sinh viên, người mới đi làm | Chuyển qua lại giữa 4–5 nguồn, lọc lại từ đầu mỗi lần (chưa đo thời gian) | *[điền khi pitch thật]* |
| 3 | Phạm Nguyên Khoa | Khi ứng tuyển nhiều công ty, tôi muốn đối chiếu CV với JD và biết cần bổ sung gì, để tiết kiệm thời gian chỉnh sửa hồ sơ | Sinh viên mới tốt nghiệp, người đang tìm việc | Đối chiếu từng yêu cầu JD với CV (chưa đo thời gian) | *[điền khi pitch thật]* |
| 4 | Ngô Chí Vĩnh | Khi bắt đầu một bài lab mới, tôi muốn biết mỗi checkpoint phải làm gì, ghi vào file nào và chấm theo tiêu chí nào, để không phải mở đi mở lại nhiều file đề | Học viên K5 lúc mới nhận đề lab | Ghép thông tin giữa 6–9 file đề (~8/30 phút đọc đề) | *[điền khi pitch thật]* |
| 5 | Ngô Chí Vĩnh | Khi sắp tới hạn nộp lab, lab coach muốn học viên tự kiểm tra được tên repo, tên file và cách nộp, để không phải trả lời lặp lại cùng một câu hỏi | Lab coach (người trả lời), học viên sắp nộp (người hỏi) | Coach trả lời lại cùng câu hỏi: ~3 phút/lần × 30–40 lần trên Discord | *[điền khi pitch thật]* |
| 6 | Ngô Chí Vĩnh | Khi làm bài lab trong buổi học, tôi muốn hoàn thành trong thời gian buổi lab, để không phải làm thêm buổi tối và không trễ deadline | Học viên K5 làm lab có phần code | Tự code tay: ~180/360 phút (lab 6 giờ, buổi học 4 giờ) | *[điền khi pitch thật]* |
| 7 | Nguyễn Ngọc Ninh | Khi đến cuối tuần, tôi muốn có danh sách deadline và task còn lại ở một nơi, để nộp đúng hạn mà không bỏ sót việc quan trọng | Sinh viên làm việc nhóm | Tổng hợp và đối chiếu nhiều nguồn dữ liệu | "Nên tập trung vào deadline hay cảnh báo trễ sớm hơn?" (thành viên nhóm) |
| 8 | Nguyễn Ngọc Ninh | Khi cần tìm tài liệu, note hoặc file nhóm trên LMS/Drive/Slack, tôi muốn tìm đúng phiên bản và định dạng, để không mất công đọc lại từ đầu | Sinh viên, nhóm học tập | Tìm đúng file và xác định phiên bản phù hợp | "AI có cần thiết hay chỉ cần quy tắc đặt tên?" (thành viên nhóm) |
| 9 | Nguyễn Ngọc Ninh | Khi muốn đặt câu hỏi cho giảng viên hoặc mentor, tôi muốn suy nghĩ và đưa ra câu hỏi ngắn gọn, đúng trọng tâm, để không làm mất thời gian của người khác | Sinh viên, trợ giảng, giảng viên | Lọc vấn đề và viết câu hỏi đúng trọng tâm | "Vấn đề này có đủ impact để chọn làm candidate chính?" (thành viên nhóm) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | #2, #4, #7, #8 | Thông tin cần dùng (tin tuyển dụng, file đề lab, deadline/task, tài liệu nhóm) nằm rải rác ở nhiều nguồn/file khác nhau, không có một nơi tổng hợp duy nhất |
| B | #1, #5 | Phải trả lời lặp lại cùng một loại câu hỏi cho nhiều người khác nhau (khách hàng hỏi giá/ship; học viên hỏi coach cách nộp bài) |
| C | #3, #9 | Cần đối chiếu hoặc chọn lọc nội dung của chính mình theo đúng yêu cầu/trọng tâm trước khi gửi đi (CV so với JD; câu hỏi so với vấn đề thật) |
| — (chưa gom) | #6 | Hoàn thành lab trong thời gian buổi học — đây là pain về khối lượng công việc/thời gian code, không phải tìm kiếm hay trả lời thông tin, nên tạm để riêng, không ép vào cluster nào |

> *Ghi chú: đây là cách gom dựa trên đọc lại 9 candidate — khi nhóm họp thật, mỗi người nói lại cảm nhận của mình, có thể gom khác đi (ví dụ #6 có thể nhập vào cluster A nếu nhóm thấy "thiếu thời gian" cũng là một dạng "thiếu tổng hợp thông tin kế hoạch").*

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian học viên/người dùng mất vào việc tìm kiếm, tổng hợp hoặc trả lời
         thông tin lặp lại đang nằm rải rác ở nhiều nguồn
├── Opportunity A: Thông tin cần dùng (tin tuyển dụng, file đề lab, deadline, tài liệu
│                   nhóm) nằm rải rác nhiều nơi, không có chỗ tổng hợp duy nhất
├── Opportunity B: Phải trả lời lặp lại cùng một câu hỏi cho nhiều người khác nhau
└── Opportunity C: Cần tự đối chiếu/chọn lọc nội dung của mình theo đúng yêu cầu
                    trước khi gửi hoặc nộp
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- Không có ý nào trong 9 candidate viết thẳng tên công cụ hay chữ "AI" vào mô tả vấn đề — cả 9 đều ở dạng Job Story đúng chuẩn. Riêng câu hỏi phản biện của #8 ("AI có cần thiết hay chỉ cần quy tắc đặt tên?") là câu hỏi tốt, nhắc nhóm cẩn thận không nhảy sang giải pháp AI quá sớm khi bàn Opportunity A.
- Candidate #6 (hoàn thành lab trong giờ) tạm **không đưa vào cây** vì là vấn đề khối lượng/thời gian, không cùng nhóm "tìm kiếm – tổng hợp – trả lời thông tin" với outcome đang chọn.

### 2.4. Chấm điểm shortlist (1–5)

> Shortlist 3 candidate dưới đây là **1 đại diện cho mỗi cluster ở mục 2.2** — chọn candidate có bằng chứng/quy trình rõ nhất trong cluster đó, để nhóm dễ so sánh thay vì chấm hết cả 9.

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| #5 (cluster B) — Coach trả lời lặp lại câu hỏi nộp bài | 5 | 4 | 5 | 5 | 5 | 4 | 5 | **33** |
| #8 (cluster A) — Tìm đúng file/phiên bản tài liệu nhóm | 4 | 3 | 3 | 3 | 4 | 4 | 5 | 26 |
| #9 (cluster C) — Đặt câu hỏi đúng trọng tâm cho mentor | 4 | 3 | 2 | 2 | 3 | 3 | 5 | 22 |

*Thang điểm 1–5, 5 = tốt nhất. Đây là điểm mình chấm thử dựa trên dữ liệu đã có trong bảng pitch; khi họp thật, nhóm nên tự chấm lại theo cảm nhận của cả 3 người, có thể ra điểm khác.*

**Candidate được chọn:** #5 — "Khi sắp tới hạn nộp lab, lab coach muốn học viên tự kiểm tra được tên repo, tên file và cách nộp, để không phải trả lời lặp lại cùng một câu hỏi."

**Vì sao chọn:**
- Điểm tổng cao nhất (33/35), vượt hẳn 2 candidate còn lại.
- Là candidate **duy nhất trong 3 cái có số liệu cụ thể** ngay từ đầu (~3 phút/lần × 30–40 lần trên Discord) — gần với yêu cầu "bằng chứng là hành vi đã xảy ra" của The Mom Test nhất, dễ kiểm chứng thêm ở CP4.
- Actor rõ ràng ở cả 2 phía (lab coach — người trả lời, học viên — người hỏi), quy trình ngắn, vừa sức làm trong 1 buổi lab.
- Cả 3 thành viên đều là học viên K5 nên đều từng ở vị trí "người hỏi", dễ hiểu domain và dễ kiểm chứng chéo trong nhóm.

**Vì sao loại các candidate còn lại:**
- #8 (tìm tài liệu nhóm): actor và quy trình còn chung chung, chưa có số liệu cụ thể (mới ở mức mô tả), cần làm rõ thêm trước khi tin tưởng impact.
- #9 (đặt câu hỏi cho mentor): pain khó đo lường (thế nào là "câu hỏi đúng trọng tâm" mang tính chủ quan), impact không rõ, khó so sánh No AI/Rule/Workflow/Agent vì đây gần với kỹ năng cá nhân hơn là một quy trình có bước nghẽn cụ thể.
- Các candidate #1, #2, #3 (của Khoa, ngoài 3 cluster chính): domain cá nhân (bán hàng, tìm việc) ít người trong nhóm 3 K5 cùng trải nghiệm trực tiếp như #5, nên khó nhóm cùng hiểu domain và kiểm chứng chéo.
- #4, #6, #7 (cùng cluster A/khác với #6): #4 và #7 đã có #8 đại diện cho pattern "thông tin rải rác"; #6 là pain về khối lượng/thời gian, không cùng loại vấn đề "tìm kiếm – tổng hợp – trả lời thông tin" nên không đưa vào shortlist.

**Xử lý bất đồng (nếu có):** *[điền khi họp thật — ví dụ: nếu 1 bạn không đồng ý #5 vì nghĩ #8 có impact lớn hơn trong dài hạn, ghi lại lý do và cách nhóm thống nhất, hoặc ghi rõ ai bảo lưu ý kiến khác]*

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | Câu hỏi về cách đặt tên repo, tên file và cách nộp bài xuất hiện lặp lại nhiều lần trên Discord (khoảng 30–40 lần từ buổi lab đầu) | Value | 5 | 2 |  Đếm tin nhắn trên Discord |
| 2 | Lab coach thấy việc trả lời lặp lại những câu này là gánh nặng, lấy mất thời gian hỗ trợ phần nội dung bài | Value | 5 | 1 |  Phỏng vấn lab coach |
| 3 | Học viên đã tìm trong README hoặc SUBMISSION trước khi hỏi nhưng vẫn không chắc (vấn đề là khó tìm, khó hiểu, không phải không đọc) | Value / Usability | 4 | 2 |  Phỏng vấn học viên nhóm khác |
| 4 | Mọi câu trả lời cho nhóm câu hỏi này đều đã có sẵn trong tài liệu đề (README, SUBMISSION) | Feasibility | 4 | 4 | — Đã kiểm khi đọc đề |
| 5 | Lớp cho phép thay đổi cách hỗ trợ trên Discord (ghim FAQ, thêm kênh hỏi đáp riêng hoặc công cụ trả lời) | Viability | 3 | 1 | Hỏi lab coach  |



### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

**Snapshot #1 — Lab coach**

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | 1 lab coach trong khóa học |
| Câu nói đáng nhớ nhất (nguyên văn) |  coach nói là có bị hỏi nhiều, nhưng chấp nhận việc trả lời lặp lại vì đó là công việc của mình, không thấy cần một công cụ/giải pháp thay thế.
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | *[chưa hỏi chi tiết 1 tình huống cụ thể — có thể hỏi thêm nếu phỏng vấn lại]* |
| Hiện đang xử lý bằng cách nào (workaround)? | Tự trả lời tay từng câu hỏi trên Discord, coi đây là một phần trách nhiệm hỗ trợ học viên |
| Mất bao lâu, bao lần? | `Chưa đo – cần xác minh` — coach xác nhận định tính "có hỏi nhiều", nhưng chưa có con số cụ thể (số lần/tuần, số phút/lần) |
| Insight / opportunity rút ra | Coach xác nhận **có bị hỏi nhiều** (ủng hộ giả định #1), nhưng nói thẳng **"nó không cần thiết"** khi được hỏi về việc có cần một giải pháp/công cụ hỗ trợ hay không — coach chấp nhận trả lời lặp lại là một phần công việc, không chủ động thấy đây là nỗi đau cần giải quyết (phản bác giả định #2 và #5). → Opportunity có thể cần đổi hướng: không phải "giúp coach bớt việc", mà nên hỏi thêm **phía học viên** xem họ có thấy mất thời gian khi phải chờ/hỏi lại không — vì đó mới là actor còn lại chưa được xác nhận |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| Phỏng vấn lab coach | 1 | Coach xác nhận **có bị hỏi lặp lại nhiều** (ủng hộ giả định #1 — tần suất thật có) | Coach nói **"không cần thiết"** phải có giải pháp — chấp nhận trả lời lặp lại là trách nhiệm công việc, không thấy đây là vấn đề cần giải quyết (phản bác giả định #2 và #5: coach không chủ động muốn thay đổi cách hỗ trợ) |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

- Nhóm **giữ nguyên actor lab coach** và giữ nguyên candidate. Nhóm không đổi problem cho "đẹp" hơn, mà đi tiếp với bằng chứng thật dù bằng chứng đang phản bác.
- Kiểm chứng xác nhận phần **tần suất** (giả định #1: coach có bị hỏi lặp lại nhiều), nhưng phản bác phần **pain** (giả định #2: coach không coi đó là gánh nặng) và phần **sẵn sàng thay đổi** (giả định #5).
- Hệ quả: rủi ro **Value** của bài đang ở mức Cao. Nhóm chấp nhận khả năng kết luận cuối là **No-Go hoặc No AI**, và sẽ dùng CP5–CP6 để lập luận cho kết luận đó.
- Hướng có thể mở rộng sau (chưa làm trong buổi này): pain có thể nằm ở phía **học viên** (người hỏi, phải tìm lại trong nhiều file đề và chờ trả lời). Giả định #3 vẫn chưa được kiểm chứng.
- **Bài học về cách hỏi:** câu "coach có cần công cụ hay giải pháp không" là câu hỏi về ý tưởng, loại The Mom Test khuyên tránh. Bằng chứng mạnh hơn là **hành vi**: coach vẫn tự trả lời tay và chưa từng thử cách nào để giảm số câu hỏi.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| Zendesk Macros (câu trả lời soạn sẵn cho câu hỏi lặp lại) | https://support.zendesk.com/hc/en-us/articles/4408844187034-Creating-macros-for-repetitive-ticket-responses-and-actions | Bước coach gõ tay câu trả lời: nhân viên hỗ trợ lưu sẵn câu trả lời cho các vấn đề lặp lại rồi áp dụng khi cần, có placeholder để cá nhân hóa | Đúng pattern của bài: Zendesk viết rằng macro *"saves agents the time and effort of manually responding to multiple customers with the same issue"*; có macro cá nhân và macro dùng chung | Zendesk là công cụ trả phí cho bộ phận chăm sóc khách hàng, không dùng trực tiếp trên Discord; người trả lời vẫn phải đọc câu hỏi và chọn đúng câu trả lời | Pattern **No AI / Rule**: coach chỉ cần một file câu trả lời soạn sẵn để copy, hoặc một tin nhắn ghim để gửi link. Không cần AI, và vẫn giữ người trả lời trong vòng lặp |
| Discord Forum Channels | https://discord.com/blog/forum-channels-space-for-organized-conversation | Bước tìm câu trả lời trước khi hỏi: mỗi chủ đề là một post riêng, có Post Guidelines hiện ra khi tạo post mới, có tag và thanh tìm kiếm để xem các post cũ | Có sẵn trong Discord, không phải xây gì; câu đã trả lời không bị trôi như trong kênh chat thường | Học viên vẫn phải chủ động tìm trước khi hỏi; cần coach hoặc admin server tạo kênh và gắn tag; coach đã nói không thấy cần thay đổi | Phương án **No AI** rẻ nhất: gom các câu hỏi về cách nộp vào một chỗ tìm được. Cần kiểm xem học viên có thật sự tìm trước khi hỏi không |
| Jill Watson, trợ giảng AI ở Georgia Tech | https://provost.gatech.edu/news/artificial-intelligence-course-creates-ai-teaching-assistant | Bước trả lời câu hỏi lặp lại: lớp khoảng 300 học viên, khoảng 10.000 tin nhắn trên diễn đàn mỗi khóa; Jill trả lời các câu thường gặp như "bài tập và tài liệu đọc ở đâu" | Học từ khoảng 40.000 bài đăng cũ; chỉ trả lời khi chắc chắn 97%; giai đoạn đầu trợ giảng người xem lại câu trả lời rồi mới đăng | Quy mô lớn hơn lớp mình rất nhiều; các tuần đầu trả lời sai, cần người duyệt; bài viết từ năm 2016 | Pattern **Workflow có người duyệt**: AI chỉ trả lời khi chắc chắn, còn lại chuyển cho người. Với lớp nhỏ và coach không thấy pain, mức này nhiều khả năng là **quá tay** |

**Kết luận research:**

```text
Bài toán "hỏi lặp lại về cách nộp" đã có lời giải ở nhiều mức:
- No AI / Rule: câu trả lời soạn sẵn (macro kiểu Zendesk) để coach không phải gõ lại từ đầu.
- No AI: Forum Channel trên Discord gom câu hỏi và câu trả lời vào một chỗ tìm được.
- Workflow có người duyệt: trợ giảng AI như Jill Watson, chỉ đáng làm khi lượng câu hỏi rất lớn.
Với lớp mình (coach không coi đây là pain và không muốn thay đổi cách hỗ trợ),
không có lý do để tự xây công cụ AI. Nếu làm gì thì chỉ nên ở mức đơn giản nhất: No AI hoặc Rule.
```

---
--

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ:

```text
HIỆN TẠI — tổng thời gian: Chưa đo

[1. Học viên vướng mắc về nộp bài] → [2. Hỏi trên kênh Discord]
   → [3. Coach dừng việc đang làm, đọc câu hỏi] → [4. Coach gõ trả lời tay]
   ← BOTTLENECK (lặp lại ~30–40 lần từ đầu khóa, mỗi lần làm gián đoạn việc khác)
   → [5. Học viên đọc, áp dụng, nộp bài]
```

| Bước | Actor | Input | Output | Thời gian / tần suất | Ghi chú |
|---:|---|---|---|---|---|
| 1 | Học viên | Đề bài (README/SUBMISSION) | Câu hỏi về tên repo/file/cách nộp | Trước mỗi hạn nộp | Xảy ra dù học viên đã đọc đề (giả định #3, chưa kiểm chứng trực tiếp với học viên) |
| 2 | Học viên | Câu hỏi | Tin nhắn trên Discord | ~30–40 lần từ đầu khóa (quan sát ban đầu) | Kênh hỏi đáp chung của lớp |
| 3 | Lab coach | Tin nhắn hỏi | Thời gian đọc + xử lý | `Chưa đo – cần xác minh` mỗi lần | Phải dừng việc hỗ trợ nội dung đang làm |
| 4 | Lab coach | Câu hỏi đã đọc | Câu trả lời bằng tay | `Chưa đo – cần xác minh` mỗi lần | Nội dung thường lặp lại câu đã trả lời trước đó cho người khác |
| 5 | Học viên | Câu trả lời của coach | Bài nộp đúng quy cách | Ngay sau khi coach trả lời | Có độ trễ nếu coach đang bận |

**Bottleneck chính:** Bước 3–4 — lab coach phải tự tay trả lời lặp lại cùng loại câu hỏi, không có nơi tổng hợp sẵn để học viên tự tra trước khi hỏi.

### 4.2. Quy trình tương lai

```text
TƯƠNG LAI — kỳ vọng giảm số lần cần hỏi trực tiếp coach

[1. Học viên vướng mắc] → [2. Tự tra FAQ/checklist cố định]  ← Rule (nội dung tĩnh,
                                                                  lấy từ README/SUBMISSION,
                                                                  coach duyệt trước khi đăng)
   → [3a. Đủ thông tin] → [Nộp bài]
   → [3b. Vẫn chưa rõ] → [4. Hỏi coach trên kênh Discord]  ← CON NGƯỜI (giữ nguyên,
                                                                 không giao cho AI quyết)
   → [5. Coach trả lời — chỉ còn câu hỏi thật sự mới/đặc biệt]

Boundary: FAQ/checklist KHÔNG tự thêm nội dung ngoài README/SUBMISSION đã được coach duyệt;
          KHÔNG tự xử lý trường hợp ngoại lệ (xin gia hạn, lỗi kỹ thuật, khiếu nại điểm)
          — những việc này luôn do coach quyết định trực tiếp.
Phương án quay về: nếu FAQ gây hiểu lầm hoặc học viên vẫn không tìm thấy câu trả lời,
                   quay lại hỏi trực tiếp coach như quy trình hiện tại — không có bước nào bị khoá cứng.
```



### 4.3. Before / after

| Chỉ số | Trước | Sau (kỳ vọng) | Ghi chú |
|---|---:|---:|---|
| Số bước | 5 | 5 (có nhánh rẽ) | Thêm bước tự tra FAQ, không bỏ bước nào của coach |
| Tổng thời gian | Chưa đo | Kỳ vọng giảm số lần cần đến bước 4–5 (coach trả lời) | Cần đo baseline thật trước khi cam kết con số |
| Số bước thủ công | 2 (bước 3, 4 — coach làm tay hoàn toàn) | 1 (chỉ còn bước 5, cho câu hỏi thật sự mới) | Bước 2 (tự tra FAQ) không cần coach can thiệp |
| Bottleneck chính | Coach trả lời lặp lại mọi câu hỏi | Coach chỉ xử lý câu hỏi đặc biệt — bottleneck còn lại là cập nhật FAQ kịp thời | Bottleneck chuyển từ "trả lời" sang "duy trì nội dung" |
| Rủi ro mới phát sinh | — | FAQ lỗi thời nếu đề bài đổi mà không cập nhật; học viên không biết có FAQ nên vẫn hỏi thẳng | Cần quy định ai cập nhật FAQ và khi nào |

---

## 5. Problem Statement v0 (CP5)

| Trường | Nội dung |
|---|---|
| **Actor** | Lab coach (người trả lời) và học viên K5 sắp tới hạn nộp bài (người hỏi) |
| **Quy trình** | Học viên vướng mắc về cách đặt tên repo/file/cách nộp bài → hỏi trực tiếp trên kênh Discord chung → lab coach dừng việc đang làm (hỗ trợ nội dung) để đọc và trả lời tay từng người |
| **Bottleneck** | Lab coach phải trả lời lặp lại cùng loại câu hỏi nhiều lần (~30–40 lần từ đầu khóa theo quan sát ban đầu), mỗi lần làm gián đoạn thời gian lẽ ra dành cho hỗ trợ nội dung bài |
| **Impact** | Lab coach mất thời gian cho việc lặp lại thay vì hỗ trợ chuyên môn; học viên phải chờ phản hồi mới chắc chắn nộp đúng, có nguy cơ trễ nếu coach đang bận |
| **Success Metric** (baseline → target, cách đo) | Metric: số lần học viên phải hỏi trực tiếp coach về cách nộp bài trên Discord. Baseline: `Chưa đo – cần xác minh` (hiện có quan sát định tính "có hỏi nhiều" từ phỏng vấn coach, chưa đếm chính xác). Target (đề xuất): giảm số câu hỏi loại này xuống còn dưới một nửa trong 2 tuần thử nghiệm có FAQ. Cách đo: đếm số tin nhắn hỏi về "cách nộp bài" trên kênh Discord trước và sau khi có FAQ |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | FAQ/checklist không tự thêm nội dung ngoài README/SUBMISSION đã được coach duyệt; không tự xử lý trường hợp ngoại lệ (xin gia hạn, lỗi kỹ thuật, khiếu nại điểm) — những việc này luôn cần coach (con người) quyết định trực tiếp |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- *(đóng vai PM hoài nghi)* Success Metric đang có baseline là `Chưa đo` — nếu nộp ở dạng này, chưa chứng minh được bottleneck thật sự lớn tới đâu. **Đồng ý một phần**: nhóm cần tranh thủ đếm lại lịch sử tin nhắn Discord thật (giả định #1 trong Assumption Map) trước khi chốt số liệu, nhưng do giới hạn thời gian buổi lab, tạm giữ nguyên baseline "Chưa đo – cần xác minh" và ghi rõ đây là việc cần làm tiếp.
- *(đóng vai PM hoài nghi)* Quy trình hiện tại mới chỉ có 1 nguồn phỏng vấn (1 lab coach) — Actor "học viên" (phía hỏi) chưa có dữ liệu xác nhận trực tiếp (giả định #3 chưa kiểm chứng). **Đồng ý**: đây là giới hạn đã ghi ở mục 9 (Hạn chế và hướng tiếp theo), nhóm nên phỏng vấn thêm 1–2 học viên nếu còn thời gian.

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
