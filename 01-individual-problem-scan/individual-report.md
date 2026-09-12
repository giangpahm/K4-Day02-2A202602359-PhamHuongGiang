# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Phạm Hương Giang
- Mã học viên: 2A202602359
- Vai trò / bối cảnh: Học viên khóa AI thực chiến (AI20K Build Phase) & Sinh viên năm cuối.
- Công việc hằng tuần:
  - Tham gia lab thực hành 4 giờ, làm assignment trên GitHub và submit lên VLearn.
  - Học trực tiếp tại classroom, sử dụng máy chiếu và mic cho việc học / trình bày.
  - Nghỉ trưa tại cafeteria trong khoảng 45–60 phút.
  - Tìm tài liệu / giải đáp câu hỏi qua class Discord.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| # | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được | Ai chịu ảnh hưởng? | Dấu hiệu thật (số + bằng chứng) |
|---|---|---|---|---|
| 1 | Tốn thời gian | Báo lỗi máy chiếu/mic phải qua người trung gian trước khi kỹ thuật viên nhận thông tin. | Giảng viên và học viên | Mất 25–30 phút đầu buổi; khoảng 30 người phải chờ. |
| 2 | Lặp lại / Tốn thời gian | Giờ trưa cafeteria đông, đến quầy mới biết món hết và còn phải chờ thanh toán. | Học viên / sinh viên | Mất 25–30 phút/bữa; khoảng 5 ngày/tuần. |
| 3 | Lặp lại | Trước khi submit VLearn phải mở thủ công các folder/file GitHub để kiểm tra file rỗng và Public. | Học viên | Mất 10–15 phút/lần submit. |
| 4 | AI có thể tốt hơn | Tìm cách xử lý từ các thread Discord dài để tìm đúng command/hướng dẫn. | Học viên | 30–40 messages/problem; mất 15–20 phút. |
| 5 | Tốn thời gian | Tìm chỗ học nhóm còn trống và có ổ cắm sạc vào giờ cao điểm. | Học viên / sinh viên | Mất 10–15 phút; phải kiểm tra 2–3 tầng. |
| 6 | Lặp lại | Scan và xoá PII như tên, số điện thoại, email trước khi push repository Public. | Học viên | Mất 5–10 phút/lần kiểm tra. |
| 7 | Pain từ người khác | Report của thành viên có format heading, table và nguồn không đồng nhất, cần format lại. | Người tổng hợp / cả nhóm | Mất 30–45 phút/lần tổng hợp. |
| 8 | Tốn thời gian | Tìm teammate trên Phoenix theo skill matrix Tech vs Product. | Học viên cần lập nhóm | Mất 1–2 giờ đọc profile và nhắn tin. |
| 9 | Pain từ người khác | Guest/student không có ID card phải chờ security viết ticket thủ công. | Security và guest/student | Mỗi ngoại lệ mất 1–2 phút; xảy ra vào khoảng 8h sáng. |
| 10 | Tốn thời gian | Đọc guideline lab dài để tìm artifact cần nộp và phân biệt individual/group. | Học viên / nhóm | Mất khoảng 15 phút để scan và chia task. |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**
- Prompt đã hỏi: `Tôi là học viên đang học trực tiếp tại cơ sở lớp học, hãy gợi ý các vấn đề lặp lại hoặc gây tắc nghẽn về mặt vận hành và công cụ.`
- Ý dùng được:
  - Vấn đề báo cáo sự cố thiết bị classroom qua người trung gian.
  - Việc kiểm tra submission trước deadline.
- Ý bỏ vì không phải pain thật:
  - "AI điều khiển tự động bật tắt máy chiếu theo lịch" vì không thực tế với hạ tầng IoT hiện tại và không xuất phát từ pain quan sát được.

**Self-check Phase 1:**
- [x] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [x] Dùng ít nhất 3/4 lăng kính
- [x] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan) | Vì sao chọn (2-3 ý) | Điều còn chưa chắc |
|---|---|---|---|
| 1 | Báo lỗi máy chiếu/mic phải qua người trung gian trước khi kỹ thuật viên nhận thông tin. | Workflow rõ; impact trực tiếp lên cả lớp; có thể tranh luận Rule / Workflow / Agent. | Tần suất không xảy ra hằng ngày. |
| 2 | Giờ trưa cafeteria đông, đến quầy mới biết món hết và còn phải chờ thanh toán. | Pain xảy ra thường xuyên; ảnh hưởng trực tiếp thời gian nghỉ; dễ đo thời gian nhận đồ ăn. | App cần đồng bộ tồn kho / POS thực tế. |
| 3 | Kiểm tra thủ công GitHub trước khi submit VLearn. | Workflow cụ thể; thời gian dễ đo; boundary rõ giữa Rule và AI. | Mức giảm lỗi còn phụ thuộc thói quen người submit. |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Báo cáo sự cố thiết bị classroom

```text
Problem 1 câu:
Giảng viên và học viên mất 25–30 phút đầu buổi vì việc báo lỗi máy chiếu/mic phải đi qua người trung gian trước khi kỹ thuật viên nhận và xử lý.

Actor:
Giảng viên và student representative.

Thời điểm / bối cảnh:
5–10 phút trước khi bắt đầu class/lab, khi kiểm tra máy chiếu hoặc mic.

Current workflow 3-7 bước:
1. Bật máy chiếu/mic và phát hiện thiết bị lỗi.
2. Kiểm tra dây cáp hoặc restart classroom computer trong khoảng 5 phút.
3. Không tự xử lý được nên cử người đi báo admin/reception.
4. Reception ghi log thủ công và gọi/radio cho kỹ thuật viên.
5. Kỹ thuật viên nhận thông tin, lấy dụng cụ rồi đi đến classroom.

Bottleneck:
Bước 3–4: truyền đạt thông tin qua người trung gian làm chậm việc tiếp nhận và có thể mô tả sai lỗi.

Impact:
Một sự cố có thể làm gián đoạn 25–30 phút đầu buổi của khoảng 30 người.
Giảng viên mất thời gian giảng dạy và kỹ thuật viên có thể mang sai dụng cụ/phụ tùng.

Success metric:
Giảm thời gian từ lúc phát hiện lỗi đến khi kỹ thuật viên nhận ticket từ khoảng 25 phút xuống dưới 5 phút.
100% ticket có đúng room + ảnh lỗi.

Non-AI alternative:
Đặt QR tại podium để mở Google Form/Zalo support, tự điền room cố định và gửi thông tin trực tiếp đến bộ phận kỹ thuật.

AI hypothesis:
Cho phép người dùng gửi ảnh/voice note qua app/bot; Vision/LLM phân loại lỗi, lấy thông tin room và tạo/dispatch ticket cho kỹ thuật viên phụ trách tầng.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — 25 phút

[1. Recable / restart: 5'] → [2. Đi đến reception: 7'] → [3. Reception log + call: 5'] → [4. Technician lấy dụng cụ + đi đến room: 8']
                                                                                 <-- bottleneck

FUTURE STATE — 4 phút

[1. Scan QR + chụp ảnh: 0.5'] → [2. Rule tự nhận room + dispatch: 0.5'] → [3. Technician nhận đúng lỗi + dụng cụ và xử lý: 3']
                                                                                                      <-- human boundary

Fallback: nếu network/QR fail thì dùng emergency bell gọi trực tiếp technical room.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Hàng chờ và món hết tại cafeteria

```text
Problem 1 câu:
Học viên mất khoảng 25–30 phút trong giờ nghỉ trưa vì phải xếp hàng, chỉ khi đến quầy mới biết món đã hết và còn phải chờ ở khâu thanh toán.

Actor:
Student / trainee.

Thời điểm / bối cảnh:
11:45–12:30 hằng ngày tại cafeteria, trong khoảng nghỉ 45–60 phút.

Current workflow 3-7 bước:
1. Xếp hàng tại cafeteria.
2. Đọc menu và phát hiện món muốn ăn đã hết hoặc phải đổi món.
3. Chờ nhân viên chuẩn bị đồ ăn.
4. Thanh toán QR và chờ reconciliation.
5. Tìm bàn để ăn.

Bottleneck:
Bước 2: chỉ phát hiện món hết khi đã đến quầy, gây indecision/change và làm chậm cả hàng.

Impact:
Mất khoảng 25–30 phút để hoàn tất việc lấy bữa ăn, làm giảm thời gian nghỉ và ăn uống.

Success metric:
Giảm thời gian từ lúc vào cafeteria đến lúc nhận meal tray từ khoảng 25 phút xuống dưới 5 phút.

Non-AI alternative:
Web/app pre-order từ 10h sáng, dùng Rule để đóng các món đã sold-out.

AI hypothesis:
Dự báo nhu cầu món ăn dựa trên lịch học / số lượng lớp để hỗ trợ cafeteria tối ưu lượng nấu.

Quick gut:
[ ] No AI / process fix
[x] Rule
[ ] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — 25 phút

[1. Queue: 15'] → [2. Think / change món: 3'] → [3. Food preparation: 3'] → [4. QR payment: 4']
                         <-- bottleneck

FUTURE STATE — 5 phút

[1. Pre-order: 2'] → [2. QR pickup: 1'] → [3. Wallet auto-charge: 2']
                                              <-- human boundary: confirm food

Fallback: nếu network fail thì quay về traditional POS sale.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Kiểm tra GitHub submission trước khi nộp VLearn

```text
Problem 1 câu:
Học viên mất 10–15 phút trước khi submit VLearn vì phải mở thủ công nhiều file/folder trên GitHub để kiểm tra file rỗng, trạng thái Public và PII.

Actor:
AI practical course student.

Thời điểm / bối cảnh:
15–20 phút cuối trước khi paste repository link vào VLearn.

Current workflow 3-7 bước:
1. Push code/file từ VS Code lên GitHub.
2. Đọc lại worksheet/rubric để nhớ yêu cầu.
3. Mở các folder/file để kiểm tra file rỗng và repository.
4. Scan nội dung để tìm PII.
5. Paste link và submit trên VLearn.

Bottleneck:
Bước 3–4: phải mở nhiều tab/file và scan thủ công.

Impact:
Mất khoảng 10–15 phút mỗi submission; có nguy cơ zero score nếu có file rỗng hoặc bị mentor nhắc vì PII.

Success metric:
Giảm thời gian kiểm tra từ khoảng 15 phút xuống dưới 1 phút.
Loại bỏ lỗi quên Public và lỗi file rỗng.

Non-AI alternative:
Dùng Regex / GitHub Actions để kiểm tra file size, branch name và các rule cấu trúc repository.

AI hypothesis:
Rule script kiểm tra structure + LLM scan nội dung để phát hiện PII hoặc heading còn thiếu.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — 15 phút

[1. Push: 2'] → [2. Check rubric: 2'] → [3. Hand-check empty/Public: 7'] → [4. PII scan: 3'] → [5. VLearn: 1']
                                      <-- bottleneck

FUTURE STATE — 3 phút

[1. Push: 2'] → [2. Rule check Public/file size: 0.2'] → [3. AI PII scan: 0.3'] → [4. Human review: 0.3'] → [5. VLearn: 0.2']
                                                                                 <-- human boundary

Fallback: nếu AI bỏ sót, student mở thủ công các file để kiểm tra lại.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Problem Card #1 — Báo cáo sự cố thiết bị classroom
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow có một bottleneck vật lý rõ ràng: thông tin sự cố phải đi qua người trung gian
trước khi kỹ thuật viên nhận được. Một sự cố có thể làm mất 25–30 phút của khoảng 30–40
người, nên opportunity cost lớn dù sự cố không xảy ra hằng ngày. Điểm đáng challenge là
liệu chỉ cần QR/process fix hay thực sự cần AI.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
1. Nếu lỗi máy chiếu/mic không xảy ra hằng ngày, quy mô pain có đủ lớn để làm solution riêng không?
2. QR/hotline/process fix có giải quyết đủ bottleneck không, hay AI đang là overkill
   ("dùng dao mổ trâu giết gà")?
```

**AI phản biện Card (nếu có):**
- Điểm yếu AI chỉ ra: Tần suất sự cố có thể thấp (ví dụ vài tuần mới xảy ra ở một phòng), nên khó justify một hệ thống phức tạp.
- Tôi sửa gì: Nhìn lại scale của impact: chỉ một classroom đã có thể làm gián đoạn 30–40 người. Vì vậy ưu tiên định vị đây là `Rule / Process Fix`, không cố ép dùng AI khi AI không tạo thêm giá trị rõ ràng.

### Self-check nộp phần 01
- [x] Có 5+ problems + top 3 Cards đủ field
- [x] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [x] Đã chọn 1 card pitch + câu hỏi challenge