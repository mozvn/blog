---
layout: post
title:  'Hôm nay Firefox đã bật mặc định việc chặn theo dõi cookie và đào tiền ảo từ bên thứ ba'
date:   2019-09-03
categories: ["Firefox", "Firefox for Mobile"]
image: "https://blog.mozilla.org/wp-content/uploads/2019/08/Fx_69_ETP_1200x660.jpg"
---

**Hôm nay, phiên bản Firefox trên máy tính và điện thoại Android cài đặt [mặc định]({{site.url}}/firefox/2019/06/04/when-it-comes-to-privacy-default-settings-matter.html), trao quyền và bảo vệ tất cả người dùng bằng cách chặn việc theo dõi cookie và đào tiền ảo từ bên thứ ba. Cột mốc này đánh dấu một bước ngoặt lón trong nhiều năm nỗ lực của chúng tôi để mang lại sự bảo vệ quyền lợi riêng tư mạnh mẽ hơn, khả dụng hơn khi sử dụng Firefox.**

#### Trình chống theo dõi nâng cao giúp người dùng kiểm soát nhiều hơn

Đối với phiên bản phát hành hôm nay, trình chống theo dõi nâng cao (Enhanced Tracking Protection) được bật mặc định cho tất cả người dùng trên thế giới như là một phần cấu hình "chuẩn" trong trình duyệt Firefox và sẽ khóa tất cả "trình theo dõi cookie từ bên thứ ba" được đề cập đến trong [danh sách ngắt kết nối](https://disconnect.me/trackerprotection). Chúng tôi [trước tiên đã bật tính năng mặc định này cho những người dùng mới]({{site.url}}/firefox/general/2019/06/04/firefox-now-available-with-enhanced-tracking-protection-by-default.html) vào tháng 6 năm 2019. Như là một phần của [hành trình](https://blog.mozilla.org/futurereleases/2018/10/23/the-path-to-enhanced-tracking-protection/) này, chúng tôi đã [kiểm tra](https://blog.mozilla.org/futurereleases/2019/02/20/enhanced-tracking-protection-testing-update/) nghiêm ngặt, [tinh chỉnh](https://blog.mozilla.org/blog/2019/01/29/todays-firefox-gives-users-more-control-over-their-privacy/), và cuối cùng đã tìm ra [một cách tiếp cận mới để chống theo dõi](https://blog.mozilla.org/futurereleases/2018/08/30/changing-our-approach-to-anti-tracking/), nó là vấn để cốt lõi để thực hiện lời hứa về quyền riêng tư và bảo mật của chúng tôi như là một khía cạnh trong trải nghiệm Firefox của bạn.

Hiện nay trên 20% người dùng Firefox bật chế độ chống theo dõi. Với bản phát hành hôm nay, chúng tôi kỳ vọng cung cấp sự bảo vệ cho 100% người dùng theo cấu hình mặc định. Trình chống theo dõi nâng cao hoạt động ngầm phía sau để ngăn một công ty hình thành hồ sơ của bạn dựa trên việc theo dõi hành vi duyệt web của bạn trên các trang web mà không có sự đồng ý của bạn hoặc do bạn không biết. Những hồ sơ và thông tin đó họ có thể đã bán hoặc sử dụng vào những mục đích mà bạn không bao giờ biết. Trình chống theo dõi nâng cao giúp giảm thiểu rủi ro này và đưa lại cho bạn quyền kiểm soát trải nghiệm trực tuyến của bạn.

Bạn sẽ biết khi nào trình chống theo dõi nâng cao hoạt động, khi bạn vào một trang web và thấy biểu tưởng hình chiếc khiên ở trên thanh địa chỉ

<img src="https://blog.mozilla.org/wp-content/uploads/2019/09/Screen-Shot-2019-09-03-at-13.51.17-600x74.png">

Khi bạn thấy biểu tượng chiếc khiên, bạn sẽ cảm thấy an toàn vì Firefox đã chặn hàng ngàn các công ty theo dõi hoạt động trực tuyến của bạn.

Đối với những người muốn xem danh sách những công ty chúng tôi đã chặn, bạn có thể nhấp vào biểu tưởng chiếc khiên, vào phần chặn nội dung (Content Blocking), và tới phần cookie (Cookies). Bạn sẽ thấy phần chặn theo dõi cookie (Blocking Tracking Cookies). Nhấp vào mũi tên bên tay phải, và bạn sẽ thấy danh sách các công ty đã được liệt kê theo dõi cookie mà Firefox đã chặn.

<div style="text-align:center">
<img src="https://blog.mozilla.org/wp-content/uploads/2019/08/ETP-Blocking-Cookies-300x264.png" style="width:239px">
</div>
<div style="text-align:center;margin-top:20px;margin-bottom:20px">
<img src="https://blog.mozilla.org/wp-content/uploads/2019/08/ETP-Blocked-Cookies-300x472.png" style="width:239px">
</div>

Nếu bạn muốn tắt việc chặn một trang cụ thể, bạn nhấp vào nút tắt chặn đối với trang web đó.

#### Bảo vệ quyền riêng tư của người dùng ngoài việc theo dõi cookie

Cookie không phải là một thực thể duy nhất theo dõi bạn trên web, cố gắng sử dụng những thứ mà bạn không biết hoặc không cho phép. [Đào tiền ảo](https://blog.mozilla.org/firefox/block-cryptominers-with-firefox/) là một ví dụ, nó truy cập CPU máy tính của bạn, làm chậm và tiêu hao pin máy của bạn để tạo ra những đồng tiền ảo làm lợi cho những người khác. Chúng tôi [đã giới thiệu tùy chọn chặn trình đào tiền ảo ở các phiên bản Firefox Nightly và Beta](https://blog.mozilla.org/futurereleases/2019/04/09/protections-against-fingerprinting-and-cryptocurrency-mining-available-in-firefox-nightly-and-beta/) trước và hôm nay đã đưa chức năng này vào trong "chế độ chuẩn" (Standard Mode) của phần tùy chọn chặn nội dung.

Một loại khác là các kịch bản mà bạn không muốn chạy trên trình duyệt của bạn, đó là [những kịch bản fingerprinting](https://blog.mozilla.org/firefox/how-to-block-fingerprinting-with-firefox/). Họ thu thập thông tin cấu hình máy tính của bạn khi bạn vào một trang web. Những thông tin này có thể được dùng để theo dõi bạn trên web, một vấn đề đã tồn tại nhiều năm nay. Để bảo vệ bạn khỏi các kịch bản fingerprinting, Firefox đã bật "chế độ nghiêm khắc" (Strict Mode). Trong một bản phát hành tương lai, chúng tôi dự định bật trình bảo vệ fingerprinting ở chế độ mặc định.

#### Phiên bản phát hành Firefox hôm nay

Để xem có gì mới hoặc những gì chúng tôi đã thay đổi trong phiên bản hôm nay, bạn có thể xem thêm ở [ghi chú phát hành](https://www.mozilla.org/firefox/69.0/releasenotes/).

Kiểm tra và tải xuống phiên bản Firefox mới nhất có sẵn [tại đây](http://mozilla.org/firefox/new).

----

Bài viết được dịch từ: [Today’s Firefox Blocks Third-Party Tracking Cookies and Cryptomining by Default](https://blog.mozilla.org/blog/2019/09/03/todays-firefox-blocks-third-party-tracking-cookies-and-cryptomining-by-default/)