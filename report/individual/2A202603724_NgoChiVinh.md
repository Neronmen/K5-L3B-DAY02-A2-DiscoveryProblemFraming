# Báo cáo cá nhân — 2A202603724_NgoChiVinh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Ngô Chí Vĩnh
- MSSV: 2A202603724
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: A2
- Link repo nhóm: https://github.com/Neronmen/K5-L3B-DAY02-A2-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi làm bài lab trong buổi học, tôi muốn hoàn thành đúng yêu cầu trong thời gian buổi lab, để không phải làm thêm buổi tối và không bị trễ deadline | Học viên, cả nhóm | Là việc tôi mất nhiều thời gian nhất tuần trước: lab buổi đầu mất khoảng 6 giờ, trong khi buổi lab chỉ có 4 giờ; phần lâu nhất là các phần tự code tay |
| 2 | Lặp lại | Khi tới giờ ăn trưa hoặc tối, tôi muốn nhanh chóng chốt được hôm nay ăn gì và đặt món, để không mất thời gian lướt app và phân vân | Bản thân, bạn đi ăn cùng | Mỗi lần mất khoảng 20 phút, 1 lần/ngày |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi bắt đầu một bài lab mới, tôi muốn biết mỗi checkpoint phải làm gì, ghi vào file nào và được chấm theo tiêu chí nào, để không phải mở đi mở lại nhiều file đề mới ghép được các thông tin đó | Học viên | Đề lab Day02 có 6 file ở thư mục gốc và 3 file trong `docs/`. Thông tin về cùng một việc nằm rải rác: tên repo ở README, deadline ở SUBMISSION, quy định dùng AI ở RULES, cách chấm ở RUBRIC. Tôi mất khoảng 30 phút để đọc và hiểu. |
| 4 | Pain từ người khác | Khi sắp tới hạn nộp lab, lab coach muốn học viên tự kiểm tra được tên repo, tên file và cách nộp, để không phải trả lời đi trả lời lại cùng một câu hỏi và còn thời gian hỗ trợ phần nội dung bài | Lab coach, học viên | Tôi thấy nhiều bạn hỏi lab coach cùng một câu về cách đặt tên và cách nộp. Ước lượng khoảng 30-40 lần từ buổi đầu làm lab, hỏi lab coach trong buổi kênh discord |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi chuẩn bị cho buổi học hoặc buổi lab tiếp theo, tôi muốn nắm lại ý chính của các buổi trước đang nằm rải rác ở slide, video bài giảng và ghi chú, để vào lớp theo kịp bài mà không phải xem lại từ đầu | Học viên | Mỗi lần ôn mất khoảng 30 phút. |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- Tôi tự scan trước được 4 ý (#1–#4), sau đó hỏi AI gợi ý thêm theo 4 lăng kính.
- Giữ lại #5 (ôn lại bài cũ từ nhiều nguồn: slide, video bài giảng, ghi chú).
- Bỏ các ý "tìm lại thông báo cũ trong group lớp" (trùng với #3 và #4, cùng là chuyện thông tin lớp học) và "theo dõi ai làm phần nào khi làm nhóm" (tôi chưa thấy đây là vấn đề thật).
- AI giúp tôi viết lại #1 cho rõ, vì ban đầu tôi chỉ ghi "làm lab vào buổi học đầu tiên", chưa nói rõ tình huống và kết quả mong muốn.
- Tôi tách #3 và #4 cho khỏi trùng nhau: #3 là cái khó của chính tôi khi đọc đề (thông tin nằm rải rác ở nhiều file), còn #4 là pain của lab coach khi phải trả lời lặp lại cùng một câu hỏi.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Đọc nhiều file đề lab để biết phải làm gì (#3) | Lặp lại mỗi lab, quy trình vẽ được rõ (đọc từng file rồi ghép lại), có baseline 30 phút, cả lớp đều gặp | `CHECKPOINTS.md` đã có bảng tóm tắt "CP – ghi vào đâu", nên pain có thể chỉ nằm ở bước ghép với RUBRIC; 30 phút mới là ước lượng của 1 lần |
| 2 | Lab coach bị hỏi lặp lại về cách đặt tên và cách nộp (#4) | Nhiều người cùng gặp (khoảng 30–40 lần), có bằng chứng kiểm lại được trên kênh Discord, impact cho cả coach và học viên | Con số 30–40 là ước lượng, cần đếm lại; chưa hỏi lab coach xem họ có thấy đây là pain không |
| 3 | Làm lab mất 6 giờ trong khi buổi học có 4 giờ (#1) | Pain lớn nhất của tôi, vượt 2 giờ so với thời lượng buổi lab | Còn rộng: "tự code tay" chưa tách được bước nghẽn cụ thể; có thể do kiến thức nền chứ không do quy trình |

Bỏ #2 (chọn món ăn) vì khó vẽ quy trình và impact nhỏ. #5 (ôn bài) giữ làm dự phòng.

### Problem Card #1 — Đọc đề lab nhiều file

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu một bài lab mới, tôi muốn biết mỗi checkpoint phải làm gì, ghi vào file nào và được chấm theo tiêu chí nào, để không phải mở đi mở lại nhiều file đề mới ghép được các thông tin đó |
| Actor | Học viên K5 lúc mới nhận đề lab (đầu buổi học) |
| Thời điểm / bối cảnh | 15–30 phút đầu buổi lab, trước khi bắt tay vào CP1; đề gồm 6 file ở thư mục gốc và 3 file trong `docs/` |
| Quy trình hiện tại (3–7 bước) | 1. Đọc README (tổng quan, thứ tự đọc) · 2. Đọc RULES (được dùng AI ở đâu) · 3. Đọc CHECKPOINTS (CP0–CP7) · 4. Đọc RUBRIC (điểm từng phần) · 5. Đọc SUBMISSION (tên repo, deadline) · 6. Mở lại các file để ghép "CP này làm gì – ghi vào đâu – chấm thế nào" |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 6, ghép thông tin giữa các file: khoảng 8 phút, phải mở đi mở lại vì cùng một CP được nói ở 3–4 file khác nhau |
| Impact (nếu không giải thì sao) | 30 phút mỗi lab bị dùng để đọc đề; nếu hiểu sai thì nộp thiếu mục hoặc ghi sai file và bị mất điểm; cả lớp cùng gặp ở mỗi lab |
| Success metric (baseline → target) | Thời gian từ lúc mở đề đến lúc biết rõ CP1 phải làm gì: 30 phút → dưới 10 phút. Đo bằng tự bấm giờ ở lab tiếp theo |
| Phương án không dùng AI | Một bảng tổng hợp 1 trang "CP – làm gì – ghi vào file nào – tiêu chí RUBRIC", làm một lần rồi dùng lại; hoặc đề nghị thêm cột tiêu chí chấm vào bảng sẵn có ở `CHECKPOINTS.md` |
| Giả thuyết về AI (nếu có) | AI đọc toàn bộ file đề và soạn bảng tổng hợp CP – yêu cầu – nơi ghi – tiêu chí chấm, có ghi nguồn từng dòng lấy từ file nào; học viên đối chiếu lại với đề gốc |
| Cảm nhận nhanh | Rule hoặc Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 30 phút / lab

[1 Đọc README: 5'] → [2 Đọc RULES: 4'] → [3 Đọc CHECKPOINTS: 6']
→ [4 Đọc RUBRIC: 4'] → [5 Đọc SUBMISSION: 3']
→ [6 Mở lại các file, ghép thông tin từng CP: 8'] ← BOTTLENECK
```

### Problem Card #2 — Lab coach bị hỏi lặp lại về cách nộp bài

| Trường | Nội dung |
|---|---|
| Job Story | Khi sắp tới hạn nộp lab, lab coach muốn học viên tự kiểm tra được tên repo, tên file và cách nộp, để không phải trả lời đi trả lời lại cùng một câu hỏi và còn thời gian hỗ trợ phần nội dung bài |
| Actor | Lab coach phụ trách lớp L3B (người trả lời); học viên sắp nộp bài (người hỏi) |
| Thời điểm / bối cảnh | Cuối buổi lab và trước deadline, câu hỏi gửi trên kênh Discord của lớp |
| Quy trình hiện tại (3–7 bước) | 1. Học viên làm xong, chuẩn bị nộp · 2. Không chắc tên repo / tên file / link nộp, mở lại README và SUBMISSION · 3. Vẫn không chắc, hỏi trên Discord · 4. Chờ lab coach trả lời · 5. Lab coach đọc và trả lời (thường là câu đã trả lời trước đó) · 6. Học viên sửa tên hoặc nộp lại |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5, lab coach trả lời lại cùng một câu: khoảng 3 phút/lần × 30–40 lần = 90–120 phút từ buổi lab đầu đến nay. Phía học viên, bước 4 chờ trả lời mất khoảng 15 phút |
| Impact (nếu không giải thì sao) | Coach mất 1,5–2 giờ cho câu hỏi lặp lại thay vì hỗ trợ nội dung bài; học viên chờ, dễ nộp sai tên repo hoặc tên file và bị tính là nộp sai |
| Success metric (baseline → target) | Số câu hỏi về đặt tên và cách nộp trên Discord mỗi lab: baseline đếm lại ở lab hôm nay → giảm ít nhất 50% ở lab tiếp theo. Đo bằng đếm tin nhắn trên Discord |
| Phương án không dùng AI | Ghim một tin nhắn FAQ và checklist nộp bài trên Discord, có ví dụ tên repo đúng và sai; coach trả lời bằng link tới tin nhắn ghim thay vì gõ lại |
| Giả thuyết về AI (nếu có) | AI trả lời câu hỏi về cách nộp dựa trên `SUBMISSION.md` và `README.md`; câu nào không có trong tài liệu thì chuyển cho coach |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 29 phút / 1 lần hỏi (phía học viên)

[1 Làm xong, chuẩn bị nộp] → [2 Mở lại README, SUBMISSION: 5']
→ [3 Hỏi trên Discord: 1'] → [4 Chờ coach trả lời: 15']
→ [5 Coach trả lời lại câu đã trả lời: 3'] ← BOTTLENECK (lặp lại 30–40 lần)
→ [6 Học viên sửa tên / nộp lại: 5']
```

### Problem Card #3 — Lab vượt thời lượng buổi học

| Trường | Nội dung |
|---|---|
| Job Story | Khi làm bài lab trong buổi học, tôi muốn hoàn thành đúng yêu cầu trong thời gian buổi lab, để không phải làm thêm buổi tối và không bị trễ deadline |
| Actor | Học viên K5 làm lab có phần code (lab tuần trước) |
| Thời điểm / bối cảnh | Trong buổi lab 4 giờ, phần còn lại phải làm tiếp buổi tối |
| Quy trình hiện tại (3–7 bước) | 1. Đọc đề, hiểu yêu cầu · 2. Chuẩn bị repo và môi trường · 3. Tự code các phần yêu cầu · 4. Chạy thử, sửa lỗi · 5. Viết báo cáo và nộp |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, tự code tay: khoảng 180 phút, chiếm một nửa tổng thời gian |
| Impact (nếu không giải thì sao) | Vượt 2 giờ so với buổi lab, phải làm thêm buổi tối; dễ trễ deadline và ảnh hưởng phần việc của nhóm |
| Success metric (baseline → target) | Tổng thời gian làm lab: 6 giờ → 4 giờ (trong buổi học). Đo bằng tự ghi giờ bắt đầu và kết thúc từng bước ở lab tiếp theo |
| Phương án không dùng AI | Đọc đề và tài liệu trước buổi học; hỏi coach ngay khi kẹt quá 15 phút; chia phần code trong nhóm |
| Giả thuyết về AI (nếu có) | Chưa rõ: cần tách bước 3 thành các bước nhỏ hơn (kẹt ở cú pháp, logic hay đọc tài liệu) mới biết AI có giúp được không |
| Cảm nhận nhanh | Chưa biết |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 6 giờ (360 phút) / lab, buổi học chỉ có 4 giờ

[1 Đọc đề: 30'] → [2 Chuẩn bị repo, môi trường: 30']
→ [3 Tự code các phần yêu cầu: 180'] ← BOTTLENECK
→ [4 Chạy thử, sửa lỗi: 60'] → [5 Viết báo cáo, nộp: 60']
```

### Card muốn pitch nhất

- Card số: 1 (Đọc đề lab nhiều file)
- Vì sao: quy trình rõ và lặp lại ở mọi lab; cả nhóm đang trải qua đúng việc này ở lab hôm nay nên dễ kiểm chứng ở CP4; bottleneck là một bước cụ thể và đo được bằng bấm giờ.
- Câu hỏi muốn nhóm phản biện: `CHECKPOINTS.md` đã có bảng "CP – ghi vào đâu". Vậy pain có còn thật không, hay chỉ cần thêm một cột tiêu chí chấm vào bảng đó (No AI) là đủ?

### AI đã phản biện card thế nào

Tôi đưa card #1 cho AI đóng vai "PM hoài nghi".

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Baseline 30 phút chỉ là ước lượng từ 1 lần đọc đề | Đồng ý | Ghi rõ là ước lượng; sẽ bấm giờ thật ở lab tiếp theo và hỏi thêm 2–3 bạn ở CP4 |
| `CHECKPOINTS.md` đã có bảng tóm tắt "CP – ghi vào đâu", nên "đọc nhiều file" có thể không phải pain thật | Đồng ý một phần | Thu hẹp bottleneck thành bước 6 (ghép thông tin giữa các file, nhất là với RUBRIC); thêm phương án No AI là bổ sung cột tiêu chí chấm vào bảng sẵn có |
| Đề lab có format cố định giữa các lab, nghĩ tới AI là quá sớm | Đồng ý một phần | Đổi cảm nhận nhanh từ Workflow thành "Rule hoặc Workflow"; để CP6 so sánh 4 mức rồi mới chốt |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch 3 card: đọc đề lab nhiều file, lab coach bị hỏi lặp lại về cách nộp bài, lab vượt thời lượng buổi học (dòng 4–6 bảng pitch, commit `7a450a0`) | Card "lab coach bị hỏi lặp lại" (#5) được nhóm chọn làm candidate, điểm cao nhất trong shortlist |
| Phản biện bài của bạn khác | Nhóm không pitch trực tiếp, chỉ điền card vào file chung, nên tôi chưa đặt câu hỏi phản biện trực tiếp cho bạn nào | Cột "Câu hỏi phản biện" ở dòng của tôi trong bảng pitch vẫn trống; đây là điểm nhóm làm chưa đủ ở CP3 |
| Nhận phản biện | Không nhận được câu hỏi trực tiếp từ nhóm vì không pitch thật. Phản biện tôi nhận được là từ AI đóng vai "PM hoài nghi" ở CP2 (xem mục 3) | Tôi đã sửa gì: thu hẹp bottleneck card #1 về bước ghép thông tin giữa các file đề |
| Gom cluster / cây OST | Không trực tiếp điền; bảng cluster và cây OST do Khoa và Ninh điền trên file chung | Card #5 của tôi được xếp chung cluster B với card "khách hỏi giá/size/ship" của Khoa (cùng pattern trả lời câu hỏi lặp lại) |
| Chọn candidate problem | Card #5 của tôi được chọn; số liệu tôi đưa ra (khoảng 30–40 lần hỏi trên Discord) là lý do chính giúp card có điểm "pain có bằng chứng" cao nhất | Candidate của nhóm: lab coach phải trả lời lặp lại câu hỏi về cách nộp bài |
| Kiểm chứng / research | Soạn Assumption Map và bộ câu hỏi phỏng vấn theo The Mom Test (commit `24d9b1e`, file `report/assets/cp4-interview-guide.md`); làm bảng research 3.3 (commit `2c0dc21`, `38a7e1f`) | Research cho thấy bài toán đã có lời giải đơn giản (câu trả lời soạn sẵn, Forum Channel), không cần tự xây AI. Tôi phát hiện nguồn GitHub Classroom không khớp bài (giải chuyện đặt tên repo, không phải chuyện coach trả lời lặp lại) và thay bằng Zendesk Macros |
| Quy trình nhóm | Góp ý khi nhóm thảo luận | Quy trình hiện tại và tương lai do Khoa vẽ (mục 4 báo cáo nhóm) |
| Problem Statement | Góp ý khi nhóm thảo luận | Problem Statement v0 và v1 do Khoa viết (mục 5 và 7 báo cáo nhóm) |
| Mức can thiệp AI | Góp ý khi nhóm thảo luận | Nhóm chọn **No AI**, đúng với kết luận research |
| Quyết định | Sau khi coach nói không coi việc trả lời lặp lại là pain, tôi đề xuất **giữ nguyên actor lab coach** và chấp nhận bài có thể thất bại, thay vì đổi actor sang học viên cho bài "đẹp" hơn | Nhóm giữ actor, ghi rủi ro Value ở mức Trung bình–Cao và ra quyết định **Not Yet** |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Viết lại các ý tôi tự nghĩ thành Job Story; gợi ý thêm problem | Viết lại #1 cho rõ tình huống và kết quả (ban đầu tôi chỉ ghi "làm lab vào buổi học đầu tiên"); tách #3 và #4 cho khỏi trùng | Gợi ý ý "tìm thông báo cũ trong group lớp" bị trùng với #3, #4; gợi ý "theo dõi ai làm phần nào" mà tôi không thật sự gặp; tự ghi lý do giữ ý thay tôi | Bỏ 2 ý không phải pain thật của tôi, đổi #5 sang "ôn bài từ nhiều nguồn"; tự điền số liệu thật (6 giờ, 20 phút, 30 phút, 30–40 lần) |
| CP2 Problem Card | Soạn nháp 3 Problem Card, quy trình nháp; đóng vai "PM hoài nghi" phản biện card #1 | Chỉ ra `CHECKPOINTS.md` đã có sẵn bảng "CP – ghi vào đâu", nên pain "đọc nhiều file" có thể nhỏ hơn tôi nghĩ | Số phút cho từng bước trong quy trình là AI ước lượng để cộng lại cho khớp tổng, không phải số tôi đo | Thu hẹp bottleneck card #1 về bước ghép thông tin giữa các file; giữ các số phút từng bước ở dạng ước lượng (chưa đo lại), chỉ tổng thời gian là số thật của tôi |
| CP3 Hội tụ nhóm | Rút gọn 3 Problem Card của tôi thành 3 dòng trong bảng pitch của báo cáo nhóm; gợi ý cách gom cluster | Viết gọn Job Story, actor, bottleneck cho vừa bảng; chỉ ra card "khách hỏi giá" của Khoa và card #5 của tôi cùng pattern "trả lời câu hỏi lặp lại" | AI không pitch hay phản biện thay được; cột "câu hỏi phản biện" phải chờ pitch thật nên vẫn trống | Tôi tự kiểm lại 3 dòng cho khớp card gốc. Phần pitch và chọn candidate nhóm tự quyết, không dùng AI |
| CP4 Kiểm chứng | Soạn Assumption Map và bộ câu hỏi phỏng vấn theo The Mom Test | Có danh sách câu không được hỏi (kiểu "bạn có muốn…"); chỉ ra giả định #2 (coach thấy đây là gánh nặng) là quan trọng nhất cần kiểm trước | Bản đầu có 6 giả định, một giả định ít quan trọng (nộp sai gây hậu quả) | Tôi rút còn 5 giả định. Buổi phỏng vấn coach do nhóm tự làm với người thật, không dùng AI |
| CP4 Research | Tìm giải pháp đã có; viết mục "Nhóm đã sửa problem thế nào sau kiểm chứng" | Tìm được case Jill Watson và Discord Forum Channels, có trích nội dung từ trang nguồn | Đưa GitHub Classroom vào dù nó giải chuyện đặt tên repo, không khớp bài "coach trả lời lặp lại"; 1 link Georgia Tech lỗi 404, trang trợ giúp Discord và tài liệu Carl-bot không mở được nên không kiểm được; sau phỏng vấn coach, AI viết đổi actor sang học viên | Tôi yêu cầu thay GitHub Classroom bằng nguồn đúng bài (Zendesk Macros), chỉ giữ 3 link đã kiểm được nội dung; tôi quyết định **giữ actor lab coach** thay vì đổi theo AI |
| CP5 Quy trình | Không dùng AI. Phần này do Khoa viết, tôi góp ý khi nhóm thảo luận | — | — | — |
| CP5–6 Problem Statement | Không dùng AI. Phần này do Khoa viết, tôi góp ý khi nhóm thảo luận | — | — | — |
| CP6 Mức can thiệp / quyết định | Không dùng AI. Phần này do Khoa viết, tôi góp ý khi nhóm thảo luận | — | — | — |
| CP7 Báo cáo cá nhân | Tổng hợp từ lịch sử commit để soạn bảng mục 4, 5, 7 và phần của tôi trong `TEAM.md`; hướng dẫn dùng git (commit, pull, push) | Liệt kê đúng commit làm bằng chứng cho từng phần việc | Có lúc AI tự ghi những điều chỉ tôi biết (lý do, câu hỏi phản biện); tự thêm dòng đồng tác giả Claude vào commit | Tôi trả lời lại phần tham gia thực tế (không pitch thật, góp ý ở CP5–CP6, không dùng AI ở CP5–CP6) để sửa bảng; xoá dòng đồng tác giả khỏi commit. **Mục 6 Reflection tôi tự viết, không dùng AI** |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

- Đề lab: `README.md`, `RULES.md`, `CHECKPOINTS.md`, `docs/01-worksheet.md`, `docs/02-deliverable-example.md`.
- Rob Fitzpatrick, *The Mom Test* (cách đặt câu hỏi phỏng vấn), qua `docs/01-worksheet.md`.
- Zendesk, *Creating macros for repetitive ticket responses and actions*: https://support.zendesk.com/hc/en-us/articles/4408844187034-Creating-macros-for-repetitive-ticket-responses-and-actions
- Discord Blog, *Forum Channels*: https://discord.com/blog/forum-channels-space-for-organized-conversation
- Georgia Tech, *Artificial Intelligence Course Creates AI Teaching Assistant* (Jill Watson): https://provost.gatech.edu/news/artificial-intelligence-course-creates-ai-teaching-assistant
