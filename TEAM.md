# Team

> Điền file này trên repo chung do nhóm trưởng fork. Nhóm điền phần **Thông tin nhóm** và **Thành viên**. Mỗi người tự điền phần của mình trong **Cá nhân**. Không copy file này sang repo khác.

## Thông tin nhóm

- Tên nhóm: A2
- Candidate problem nhóm chọn (1 câu): Lab coach phải trả lời lặp lại câu hỏi về cách nộp bài (tên repo, tên file, cách nộp) trước mỗi hạn deadline
- Quyết định cuối (Go / Not Yet / No-Go): Not Yet (No AI ưu tiên thử trước)

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Phạm Nguyên Khoa | 2A202603795 | Điều phối, viết Problem Statement | Neronmen |
| 2 | Nguyễn Ngọc Ninh | 2A202603774 | Kiểm chứng (phỏng vấn), hỗ trợ Problem Statement v0 | *[Ninh tự điền]* |
| 3 | Ngô Chí Vĩnh | 2A202603724 | Research giải pháp đã có, Assumption Map, bộ câu hỏi phỏng vấn | NgChiVinh |


Không ghi email hay số điện thoại vào bảng này, vì repo có thể để public.

Gợi ý vai trò (một người có thể giữ nhiều vai): điều phối thời gian, ghi chép, người phản biện chính, phụ trách kiểm chứng (phỏng vấn/survey), phụ trách research, vẽ quy trình, viết Problem Statement.

## Phân công theo checkpoint

| Checkpoint | Người chính | Người hỗ trợ | Sản phẩm |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Khoa (điều phối) | Cả nhóm | Cluster, cây OST, bảng chấm điểm |
| CP4 — Kiểm chứng | Ninh | Cả nhóm | Assumption map, snapshot hoặc survey |
| CP4 — Research | Vĩnh | Cả nhóm | Bảng research có link |
| CP5 — Quy trình trước/sau | Vĩnh | Khoa | Quy trình + bảng before/after |
| CP5 — Problem Statement v0 | Khoa | Ninh | Problem Statement v0 |
| CP6 — Mức can thiệp + Problem Statement v1 | Khoa | Cả nhóm | Ma trận, AI Canvas, eval, Problem Statement v1 |
| CP6 — Quyết định | Cả nhóm | — | 4 rủi ro + Go/Not Yet/No-Go |

## Cá nhân

Mỗi thành viên thêm một mục theo mẫu dưới đây, tiêu đề là `HoVaTen-MSSV`.

### HoVaTen-MSSV

**Phần việc phụ trách:**

-

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

-

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

-

**Điều mình học được từ phần nhóm:**


### PhamNguyenKhoa-2A202603795

**Phần việc phụ trách:**

- Điều phối nhóm, gom cluster/cây OST, chấm điểm chọn candidate, viết Problem Statement v0/v1, lập ma trận mức can thiệp AI

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Tổng hợp 9 candidate của cả nhóm thành 3 cluster và cây OST (mục 2.2–2.3)
- Lập bảng chấm điểm shortlist và chốt candidate #5 (mục 2.4)
- Viết Problem Statement v0 (mục 5) và v1 kèm tiêu chí đánh giá (mục 7)
- Lập ma trận độ mơ hồ × độ phức tạp, so sánh 4 mức can thiệp AI, chốt chọn No AI (mục 6)

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- `report/team/group_report.md` mục 2, 5, 6, 7; commit `0834264`, `08a5e74`
- File cá nhân: `report/individual/2A202603795_PhamNguyenKhoa.md`

**Điều mình học được từ phần nhóm:**

- Baseline chưa đo được thì phải ghi rõ "Chưa đo – cần xác minh" thay vì ước lượng cho có số liệu
- Mức can thiệp AI nên chọn từ thấp lên cao, không mặc định chọn AI ngay từ đầu

### NgoChiVinh-2A202603724

**Phần việc phụ trách:**

- Đưa ra candidate được nhóm chọn (card #5: lab coach bị hỏi lặp lại về cách nộp bài).
- CP4: Assumption Map, bộ câu hỏi phỏng vấn theo The Mom Test, research giải pháp đã có.

**Đóng góp cụ thể** (mình đã làm gì, ra sản phẩm gì):

- Pitch 3 Problem Card (dòng 4–6 bảng pitch); card #5 được chọn làm candidate của nhóm.
- Soạn Assumption Map 5 giả định (mục 3.1 `group_report.md`) và bộ câu hỏi phỏng vấn lab coach, học viên, cách đếm log Discord (`report/assets/cp4-interview-guide.md`).
- Làm bảng research 3.3 với 3 nguồn đã kiểm link (Zendesk Macros, Discord Forum Channels, Jill Watson) và phần kết luận research; thay nguồn GitHub Classroom vì không khớp với bài.
- Viết mục "Nhóm đã sửa problem thế nào sau kiểm chứng": đề xuất giữ actor lab coach dù kết quả phỏng vấn phản bác giả định về pain.

**Bằng chứng** (phần nào trong `group_report.md`, file nào trong `report/assets/`, commit nào):

- Bảng pitch dòng 4–6: commit `7a450a0`.
- Assumption Map (mục 3.1) và `report/assets/cp4-interview-guide.md`: commit `24d9b1e`.
- Mục "Nhóm đã sửa problem…" và research 3.3: commit `2c0dc21`, `38a7e1f`.
- Báo cáo cá nhân CP1–CP2: commit `dbc9c1b`.

**Điều mình học được từ phần nhóm:**

- [?]
