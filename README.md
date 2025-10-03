# Đồ án Nhập môn Công nghệ Phần mềm: Media Platform Giải Chạy

Đây là repository source code và tài liệu cho đồ án môn học Nhập môn Công nghệ Phần mềm, với đề tài phát triển một Web App truyền thông đa phương tiện dành cho các sự kiện giải chạy.

## 📝 Mô tả dự án

Dự án này xây dựng một hệ thống quản trị nội dung số (CMS) chuyên biệt, cho phép doanh nghiệp tổ chức giải chạy có thể quản lý và xuất bản nội dung media một cách hiệu quả. Hệ thống áp dụng quy trình phát triển phần mềm Agile-Scrum, được quản lý và theo dõi chi tiết trên Jira, đồng bộ với GitHub qua Smart Commits.

## ✨ Tính năng nổi bật

* **Quản lý Vòng đời Nội dung:** Quy trình tạo, gửi duyệt, và phê duyệt/từ chối nội dung một cách chặt chẽ.
* **Xuất bản Đa kênh:** Lên lịch và xuất bản nội dung tự động lên các kênh tích hợp như Website, Fanpage Facebook...
* **Công cụ hỗ trợ sáng tạo:** Tích hợp công cụ tạo poster/thumbnail đơn giản từ template có sẵn.
* **Tối ưu SEO & Analytics:** Tự động tạo sitemap, hỗ trợ thẻ OpenGraph/Schema và cung cấp dashboard theo dõi hiệu quả nội dung.
* **Trải nghiệm người dùng hiện đại:** Hỗ trợ Progressive Web App (PWA) cho phép truy cập offline và gửi thông báo đẩy (Push Notifications).
* **Hỗ trợ Livestream:** Tích hợp và phát các luồng video trực tiếp từ các nền tảng mạng xã hội.

## 🎨 Thiết kế hệ thống (Artefacts)

Các tài liệu thiết kế và phân tích hệ thống được lưu trữ trong thư mục `/diagrams`:

* **Sơ đồ Use Case:** Mô tả các chức năng chính và tương tác của người dùng.
    * [Xem tại đây](./diagrams/use-case-diagram.png)
* **Sơ đồ Tuần tự (Sequence Diagram):** Mô tả chi tiết 2 luồng quan trọng:
    * Luồng duyệt và xuất bản nội dung - [Xem tại đây](./diagrams/sequence-diagram-approval.png)
    * Luồng người dùng xem livestream - [Xem tại đây](./diagrams/sequence-diagram-livestream.png)
* **Sơ đồ Quan hệ Thực thể (ERD):** Thiết kế chi tiết cơ sở dữ liệu.
    * [Xem tại đây](./diagrams/erd.png)

*(Lưu ý: Bạn hãy đảm bảo tên file và đường dẫn đến các file ảnh sơ đồ của bạn là chính xác)*

## 🛠️ Công nghệ sử dụng

* **Frontend:** `[Điền công nghệ bạn dùng, ví dụ: React.js, Vue.js, Angular...]`
* **Backend:** `[Điền công nghệ bạn dùng, ví dụ: Node.js (Express), Python (Django), Java (Spring Boot)...]`
* **Database:** `[Điền công nghệ bạn dùng, ví dụ: PostgreSQL, MySQL, MongoDB...]`
* **Project Management:** Jira (Agile Scrum)
* **Version Control:** Git & GitHub

## 🚀 Hướng dẫn cài đặt & Chạy thử

Để chạy dự án này trên máy tính cá nhân, hãy làm theo các bước sau:

**Yêu cầu:**
* Cài đặt Git
* Cài đặt Node.js (phiên bản 16.x trở lên)
* `[Liệt kê thêm các yêu cầu khác nếu có, ví dụ: Docker, Python...]`

**Các bước cài đặt:**

1.  **Clone repository về máy:**
    ```bash
    git clone [https://github.com/](https://github.com/)[Tên-user-của-bạn]/[Tên-repo-của-bạn].git
    ```

2.  **Di chuyển vào thư mục dự án:**
    ```bash
    cd [Tên-repo-của-bạn]
    ```

3.  **Cài đặt các thư viện cần thiết (dependencies):**
    ```bash
    # Dành cho project backend
    cd backend
    npm install

    # Dành cho project frontend
    cd ../frontend
    npm install
    ```

4.  **Chạy dự án:**
    ```bash
    # Chạy backend (ví dụ)
    cd ../backend
    npm start

    # Chạy frontend (ví dụ)
    cd ../frontend
    npm start
    ```

5.  Mở trình duyệt và truy cập vào `http://localhost:3000` (hoặc port tương ứng).


## 👤 Tác giả

* **Họ và tên:** `[Tên của bạn]`
* **MSSV:** `[Mã số sinh viên của bạn]`
* **Lớp:** `[Lớp của bạn]`

---

Cảm ơn đã xem qua repository này!
