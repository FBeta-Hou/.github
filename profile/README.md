# Hỗ Trợ Thiên Tai

[![Demo](https://img.shields.io/badge/Demo-2ea44f?style=for-the-badge)](https://fbetahou.budibase.app/app/hotrothientai) [![Documentation](https://img.shields.io/badge/Documentation-blue?style=for-the-badge)](https://fbeta-hou.github.io/FBeta-fulldocs/)

# Giới thiệu - Đặt vấn đề 
Một trong những lợi ích lớn của LCDP (Low-Code Development Platforms) là khả năng nhanh chóng chuyển đổi từ ý tưởng thành sản phẩm. Điều này đặc biệt quan trọng trong các tình huống khẩn cấp, như đại dịch Covid-19 hay thiên tai do bão lũ, khi thời gian là yếu tố quyết định. Trong các tình huống này, nhu cầu sử dụng công nghệ thông tin để kết nối cộng đồng, cung cấp thông tin nhanh chóng và hỗ trợ các hoạt động ứng phó, khắc phục hậu quả, và hỗ trợ nhân đạo là rất cấp thiết.
# Giải pháp ứng dụng Budibase phòng chống thiên tai
### Mục tiêu ứng dụng: 
- Cung cấp nền tảng để cập nhật tin tức về tình hình thiên tai.
- Cung cấp danh sách các khu vực an toàn và điểm di tản để người dân nhanh chóng tìm nơi trú ẩn.
- Cho phép gửi yêu cầu cứu trợ khẩn cấp.
- Quản lý danh sách và phân phối nguồn cứu trợ.
  
### Ứng dụng Budibase sẽ cung cấp các tính năng chính sau:

📰 1. Tin tức phòng chống thiên tai 
- Cập nhật tin tức và cảnh báo thiên tai.
- Hướng dẫn các biện pháp phòng tránh thiên tai.

📝 2. Danh sách khu vực di tản
- Hiển thị các khu vực di tản an toàn.
- Cập nhật tình trạng và chỉ dẫn đường đi đến các khu vực di tản.

📣 3. Gửi yêu cầu cứu trợ
- Cho phép người dân gửi yêu cầu cứu trợ khẩn cấp.
- Theo dõi tình trạng yêu cầu cứu trợ.

📝 4. Danh sách cứu trợ
- Cung cấp thông tin về các tổ chức cứu trợ và gói hỗ trợ.
- Hướng dẫn liên hệ và nhận cứu trợ.

## Công nghệ 
!(Img)[WEB.png]
- **Nền tảng phát triển:** Budibase
- **Hệ thống bản đồ:** GoongJs
- **Thông báo khẩn:** Firebase 
- **Cơ sở dữ liệu**: BudibaseDB, MongoDB
## Lợi ích dự kiến 
- Nâng cao khả năng ứng phó nhanh chóng, giảm thiểu thiệt hại từ thiên tai.
- Kết nối cộng đồng và các tổ chức cứu trợ hiệu quả hơn.
- Tăng cường minh bạch trong quản lý và phân phối cứu trợ.
# Cấu trúc project:
## Giới Thiệu Dự Án

Dự án **FBeta** bao gồm ba repo chính, mỗi repo đảm nhận một vai trò khác nhau trong hệ thống cứu trợ thiên tai:

1. **[FBeta-Services](https://github.com/FBeta-Hou/FBeta-Services)**: Đây là dịch vụ nền tảng cung cấp các chức năng bản đồ và thông báo đẩy. Dịch vụ sử dụng Goong API để hiển thị bản đồ và Firebase Cloud Messaging (FCM) để gửi thông báo đến người dùng về tình hình thiên tai và các khu vực an toàn.

2. **[FBeta-Hou-App](https://github.com/FBeta-Hou/FBeta-Hou-App)**: Repo này chứa ứng dụng người dùng được xây dựng trên nền tảng Budibase, cung cấp giao diện người dùng để xem thông tin về thiên tai, khu vực an toàn, và nhận các thông báo quan trọng từ quản trị viên.

3. **[FBeta-fulldocs](https://github.com/FBeta-Hou/FBeta-fulldocs)**: Repo này lưu trữ tài liệu hướng dẫn sử dụng ứng dụng và các bước triển khai tài liệu lên GitHub Pages. Nó cung cấp tài liệu chi tiết về cách sử dụng ứng dụng, cũng như các hướng dẫn dành cho người dùng và quản trị viên.

[Hướng dẫn cài đặt ](https://fbeta-hou.github.io/FBeta-fulldocs/CachCaiDat/)

[Hướng dẫn sử dụng ](https://fbeta-hou.github.io/FBeta-fulldocs/CachSD/)

# 🙌 Đóng góp cho dự án
Nếu bạn muốn đóng góp cho dự án, hãy đọc [CONTRIBUTING.md](https://github.com/FBeta-Hou/.github/blob/main/CONTRIBUTING.md) để biết thêm chi tiết.

Mọi đóng góp của các bạn đều được trân trọng, đừng ngần ngại gửi pull request cho dự án.
# Liên hệ 
-   Nguyễn Hồng Ánh: 22a1001d0029@students.hou.edu.vn
-   Lê Cát Khánh: 22a1001d0168@students.hou.edu.vn
-   Tống Tâm Xuân: 22a1001d0378@students.hou.edu.vn
# 📝 License 
This project is licensed under the terms of the [GPL-3.0](https://github.com/FBeta-Hou/.github/blob/main/LICENSE) license.
<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
