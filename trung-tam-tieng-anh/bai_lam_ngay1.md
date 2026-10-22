# BÀI LÀM – ÔN TẬP NGÀY 1

- **Họ tên: Nguyễn Vương Anh Minh**
- **Lớp: CNTT1**
- **Link repository:**
- **Hệ điều hành (Windows/macOS): Windows**

## Phần A. Tổ chức thư mục bằng GUI

> Phần A được chấm qua kết quả B1 (tên thư mục gốc) và kết quả liệt kê toàn bộ dự án B8 ở Phần B, không cần ghi thêm ở đây.

## Phần B. Thao tác bằng CLI

### Các lệnh đã chạy (B1–B7)

```shell
B1: pwd
B2: ls -recurse
B3: mv .\lich_hoc.txt .\docs\,  mv .\logo_trung_tam.PNG, .\anh_lop_hoc.JPG .\media\
B4: cp .\media\logo_trung_tam.PNG V\archive\
B5: rm .\temp_201.tmp, rm .\temp_202.tmp
B6: cd .\logs\, ls, cd..
B7: cp ..\media\anh_lop_hoc.JPG ..\archive\
B8: ls -Recurse
```

### Kết quả B1 (pwd)

```text
Path
----
D:\trung-tam-tieng-anh
```

### Kết quả liệt kê toàn bộ dự án – B8 (Windows: Get-ChildItem -Recurse -Force; macOS: ls -aR)

```text
Path
----
D:\trung-tam-tieng-anh





Directory: D:\trung-tam-tieng-anh

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d----          10/22/2026  1:24 AM                archive
d----          10/22/2026  1:42 AM                data
d----          10/22/2026  1:24 AM                docs
d----          10/22/2026  1:43 AM                logs
d----          10/22/2026  1:24 AM                media
-a---          10/19/2026 10:04 AM             83 .env
-a---          10/19/2026 10:04 AM          13559 anh_lop_hoc.JPG
-a---          10/19/2026 10:04 AM            902 bai_lam_ngay1.md
-a---          10/19/2026 10:04 AM           5184 logo_trung_tam.PNG
-a---          10/19/2026 10:04 AM             22 temp_201.tmp
-a---          10/19/2026 10:04 AM             22 temp_202.tmp
 Directory: D:\trung-tam-tieng-anh\data

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 10:04 AM           5070 hoc_vien_khoa.xlsx

    Directory: D:\trung-tam-tieng-anh\logs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 10:04 AM           1072 access.log





PS D:\trung-tam-tieng-anh> mv .\lich_hoc.txt .\docs\
PS D:\trung-tam-tieng-anh> mv .\logo_trung_tam.PNG, .\anh_lop_hoc.JPG .\media\
PS D:\trung-tam-tieng-anh> cp .\media\logo_trung_tam.PNG .\archive\
PS D:\trung-tam-tieng-anh> rm .\temp_201.tmp
PS D:\trung-tam-tieng-anh> rm .\temp_202.tmp


 
 
 
Directory: D:\trung-tam-tieng-anh\logs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 10:04 AM           1072 access.log



 Directory: D:\trung-tam-tieng-anh

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d----          10/22/2026  2:12 AM                archive
d----          10/22/2026  1:42 AM                data
d----          10/22/2026  1:59 AM                docs
d----          10/22/2026  1:43 AM                logs
d----          10/22/2026  1:59 AM                media
-a---          10/19/2026 10:04 AM             83 .env
-a---          10/19/2026 10:04 AM            902 bai_lam_ngay1.md

    Directory: D:\trung-tam-tieng-anh\archive

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 10:04 AM          13559 anh_lop_hoc.JPG
-a---          10/19/2026 10:04 AM           5184 logo_trung_tam.PNG

    Directory: D:\trung-tam-tieng-anh\data

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 10:04 AM           5070 hoc_vien_khoa.xlsx

    Directory: D:\trung-tam-tieng-anh\docs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 10:04 AM             67 lich_hoc.txt

    Directory: D:\trung-tam-tieng-anh\logs

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 10:04 AM           1072 access.log

    Directory: D:\trung-tam-tieng-anh\media

Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a---          10/19/2026 10:04 AM          13559 anh_lop_hoc.JPG
-a---          10/19/2026 10:04 AM           5184 logo_trung_tam.PNG
```

## Tự chấm (điền sau khi có đáp án)

- **Điểm tự chấm:** 96/100
  - **Lỗi mình đã mắc và cách sửa: xóa thư mục ẩn bằng tay**
