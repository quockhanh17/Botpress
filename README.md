# Botpress

## 1.	Tải và cài đặt Botpress:
- Tải Botpress source tại trang chủ của Botpress: https://botpress.com/

![Trangchubotpress](https://user-images.githubusercontent.com/93696035/146646686-ed8a04ff-93f4-48cd-aa65-f2a706660d7b.png)

- Sau khi tải source từ trang chủ, chúng tôi chạy file bp.exe để tiến hành cài đặt.

![bp](https://user-images.githubusercontent.com/93696035/146646785-f2adf9a7-d82b-435f-8c2e-2c9118601fae.png)

- Khi đã chạy và cài đặt thành công hệ thống sẽ báo “Botpress is exposed at: http://localhost:3000” đồng nghĩa với hệ thống Botpress đã hoạt động trên localhost:3000

## 2. Tạo bot và thiết lập bot:

- Để bắt đầu với việc tạo bot chúng ta cần đăng nhập vào localhost:3000

![Regist](https://user-images.githubusercontent.com/93696035/146647003-9cea46ac-0fa6-476c-b77a-9c4987f40122.png)

- Sau khi đăng nhập, nhấn vào Create Bot và chọn New Bot để bắt đầu tạo bot. Tại bảng tạo bot chúng ta sẽ nhập: tên bot, ID bot và kiểu bot.

![creat](https://user-images.githubusercontent.com/93696035/146647031-3bf81ec4-c53a-483c-8256-d51b270d4077.png)

## 3. Nhúng bot lên PHP:
−	Để nhúng Botpress lên PHP, chúng sẽ thêm vào cuối của trang Index câu lệnh:

![script 1](https://user-images.githubusercontent.com/93696035/146647265-37c09ccf-a7cd-4e00-92f8-402ff4f64ec7.png)

![script 2](https://user-images.githubusercontent.com/93696035/146647268-bd5bcb07-58b0-4a31-ba1e-5a5df6f94791.png)

−	Sau khi đã thêm câu lệnh, chúng ta sẽ đổi “your-url-here” và “your-bot-id” tương ứng lần lược với URL mà Botpress của chúng ta đang hoạt động và Bot ID mà chúng ta đã đặt khi tạo bot.

![nhung](https://user-images.githubusercontent.com/93696035/146647327-10890a56-4e50-4a84-b448-e7b3b8f3c6b2.png)

## 4. Chạy thử chương trình và kết quả:
−	Khi nhúng bot thành công thì phía dưới góc trái của trang PHP của chúng ta sẽ hiện một biểu tượng hộp thoại.

![ketqua2](https://user-images.githubusercontent.com/93696035/146647392-b58a51c7-4d4a-416f-95e3-1567f218ad6c.png)

−	Vậy là chúng ta đã có thể tương tác với bot.

![ketqua](https://user-images.githubusercontent.com/93696035/146647412-279e348d-413d-4815-a357-c244d68f8a25.png)

# Import Botpress Demo
## Bước 1: Chọn Create Bot -> Import Existing.

![Import 1](https://user-images.githubusercontent.com/93696035/146661136-c69746de-df56-4f98-880b-0d48a7d9166d.png)

## Bước 2: Chọn Browse và chọn đường dẫn đến File Botpress Demo đã tải.

![Import 2](https://user-images.githubusercontent.com/93696035/146661144-f11232e7-4f5b-4bbb-a1ec-2f3abf9574bc.png)
