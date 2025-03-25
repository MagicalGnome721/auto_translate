# Tự động dịch văn bản sang Tiếng Việt

## Giới thiệu
Đây là một chương trình Python sử dụng mô hình dịch máy của Facebook NLLB-200 để dịch văn bản từ nhiều ngôn ngữ khác nhau sang Tiếng Việt.

## Yêu cầu
- Python 3.8 trở lên
- Các thư viện cần thiết:
  ```bash
  pip install transformers torch sentencepiece langdetect
  ```
- **Bạn phải tạo một token trên Hugging Face** để sử dụng model. Đăng ký và lấy token tại: [https://huggingface.co/settings/tokens](https://huggingface.co/settings/tokens)

## Cách sử dụng
1. Chạy chương trình.
2. Chọn ngôn ngữ nguồn.
3. Nhập văn bản cần dịch.
4. Chương trình sẽ trả về bản dịch sang Tiếng Việt.

## Danh sách ngôn ngữ hỗ trợ
- Tiếng Anh (English)
- Tiếng Pháp (French)
- Tiếng Đức (German)
- Tiếng Trung Giản Thể (Chinese Simplified)
- Tiếng Trung Phồn Thể (Chinese Traditional)
- Tiếng Nhật (Japanese)
- Tiếng Hàn (Korean)
- Tiếng Nga (Russian)
- Tiếng Tây Ban Nha (Spanish)

## Ghi chú
- Văn bản dài sẽ được chia nhỏ để xử lý nhanh hơn.
- Nếu chọn Tiếng Việt làm ngôn ngữ nguồn, chương trình sẽ báo lỗi vì không cần dịch.

## Liên hệ
Nếu có bất kỳ vấn đề gì, hãy mở issue trên GitHub hoặc liên hệ với mình.

