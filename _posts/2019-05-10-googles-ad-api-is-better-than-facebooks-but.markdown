---
layout: post
title:  "API quảng cáo của Google tốt hơn của Facebook, nhưng…"
date:   2019-05-10 13:34:20
categories: General
author: Mozilla
image: "/assets/img/posts/googles-ad-api.png"
---
**… với một vài thiếu sót quan trọng. Công cụ của Google đáp ứng 4 trong 5 tiêu chuẩn tối thiểu của các chuyên gia**

Tháng trước, Mozilla [đã đưa ra phân tích](https://blog.mozilla.org/blog/2019/04/29/facebooks-ad-archive-api-is-inadequate/) về API lưu trữ quảng cáo của Facebook (Ad Archive API), một công cụ cho phép các nhà nghiên cứu hiểu được cách mà các quảng cáo chính trị nhắm đến mục tiêu người dùng Facebook. Mục tiêu của chúng tôi: để xác định xem Facebook có thực hiện lời hứa của mình về việc làm cho quảng cáo chính trị trở nên minh bạch hơn (nhưng họ đã không làm).

Hôm nay, chúng tôi đưa ra phân tích với API lưu trữ quảng cáo của Google. Google cũng hứa với Liên Minh Châu Âu rằng họ sẽ phát hành một công cụ quảng cáo minh bạch trước cuộc bầu cử Nghị viện EU 2019.

Phát hiện của chúng tôi: API của Google tốt hơn rất nhiều so với Facebook, nhưng vẫn chưa hoàn thiện. API của Google đáp ứng 4 trên [5 tiêu chuẩn tối thiểu](https://blog.mozilla.org/blog/2019/04/29/facebooks-ad-archive-api-is-inadequate/) của các chuyên gia (Facebook chỉ đạt 2 tiêu chuẩn)

Google làm tốt hơn nhiều so với Facebook trong việc cung cấp quyền truy cập dữ liệu ở một định dạng cho phép việc nghiên cứu và phân tích. Đó là một yêu cầu cực kỳ quan trọng; nó là cần thiết cho việc nghiên cứu cơ bản. Mặc dù dữ liệu Google cung cấp có thể sự dụng được nhưng nó không đầy đủ. Google không cung cấp dữ liệu về các tiêu chí nhắm mục tiêu mà các nhà quảng cáo sử dụng, gây khó khăn trong việc xác định ai đang cố gắng gây ảnh hưởng đến ai hoặc làm thế nào thông tin được lan truyền đi.

Dưới đây là các phân tích cụ thể của chúng tôi về API của Google:

[1]✅

Tiêu chuẩn của các nhà nghiên cứu: API mở, có chức năng cung cấp nội dung quảng cáo chính trị toàn diện.

API của Google: Liệt kê đầy đủ các quảng cáo, chiến dịch, và các nhà quảng cáo đang sẵn có, danh sách có thể tìm kiếm hoặc chọn bộ lọc. Toàn bộ cơ sở dữ liệu có thể được tải xuống hàng loạt và có thể phân tích theo từng phần. Tuy nhiên có những thiếu sót: không có dữ liệu về những đối tượng mà quảng cáo nhắm tới, như giới tính, tuổi, hoặc khu vực của họ. Và Google đã cung cấp ít dữ liệu hơn so với Facebook, có thể do định nghĩa về “các quảng cáo chính trị” của Google

[2]❌

Tiêu chuẩn của các nhà nghiên cứu: API mở, có chức năng cung cấp nội dung quảng cáo và thông tin liên quan đến tiêu chí nhắm mục tiêu.

API của Google: Mặc dù API cung cấp nội dung của các quảng cáo, giống như Facebook, nhưng nó không cung cấp thông tin về tiêu chí nhắm mục tiêu, nó cũng không cung cấp dữ liệu tương tác dữ liệu (ví dụ: lượt click). Dữ liệu liên quan đến việc nhắm mục tiêu và tương tác rất quan trọng với các nhà nghiên cứu vì nó cho phép họ thấy những kiểu người dùng mà nhà quảng cáo cố gắng gây ảnh hưởng và liệu các cố gắng của họ có thành công hay không.

[3]✅

Tiêu chuẩn của các nhà nghiên cứu: API mở, có chức năng cập nhật và có thể truy cập dữ liệu lịch sử.

API của Google: API dường như được cập nhật.

[4]✅

Tiêu chuẩn của các nhà nghiên cứu: API mở, có thể truy cập và chia sẻ cho mọi người

API của Google: Quyền truy cập công cộng có sẵn thông qua chương trình Google Cloud Public Datasets.

[5]✅

Tiêu chuẩn của các nhà nghiên cứu: API mở, có thể trao quyền, không giới hạn việc nghiên cứu và phân tích.

API của Google: Công cụ này có các thành phần hỗ trợ việc nghiên cứu, như khả năng tải xuống hàng loạt; không có giới hạn băng thông; bộ lọc tìm kiếm; và các đường dẫn cho quảng cáo.

Nhìn chung: mặc dù đạt điểm cao, nhưng vẫn chưa đủ để cho phép các nhà nghiên cứu tìm hiểu những thông tin sai lệch trên nền tảng của Google. Công ty cũng trì hoãn đáng kể việc phát hành API của họ, công bố trước vài tuần trước cuộc bầu cử EU sắp tới và gần hai tháng sau thời hạn họ đã hứa ban đầu.

Với các cuộc bầu cử EU sắp tới, chúng tôi hi vọng Google (và [Facebook](https://blog.mozilla.org/blog/2019/04/29/facebooks-ad-archive-api-is-inadequate/)) sẽ nhanh chóng hành động để cải thiện API quảng cáo của họ – hành động mà đáng lẽ phải được thực hiện từ nhiều tháng trước.

----

Bài viết được dịch từ: [Google’s Ad API is Better Than Facebook’s, But… ](https://blog.mozilla.org/blog/2019/05/10/googles-ad-api-is-better-than-facebooks-but/)