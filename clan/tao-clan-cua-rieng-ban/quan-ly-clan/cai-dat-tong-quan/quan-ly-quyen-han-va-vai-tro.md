---
description: >-
  Quản lý quyền hạn và vai trò giúp bạn kiểm soát những gì mỗi thành viên có thể
  làm trong Clan, đảm bảo cộng đồng hoạt động an toàn và trật tự
---

# Quản lý quyền hạn và vai trò

### 1. Quản lý quyền hạn

Khi cộng đồng phát triển, số lượng thành viên tham gia và mức độ tương tác ngày càng lớn. Nếu không kiểm soát được quyền hạn, rất dễ xảy ra tình trạng spam tin nhắn, xóa nội dung quan trọng hoặc chỉnh sửa kênh ngoài ý muốn. Điều này không chỉ gây mất trật tự mà còn ảnh hưởng đến trải nghiệm chung của cả nhóm.

#### Các quyền hiện có trong hệ thống

<figure><img src="../../../../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

* **Administrator** – Toàn quyền quản lý clan và list channel (gần tương đương với chủ sở hữu).
* **Manage Clan** – Quản lý cài đặt clan, vai trò, kênh và hoạt động thành viên.&#x20;

{% hint style="info" %}
Tuy nhiên quyền **Manage Clan** <mark style="color:red;">**không nhìn thấy và không quản lý được toàn bộ danh sách kênh**</mark>, điểm này khác biệt so với Administrator.
{% endhint %}

* **Manage Channel** – Tạo, chỉnh sửa, xóa kênh.
* **Manage Thread** – Tạo, chỉnh sửa, xóa Chủ đề (bao gồm Chủ đề riêng tư).
* **Send Message** – Gửi tin nhắn trong kênh công khai (bao gồm Chủ đề/Thảo luận ngắn).
* **Delete Message** – Xóa tin nhắn trong kênh công khai (bao gồm Chủ đề/Thảo luận ngắn).
* **View Channel** – Xem kênh công khai.

{% hint style="info" %}
### Phân biệt các quyền trong Clan

* **Owner (Chủ sở hữu)**
  * Khi khởi tạo Clan, người tạo Clan sẽ mặc định là **Chủ sở hữu**.&#x20;
  * Không ai có thể kick Owner. Owner chỉ có thể **chuyển quyền sở hữu** cho người khác.
  * Quyền hạn cao nhất, làm được tất cả mọi hành động.
  * Có quyền quản trị tuyệt đối, bao gồm quản lý thành viên, vai trò, kênh, và toàn bộ thiết lập của clan.
* **Administrator (Quản trị viên)**
  * Quyền hạn chỉ dưới Owner, gần như toàn quyền quản lý clan.
  * Có thể quản lý danh sách kênh (list channel), vai trò, thành viên, và hầu hết các cài đặt.
  * Có thể kick Admin khác hoặc thành viên thường, **nhưng không thể kick Owner (Chủ sở hữu)**
{% endhint %}

#### Cách thiết lập quyền

{% stepper %}
{% step %}
Trong menu bên trái, chọn **Vai trò.**

![](<../../../../.gitbook/assets/unknown (30).png>)
{% endstep %}

{% step %}
Trong **Quyền mặc định**, bạn thiết lập những hành động cơ bản mà tất cả thành viên trong clan đều có thể thực hiện.

![](<../../../../.gitbook/assets/unknown (31).png>)
{% endstep %}

{% step %}
Chọn quyền bạn muốn áp dụng với tất cả mọi người và nhấn **Lưu thay đổi**&#x20;

![](<../../../../.gitbook/assets/unknown (32).png>)

{% hint style="info" %}
Mặc định, mọi người khi tham gia clan sẽ thuộc role **@everyone**.\
Với role này, nên chỉ bật các quyền tối thiểu như **Xem kênh** và **Gửi tin nhắn** để đảm bảo trật tự và an toàn cho cộng đồng.&#x20;
{% endhint %}
{% endstep %}
{% endstepper %}

### 2. Quản lý vai trò&#x20;

Không phải tất cả thành viên trong Clan đều cần quyền hạn giống nhau. Với Vai trò, bạn có thể tạo nhiều vai trò khác nhau có quyền hạn khác nhau. Ngoài ra, bạn có thể gán màu sắc, biểu tượng riêng cho từng nhóm. Điều này giúp Clan vận hành chuyên nghiệp hơn, dễ dàng quản lý khi cộng đồng của bạn lớn dần.

#### **Cách tạo và phân quyền**

{% stepper %}
{% step %}
Ở menu bên trái, chọn **Vai trò**&#x20;

![](<../../../../.gitbook/assets/unknown (37).png>)
{% endstep %}

{% step %}
Nhấn **Tạo Vai trò,** sau đó chỉnh sửa tên, màu và icon trong mục **Hiển thị.**&#x20;

<div align="left"><figure><img src="../../../../.gitbook/assets/image (62).png" alt="" width="292"><figcaption></figcaption></figure></div>

<div align="left"><figure><img src="../../../../.gitbook/assets/image (63).png" alt="" width="291"><figcaption></figcaption></figure></div>

{% hint style="info" %}
Dung lượng tối đa cho Biểu tượng vai trò là 256KB
{% endhint %}
{% endstep %}

{% step %}
Ở **Quản lý thành viên,** nhấn **Thêm thành viên** để thêm thành viên vào **Vai trò.**

{% hint style="success" %}
Bạn có thể thêm hoặc thu hồi quyền nâng cao bằng cách tạo **vai trò mới**, sau đó gán cho từng thành viên (thực hiện tại mục **Quản lý thành viên**).
{% endhint %}

<div align="left"><figure><img src="../../../../.gitbook/assets/image (64).png" alt="" width="317"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Trong **Quyền,** tùy chỉnh các quyền mà **Vai trò** đó có thể thực hiện (ví dụ: Quản trị, gửi tin nhắn, xóa tin nhắn...).

<div align="left"><figure><img src="../../../../.gitbook/assets/image (65).png" alt=""><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Nhấn **Lưu thay đổi** để lưu lại phân quyền.
{% endstep %}

{% step %}
Thay đổi thứ tự hiển thị của Vai trò.

<div align="left"><figure><img src="../../../../.gitbook/assets/image (47).png" alt="" width="365"><figcaption></figcaption></figure></div>

Bạn chỉ cần kéo thả từng Vai trò để sắp xếp thứ tự các Vai trò. Nếu thành viên được gán nhiều hơn 1 Vai trò, thì sẽ hiển thị theo thứ tự này.
{% endstep %}
{% endstepper %}

### 3. Ghi đè quyền hạn

Ghi đè quyền hạn là cách thiết lập quyền đặc biệt cho **Kênh riêng tư hoặc Chủ đề riêng tư**.

* Khi một Kênh/Chủ đề được tạo ở chế độ riêng tư, chỉ những **vai trò** hoặc **người dùng** được thêm trực tiếp mới có thể thấy.
*   Trong từng Kênh/Chủ đề riêng tư, bạn có thể **tùy chỉnh chi tiết quyền** cho từng vai trò hoặc người dùng:

    * Cho phép hoặc chặn xem Kênh.
    * Cho phép hoặc chặn gửi tin nhắn.
    * Cho phép hoặc chặn quản lý Chủ đề, xóa tin nhắn…

    **Cách tùy chỉnh chi tiết quyền trong Kênh/Chủ đề riêng tư:**

{% stepper %}
{% step %}
Nhấp vào bánh răng ở kênh/chuỗi thảo luận riêng tư của bạn

<div align="left"><figure><img src="../../../../.gitbook/assets/image (107).png" alt="" width="205"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Nhấn Quyền hạn trong menu bên trái&#x20;

<div align="left"><figure><img src="../../../../.gitbook/assets/image (108).png" alt="" width="143"><figcaption></figcaption></figure></div>
{% endstep %}

{% step %}
Tùy chỉnh quyền cho thành viên trong kênh của bạn&#x20;

<figure><img src="../../../../.gitbook/assets/image (109).png" alt=""><figcaption></figcaption></figure>
{% endstep %}

{% step %}
Nhấn lưu thay đổi để hoàn thành thao tác
{% endstep %}
{% endstepper %}

{% hint style="success" %}
Tính năng này giúp bạn quản lý linh hoạt: ví dụ một thành viên bình thường có thể chỉ đọc nội dung trong kênh riêng tư, còn quản trị viên phụ có thể vừa đọc vừa gửi tin nhắn.
{% endhint %}
