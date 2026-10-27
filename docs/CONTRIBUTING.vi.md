# Hướng dẫn đóng góp

[Tiếng Việt](../README.md) · [English](readme/en.md) · [简体中文](readme/zh-CN.md)

## Thay đổi về bằng chứng

Bắt đầu bằng một ID bản ghi ổn định trong `data/evidence.json`. Cung cấp URL/DOI của bài báo gốc, thiết kế nghiên cứu, quần thể, đối tượng so sánh, kết cục, ước lượng và khoảng ước lượng, cùng nội dung bạn thực sự đã đọc: các phần liên quan của toàn văn, bản tóm tắt, siêu dữ liệu hoặc chưa đọc. Nêu ngày và giới hạn của việc kiểm tra. Với nguồn không truy cập được, hãy ghi lại việc truy cập thất bại thay vì tuyên bố đã xác minh.

Khi sửa bản ghi hiện có, dùng lại ID; giữ nguyên danh tính lịch sử của `originalClaim` và `originalClaimRaw`. Ghi kết luận xác minh vào `finding`, không được sửa lại phát biểu gốc để xóa bỏ sai sót. Trước khi thêm bản ghi, kiểm tra xem nội dung đó đã được yếu tố khác bao quát hay chưa; không chia cùng một nghiên cứu thành nhiều “lợi ích kéo dài tuổi thọ” có thể cộng dồn.

- Xếp hạng kết luận được hiển thị về tử vong do mọi nguyên nhân, không dựa vào uy tín của tạp chí. Kết quả không ghi nhận tác động trong nghiên cứu ngẫu nhiên có thể là bằng chứng mạnh hơn một mối liên hệ lớn trong nghiên cứu quan sát.
- Giữ nguyên giới hạn về quần thể và chỉ định. Không biến bằng chứng điều trị bệnh thành khuyến nghị cho người khỏe mạnh.
- Giữ nguyên HR/RR/OR, chiều so sánh, thời gian theo dõi và mức tin cậy. Nếu không có khoảng ước lượng hoặc nguy cơ tuyệt đối, hãy nêu rõ; không tự bịa ra.
- Liên kết đến nghiên cứu gốc. Không đưa toàn văn bài báo hoặc hình ảnh của bên thứ ba vào kho mã khi chưa kiểm tra điều khoản sử dụng.
- Phân biệt mối liên hệ, can thiệp có tính nhân quả, tiêu chí đánh giá gián tiếp và bằng chứng chưa đủ. Các mức xếp hạng của dự án không phải là một đánh giá GRADE đầy đủ.

## Dịch thuật

Các bản ghi tiếng Anh nằm trong `locales/en.json`; tiếng Việt, Tây Ban Nha, Pháp, Đức, Bồ Đào Nha, Nhật và Ả Rập nằm trong `locales/{vi,es,fr,de,pt,ja,ar}.json`. Mỗi ngôn ngữ hoàn chỉnh phải bao quát cùng các ID bản ghi ổn định, đủ 11 trường cốt lõi và các ghi chú nguồn theo thứ tự ban đầu. Các khóa giao diện và thuật ngữ phải khớp với `locales/interface.json`; thiếu ngôn ngữ hoặc trường sẽ khiến bản dựng nghiêm ngặt thất bại, và sao chép văn bản tiếng Anh không được coi là hoàn thành bản dịch sang ngôn ngữ khác.

Một thay đổi về y khoa phải cập nhật đồng thời tiếng Trung, tiếng Anh và cả bảy ngôn ngữ bổ sung. Giữ nguyên loại hiệu ứng, ước lượng, mức tin cậy, chiều so sánh, quần thể, ý phủ định và các giới hạn. Giữ `originalClaim` mang tính lịch sử tách biệt với kết luận hiện tại. Tiêu đề bài báo gốc và các bản lưu tiếng Trung được ghi nhãn rõ ràng có thể giữ nguyên ngôn ngữ gốc.

Các sửa đổi về y khoa phải được đồng bộ ở chín ngôn ngữ và HTML được tạo; bản dịch phải nêu đủ đối tượng và quan hệ so sánh trong câu, không được trau chuốt lời văn để nâng mức độ khuyến nghị. Khi giữ nguyên ngôn ngữ của bản lưu tiếng Trung gốc, ghi chú nguồn và nội dung gốc của các đợt xác minh, giao diện phải ghi nhãn rõ ràng. Kiểm tra cấu trúc và số liệu không thay thế được việc đọc duyệt ngữ nghĩa; dịch thuật cũng không đồng nghĩa với việc độc lập đọc lại bài báo. Bản đánh giá phải nêu phạm vi thực sự đã đọc, không được tuyên bố có chứng nhận của chuyên gia y khoa bản ngữ.

Lưu các bản dịch đã được duyệt trong hệ thống quản lý phiên bản. Sau khi xác thực, kiểm tra từng ngôn ngữ trên máy tính và thiết bị di động, các phần chi tiết dài và bản xuất; tiếng Ả Rập còn cần kiểm tra RTL, khoảng số, DOI và PNG. Giữ các lưu ý giới hạn của nghiên cứu luôn hiển thị và không thêm dữ liệu không có căn cứ vào sơ đồ.

## Nội dung cho người đọc và thuật ngữ

Các thẻ công khai dùng `locales/readers/{zh,en,vi,es,fr,de,pt,ja,ar}.json`. Mỗi nghiên cứu cần một `summary` ngắn gọn và một `takeaway` thực tiễn; `title` tùy chọn có thể thay thế tiêu đề nguồn mang phong cách biên tập hoặc kiểm toán. Viết cho người đọc, giữ nguyên phép so sánh, quần thể và sự không chắc chắn, đồng thời giữ nguyên bản ghi nguồn chi tiết. Cập nhật đồng thời cả chín ngôn ngữ. Các bản lưu phát biểu gốc không được hiển thị trong giao diện dành cho người đọc.

`data/glossary.json` giải thích các chữ viết tắt chuyên môn bằng cả chín ngôn ngữ. Ghi chú dẫn nguồn tiếng Việt nằm trong `locales/citations.vi.json`, với khóa là URL nguồn. Phân biệt HR, RR, OR và các tỷ số thời gian sống còn. Kiểm tra thao tác di chuột trên máy tính, tiêu điểm bàn phím và thao tác chạm trên thiết bị di động, bao gồm đóng bằng phím Escape, thứ tự lớp của hộp thoại và khả năng vừa khung nhìn. Biểu trưng vector gốc là `assets/logo.svg`.

## Dựng và kiểm tra

Dùng Python 3.10 trở lên. Sao chép kho mã, rồi dựng, xác thực và xem trước:

```sh
git clone https://github.com/ninhhaidang/HowToLiveLonger.git
cd HowToLiveLonger
python3 scripts/build.py
python3 scripts/validate.py --check-build
python3 -m http.server 8000
```

Truy cập <http://localhost:8000>. Sau khi sửa mẫu hoặc dữ liệu, dựng lại và đưa `index.html` được tạo vào commit.

Trình xác thực kiểm tra lược đồ, ID, các trường nguồn, cả chín ngôn ngữ, loại hiệu ứng/khoảng tin cậy và các token số, thông tin nguồn gốc được lưu trữ và khả năng tái tạo đầu ra. Công cụ này không thể xác lập tính hợp lệ về lâm sàng, sắc thái bản dịch, khả năng truy cập URL hay chất lượng hình ảnh. Điều tra mọi lỗi thay vì nới lỏng một phép kiểm tra để vượt qua xác thực.

Mở chính tệp `index.html` được tạo, rồi kiểm tra cả chín ngôn ngữ ở độ rộng máy tính và thiết bị di động: tìm kiếm, bộ lọc danh mục và mức bằng chứng, tính nhất quán giữa bảng và cây, phần chi tiết và thao tác đóng bằng bàn phím, khôi phục trạng thái, tải CSV/JSON, sao chép tóm tắt và thẻ PNG. Tệp tải xuống thực sự phải phân tích được hoặc mở được; chỉ phát một sự kiện nhấp không phải là bằng chứng thành công. Giữ các lưu ý giới hạn của nghiên cứu luôn hiển thị trong các bản tóm tắt/thẻ được chia sẻ.

## Đánh giá và bàn giao

Mô tả thay đổi cần xác định phiên bản đầu vào cố định, các tệp đã thay đổi, những kiểm tra thực sự đã thực hiện kèm bằng chứng có thể truy cập, và những gì chưa được xác minh. Liên kết đến một bản ghi, dòng tệp hoặc đầu ra cụ thể, không chỉ ghi “xem cuộc trò chuyện của tôi”. Với thay đổi về bằng chứng, người đánh giá cần độc lập kiểm tra nghiên cứu được trích dẫn và các ngôn ngữ bị ảnh hưởng; việc tự kiểm tra khi triển khai không phải là nghiệm thu cuối cùng.

Các README gốc làm mốc ban đầu bằng tiếng Trung và tiếng Anh nằm tại `docs/original-readme.*.md`; giữ nguyên từng byte, không đưa vào dịch tự động hoặc viết lại theo kết luận y khoa mới. Khi cập nhật bản ghi y khoa tiếng Trung, đồng bộ tất cả bản dịch và HTML được tạo; ngày xác minh chỉ áp dụng cho phạm vi thực sự đã đọc trong lần đó.

Kho mã giữ nguyên giấy phép [Unlicense](../LICENSE) hiện có. Giữ thông tin ghi công tác giả và nguồn. Các bài báo được liên kết và tài liệu của bên thứ ba có điều khoản riêng. Không đưa thông tin xác thực, dữ liệu y tế riêng tư, trạng thái tài khoản cục bộ, các thư viện phụ thuộc hoặc không gian làm việc tạm thời của tác nhân vào phần đóng góp.

## Xuất bản

Dựng và xác thực cục bộ trước khi đẩy lên. Đưa cả thay đổi nguồn và `index.html` được tạo vào commit. Khi được bật, GitHub Pages phục vụ nhánh `main` từ thư mục gốc của kho mã; `.nojekyll` bỏ qua xử lý Jekyll. Không đưa các tệp workflow vào kho mã này.

Trang công khai của upstream là <https://geekan.github.io/HowToLiveLonger/>. Có thể mở bản tiếng Việt của fork này ngoại tuyến tại `index.html#lang=vi&view=table`. Trang nhúng dữ liệu, bản dịch, logo và ảnh bìa; ảnh xem trước trên mạng xã hội nằm ở `assets/cover-social-v3.png`.

## Sơ đồ dự án

| Đường dẫn | Mục đích |
| --- | --- |
| `src/` | Mẫu HTML và tương tác trên trang |
| `data/` | Bản ghi nghiên cứu, nguồn và bảng thuật ngữ |
| `locales/` | Bản dịch giao diện và nghiên cứu; thẻ dành cho người đọc trong `readers/` |
| `scripts/` | Công cụ dựng và xác thực |
| `skills/howtolivelonger/` | Kỹ năng có thể cài đặt cho tác nhân; lấy JSON công khai |
| `assets/` | Logo, ảnh bìa và hình minh họa nguồn |
| `docs/` | Bài viết gốc, bản ghi đánh giá và README đã dịch |
| `index.html` | Trang web được tạo để dùng với Pages và ngoại tuyến |
