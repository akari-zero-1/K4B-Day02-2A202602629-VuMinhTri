# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Vũ Minh Trí
- Mã học viên: 2A202602629
- Nhóm: B2 - Viber
- Candidate problem nhóm chọn: Thiết kế giáo án và xuất file quiz Excel theo đúng template để import vào hệ thống quiz cho học sinh.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động                  | Tôi đã làm gì? (việc cụ thể)                                                                                                                       | Kết quả / ảnh hưởng tới nhóm                                                                                     |
| -------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Scan cá nhân               | Tôi đề xuất 3 candidate về tổng hợp lịch học/deadline, tìm tài liệu GenAI và sắp xếp nhiều công việc.                                              | Nhóm có thêm các vấn đề thuộc nhóm tìm kiếm thông tin và quản lý task để so sánh với các candidate khác.         |
| Pitch Problem Card         | Tôi trình bày các vấn đề mình gặp khi phải tổng hợp thông tin từ Discord, Outlook, MS Teams và tự sắp xếp lịch học.                                | Nhóm hiểu rõ hơn actor, workflow và thời gian bị mất trong các vấn đề tôi đưa ra.                                |
| Challenge bài của bạn khác | Tôi tập trung xem các candidate có actor rõ, bottleneck cụ thể, số liệu đo được và làm được trong phạm vi lab hay không.                           | Nhóm tránh chọn những bài quá rộng hoặc phụ thuộc quá nhiều vào việc tích hợp hệ thống.                          |
| Gom trùng / cluster        | Tôi tham gia nhận diện các nhóm vấn đề như tìm kiếm/khôi phục thông tin và quản lý nhiều task.                                                     | Nhóm dễ nhìn thấy pattern chung giữa các candidate và so sánh theo từng cluster.                                 |
| Chọn candidate problem     | Tôi cùng nhóm so sánh các candidate theo actor, workflow, evidence, impact và khả năng so sánh Rule/Workflow/Agent.                                | Nhóm chọn candidate thiết kế giáo án và xuất quiz Excel vì output rõ, template kiểm tra được và phạm vi phù hợp. |
| Validation / research      | Tôi tham gia đối chiếu baseline chuẩn bị bài khoảng 50 phút, trong đó nhập template mất khoảng 12 phút, cùng kết quả phỏng vấn 2 trợ giảng.        | Nhóm có cơ sở xác định nhập liệu Excel là bottleneck thay vì chỉ dựa vào cảm nhận.                               |
| Workflow nhóm              | Với vai trò Workflow, tôi mô tả 5 bước: đọc tài liệu, lên khung bài, soạn câu hỏi, nhập Excel, upload và preview.                                  | Nhóm xác định rõ bước 4 là điểm nghẽn, mất 12 phút trong tổng 50 phút.                                           |
| Problem Statement          | Tôi góp phần làm rõ actor là giáo viên/trợ giảng, input là tài liệu bài học, output là file Excel và metric là thời gian chuẩn bị cùng lỗi format. | Problem Statement có phạm vi, baseline, success metric và Human Boundary rõ hơn.                                 |
| Rule / Workflow / Agent    | Tôi phân tích việc dùng Rule cho kiểm tra cột và format, AI cho việc đọc hiểu tài liệu và draft câu hỏi, giáo viên cho bước review.                | Nhóm chọn Workflow thay vì Agent vì quy trình khá tuyến tính và không cần AI tự lập kế hoạch.                    |
| Decision                   | Tôi ủng hộ quyết định GO cho một pilot nhỏ, đồng thời đề xuất bước review, fallback và rollback nếu AI tạo nội dung sai.                           | Nhóm có quyết định GO có kiểm soát, không triển khai AI tự động hoàn toàn ngay từ đầu.                           |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của tôi là phần phân tích workflow. Tôi đã giúp nhóm cụ thể hóa quy trình chuẩn bị quiz thành 5 bước và xác định bước nhập, căn chỉnh template Excel là bottleneck chính. Từ đó, nhóm có cơ sở chọn Workflow kết hợp AI draft, Rule kiểm tra format và giáo viên review trước khi upload.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase                   | Tôi dùng AI để làm gì?                                                              | AI hữu ích ở đâu?                                                                           | AI sai / hời hợt ở đâu?                                                   | Tôi sửa gì bằng nhận định của mình?                                                                                    |
| ----------------------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Scan                    | Gợi ý cách nhóm các vấn đề cá nhân về tìm kiếm thông tin, deadline và quản lý task. | Giúp tôi nhìn các vấn đề dưới góc độ actor, workflow và pain.                               | Có thể đưa ra các ý tưởng rộng hoặc solution-first mà chưa có bằng chứng. | Tôi chỉ giữ những candidate xuất phát từ trải nghiệm thật và có thể đo được.                                           |
| Problem Card            | Phản biện actor, bottleneck, input/output và khả năng làm trong lab.                | Giúp tôi phát hiện phần mô tả còn chung chung.                                              | Không tự biết candidate nào thật sự xảy ra thường xuyên với tôi.          | Tôi dựa vào trải nghiệm cá nhân và số thời gian thực tế để chọn nội dung phù hợp.                                      |
| Workflow                | Sắp xếp current workflow và future workflow thành các bước rõ ràng.                 | Giúp trình bày nhanh luồng 5 bước và các điểm handoff.                                      | Có xu hướng tự động hóa quá nhiều hoặc bỏ qua bước review của giáo viên.  | Tôi giữ lại Human Boundary, xác định bước nhập Excel 12 phút là bottleneck và thêm fallback khi AI sai.                |
| Research                | Tìm và kiểm tra các nguồn tham khảo về import spreadsheet, Wayground và Excel.      | Giúp tôi so sánh pattern template-first và data validation.                                 | Một số link hoặc nội dung có thể cũ, không đúng nền tảng nhóm đang dùng.  | Tôi kiểm tra lại link, thay link không hoạt động và ghi rõ không được mặc định dùng template Kahoot cho hệ thống khác. |
| Problem Statement       | Gợi ý cách viết actor, workflow, impact, success metric và boundary.                | Giúp cấu trúc problem statement đầy đủ và dễ kiểm tra.                                      | Có thể biến mục tiêu kỳ vọng thành kết quả đã được chứng minh.            | Tôi tách baseline đã đo được 50 phút khỏi mục tiêu kỳ vọng 12 phút và ghi rõ cần pilot để xác nhận.                    |
| Rule / Workflow / Agent | So sánh ba mức giải pháp và phản biện việc có cần Agent hay không.                  | Giúp làm rõ Rule phù hợp cho format, AI phù hợp cho ngữ nghĩa và Workflow là lớp điều phối. | AI có thể đề xuất Agent dù quy trình của nhóm khá tuyến tính.             | Tôi chọn Workflow kết hợp AI, Rule và người review thay vì Agent tự lập kế hoạch và tự upload.                         |
| Decision                | Kiểm tra các điều kiện GO, pilot, fallback và rollback.                             | Giúp tôi liệt kê rủi ro và tiêu chí exit cụ thể.                                            | Không thể tự quyết định thay nhóm rằng kết quả pilot đã đủ tốt.           | Tôi giữ quyết định GO ở mức pilot nhỏ, yêu cầu đo thời gian, lỗi format và thời gian review trước khi triển khai rộng. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):

- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text

Khi nghe các problem của các bạn, tôi nhận ra một problem tốt cần có actor, workflow và bằng chứng cụ thể, không chỉ có ý tưởng giải pháp. Tôi chọn candidate quiz Excel vì output rõ, dễ đo và phù hợp với phạm vi lab; với vai trò Workflow, tôi xác định bước nhập template là bottleneck chính. Nhóm chọn Workflow kết hợp AI draft, Rule kiểm tra format và giáo viên review để giữ Human Boundary. Tôi học được rằng cần tách baseline thực tế khỏi mục tiêu kỳ vọng, đồng thời kiểm tra kỹ link, số liệu và template. Nếu làm lại, tôi sẽ challenge nhóm sớm hơn về cách đo lỗi format 15% và mục tiêu 0%.

```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [ ] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [ ] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [ ] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [ ] [15đ] Nhóm có workflow trước/sau
- [ ] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [ ] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [ ] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [ ] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [ ] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
