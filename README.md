## Hướng dẫn cài đặt
### Cài đặt PHPEXCEL
Để cài đặt thư viện PHPExcel, bạn thực hiện một trong hai phương án sau đây

**Phương án 1: Cài đặt PHPExcel qua composer (khuyến khích dùng)**

Hãy bỏ qua nếu bạn không hiểu composer là gì
```
composer require phpoffice/phpexcel
```

**Phương án 2: Cài đặt qua mã nguồn**
- Truy cập https://github.com/PHPOffice/PHPExcel/releases và tải về phiên bản mới nhất
- Giải nén, copy thư mục `Classes` vào `includes` (nukeviet)
- Đổi tên thư mục `Classes` vừa copy thành `class`. Chúng ta sẽ có `includes/class/PHPExcel.php`

### Cài đặt plugin
- Downnload giải nén vào thư mục tương ứng
- **Truy cập ACP / Sản phẩm**. Lúc này xẽ xuất hiện thêm menu **Nhập / xuất Excel**
