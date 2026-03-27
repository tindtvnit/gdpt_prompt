# gdpt_prompt

Bộ prompt sinh ảnh AI mô tả đồng phục các thành phần trong **Gia Đình Phật Tử (GĐPT)** Việt Nam.  
Các prompt được thiết kế để dùng với các công cụ sinh ảnh AI như **ChatGPT (DALL·E)**, **Midjourney**, **Stable Diffusion**, **Adobe Firefly**, v.v.

---

## Danh sách file prompt

### Thường phục (đồng phục sinh hoạt)

| File | Đối tượng | Mô tả |
|---|---|---|
| `huynhtruongnam.txt` | Huynh Trưởng Nam | Nam huynh trưởng trưởng thành (20–40 tuổi), đứng thẳng, tự tin |
| `oanhvunam.txt` | Oanh Vũ Nam | Bé trai Oanh Vũ (7–10 tuổi), đồng phục thường ngày |
| `oanhvunu.txt` | Oanh Vũ Nữ | Bé gái Oanh Vũ (7–10 tuổi), đồng phục thường ngày |
| `thanhnam.txt` | Thanh Nam | Nam đoàn sinh Thanh (từ 18 tuổi trở lên) |
| `thieunam.txt` | Thiếu Nam | Nam đoàn sinh Thiếu (thiếu niên) |

### Trại phục (đồng phục cắm trại)

| File | Đối tượng | Mô tả |
|---|---|---|
| `traiphuc_huynhtruongnu.txt` | Huynh Trưởng Nữ | Nữ huynh trưởng (22–35 tuổi), trại phục dài tay |
| `traiphuc_thanhnu.txt` | Thanh Nữ | Nữ đoàn sinh Thanh (18–22 tuổi), trại phục dài tay |
| `traiphuc_thieunu.txt` | Thiếu Nữ | Nữ đoàn sinh Thiếu (14–17 tuổi), trại phục dài tay |

---

## Cách sử dụng

### 1. Chọn file prompt phù hợp

Chọn file tương ứng với thành phần GĐPT bạn muốn tạo ảnh.

### 2. Sao chép toàn bộ nội dung prompt

Mở file `.txt`, chọn tất cả và sao chép (Ctrl+A → Ctrl+C).

### 3. Dán vào công cụ sinh ảnh AI

**ChatGPT, Germini:**
1. Mở web
2. Dán prompt vào ô chat và gửi
3. ChatGPT sẽ tự động tạo ảnh

**Midjourney:**
1. Vào server Discord của Midjourney
2. Gõ `/imagine` rồi dán nội dung prompt vào
3. Nhấn Enter để tạo ảnh

**Stable Diffusion / ComfyUI:**
1. Dán nội dung vào ô **Positive Prompt**
2. Chạy generate

### 4. Lưu ý quan trọng

- Các prompt đã bao gồm mô tả chi tiết về màu sắc, phụ kiện, tư thế — **không cần chỉnh sửa thêm** để có kết quả chuẩn.
- Nếu ảnh chưa đúng, thử **chạy lại** (re-generate) vài lần để đạt kết quả tốt nhất.
- Với Midjourney, thêm tham số `--ar 3:4` vào cuối prompt để có tỉ lệ ảnh đứng phù hợp hơn.

---

## Đặc điểm đồng phục GĐPT trong các prompt

- **Màu áo:** Xanh lam nhạt (light blue)
- **Màu quần/váy:** Xanh navy đậm
- **Nút áo:** Cùng màu xanh lam với áo (không phải màu trắng)
- **Giày:** Giày hoạt động ngoài trời / giày hiking (không phải giày da đen)
- **Không có:** Phù hiệu hoa sen, khăn quàng hướng đạo, patches trên tay áo

---

## Liên hệ & đóng góp

Nếu bạn muốn đóng góp thêm prompt cho các thành phần chưa có (ví dụ: Oanh Vũ với trại phục, Thiếu Nam trại phục...), vui lòng tạo Pull Request hoặc mở Issue trên GitHub.
