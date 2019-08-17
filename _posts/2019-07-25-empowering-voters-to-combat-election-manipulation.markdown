---
layout: post
title:  'Trao quyền cho cử tri để chống lại sự thao túng bầu cử'
date:   2019-07-25
categories: "General"
image: "https://blog.mozilla.org/wp-content/uploads/2019/02/01_misinformation-campaign-graphic.jpg"
---

**Năm ngoái, Mozilla đã tìm mọi cách để trao quyền bầu cử cho cử tri trước sự thay đổi động lực bầu cử gây ra bởi internet và quảng cáo trực tuyến. Công việc này đã bao gồm [việc tham gia](https://blog.mozilla.org/wp-content/uploads/2019/01/Mozilla-letter-to-EU-Commission-on-Facebook-transparency-31-01-19-1.pdf) của chúng tôi vào quy tắc thực hành thông tin sai lệch của EU, thúc đẩy sự thay đổi trong ngành công nghiệp, dẫn đến việc ra mắt [bộ công cụ bầu cử Firefox EU](https://blog.mozilla.org/blog/2019/05/05/eu-elections-2019/) nhằm cung cấp thông tin cho mọi người về quá trình bầu cử, về việc theo dõi và quảng cáo trực tuyến có ảnh hưởng đến hành vi bỏ phiếu của họ và làm thế nào để họ có thể dễ dàng bảo vệ mình.**

Chúng tôi cũng đã hi vọng bổ sung thêm chuyên môn kỹ thuật của chúng tôi để tạo ra một bảng điều khiển phân tích giúp các nhà nghiên cứu và nhà báo có thể theo dõi cuộc bầu cử. Bảng điều khiển sẽ thu thập dữ liệu về các quảng cáo chính trị đang chạy trên các nền tảng khác nhau và cung cấp "các cảnh hậu trường" để biết được cách những quảng cáo này được chia sẻ và nhắm mục tiêu.

Nhưng để đạt được mục tiêu này chúng tôi đã cần tới các nền tảng tuân theo [cam kết](https://blog.mozilla.org/blog/2019/02/13/facebook-answers-mozillas-call-to-deliver-open-ad-api-ahead-of-eu-election/) của chính họ để cung cấp dữ liệu thông qua API lưu trữ quảng cáo của họ.

Đây là những gì đã xảy ra.

#### Các nền tảng đã không cung cấp đủ dữ liệu
Vào ngày 29 tháng 3, Facebook đã bắt đầu [phát hành](https://blog.mozilla.org/blog/2019/02/13/facebook-answers-mozillas-call-to-deliver-open-ad-api-ahead-of-eu-election/) dữ liệu quảng cáo chính trị của mình thông qua một API có sẵn công khai. Chúng tôi nhanh chóng kết luận API này là [không đầy đủ](https://blog.mozilla.org/blog/2019/04/29/facebooks-ad-archive-api-is-inadequate/).

- Thông tin nhắm mục tiêu không có sẵn.
- Truy cập dữ liệu hàng loạt không được cung cấp.
- Dữ liệu không được gắn thẻ đúng.
- Tìm kiếm giống hệt nhau nhưng ra kết quả khác nhau.

Tình trạng API làm cho nó gần như không thể trích xuất dữ liệu cần thiết để điền vào bảng điều khiển mà chúng tôi đã hi vọng tạo ra để làm cho thông tin này dễ tiếp cận hơn.

Và mặc dù [Google](https://blog.mozilla.org/blog/2019/05/10/googles-ad-api-is-better-than-facebooks-but/) không cung cấp các tiêu chí nhắm mục tiêu mà các nhà quảng cáo sử dụng trên nền tảng, nhưng đã cung cấp quyền truy cập vào dữ liệu theo một định dạng cho phép việc nghiên cứu và phân tích thực tế.

Đó không phải là trường hợp của Facebook.

#### Vậy thì sao?

Phải mất cả tháng 4 để tìm ra cách làm việc xung quanh API để thu thập bất kỳ thông tin quảng cáo chính trị nào chạy trên nền tảng Facebook.

Sau vài tuần, hàng trăm giờ, và hàng ngàn lần nhấn phím, nhóm Mozilla đã tạo [báo cáo quảng cáo minh bạch của EU](http://adtransparency.mozilla.org/). Các báo cáo chứa số liệu thống kê tổng hợp về sự chi tiêu và các con số ấn tượng về các quảng cáo chính trị trên Facebook, Instagram, Google, và YouTube.

Mặc dù đây không phải là công cụ linh hoạt mà chúng tôi đã hình dung khi bắt đầu hành trình này nhưng chúng tôi hi vọng nó sẽ giúp ích.

Nhưng bất chấp nỗ lực của chúng tôi giúp Facebook gỡ rối hệ thống của họ, API đã bị lỗi từ ngày 18 tháng 5 đến ngày 26 tháng 5, khiến chúng tôi không thể sử dụng API và tạo ra bất kỳ báo cáo nào trong những ngày cuối cùng của cuộc bầu cử.

Tất cả những điều này đã được ghi nhận thông qua hàng chục báo cáo lỗi được gửi cho Facebook, chỉ ra các biện pháp để sửa lỗi API.

#### Lộ trình cho Facebook

Cuối cùng sự đóng góp của chúng tôi cho nỗ lực này trông rất khác so với những gì chúng tôi đã đặt ra ban đầu. Thay vì một công cụ, chúng tôi có [tài liệu](https://adtransparency.mozilla.org/eu/log/) chi tiết mỗi lần API bị lỗi, mọi rào cản gặp phải và một chuỗi [các mẹo và thủ thuật](https://adtransparency.mozilla.org/eu/methods/) để giúp mọi người sử dụng API.

Tài liệu này cung cấp cho Facebook một lộ trình rõ ràng để tạo các cải tiến cần thiết cho API hoạt động một cách hữu ích trước khi cuộc bầu cử tiếp theo diễn ra. Các cuộc bầu cử đã được thông qua, nhưng nhu cầu về sự minh bạch thông điệp chính trị thì không.

Trên thực tế, các cuộc bầu cử quan trọng dự kiến sẽ diễn ra gần như mỗi tháng cho đến cuối năm và Facebook gần đây đã tung ra công cụ này trên toàn cầu.

Chúng tôi cần Facebook tốt hơn. Chúng tôi cần một API thực sự có ích - không gây trở ngại cho các nhà nghiên cứu và các nhà báo phát hiện ra ai là người đã mua những quảng cáo, cách những quảng cáo này nhắm mục tiêu và người mà họ đang được phục vụ. Nó là một công việc quan trọng nhằm thông báo cho công chúng và các nhà hoạch định chính sách về bản chất và hậu quả của thông tin sai lệch.

Điều này là rất quan trọng trong việc nhận biết thông tin sai lệch. Đó là lý do tại sao chúng tôi lập kế hoạch để tiếp tục công việc của mình về vấn đề này và tiếp tục làm việc để làm sáng tỏ việc quảng cáo trực tuyến ảnh hưởng đến các cuộc bầu cử như thế nào. 

----

Bài viết được dịch từ: [Empowering voters to combat election manipulation](https://blog.mozilla.org/blog/2019/07/25/empowering-voters-to-combat-election-manipulation/)