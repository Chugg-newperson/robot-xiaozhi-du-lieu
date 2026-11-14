# Dữ liệu cho Robot Xiaozhi bánh xích

Kho này **công khai** để robot tải dữ liệu qua Wi-Fi (robot không đọc được kho riêng tư). Kho chỉ chứa dữ liệu, **không có mã chương trình**.

| Tệp | Là gì |
|---|---|
| `catalog.txt` | Danh mục giáo trình robot đọc (mỗi dòng: mã gói, tên, đường dẫn, số byte, mã kiểm tra) |
| `cuoc-song-hang-ngay.rgt` | Kho chủ đề "Cuộc sống hàng ngày" (17 chủ đề, tự soạn, kèm từ khoá + đoạn hội thoại) |
| `thu-nghe-bai-goc.rgt` | Gói THỬ đường phát bài nghe gốc (4 bài nhỏ, trỏ tới `nhac_thu.webm`) |
| `nhac_thu.webm` | Nhạc thử của dự án (tự làm, 12 giây, WebM/Opus) – để thử phát bài nghe qua mạng |
| `youtube-trang.txt` | Danh sách trang trung gian nghe nhạc YouTube (để trống tới khi thử được) |

**Cách sửa / thêm:** sửa trong kho chính (`giao-trinh/`, script `scripts/robot/csv_to_pack.py`), chép tệp mới sang đây, sửa dòng tương ứng trong `catalog.txt` (số byte + mã kiểm tra đổi theo).

Không đưa giáo trình có bản quyền (KIIP, 세종한국어, EPS-TOPIK…) lên đây khi chưa được phép.
