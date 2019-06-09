---
layout: post
title:  'Firefox hiện tích hợp sẵn trình chống theo dõi nâng cao bằng các bản cập nhật mặc định bổ sung cho Facebook Container, Firefox Monitor và Lockwise'
date:   2019-06-04 06:32:23
categories: ["Firefox", "General"]
image: "https://blog.mozilla.org/wp-content/uploads/2019/06/FX_Blog_EPT_Dave_Camp_1200x660-768x422.jpg"
---

**Nó đã được tích hợp vài tuần kể từ khi tôi [được thăng chức làm phó chủ tịch cấp cao của Firefox](https://blog.mozilla.org/blog/2019/04/25/firefox-and-emerging-markets-leadership/), người chịu trách nhiệm phát triển nền tảng web và toàn bộ Firefox. Là một nhân viên làm việc hơn 10 năm, tôi đã nhìn thấy rất nhiều điều trong ngành công nghệ từ các vi phạm dữ liệu, tính trung lập internet và sự thăng trầm của các công ty công nghệ. Tôi tin rằng Firefox đã và sẽ tiếp tục tạo ra một tác động lớn trong việc xây dựng các biện pháp bảo vệ cần thiết để giữ an toàn cho mọi người khi trực tuyến.**

Năm vừa qua, chúng ta đã thấy các công ty công nghệ nói về một trò chơi lớn về quyền riêng tư và họ nhận ra rằng, sau một số vụ bê bối toàn cầu mọi người cảm thấy không còn được an toàn khi trực tuyến. Tại Firefox, chúng tôi tin rằng để thực sự bảo vệ mọi người, chúng tôi cần thiết lập một tiêu chuẩn mới, đặt quyền riêng tư của mọi người lên hàng đầu. Chúng tôi đã nỗ lực thiết lập tiêu chuẩn này bằng cách cung cấp các tính năng liên quan đến quyền riêng tư, như [trình chống theo dõi ở chế độ duyệt web riêng tư](https://blog.mozilla.org/blog/2015/11/03/firefox-now-offers-a-more-private-browsing-experience/), chúng tôi đã làm điều này từ rất lâu trước khi những vấn đề này được đưa ra ánh sáng. Với sự nâng cao nhận thức về quyền riêng tư, chúng tôi cảm thấy rằng đây là thời điểm thích hợp cho bước tiếp theo trong việc bảo vệ trực tuyến mạnh mẽ hơn cho mọi người.

Năm ngoái, chúng tôi đã công bố [cách tiếp cận mới về việc chống theo dõi](https://blog.mozilla.org/futurereleases/2018/08/30/changing-our-approach-to-anti-tracking/) và cam kết của chúng tôi trong việc giúp mọi người an toàn khi sử dụng Firefox. Một trong những sáng kiến được nêu ra là chặn cookie từ các trình theo dõi của các bên thứ ba đã được liệt kê trong Firefox. Hôm nay, Firefox sẽ giới thiệu tính năng này, trình chống theo dõi nâng cao cài mặc định cho tất cả người dùng mới, để gây khó khăn hơn cho hàng ngàn công ty muốn theo dõi bạn. Ngoài ra, chúng tôi đang cập nhật các tính năng tập trung vào quyền riêng tư bao gồm tiện ích mở rộng Facebook Container, Lockwise trên phiên bản Firefox máy tính - một tiện ích giúp bạn lưu trữ mật khẩu của bạn an toàn trên tất cả các nền tảng, và bảng điều khiển mới của Firefox Monitor để quản lý nhiều địa chỉ email.

#### Trình bảo vệ theo dõi nâng cao chặn các trang web theo dõi bạn

Đối với người dùng mới cài đặt và tải Firefox lần đầu, trình chống theo dõi nâng cao sẽ tự động được bật theo mặc định như một phần của cài đặt "Tiêu chuẩn" trong trình duyệt và sẽ chặn cookie theo dõi của bên thứ ba theo như [danh sách ngắt kết nối](https://disconnect.me/trackerprotection). Chúng tôi nói kỹ hơn về việc theo dõi cookie [tại đây](https://blog.mozilla.org/firefox/control-trackers-with-firefox/). Trình chống theo dõi nâng cao sẽ thực sự vô hình đối với bạn và bạn sẽ chỉ thấy rằng nó đang hoạt động khi bạn truy cập một trang web và thấy biểu tượng cái khiên ở trên thanh địa chỉ, bên cạnh biểu tưởng "i". Khi bạn thấy biểu tượng cái khiên, bạn sẽ cảm thấy an toàn rằng Firefox đang chặn hàng ngàn công ty theo dõi bạn.

Đối với những người muốn xem những công ty nào chúng tôi chặn, bạn có thể bấm vào biểu tượng cái khiên, đi đến phần chặn nội dung, sau đó chọn cookie. Nó nên gọi là chặn theo dõi cookie. Sau đó, nhấp vào mũi tên ở phía bên tay phải và bạn sẽ thấy các công ty được liệt kê là các bên thứ ba có trình theo dõi cookie mà Firefox đã chặn. Nếu bạn muốn tắt chặn cho một trang web cụ thể, hãy bấm vào nút tắt chặn trang web này.

Đối với những người dùng hiện tại, chúng tôi sẽ đặt trình chống theo dõi nâng cao theo mặc định trong những tháng tới mà bạn sẽ không phải thay đổi gì cả. Nếu bạn không thể chờ đợi, bạn có thể bật chức năng này bằng cách bật biểu tượng trình đơn (hình ba dòng kẻ ngang) bên phải của trình duyệt của bạn, sau đó vào phần chặn nội dung. Đi tới phần tùy chọn riêng tư của bạn và chọn phần thiết lập tùy chỉnh ở bên phải. Đánh dấu vào hộp kiểm cookie và đảm bảo rằng "trình theo dõi bên thứ ba" được chọn. Để tìm hiểu thêm về cài đặt bảo mật và quyền riêng tư của chúng tôi hãy xem [tại đây](https://support.mozilla.org/en-US/kb/content-blocking).

<div style="text-align:center">
<img style="width:600px" src="https://blog.mozilla.org/wp-content/uploads/2019/05/ETP_EN_Custom_PC_Cropped-600x508.jpg">
</div>
<br/>
<p style="text-align:center;"><i>Đối với người dùng hiện tại, đi đến phần tùy chọn quyền riêng tư, nhấp vào thiết bị tùy chỉnh và đánh dấu vào hộp kiểm Cookie</i></p>

#### Facebook Container mới nhất chặn các theo dõi từ các trang web.

Đầu năm nay, Mozilla đã được công ty [Fast Company](https://www.fastcompany.com/most-innovative-companies/2019/sectors/security) vinh danh là một trong [những công ty sáng tạo nhất thế giới](https://blog.mozilla.org/internetcitizen/2019/03/05/fast-company-innovative-2019/). Đáng chú ý là tiện ích mở rộng [Facebook Container](https://addons.mozilla.org/en-US/firefox/addon/facebook-container/) của chúng tôi đóng vai trò to lớn trong việc giúp chúng tôi có được vị trí này. Với hơn hai triệu lượt tải xuống kể từ khi ra mắt, Facebook Container của chúng tôi là tiện tích mở rộng giúp bạn kiểm soát và cô lập hoạt động web của mình với Facebook ([chẳng hạn theo dõi bạn trên web](https://blog.mozilla.org/firefox/facebook-container-extension/)). Hôm nay, chúng tôi đã phát hành bản cập nhật mới nhất cho Facebook Container, điều này ngăn Facebook theo dõi bạn trên các trang web có nhúng các đoạn mã của Facebook như các nút Like, Share.

Ví dụ, khi bạn đang ở trên một trang web tin tức và đọc một bài báo, bạn thường thấy các nút Like và Share của Facebook. Facebook Container sẽ chặn các nút này và tất cả các kết nối đến các máy chủ Facebook, để Facebook không thể theo dõi lượt truy cập của bạn trên các trang web này. Việc này khiến Facebook khó khăn hơn nhiều trong việc xây dựng các [shadow profile](https://theconversation.com/shadow-profiles-facebook-knows-about-you-even-if-youre-not-on-facebook-94804) của những người chưa có tài khoản Facebook. Bạn sẽ biết việc chặn có hiệu lực khi bạn nhìn thấy huy hiệu hàng rào màu tím của Facebook Container.

<div style="text-align:center">
<img style="width:600px" src="https://blog.mozilla.org/wp-content/uploads/2019/05/FBC_EN-600x360.jpg">
</div>
<br/>
<p style="text-align:center;"><i>Facebook Container sẽ chặn các nút này và tất cả các kết nối đến máy chủ Facebook</i></p>


Để thêm phiên bản mới nhất của Facebook Container, hãy truy cập [tại đây](https://addons.mozilla.org/en-US/firefox/addon/facebook-container/).

#### Gặp gỡ Firefox Lockwise: Quản lý mật khẩu của bạn một cách an toàn và mang chúng đi mọi nơi

Mùa hè năm ngoái, chúng tôi đã mang đến cho bạn [Firefox Lockbox cho iOS](https://blog.mozilla.org/blog/2018/07/10/introducing-firefoxs-first-mobile-test-pilot-experiments-lockbox-and-notes/), và vào tháng 3 năm nay chúng tôi đã công bố cả 2 bản [Firefox Lockbox cho Android](https://blog.mozilla.org/blog/2019/03/26/firefox-lockbox-now-on-android-keeping-your-passwords-safe/) và [phiên bản được tối ưu hóa cho iPad](https://blog.mozilla.org/firefox/lockbox-on-the-ipad/) để mở rộng hệ sinh thái. Một trong những tính năng được yêu cầu nhiều nhất từ người dùng là tìm cách quản lý mật khẩu của họ. Hôm nay, chúng tôi sẽ giới thiệu một tiện ích mở rộng cho máy tính để bàn Firefox có tính năng này và hoàn thiện sản phẩm hơn, chúng tôi giờ gọi nó là Firefox Lockwise.

<iframe width="560" height="315" src="https://www.youtube.com/embed/8VoheBpsLoY" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br/>
Là một phần của bộ sản phẩm Firefox Lockwise, trước đây gọi là Firefox Lockbox, tiện ích mở rộng trên máy tính để bàn sẽ cung cấp cho bạn quyền kiểm soát nhiều hơn đối với các mật khẩu đã được lưu trữ mà được chia sẻ từ mọi thiết bị. Tiện ích này sẽ cung cấp một điểm tiếp xúc bổ sung để lưu trữ, chỉnh sửa và truy cập mật khẩu của bạn. Tiện ích này cung cấp trải nghiệm nâng cao cho thông tin đăng nhập đã lưu của bạn, điều này sẽ cho phép bạn quản lý và tương tác nhiều hơn với mật khẩu được lưu trên Firefox. Bạn sẽ nhận thấy trải nghiệm tích hợp liền mạch trong Firefox khi bạn chuyển từ máy tính sang thiết bị di động, với giao diện và các tính năng chính tương tự để dễ dàng điều hướng và truy cập vào các thông tin đăng nhập của bạn.

Firefox Lockwise mới trên máy tính bàn bao gồm các tính năng:

- Quản lý danh sách mật khẩu đã lưu của bạn - Giao diện bảng điều khiển mới giúp dễ dàng cập nhật và quản lý danh sách đã lưu của bạn. Nếu bạn không còn thường xuyên truy cập trang web, bạn có thể dễ dàng xóa mật khẩu đã lưu. Và đối với các trang web bạn truy cập thường xuyên bạn có thể nhanh chóng xem và chỉnh sửa thông tin đang được lưu trữ, giúp bạn dễ dàng kiểm soát quyền riêng tư trực tuyến.
- Truy cập mật khẩu của bạn ở bất cứ đâu - Cả ứng dụng di động và tiện ích mở rộng trên máy tính đều có thể giúp bạn truy cập nhanh chóng vào trang web của bạn, bất kể bạn sử dụng thiết bị nào.

Cho dù bạn là ai, hãy thử Firefox Lockwise, có trên [iOS](https://app.adjust.com/qywno6t?redirect=https%3A%2F%2Fitunes.apple.com%2Fapp%2Fid1314000270%3Fmt%3D8) và [Android](https://app.adjust.com/gi0ycmr?redirect=https%3A%2F%2Fplay.google.com%2Fstore%2Fapps%2Fdetails%3Fid%3Dmozilla.lockbox), và bây giờ là một [tiện ích trên Firefox dành cho máy tính để bàn](https://lockwise.firefox.com/)

#### Firefox Monitor thêm bảng điều khiển để quản lý nhiều địa chỉ thư điện tử

Kể từ khi [Firefox Monitor ra mắt](https://blog.mozilla.org/blog/2018/09/25/introducing-firefox-monitor-helping-people-take-control-after-a-data-breach/), một dịch vụ miễn phí thông báo cho bạn khi thư điện tử của bạn là một phần của việc vi phạm dữ liệu, hơn 635.000 người đã đăng ký thông báo. Người dùng đã kiểm tra nhiều thư điện tử của mình, do đó tính năng quản lý nhiều tài khoản là tính năng hàng đầu và yêu cầu thường xuyên. Hôm nay, chúng tôi sẽ ra mắt một bảng điều khiển trung tâm để giúp bạn theo dõi và quản lý nhiều địa chỉ thư điện tử, cho dù đó là tài khoản cá nhân hay địa chỉ thư dùng trong công việc.

Thông qua bảng điều khiển, bạn sẽ nhận được nhanh chóng bảng tóm tắt các bản cập nhật cho tất cả các tài khoản thư điện tử mà bạn đã đăng ký. Bạn có thể dễ dàng xác định email nào đang bị theo dõi, có bao nhiêu vi phạm dữ liệu đã biết có thể làm lộ thông tin của bạn và đặc biệt có thể là việc có bất kỳ mật khẩu nào bị rò rỉ qua các vi phạm đó. Thêm một email mới vào tài khoản Firefox Monitor rất đơn giản, và cho dù bạn đang quản lý một hoặc nhiều tài khoản email mới, bạn sẽ có thể chọn một email chính để nhận tất cả các thông báo và cảnh báo. Chúng tôi đã thêm một biện pháp an toàn để đảm bảo rằng tất cả email phải được xác minh trước khi chúng được kích hoạt.

<img src="https://blog.mozilla.org/wp-content/uploads/2019/05/Monitor_MobileDash_EN-600x806.jpg">
<br/>
<p style="text-align:center;"><i>Xác định email nào đang bị theo dõi, có bao nhiêu vi phạm dữ liệu đã được biết có thể làm lộ thông tin của bạn hay thậm chí là lộ thông tin mật khẩu trên các vi phạm đó.</i></p>

Trở thành một phần của các vi phạm dữ liệu không phải là điều thú vị, nhưng theo dõi và biết nơi thông tin cá nhân của bạn có thể bị công khai là một trong những bước đầu tiên để kiểm soát quyền riêng tư trực tuyến của bạn.

Chúng tôi mời bạn xem bảng điều khiển vi phạm trên [Firefox Monitor](http://monitor.firefox.com/)

----

Bài viết được dịch từ: [Firefox Now Available with Enhanced Tracking Protection by Default Plus Updates to Facebook Container, Firefox Monitor and Lockwise](https://blog.mozilla.org/blog/2019/06/04/firefox-now-available-with-enhanced-tracking-protection-by-default/)