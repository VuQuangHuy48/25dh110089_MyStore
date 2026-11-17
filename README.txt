# Đồ án: Website bán hàng MyStore

## Hướng dẫn chạy:
1. Mở SQL Server, chạy file `Database_MyStore.sql` (đính kèm) để tạo CSDL `MyStore`.
2. Mở file `Web.config`, tìm dòng `data source=...` trong thẻ `<connectionStrings>`.
3. Sửa `data source` thành tên SQL Server trên máy của bạn (ví dụ: `localhost`, `.\SQLEXPRESS`, hoặc `(localdb)\MSSQLLocalDB`).
4. Mở project bằng Visual Studio, nhấn F5 để chạy.
5. nếu mở thấy lỗi thư viện thì cô chuột phải vào solution chọn Restore Nuget Packages nhé.
