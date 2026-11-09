# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: A2
- Thành viên: xem `TEAM.md`
- Candidate problem được chọn (1 câu): *[điền sau khi nhóm hội tụ xong CP3]*
- Quyết định cuối: *[điền sau CP6]*

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

> Mẫu dòng 1–3 là của Phạm Nguyên Khoa (đã điền sẵn làm ví dụ). Các dòng 4–9 (hoặc tới 12 nếu nhóm đông hơn) do 2 thành viên còn lại tự điền từ Problem Card của họ khi pitch thật trong buổi lab — không điền thay nhau.

| # | Người đưa ra | Candidate (Job Story ngắn) | Actor | Bottleneck | Câu hỏi phản biện nhận được (ai hỏi) |
|---:|---|---|---|---|---|
| 1 | Phạm Nguyên Khoa | Khi khách hàng nhắn hỏi giá/size/màu/ship, tôi muốn trả lời nhanh mà không gõ lại nhiều lần, để không bỏ lỡ khách | Người bán hàng online nhỏ lẻ | Tra lại thông tin sản phẩm (chưa đo thời gian) | *[điền khi pitch thật]* |
| 2 | Phạm Nguyên Khoa | Khi tìm việc làm thêm/thực tập, tôi muốn tổng hợp tin tuyển dụng phù hợp tại một nơi, để không mất thời gian tìm trên nhiều nguồn | Sinh viên, người mới đi làm | Chuyển qua lại giữa 4–5 nguồn, lọc lại từ đầu mỗi lần (chưa đo thời gian) | *[điền khi pitch thật]* |
| 3 | Phạm Nguyên Khoa | Khi ứng tuyển nhiều công ty, tôi muốn đối chiếu CV với JD và biết cần bổ sung gì, để tiết kiệm thời gian chỉnh sửa hồ sơ | Sinh viên mới tốt nghiệp, người đang tìm việc | Đối chiếu từng yêu cầu JD với CV (chưa đo thời gian) | *[điền khi pitch thật]* |
| 4 | Ngô Chí Vĩnh | Khi bắt đầu một bài lab mới, tôi muốn biết mỗi checkpoint phải làm gì, ghi vào file nào và chấm theo tiêu chí nào, để không phải mở đi mở lại nhiều file đề | Học viên K5 lúc mới nhận đề lab | Ghép thông tin giữa 6–9 file đề (khoảng 8 trong 30 phút đọc đề) | *[điền khi pitch thật]* |
| 5 | Ngô Chí Vĩnh | Khi sắp tới hạn nộp lab, lab coach muốn học viên tự kiểm tra được tên repo, tên file và cách nộp, để không phải trả lời lặp lại cùng một câu hỏi | Lab coach (người trả lời), học viên sắp nộp (người hỏi) | Coach trả lời lại cùng câu hỏi: khoảng 3 phút/lần × 30–40 lần trên Discord | *[điền khi pitch thật]* |
| 6 | Ngô Chí Vĩnh | Khi làm bài lab trong buổi học, tôi muốn hoàn thành trong thời gian buổi lab, để không phải làm thêm buổi tối và không trễ deadline | Học viên K5 làm lab có phần code | Tự code tay: khoảng 180 trong 360 phút (lab 6 giờ, buổi học 4 giờ) | *[điền khi pitch thật]* |
| 7 | Nguyễn Ngọc Ninh |Khi đến cuối tuần, tôi muốn có danh sách deadline và task còn lại ở một nơi, để nộp đúng hạn mà không bỏ sót việc quan trọng |Sinh viên làm việc nhóm | Tổng hợp và đối chiếu nhiều nguồn dữ liệu|“Nên tập trung vào deadline hay cảnh báo trễ sớm hơn?” (thành viên nhóm) |
| 8 | Nguyễn Ngọc Ninh |Khi cần tìm tài liệu, note hoặc file nhóm trên LMS/Drive/Slack, tôi muốn tìm đúng phiên bản và định dạng, để không mất công đọc lại từ đầu |Sinh viên, nhóm học tập |Tìm đúng file và xác định phiên bản phù hợp |“AI có cần thiết hay chỉ cần quy tắc đặt tên?” (thành viên nhóm) |
| 9 | Nguyễn Ngọc Ninh | Khi muốn đặt câu hỏi cho giảng viên hoặc mentor, tôi muốn suy nghĩ và đưa ra câu hỏi ngắn gọn, đúng trọng tâm, để không làm mất thời gian của người khác|Sinh viên, trợ giảng, giảng viên |Lọc vấn đề và viết câu hỏi đúng trọng tâm |“Vấn đề này có đủ impact để chọn làm candidate chính?” (thành viên nhóm) |

### 2.2. Cluster

| Cluster | Các candidate | Pattern chung |
|---|---|---|
| A | | |
| B | | |
| C | | |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: 
├── Opportunity A: 
├── Opportunity B: 
└── Opportunity C: 
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

-

### 2.4. Chấm điểm shortlist (1–5)

| Candidate | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain | Tổng |
|---|---:|---:|---:|---:|---:|---:|---:|---:|
| | | | | | | | | |
| | | | | | | | | |
| | | | | | | | | |

**Candidate được chọn:**

**Vì sao chọn:**

**Vì sao loại các candidate còn lại:**

**Xử lý bất đồng (nếu có):**

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

| # | Giả định | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước? |
|---:|---|---|---:|---:|---|
| 1 | | | | | |
| 2 | | | | | |
| 3 | | | | | |
| 4 | | | | | |
| 5 | | | | | |
| 6 | | | | | |

*Điền 4–6 giả định; xóa dòng thừa.*

Giả định nhóm kiểm chứng trong buổi này:

### 3.2. Kiểm chứng

Cách đã dùng: Phỏng vấn / Survey / Log, ticket, review

Interview snapshot (mỗi buổi phỏng vấn một bảng, hoặc đặt file trong `report/assets/cp4-interview-snapshot-N.md`):

| Trường | Nội dung |
|---|---|
| Người được hỏi (vai trò, không ghi tên thật) | |
| Câu nói đáng nhớ nhất (nguyên văn) | |
| Lần gần nhất gặp vấn đề này: chuyện gì đã xảy ra? | |
| Hiện đang xử lý bằng cách nào (workaround)? | |
| Mất bao lâu, bao lần? | |
| Insight / opportunity rút ra | |

Tổng hợp:

| Nguồn | Số người / số mẫu | Tín hiệu xác nhận | Tín hiệu phản bác |
|---|---:|---|---|
| | | | |

**Nhóm đã sửa problem thế nào sau kiểm chứng:**

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern | Link | Giải bước nào trong quy trình? | Điểm mạnh | Khoảng trống / rủi ro | Bài học cho nhóm |
|---|---|---|---|---|---|
| | | | | | |
| | | | | | |
| | | | | | |

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
