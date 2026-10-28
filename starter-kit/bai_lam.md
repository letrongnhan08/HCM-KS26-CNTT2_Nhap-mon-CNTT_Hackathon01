# BÀI LÀM – HACKATHON 01

- **Mã đề:** 22
- **Họ tên:** Lê Trọng Nhân
- **Lớp:** HCM-KS26-CNTT2
- **Link repository:** 
- **Hệ điều hành (Windows/macOS):** Windows

## 4.2. Thao tác máy tính cơ bản bằng CLI

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng
Lệnh sử dụng
./
Get-ChildItem 
-Recurse 
-Force
mv
rm
```

### Kết quả liệt kê toàn bộ dự án (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)
PS D:\HCM-K26-CNTT2\IT-108\hackathon\starter-kit\rua-xe-website> Get-ChildItem -Recurse -Force


    Directory: D:\HCM-K26-CNTT2\IT-108\hackathon\starter-kit\rua-xe-website


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----        10/28/2026   1:54 PM                backup
d-----        10/28/2026   1:54 PM                data
d-----        10/28/2026   1:54 PM                docs
d-----        10/28/2026   1:54 PM                logs
d-----        10/28/2026   1:54 PM                media
-a----        10/27/2026   1:32 AM             64 .env
-a----        10/27/2026   1:32 AM           2227 bai_lam.md
-a----        10/27/2026   1:32 AM             53 Bang_Quy_Trinh.txt
-a----        10/27/2026   1:32 AM           6191 Logo_Rua_Xe.PNG
-a----        10/27/2026   1:32 AM             22 temp_305.tmp

```text
(Dán kết quả vào đây – xoá dòng này)
PS D:\HCM-K26-CNTT2\IT-108\hackathon\starter-kit> ./rua-xe-website/carwash.log
PS D:\HCM-K26-CNTT2\IT-108\hackathon\starter-kit\rua-xe-website> Get-ChildItem -Recurse -Force
PS D:\HCM-K26-CNTT2\IT-108\hackathon\starter-kit\rua-xe-website> mv "bang_quy_trinh.txt" docs/
PS D:\HCM-K26-CNTT2\IT-108\hackathon\starter-kit\rua-xe-website> mv "logo_rua_xe.PNG" media/
PS D:\HCM-K26-CNTT2\IT-108\hackathon\starter-kit\rua-xe-website> rm temp_305.tmp

```

## 4.3. Lọc log thủ công

### Lệnh đã chạy
Get-Content
Select-String
ni (New-Item)
(>)
```shell
# Ghi lệnh vào đây (xoá dòng này)
PS D:\HCM-K26-CNTT2\IT-108\hackathon\starter-kit\rua-xe-website\logs> Get-Content Carwash.log | Select-String "Error"
PS D:\HCM-K26-CNTT2\IT-108\hackathon\starter-kit\rua-xe-website\logs> ni daily_report.txt
PS D:\HCM-K26-CNTT2\IT-108\hackathon\starter-kit\rua-xe-website\logs> Get-Content Carwash.log | Select-String "Error" >  daily_report.txt

```

### 2 dòng lỗi đầu tiên trong daily_report.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.4. Thao tác với tài liệu Markdown (README.md)

> README.md được chấm trực tiếp trên file `README.md` ở gốc dự án. Đánh dấu `[x]` vào các mục đã làm để tự kiểm tra.

- [x] Heading 1: tên dự án
- [x] Mô tả ngắn có cả **in đậm** và *in nghiêng*
- [ ] Bảng `Thư mục | Nội dung`, ít nhất 3 dòng dữ liệu
- [ ] Code block chứa lệnh PowerShell/Terminal liệt kê nội dung dự án
- [ ] Task list ít nhất 2 công việc, có ít nhất 1 mục đã hoàn thành
- [ ] Blockquote nhắc không upload `.env`

## 4.5. Chạy script auto_report (.ps1 hoặc .sh)

### Lệnh chạy (Windows: nếu dùng Phụ lục 2 thì ghi cả 2 lệnh)

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả hiển thị

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.6. Đếm số dòng lỗi

### Lệnh

```shell
# Ghi lệnh vào đây (xoá dòng này)

```

### Kết quả đếm (Windows: giá trị Count; macOS: con số in ra)

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.7. Báo cáo tổng hợp

### Các lệnh đã chạy

```shell
# Ghi lần lượt các lệnh đã chạy, mỗi lệnh một dòng (xoá dòng này)

```

### Nội dung file logs/tong_hop.txt

```text
(Dán kết quả vào đây – xoá dòng này)

```

## 4.8. Excel

> Phần Excel được chấm trực tiếp trên file `data/luot_rua_xe_thang_2.xlsx`, không cần ghi vào đây.
