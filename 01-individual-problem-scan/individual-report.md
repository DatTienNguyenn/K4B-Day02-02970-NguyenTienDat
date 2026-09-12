# 01 — Individual Problem Scan

> Điền theo Phase 1 + Phase 2 trong `01-worksheet.md`. Tự scan trước, dùng AI sau để phản biện. Không copy ví dụ Weekly Report.

## Thông tin cá nhân

- Họ và tên: Nguyễn Tiến Đạt
- Mã học viên: 2A202602970
- Vai trò / bối cảnh: sinh viên năm cuối đại học, chuẩn bị tốt nghiệp, đã có kinh nghiệm intern SE ở công ty startup trong 8 tháng.
- Công việc hằng tuần (3-5 gạch đầu dòng để soi problem): kiểm tra ticket trên jira, daily meeting, họp sync với team product, hr và cùng trong team developer mỗi vài ngày và training nội bộ công ty theo tháng. Công việc cần sự gọi điện trao đổi lớn vì nhân sự bị chia ra ở hai đầu cầu HN-SG. Thỉnh thoảng sẽ được các bên product/sale nhờ sự trợ giúp của IT helpdesk để tối ưu hóa một vài công việc.

---

## Phase 1 — Scan 5+ problems (tối thiểu 5, khuyến khích 8-10)

**Cách điền:** mỗi dòng = việc gì + ai chịu + đo bằng gì. Cột `Dấu hiệu thật` bắt buộc có số: mất bao lâu (bấm giờ mấy lần), mấy lần/tuần, bao nhiêu người gặp, log/ticket/quote nào.

| #   | Lăng kính (Lặp lại / Tốn thời gian / AI có thể tốt hơn / Pain từ người khác) | Problem quan sát được                                                                                       | Ai chịu ảnh hưởng?                                                                                | Dấu hiệu thật (số + bằng chứng)                                                                                                                |
| --- | ---------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | Lặp lại / Tốn thời gian                                                      | Mất thời gian kiểm tra thông báo Discord, Gmail và Teams để nắm được thông tin.                             | Bản thân tôi và các thành viên tham gia chương trình AI thực chiến.                               | Có nhiều kênh thông tin; chưa có số phút/lần kiểm tra cụ thể trong tài liệu tổng hợp.                                                          |
| 2   | Lặp lại / Tốn thời gian                                                      | Thời gian đi chợ, nấu ăn và dọn dẹp.                                                                        | Những người có việc bận đột xuất hoặc không cố định được thời gian làm việc.                      | Đây là nhu cầu lặp lại; tài liệu tổng hợp chưa ghi số lần/tuần hoặc số phút.                                                                   |
| 3   | AI có thể tốt hơn                                                            | Tổng hợp thông tin bài giảng đã học vào cuối ngày.                                                          | Học sinh, sinh viên đại học và sau đại học, đặc biệt người học nhiều lớp trong một ngày.          | Thường phải review vào buổi tối muộn; tài liệu tổng hợp chưa ghi thời lượng cụ thể.                                                            |
| 4   | Pain từ người khác                                                           | Gửi email cho nhiều người cùng lúc nhưng phải thay đổi tên, thời gian, nơi công tác và ảnh theo từng người. | Team sale hoặc customer support trong các công ty bán sản phẩm/phần mềm hoặc có chương trình mới. | Có thể phải gửi hàng nghìn đến hàng trăm nghìn email trong một buổi; một chị global sale phải copy-paste và sửa từng email.                    |
| 5   | Pain từ người khác                                                           | Thu thập email và tổng hợp theo category, mức độ ưu tiên và thông tin hóa đơn.                              | Nhân viên HR, kế toán và administrative.                                                          | Kế toán ở startup mất gần hết một ngày chỉ để kiểm tra mail và ghi lại số tiền hóa đơn; có nhiều category như mua hàng, nhân viên và công tác. |
| 6   | Tốn thời gian / AI có thể tốt hơn                                            | Tổng hợp nhanh thông tin cuộc họp sau buổi họp mà không phải làm bằng tay.                                  | Các thành viên tham gia nhiều cuộc họp trong ngày.                                                | Có thể có nhiều cuộc họp liên tục trong cùng ngày; xem lại video mất thời gian và thường phải hỏi lại nội dung.                                |
|     |

> Gợi ý tự soi: tuần trước mất nhiều thời gian nhất vào việc gì? Việc gì hay trì hoãn? Người khác hay hỏi lại câu gì? Workflow nào ai cũng biết là chậm?

**AI đã dùng ở Phase 1 (nếu có):**

- Prompt đã hỏi:
- Ý dùng được:
- Ý bỏ vì không phải pain thật:

**Self-check Phase 1:**

- [ ] Đủ 5+ dòng, mỗi dòng có actor + số đo cụ thể
- [ ] Dùng ít nhất 3/4 lăng kính
- [ ] Không có dòng chung chung kiểu "mất nhiều thời gian"

---

## Phase 2 — Top 3 Problem Cards

### 2.1. Chọn top 3

Giữ bài nào: actor cụ thể, workflow vẽ được 3-7 bước, bottleneck ở 1 bước, impact đo được. Loại bài quá rộng.

| Rank | Problem (copy từ bảng scan)                                                                                                                                       | Vì sao chọn (2-3 ý)                                                                                                                          | Điều còn chưa chắc                                                                   |
| ---- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| 1    | Việc gửi mail cho nhiều người cùng một lúc nhưng trong mail có những nội dung cần thay đổi tùy vào ngữ cảnh (tên riêng, thời gian, nơi công tác, ảnh đính kèm...) | Nhu cầu nhiều trong môi trường số; workflow lặp lại với số lượng người nhận rất lớn; bottleneck là sửa nội dung thủ công cho từng người.     | Tính bảo mật của email và không thể thu hồi hàng loạt nếu phát hiện lỗi sau khi gửi. |
| 2    | Mất thời gian kiểm tra thông báo Discord/Gmail/Teams để nắm được thông tin khẩn cấp                                                                               | Mỗi người có nhiều kênh thông tin; rất dễ bỏ lỡ kênh ít dùng hoặc không có thời gian kiểm tra tất cả trong ngày.                             | Tính bảo mật khi cần được cho phép tiếp nhận thông báo của người dùng.               |
| 3    | Tổng hợp thông tin cuộc họp nhanh chóng sau buổi họp mà không cần phải làm bằng tay                                                                               | Đây là trải nghiệm đã từng gặp khi có nhiều cuộc họp trong ngày giữa team dev và product; không thể nghe lại toàn bộ và thường phải hỏi lại. | AI có thể bỏ sót thông tin quan trọng hoặc tóm tắt sai ý.                            |

### 2.2. Problem Cards chi tiết (lặp lại cho cả 3 cards)

---

#### Problem Card #1 — Gửi email hàng loạt theo ngữ cảnh

```text
Problem 1 câu: Team sale phải gửi nhiều email nhưng vẫn phải sửa thủ công tên, thời gian, nơi công tác và ảnh đính kèm theo từng người nhận.

Actor: Team sale hoặc customer support.

Thời điểm / bối cảnh: Khi cần networking, kết nối khách hàng hoặc gửi thông tin về sản phẩm/chương trình mới.

Current workflow 3-7 bước:
1. Mở ứng dụng gửi email và chuẩn bị tệp đính kèm.
2. Chuẩn bị tiêu đề, nội dung mail và người nhận (20 mail, khoảng 20 phút).
3. Lặp lại quy trình, chỉnh tên và ảnh đính kèm cho đúng từng người (khoảng 40 phút).
4. Đánh dấu người đã gửi (khoảng 5 phút).

Bottleneck: Chuẩn bị thủ công nội dung và các trường cần thay đổi; con người phải chuẩn bị sheet dữ liệu tương ứng.

Impact: Gửi hàng nghìn đến hàng trăm nghìn email có cá nhân hóa sẽ mất nhiều thời gian và dễ sai.

Success metric: Giảm thời gian gửi mail và không phải chỉnh sửa, gửi từng mail bằng tay.

Non-AI alternative: Dùng mail merge và sheet dữ liệu có các trường tên, thời gian, nơi công tác, ảnh.

AI hypothesis: Kết nối email với AI để lấy dữ liệu từng người, tạo nội dung cá nhân hóa và gửi theo workflow có kiểm tra.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #1** (ASCII / Mermaid / ảnh đính kèm):

```text
CURRENT STATE — khoảng 70 phút cho 20 mail

[1 mở app/tệp: 5'] → [2 chuẩn bị nội dung: 20'] → [3 chỉnh từng mail: 40']  <-- bottleneck → [4 đánh dấu: 5']

FUTURE STATE — khoảng 34 phút

[1 kết nối email: 2'] → [2 chuẩn bị sheet dữ liệu: 20'] → [3 AI tạo/gửi, con người review: 10']  <-- human boundary

Fallback: nếu AI sai thì dừng gửi, sửa sheet/nội dung và chỉ gửi tiếp sau khi con người kiểm tra.
```

File đính kèm (nếu vẽ riêng): `01-individual-problem-scan-workflow-card-1.png`

---

#### Problem Card #2 — Bỏ lỡ thông báo khẩn cấp đa kênh

```text
Problem 1 câu: Người tham gia chương trình dễ bỏ lỡ thông tin khẩn cấp vì phải kiểm tra thủ công Discord, Gmail và Teams.

Actor: Bản thân tôi và các thành viên tham gia chương trình AI thực chiến.

Thời điểm / bối cảnh: Trong ngày, khi thông tin được gửi rải rác qua nhiều nền tảng.

Current workflow 3-7 bước:
1. Người dùng nhận thông báo trên Discord, Gmail hoặc Teams.
2. Mở từng nền tảng để kiểm tra thông tin.
3. Đọc và xác định thông tin có khẩn cấp hay không.
4. Ghi nhớ hoặc phản hồi thông tin cần xử lý.

Bottleneck: Phải kiểm tra nhiều kênh thủ công và dễ bỏ sót kênh ít dùng.

Impact: Có thể bỏ lỡ thông tin quan trọng trong chương trình.

Success metric: Giảm số thông báo khẩn cấp bị bỏ lỡ; thời gian kiểm tra các kênh giảm.

Non-AI alternative: Quy về một kênh thông báo chung và đặt lịch kiểm tra cố định.

AI hypothesis: AI được cấp quyền đọc các kênh đã chọn, lọc thông tin khẩn cấp và gom thành một bản tóm tắt/thông báo.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #2:**

```text
CURRENT STATE — chưa có số đo cụ thể

[1 nhận thông báo] → [2 mở từng kênh] → [3 đọc/lọc thông tin]  <-- bottleneck

FUTURE STATE — chưa có số đo cụ thể

[1 AI gom/lọc thông báo] → [2 AI tóm tắt] → [3 con người review]  <-- human boundary

Fallback: Nếu AI không được cấp quyền hoặc lọc sai, người dùng kiểm tra trực tiếp từng nền tảng.
```

File đính kèm: `01-individual-problem-scan-workflow-card-2.png`

---

#### Problem Card #3 — Tóm tắt nội dung cuộc họp

```text
Problem 1 câu: Thành viên phải xem lại video hoặc hỏi lại sau cuộc họp để nhớ các nội dung chính khi có nhiều cuộc họp trong ngày.

Actor: Các thành viên tham gia nhiều cuộc họp trong ngày.

Thời điểm / bối cảnh: Sau các cuộc họp liên tục giữa team developer, team product và các bên liên quan.

Current workflow 3-7 bước:
1. Tham gia cuộc họp và ghi nhận nội dung.
2. Kết thúc cuộc họp nhưng chưa kịp tổng hợp.
3. Xem lại video hoặc hỏi đồng nghiệp khi cần nhớ nội dung.
4. Tự tổng hợp các ý chính và việc cần làm.

Bottleneck: Xem lại toàn bộ video hoặc hỏi lại người khác để khôi phục nội dung cuộc họp.

Impact: Mất thời gian, dễ quên nội dung và có thể bỏ sót việc cần làm.

Success metric: Có bản tóm tắt và danh sách việc cần làm sau mỗi cuộc họp; giảm thời gian xem lại video.

Non-AI alternative: Cử một người ghi biên bản theo mẫu cố định.

AI hypothesis: AI chuyển nội dung cuộc họp thành bản tóm tắt, quyết định và action items để con người kiểm tra.

Quick gut:
[ ] No AI / process fix
[ ] Rule
[x] Workflow
[ ] Agent
[ ] Chưa biết
```

**Draft workflow Card #3:**

```text
CURRENT STATE — khoảng 135 phút (bao gồm 60' họp)

[1 tham gia họp & ghi chép thô: 60'] → [2 xem lại video/hỏi lại: 30'] → [3 tự tổng hợp & phân loại: 45']  <-- bottleneck

FUTURE STATE — khoảng 15 phút (xử lý sau họp)

[1 AI bóc băng audio thành text: 5'] → [2 AI tạo tóm tắt & action items: 2'] → [3 con người review & chốt: 8']  <-- human boundary

Fallback: Nếu bản tóm tắt thiếu hoặc sai, xem lại đoạn video liên quan và chỉnh sửa biên bản thủ công.
```

File đính kèm: `01-individual-problem-scan-workflow-card-3.png`

---

### 2.3. Card muốn pitch nhất (chuẩn bị 2 phút)

**Card tôi muốn pitch nhất:**

```text
Gửi email hàng loạt theo ngữ cảnh
```

**Vì sao (2-3 câu: workflow gì, số đo gì, impact gì):**

```text
Workflow gửi email cho nhiều người được cá nhân hóa theo sheet dữ liệu. Với 20 mail, quy trình hiện tại mất khoảng 70 phút, trong đó 40 phút là chỉnh sửa từng mail; AI có thể giảm thời gian và giảm thao tác copy-paste nhưng vẫn cần con người review trước khi gửi.
```

**Câu hỏi tôi muốn nhóm challenge (1-2 câu hỏi đúng chỗ yếu):**

```text
Làm thế nào để kiểm soát quyền truy cập dữ liệu người nhận và xử lý việc không thể thu hồi hàng loạt nếu AI gửi sai?
```

**AI phản biện Card (nếu có):**

- Điểm yếu AI chỉ ra: Mâu thuẫn trong Fallback Plan: Ở quy mô "hàng nghìn đến hàng trăm nghìn email", bạn đề xuất Fallback là "chỉ gửi tiếp sau khi con người kiểm tra". Nếu con người phải ngồi đọc review lại hàng nghìn email do AI viết để đảm bảo không sai sót, thì Bottleneck không hề biến mất, nó chỉ chuyển từ "người viết" sang "người duyệt"
- Tôi sửa gì: Tôi vẫn chọn để con người là chốt chặn kiểm thử cuối cùng. Việc duyệt chắc chắn sẽ đảm bảo rủi ro và không cần thao tác tay nhiều như viết.

### Self-check nộp phần 01

- [ ] Có 5+ problems + top 3 Cards đủ field
- [ ] Mỗi Card có workflow trước/sau + bottleneck + metric + fallback
- [ ] Đã chọn 1 card pitch + câu hỏi challenge
