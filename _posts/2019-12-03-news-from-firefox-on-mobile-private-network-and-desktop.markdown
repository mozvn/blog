---
layout: post
title:  'Tính năng mới của phiên bản Firefox trên điện thoại và trên máy tính, và Firefox Private Network'
date:   2019-12-03
categories: ["Firefox", "Firefox for mobile", "General"]
image: "https://blog.mozilla.org/wp-content/uploads/2019/11/Firefox71-1-trillion-B.jpg"
---

Khi một năm sắp kết thúc, chúng tôi nhìn lại những gì đã hoàn thành. Như đã được đề cập nhiều trên báo chí gần đây, năm nay có thể là [dấu ấn của sự phục hưng quyền riêng tư của chúng tôi](https://www.fastcompany.com/90428050/firefox-at-15-its-rise-fall-and-privacy-first-renaissance). Chúng tôi xây dựng các biện pháp bảo vệ quyền riêng tư bổ sung trên trình duyệt bao gồm [việc cấu hình mặc định chặn các trình theo dõi cookie và đào tiền ảo của các bên thứ ba](https://blog.mozilla.org/blog/2019/09/03/todays-firefox-blocks-third-party-tracking-cookies-and-cryptomining-by-default/) và tạo ra một [bản báo cáo dễ nhìn để phơi bày ra các trình theo dõi và thu thập các hành vi duyệt web của bạn](https://blog.mozilla.org/blog/2019/10/22/latest-firefox-brings-privacy-protections-front-and-center-letting-you-track-the-trackers/). Đến hôm nay chúng tôi đã chặn hơn 1 nghìn tỷ các yêu cầu từ các trình theo dõi cố gắng theo dõi bạn trên web! Quyền riêng tư luôn là một phần [DNA](https://www.mozilla.org/about/manifesto/) của chúng tôi. Chúng tôi luôn tin tưởng vào vai trò của chúng tôi luôn [giúp mọi người kiểm soát nhiều hơn cuộc sống trực tuyến của họ](https://blog.mozilla.org/blog/2019/06/04/the-web-the-world-needs-can-be-ours-again-if-we-want-it/).

<img src="https://ffp4g1ylyit3jdyti1hqcvtb-wpengine.netdna-ssl.com/wp-content/uploads/2019/11/tracker-graph_EN1.gif">
<br/>
<p style="text-align:center;"><i>1 nghìn tỷ yêu cầu theo dõi đã bị chặn với trình bảo vệ theo dõi nâng cao</i></p>

Hôm nay, chúng tôi đã có một cái gì đó cho tất cả mọi người, cho những người am hiểu về công nghệ để thử các tính năng và các sản phẩm đầu tiên về quyền riêng tư hoặc những người thích quá trình đa nhiệm trên máy tính để bàn của họ. Chúng tôi có nhiều dự định cho năm sau và sẽ tiếp tục giữ lời hứa của chúng tôi để tạo ra những tính năng và sản phẩm tập trung vào quyền riêng tư. Trước khi chúng tôi giới thiệu rộng rãi tới người tiêu dùng, chúng tôi vẫn còn có một số điều cần phải làm. Vì vậy hôm nay chúng tôi khởi động giai đoạn tiếp theo của chúng tôi trong quá trình thử nghiệm bản Firefox Private Network, và ứng dụng Firefox Review mới nhất dành cho Android sử dụng GeckoView. Mặc dù năm nay sắp trôi qua, giống như những yêu tinh của ngài Santa chúng tôi làm việc suốt ngày đêm để cung cấp các thử nghiệm và phiên bản mới nhất của trình duyệt Firefox cho máy tính để bàn và iOS.

#### Bản thử nghiệm Firefox Private Network mới nhất bảo về người dùng đúng dịp nghỉ lễ

Vào tháng chín, chúng tôi [đã giới thiệu bản phát hành thử nghiệm của phiên bản Firefox Private Network (FPN)](https://blog.mozilla.org/blog/2019/09/10/firefoxs-test-pilot-program-returns-with-firefox-private-network-beta/), một tiện ích mở rộng cung cấp một đường dẫn web mã hóa, an toàn để bảo vệ thông tin cá nhân và kết nối của bạn khi bạn sử dụng trình duyệt Firefox. Từ lúc đó, chúng tôi đã nhận được phản hồi từ những người thử nghiệm về cách họ sử dụng FPN, các biện pháp bảo vệ, và chúng tôi đã tìm hiển về những trang web không tương thích cũng như các vấn đề liên quan đến kết nối. Điều này cho phép chúng tôi nhanh chóng xác định và sửa lỗi, và đảm bảo một sản phẩm ổn định.

Khi chúng tôi tiếp tục thử nghiệm bản beta, chúng tôi đang xem xét nhiều cách khác nhau để mang lại sự bảo vệ quyền riêng tư bổ sung cho người dùng của chúng tôi. Hôm nay chúng tôi công bố một [bản thử nghiệm beta bổ sung cho những người dùng tài khoản Firefox ở Mỹ, những người không có cơ hội tham gia vào nhóm ban đầu và quan tâm đến việc thử nghiệm FPN](http://fpn.firefox.com/).

Trong giai đoạn tiếp theo của phiên bản beta của chúng tôi, chúng tôi [đang cung cấp một dịch vụ miễn phí trong một khoảng thời gian nhất định cho phép bạn mã hóa các kết nối Firefox của bạn tối đa 12 giờ mỗi tháng](https://fpn.firefox.com/vpn?utm_medium=referral&utm_source=blog.mozilla.org&utm_campaign=fx-71). Với những ngày nghỉ sắp tới, FPN không thể đến vào thời điểm thuận tiện hơn. Chúng tôi biết mọi người đang đi du lịch và có thể phải dựa vào mạng wifi công cộng không bảo mật, như mạng ở sân bay, tại quán cà phê địa phương của bạn hoặc thậm chí tại phòng khám bác sĩ của bạn. FPN cung cấp đường truyền internet mã hóa do đó giúp bạn yên tâm bất cứ khi nào bạn sử dụng trình duyệt của chúng tôi.

[Thời gian thử nghiệm này đã sẵn sàng ở Mỹ trên trình duyệt Firefox](https://fpn.firefox.com/vpn?utm_medium=referral&utm_source=blog.mozilla.org&utm_campaign=fx-71) và bạn sẽ cần một [tài khoản Firefox](https://www.mozilla.org/en-US/firefox/accounts/) để thử dịch vụ. Bạn có thể đăng ký trực tiếp từ tiện ích mở rộng [tại đây](http://fpn.firefox.com/).

Đối với những người muốn mở rộng sự bảo vệ của họ ngoài trình duyệt, bạn có thể đăng ký để trở thành một trong những người đầu tiên trải nghiệm thành viên mới của gia đình FPN. Trong tháng này [chủ tài khoản Firefox](https://www.mozilla.org/firefox/accounts/) có thể yêu cầu lời mời trải nghiệm sự bảo vệ cấp độ thiết bị với VPN mới (virtual private network) đầy đủ thiết bị của chúng tôi. [Tham gia danh sách chờ](https://fpn.firefox.com/vpn?utm_medium=referral&utm_source=blog.mozilla.org&utm_campaign=fx-71) và nếu bạn đủ điều kiện, chúng tôi sẽ xúc tiến công việc với một đường dẫn để truy cập VPN với mức giá hiện tại là $4.99 mỗi tháng. Hiện tại VPN sẽ chỉ có trên Windows 10, và giống như phần còn lại của FPN, nó chỉ khả dụng cho các chủ tài khoản Firefox ở Mỹ. Giá cả và các nền tảng khác sẽ tiếp tục phát triển và chúng tôi mong muốn được nghe phản hồi của bạn.

#### Những người thử nghiệm bản beta dành cho thiết bị di động chú ý: đã có bản phát hành Firefox Preview Beta

Mùa hè vừa qua chúng tôi đã giới thiệu [Firefox Preview](https://blog.mozilla.org/futurereleases/2019/06/27/reinventing-firefox-for-android-a-preview/) Beta, phiên bản thử nghiệm có sẵn công khai của trình duyệt Firefox dành cho Android sử dụng [GeckoView](https://hacks.mozilla.org/2019/06/geckoview-in-2019/), một công cụ trình duyệt di động hiệu suất cao của Mozilla. Nó cho phép chúng tôi cung cấp trải nghiệm trực tuyến tốt hơn, nhanh hơn và riêng tư hơn cho người dùng Android. Hôm nay, chúng tôi có một bản cập nhật về tiến trình của chúng tôi, bao gồm các tính năng mới mà chúng tôi đã thêm vào kể từ phiên bản beta đầu tiên vào tháng 6. Để tìm hiểu thêm hãy xem [thông báo ở đây](https://blog.mozilla.org/futurereleases/2019/12/03/firefox-preview-beta-reaches-another-milestone).

#### Picture-in-Picture có sẵn trong phiên bản Firefox phát hành hôm nay

Có một sự thật rằng chúng ta thường làm nhiều việc cùng một lúc kể cả khi là kiểm tra thư điện tử trong cuộc họp hay mua sắm trực tuyến và xem video sản phẩm trước khi chúng ta nhấn nút mua. Tất cả chúng ta đều có cuộc sống bận rộn và muốn tận dụng tối đa từng phút. Trong ngày hôm nay chúng tôi đã triển khai Picture-in-Picture có sẵn trong tất cả các trang web video.

Picture-in-Picture cho phép một video được chứa trong một cửa sổ nhỏ và riêng biệt mà vẫn có thể xem được cho dù bạn chuyển từ thẻ này sang thẻ khác hay bên ngoài trình duyệt Firefox. Để xem Picture-in-Picture có sẵn với bạn hay không, hãy di chuột qua video để xem có xuất hiện một tùy chọn nhỏ màu xanh dương "Picture in Picture" hay không. Khi bạn nhấp vào tùy chọn, video sẽ tự bật và sẽ luôn ở vị trí cửa sổ trên cùng, cho phép bạn tiếp tục xem video ngay cả khi bạn chuyển thẻ. Hiện tại, Picture-in-Picture sẽ chỉ hỗ trợ trên hệ điều hành Windows. Nó sẽ có sẵn cho MacOS và Linux trong phiên bản trình duyệt phát hành vào tháng 1 năm 2020.

<img src="https://blog.mozilla.org/wp-content/uploads/2019/11/en-768x323.png">
<br/>
<p style="text-align:center;"><i>Di chuột của bạn vào video để thấy một tùy chọn màu xanh dương "Picture in Picture"</i></p>


Để xem có gì mới và thay đổi trên phiên bản phát hành bạn có thể xem [các ghi chú phát hành](https://www.mozilla.org/firefox/71.0/releasenotes/) của chúng tôi.

Kiểm tra và tải xuống bản Firefox mới nhất [tại đây](http://mozilla.org/firefox/new).

----

Bài viết được dịch từ: [News from Firefox on Mobile, Private Network and Desktop](https://blog.mozilla.org/blog/2019/12/03/news-from-firefox-on-mobile-private-network-and-desktop/)