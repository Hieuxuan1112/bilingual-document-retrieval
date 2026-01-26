# Bilingual Document Retrieval

Công cụ tìm kiếm và đối chiếu tự động tài liệu song ngữ (hướng tới Hán–Việt).

## Tiến độ hiện tại
- [x] **Giai đoạn 1 (Setup):** Cài đặt môi trường, thư viện và load model thành công.
- [x] **Giai đoạn 2 (Core Logic):** Xây dựng module so khớp nội bộ (Internal Matching) sử dụng LaBSE.
  - Đã cài đặt hàm `find_best_match_labse`.
  - Đã thêm module tự tạo dữ liệu giả (Dummy Data) để Unit Test.
  - Kết quả test: Model phân biệt tốt giữa văn bản Lịch sử và Khoa học.

## Cài đặt
```bash
pip install -r requirements.txt