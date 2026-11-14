# Cursor FX Releases

Public release channel for **Cursor FX by VINT Studio**.

- Private source repository: https://github.com/tkhongcan/CursorFX
- Public update repository: https://github.com/tkhongcan/CursorFX-Releases
- Latest version manifest: [version.json](./version.json)
- Release history: https://github.com/tkhongcan/CursorFX-Releases/releases

## English

### Update manifest

The application checks `version.json` to learn the latest published version. A release is considered installable only after its Windows package has been uploaded and the manifest contains a valid HTTPS download URL and SHA-256 checksum.

### Publishing a release

1. Build and test the Windows application.
2. Create a GitHub Release with a version tag such as `v1.0.0`.
3. Upload the packaged installer/archive as a release asset.
4. Calculate its SHA-256 checksum.
5. Update `version.json` with the version, release page URL, asset URL, checksum, and release notes.
6. Test update detection and installation on a clean Windows 11 machine.

Do not publish source code, private credentials, access tokens, personal data, or user library/configuration backups in this repository.

### Current status

The repository is prepared as the public update channel. No installable application package has been published yet.

---

## Tiếng Việt

### Giới thiệu

Đây là kho phát hành công khai và cung cấp bản cập nhật cho **Cursor FX của VINT Studio**.

- Kho mã nguồn riêng tư: https://github.com/tkhongcan/CursorFX
- Kho cập nhật công khai: https://github.com/tkhongcan/CursorFX-Releases
- Tệp thông tin phiên bản mới nhất: [version.json](./version.json)
- Lịch sử phát hành: https://github.com/tkhongcan/CursorFX-Releases/releases

### Tệp thông tin cập nhật

Ứng dụng kiểm tra tệp `version.json` để xác định phiên bản mới nhất đã được phát hành. Một bản phát hành chỉ được xem là có thể cài đặt khi gói ứng dụng Windows đã được tải lên và tệp manifest có đường dẫn tải xuống HTTPS hợp lệ cùng mã kiểm tra SHA-256.

### Quy trình phát hành phiên bản mới

1. Biên dịch và kiểm thử ứng dụng Windows.
2. Tạo GitHub Release với thẻ phiên bản, ví dụ `v1.0.0`.
3. Tải bộ cài đặt hoặc tệp nén của ứng dụng lên phần tài sản (Assets) của bản phát hành.
4. Tính mã kiểm tra SHA-256 của tệp.
5. Cập nhật `version.json` với phiên bản, đường dẫn trang phát hành, đường dẫn tải tệp, mã SHA-256 và nội dung ghi chú phát hành.
6. Kiểm tra chức năng phát hiện cập nhật và cài đặt trên một máy Windows 11 sạch.

Không đăng tải mã nguồn, thông tin đăng nhập riêng tư, access token, dữ liệu cá nhân hoặc bản sao thư viện/cấu hình của người dùng lên kho này.

### Trạng thái hiện tại

Kho lưu trữ đã được chuẩn bị làm kênh cập nhật công khai. Hiện chưa có gói cài đặt ứng dụng nào được phát hành.
