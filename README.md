# ZenSpa 3D – Massage Online

Trang web giải trí, phi lợi nhuận: một phòng spa 3D (Three.js) nơi khách nhập tên, chọn người nằm massage (nam/nữ) và xem các liệu pháp đấm lưng, xoa tinh dầu, đá nóng, ống tre.

## Chạy thử

Trang phải được mở qua HTTP, không mở trực tiếp file `index.html` (trình phát YouTube sẽ báo lỗi 153):

```bash
python -m http.server 5173
```

Sau đó mở http://localhost:5173. Lần đầu tải mô hình người có thể mất tới khoảng một phút.

## Ghi công & bản quyền

### Mô hình 3D

Nhân vật người lấy từ [Microsoft Rocketbox](https://github.com/microsoft/Microsoft-Rocketbox), phát hành theo [giấy phép MIT](https://github.com/microsoft/Microsoft-Rocketbox/blob/master/LICENSE).
Copyright (c) Microsoft Corporation. Mô hình được tải trực tiếp từ kho GitHub của Microsoft khi chạy, không được sao chép vào repo này.

### Nhạc nền

Nhạc phát qua trình phát nhúng chính thức của YouTube (YouTube IFrame Player API). Trang này không lưu, tải xuống hay phân phối lại bất kỳ file nhạc nào. Bản quyền các bài hát và video thuộc về nghệ sĩ và hãng đĩa:

- ROSÉ & Bruno Mars – *APT.*
- ROSÉ – *On The Ground*
- Ariana Grande – *we can't be friends (wait for your love)*, *God is a woman*, *no tears left to cry*, *thank u, next*, *7 rings*

Trang này không liên kết với, không được tài trợ hay xác nhận bởi các nghệ sĩ, hãng đĩa hay YouTube. Việc sử dụng tuân theo [Điều khoản dịch vụ của YouTube](https://www.youtube.com/t/terms).

### Thư viện

- [Three.js](https://threejs.org/) (MIT)
- [canvas-confetti](https://github.com/catdad/canvas-confetti) (ISC)
