# WEBSITE BÁN BÁNH NGỌT – REACTJS SPA

## 1. Giới thiệu dự án

**Tên đề tài:** Xây dựng ứng dụng web đơn trang bán bánh ngọt với dữ liệu động từ API JSON.

Đây là đồ án cơ sở ngành Công nghệ thông tin, tập trung nghiên cứu và xây dựng website bán bánh ngọt theo mô hình **Single Page Application (SPA)** bằng thư viện **ReactJS**.

Ứng dụng sử dụng API JSON giả lập để cung cấp dữ liệu sản phẩm động, hỗ trợ người dùng tìm kiếm, lựa chọn bánh ngọt, xem thông tin chi tiết và quản lý giỏ hàng.

Thông qua dự án, sinh viên vận dụng kiến thức HTML, CSS, JavaScript, ReactJS và API để xây dựng ứng dụng web có giao diện trực quan, dễ sử dụng và có tính tương tác.

## 2. Mục tiêu dự án

- Tìm hiểu mô hình Single Page Application (SPA).
- Nghiên cứu và vận dụng thư viện ReactJS.
- Tìm hiểu cách sử dụng API và định dạng dữ liệu JSON.
- Xây dựng website bán bánh ngọt với dữ liệu sản phẩm động.
- Thiết kế giao diện thân thiện, dễ sử dụng.
- Xây dựng chức năng tìm kiếm, lọc, xem chi tiết sản phẩm và quản lý giỏ hàng.
- Hoàn thiện ứng dụng demo và báo cáo đồ án.

## 3. Các chức năng chính

| STT | Chức năng | Mô tả |
|---|---|---|
| 1 | Hiển thị sản phẩm | Lấy dữ liệu bánh ngọt từ API JSON và hiển thị trên website. |
| 2 | Tìm kiếm sản phẩm | Tìm kiếm bánh ngọt theo tên sản phẩm. |
| 3 | Phân loại sản phẩm | Hiển thị sản phẩm theo từng loại bánh. |
| 4 | Lọc sản phẩm | Lọc danh sách theo danh mục đã chọn. |
| 5 | Chi tiết sản phẩm | Hiển thị hình ảnh, tên, giá và mô tả bánh ngọt. |
| 6 | Giỏ hàng | Thêm và quản lý các sản phẩm trong giỏ hàng. |
| 7 | Xem trước đơn hàng | Hiển thị thông tin sản phẩm được lựa chọn trước khi đặt hàng. |
| 8 | Phân trang | Chia danh sách sản phẩm thành nhiều trang để thuận tiện theo dõi. |

## 4. Công nghệ sử dụng

| Công nghệ | Mục đích |
|---|---|
| HTML5 | Xây dựng cấu trúc giao diện. |
| CSS3 | Thiết kế và định dạng giao diện. |
| JavaScript | Xử lý logic và tương tác người dùng. |
| ReactJS | Xây dựng giao diện theo mô hình SPA. |
| JSON | Lưu trữ và trao đổi dữ liệu sản phẩm. |
| JSON Server | Xây dựng API giả lập cung cấp dữ liệu. |
| Node.js / npm | Quản lý môi trường và thư viện dự án. |
| Git / GitHub | Quản lý mã nguồn và theo dõi tiến độ. |

## 5. Cấu trúc thư mục dự án

Cấu trúc repository dự kiến:

```text
project/
│
├── src/                 # Mã nguồn ứng dụng ReactJS
├── public/              # Tài nguyên tĩnh
├── setup/               # Dữ liệu và hướng dẫn cài đặt
├── progress-report/     # Báo cáo tiến độ hằng tuần
│
├── thesis/              # Tài liệu đồ án
│   ├── doc/             # Báo cáo Word
│   ├── pdf/             # Báo cáo PDF
│   ├── html/            # Tài liệu HTML
│   ├── abs/             # Slide thuyết trình
│   └── refs/            # Tài liệu tham khảo
│
├── package.json         # Thông tin và thư viện dự án
└── README.md            # Giới thiệu và hướng dẫn dự án
```

## 6. Hướng dẫn cài đặt và chạy dự án

### 6.1. Chuẩn bị môi trường

Cài đặt các công cụ:

- Node.js và npm.
- Visual Studio Code.
- Git.

### 6.2. Tải mã nguồn

Clone repository từ GitHub:

```bash
git clone <URL_REPOSITORY>
```

Truy cập thư mục dự án:

```bash
cd <TEN_THU_MUC_DU_AN>
```

### 6.3. Cài đặt thư viện

```bash
npm install
```

### 6.4. Khởi chạy API JSON giả lập

Nếu dữ liệu được lưu trong file `db.json`, chạy:

```bash
npx json-server --watch db.json --port 3000
```

Địa chỉ API sản phẩm:

```text
http://localhost:3000/cakes
```

### 6.5. Khởi chạy ứng dụng ReactJS

Mở terminal khác và thực hiện:

```bash
npm run dev
```

Truy cập địa chỉ localhost được hiển thị trên terminal để sử dụng website.

**Lưu ý:** Cần khởi chạy API JSON giả lập trước để ứng dụng có thể lấy và hiển thị dữ liệu sản phẩm.

## 7. Tiến độ thực hiện

| Giai đoạn | Nội dung thực hiện |
|---|---|
| Tuần 1 | Tìm hiểu yêu cầu đề tài, ReactJS, SPA, API và JSON. |
| Tuần 2 | Thiết kế giao diện, xây dựng cấu trúc ứng dụng và API giả lập. |
| Tuần 3 | Phát triển các chức năng tìm kiếm, lọc, chi tiết sản phẩm và giỏ hàng. |
| Tuần 4 | Kiểm thử, sửa lỗi, hoàn thiện ứng dụng và báo cáo đồ án. |

Các báo cáo tiến độ được lưu trữ trong thư mục `progress-report`.

## 8. Phạm vi dự án

Dự án tập trung xây dựng website bán bánh ngọt ở mức demo, sử dụng dữ liệu giả lập dưới dạng JSON.

Các chức năng được triển khai nhằm minh họa quá trình xây dựng ứng dụng web đơn trang và xử lý dữ liệu động.

**Giới hạn của đề tài:**

- Chưa tích hợp thanh toán trực tuyến.
- Chưa xây dựng hệ thống quản lý kho.
- Chưa tích hợp vận chuyển và giao hàng.
- Chưa triển khai các nghiệp vụ thương mại điện tử thực tế.

## 9. Hướng phát triển

Trong tương lai, dự án có thể được mở rộng với các chức năng:

- Đăng ký và đăng nhập tài khoản.
- Quản lý đơn hàng.
- Tích hợp cơ sở dữ liệu thực tế.
- Xây dựng trang quản trị sản phẩm.
- Tích hợp thanh toán trực tuyến.
- Tối ưu giao diện trên thiết bị di động.

## 10. Thông tin thực hiện

**Sinh viên thực hiện:** Nguyễn Thanh Liêm

**Mã số sinh viên:** 110124239

**Lớp:** DA24TTB

**Ngành:** Công nghệ thông tin

**Giảng viên hướng dẫn:** ThS. Phạm Thị Trúc Mai

**Đơn vị:** Khoa Công nghệ thông tin – Trường Kỹ thuật và Công nghệ

**Email liên hệ:** nguyenliemtvh12@gmail.com

**Điện thoại:** 0369082407

## 11. Thời gian thực hiện

- **Bắt đầu:** 12/10/2026
- **Kết thúc dự kiến:** 28/12/2026

---

**ĐỒ ÁN CƠ SỞ NGÀNH – CÔNG NGHỆ THÔNG TIN – 2026**

Repository được sử dụng để quản lý mã nguồn, tài liệu và cập nhật tiến độ thực hiện đồ án trên GitHub.
