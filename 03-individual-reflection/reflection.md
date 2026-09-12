# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Vũ Việt Hoàng
- Mã học viên: 2A202602398
- Nhóm: ZONE B - Công ty TNHH 1 mình tôi
- Candidate problem nhóm chọn: Sinh viên sử dụng Discord cho việc học phải dành khoảng 20-30 phút mỗi ngày để đọc và lọc nhiều channel nhằm tìm task, assignment, deadline hoặc thay đổi lịch, nhưng vẫn có nguy cơ bỏ sót thông tin cần hành động.

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Scan 8 problem từ đời sống/xã hội theo 4 lăng kính (thủ tục hành chính, tìm bãi gửi xe, theo dõi chi tiêu đa app, so sánh giá TMĐT, người lớn tuổi dùng app ngân hàng, chờ khám bệnh, tra tuyến xe buýt, tra chính sách xã hội); hoàn thiện 3 Problem Card chi tiết kèm workflow trước/sau. | Đưa 3 bài toán dân sinh vào pool chung của nhóm (#4 Thủ tục hành chính, #5 Tìm bãi xe, #6 Theo dõi chi tiêu), tạo đối trọng với nhóm bài toán học tập và bài toán doanh nghiệp. |
| Pitch Problem Card | Pitch bài #4 (Phải quay lại 2-3 lần khi làm thủ tục hành chính vì hồ sơ thiếu/sai mẫu), nêu rõ bottleneck ở bước tự tìm hiểu & chuẩn bị hồ sơ và impact 4-5 giờ/lần đi. | Nhóm ghi nhận đây là pain có impact lớn nhưng chỉ ra rủi ro: thủ tục thay đổi liên tục, rủi ro pháp lý cao, khó tích hợp dữ liệu cơ quan công quyền. |
| Challenge bài của bạn khác | Trong tranh luận giữa bài #18 (Vũ Anh) và #11 (Đạt), tôi đồng tình với lập luận của Việt Anh và Duy rằng pain thật nằm ở việc thông tin deadline bị chôn trong chat chứ không phải do sinh viên lười nhập tay vào Google Calendar. | Góp phần củng cố sự đồng thuận nghiêng về bài #18, giúp Đạt chấp nhận rút bài #11 nhanh hơn. |
| Gom trùng / cluster | Đồng ý xếp cả 3 bài của mình (#4 thủ tục hành chính, #5 bãi xe, #6 chi tiêu) vào cụm D sau khi nhóm chỉ ra điểm chung là phụ thuộc hạ tầng thực địa/API bên ngoài mà nhóm không truy cập được. | Giúp nhóm loại nhanh cụm D, tập trung thời gian bàn sâu vào cụm A và B. |
| Chọn candidate problem | Chấp nhận rút cả 3 bài của mình khi nhóm chỉ ra cả 3 đều thuộc cụm D (phụ thuộc hạ tầng thực địa hoặc API bên thứ ba đóng kín), không khả thi trong lab 4 tiếng; bỏ phiếu cho bài #18 của Vũ Anh. | Giúp nhóm hội tụ nhanh về một bài duy nhất (34/35 điểm) thay vì kéo dài tranh luận giữa các cụm. |
| Validation / research | Tham gia đóng góp ý kiến trong lúc nhóm phỏng vấn nội bộ và tổng hợp micro-survey 8 sinh viên, dù không trực tiếp là người đi hỏi. | Giúp nhóm rút ra insight rằng pain nằm ở việc hiểu/lọc nội dung, không chỉ ở số lượng thông báo. |
| Workflow nhóm | Góp ý bổ sung bước Rule kiểm tra field bắt buộc trước khi tính Priority Score, và nhấn mạnh cần có nhánh fallback khi AI confidence thấp. | Củng cố nguyên tắc AI chỉ đề xuất, không tự ý ghi task/deadline khi chưa chắc chắn. |
| Problem Statement | Góp ý siết chặt field Boundary: không đọc DM, không xử lý LMS/email, không tự tạo/sửa lịch khi sinh viên chưa Confirm. | Giúp PS v1 nêu rõ ranh giới hệ thống được/không được làm, tránh mơ hồ như bản v0. |
| Rule / Workflow / Agent | Đồng thuận chọn mức Workflow, phản đối ý kiến đẩy lên Agent tự động vì lo ngại rủi ro thiếu kiểm soát khi hệ thống tự quyết định ghi lịch. | Củng cố quyết định giữ nguyên tắc Human Confirm là boundary bắt buộc, không nhượng bộ sang Agent toàn quyền. |
| Decision | Đồng ý với quyết định "Go cho pilot thủ công, Not Yet cho production", dựa trên lý do baseline đo lường mới chỉ có 1 workflow cá nhân và 8 khảo sát, chưa đủ để tự tin mở rộng ngay. | Giúp nhóm thống nhất scope pilot nhỏ (100 message ẩn danh, 7 ngày) thay vì vội triển khai bot thật. |

**Dấu tay rõ nhất của Bản thân trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nhất của Bản thân nằm ở nhánh kiểm soát chất lượng trong Future Workflow: Bản thân đề xuất thêm bước Rule kiểm tra các field bắt buộc (task, người giao, hạn nộp) trước khi tính Priority Score, và nhánh fallback đẩy message sang danh sách "cần người đọc lại" khi AI confidence thấp thay vì để AI đoán bừa một deadline. Nhờ hai chi tiết này, nguyên tắc "AI chỉ đề xuất, không tự ghi task/deadline" trong PS v1 có cơ chế thực thi cụ thể ở đúng bước nào trong workflow, chứ không dừng lại ở một câu tuyên bố.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Bản thân dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Bản thân sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Nhờ AI gợi ý thêm problem đời sống/xã hội theo 4 lăng kính sau khi tự scan trước. | Mở rộng góc nhìn sang các mảng Bản thân chưa nghĩ tới: tra chính sách xã hội, người lớn tuổi dùng app ngân hàng, chờ khám bệnh. | AI đề xuất ý quá rộng kiểu "xây app quản lý toàn bộ cuộc sống cá nhân" — không chỉ ra được bottleneck ở bước nào. | Loại các ý không phải pain thật của Bản thân/người quen; giữ lại 8 ý có actor rõ và gắn số đo cụ thể (phút/lần, lần/tuần). |
| Problem Card | Nhờ AI cấu trúc 3 Problem Card theo đúng khung worksheet (Actor, workflow, bottleneck, metric, non-AI alternative). | Giúp diễn đạt current/future workflow mạch lạc, không bỏ sót field bắt buộc. | AI điền số ước lượng chung chung, không phản ánh thực tế Việt Nam. | Tự đối chiếu lại số với thực tế: thủ tục hành chính phải quay lại 2-3 lần, mỗi lần 4-5 giờ; tìm bãi xe 10-20 phút/lần. |
| Workflow | Nhờ AI phác thảo giải pháp mở rộng cho bài thủ tục hành chính (soát hồ sơ + xếp lịch hẹn + ưu tiên ticket) để tham khảo khi nhóm bàn về AI intervention point. | Chia được bài toán thành các module rõ ràng và gắn mỗi module với mức Rule/Workflow/Agent phù hợp. | AI thiên về đề xuất Agent tự điều phối lịch, chưa cân nhắc đủ yêu cầu minh bạch của dịch vụ công/hệ thống có ảnh hưởng nhiều người. | Rút ra nguyên tắc mang vào bài của nhóm: bước tính điểm ưu tiên nên là Rule công thức công khai, không dùng model mờ đục quyết định thay con người. |
| Research | Không dùng — phần phỏng vấn/survey và tìm tool tham khảo (Todoist, Zapier, Motion AI) do các bạn trong nhóm trực tiếp thực hiện. | | | |
| Problem Statement | Không dùng AI để viết field — chỉ tự góp ý trực tiếp trong thảo luận nhóm về việc siết Boundary. | | | |
| Rule / Workflow / Agent | Không dùng AI để quyết định — tự lập luận dựa trên rủi ro thiếu kiểm soát khi hệ thống ghi lịch tự động mà không có Human Confirm. | | | |
| Decision | Không dùng AI — đồng thuận theo bằng chứng baseline nhóm đã thu thập (1 workflow cá nhân, 3 interview, 8 khảo sát). | | | |

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
Khi nghe top 3 problems của các bạn trong nhóm, bản thân tôi nhận ra tiêu chí quan trọng nhất để một bài toán "làm được trong lab 4 tiếng" không phải là bài đó nghe hay hay có vẻ ngầu, mà là nhóm có kiểm chứng được ngay và có quyền truy cập dữ liệu thật hay không. Cả 3 bài của tôi (thủ tục hành chính, bãi xe, chi tiêu cá nhân) đều là pain thật, nhưng khi bị nhóm chất vấn, bản thân tôi nhận ra chúng đều phụ thuộc vào hạ tầng hoặc dữ liệu bên ngoài mà nhóm không thể mô phỏng hay kiểm chứng trong buổi lab, giống hệt tình huống của bài Xanh SM mà Duy phải rút vì không có quyền truy cập dữ liệu nội bộ. Ban đầu bản thân tôi khá tiếc vì đã đầu tư khá kỹ cho 3 Problem Card của mình, nhưng sau khi nghe bài Discord của Vũ Anh và thấy cả 6 người trong nhóm đều gặp đúng pain đó hàng ngày, bản thân hiểu ngay đây mới là bài có thể kiểm chứng bằng dữ liệu thật ngay tại chỗ nên đã chủ động đổi phiếu thay vì cố bảo vệ bài của mình. Nhóm cũng từng có lúc nghiêng về hướng solution-first khi bàn tới việc để AI tự động ghi thẳng task/deadline vào lịch mà không cần xác nhận, nhưng khi Bản thân và một số bạn đặt câu hỏi "nếu AI hiểu nhầm câu đùa thành deadline gấp thì ai chịu trách nhiệm", nhóm mới quay lại bàn kỹ hơn về ranh giới Human Confirm trước khi ghi lịch. Điều khó nhất với Bản thân khi làm Problem Card không phải là xác định bottleneck, mà là tìm số đo thật: nhiều problem đời sống Bản thân quan sát được nhưng chưa từng bấm giờ chính xác, nên phải tự ước lượng dựa trên tần suất và so sánh với thực tế phổ biến thay vì có số liệu đo trực tiếp. Nếu làm lại, Bản thân sẽ chọn ít nhất một bài toán mà bản thân có thể tự thu thập dữ liệu ngay trong ngày (ví dụ bấm giờ thật khi tìm bãi xe) thay vì chỉ ước lượng, để khi bị nhóm challenge về evidence Bản thân có bằng chứng chắc chắn hơn.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI
