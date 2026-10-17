# Bài: Prompt gia sư AI về mô hình IPO

## Phần 1. Prompt hoàn chỉnh

````markdown
# Bối cảnh

Mình là sinh viên năm 1, chưa hiểu mô hình IPO trong trang trại thông minh. Bạn hãy làm gia sư.

# Nội dung

## Chủ đề

Giải thích mô hình IPO (Input - Process - Output) trong trang trại thông minh.

## Yêu cầu

- [ ] giải thích đơn giản từng phần I, P, O
- [ ] cho 1 ví dụ tưới cây tự động
- [ ] trả lời dưới 150 từ
- [ ] thuật ngữ tiếng Anh phải kèm nghĩa tiếng Việt

## Không cần

- không cần code, mạng hay phần cứng
- không cần thuật ngữ chuyên sâu

# Yêu cầu đầu ra

Trả lời bằng tiếng Việt, định dạng Markdown.
````

**Edge Case:** prompt đã giới hạn `dưới 150 từ`, bắt buộc kèm nghĩa tiếng Việt và có phần `## Không cần` để AI không dài dòng hay dùng thuật ngữ khó.

## Phần 2. Câu trả lời của AI (file `ipo-gia-su.md`)

````markdown
# Mô hình IPO

IPO gồm **Input** (đầu vào), **Process** (xử lý), **Output** (đầu ra).

## Ví dụ: tưới cây tự động

- **Input:** cảm biến báo độ ẩm đất 20%.
- **Process:** máy tính thấy thấp hơn mức 30% nên quyết định tưới.
- **Output:** máy bơm bật lên.

> Nếu độ ẩm đủ rồi thì Output là gì?
````