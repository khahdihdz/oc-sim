# OC Simulator — Game Giả Lập Ép Xung Máy Tính

![OC Simulator — Game Giả Lập Ép Xung Máy Tính](assets/thumbnail.jpg)

Game giả lập ép xung PC chạy trực tiếp trên trình duyệt, giao diện tiếng Việt, dùng công thức ép xung thật để tính công suất, nhiệt độ và độ ổn định.

## Chơi ngay

- GitHub Pages: https://khahdihdz.github.io/oc-sim/
- Vercel: https://oc-sim.vercel.app/

Không cần cài đặt, mở link là chơi. Tiến trình được lưu tự động trên trình duyệt.

## Cách chơi

Bắt đầu với một bộ máy yếu và ít tiền, ép xung để tăng hiệu năng, làm nhiệm vụ, kiếm tiền mua linh kiện xịn hơn và leo cấp từ **Nghiệp Dư** lên **Huyền Thoại Ép Xung**.

- **Ép xung CPU:** chỉnh Multiplier, BCLK, Vcore (bước nhảy 0,001V / 0,005V / 0,01V / 0,025V), LLC 5 mức chống sụt áp, giới hạn PL1/PL2.
- **Ép xung GPU và RAM:** chỉnh xung nhân, xung bộ nhớ, giới hạn điện, quạt, timings và điện áp RAM.
- **Công thức thật:** công suất P = TDP × (f/f₀) × (V/V₀)², nhiệt độ theo tản nhiệt, TjMax 100°C, throttle từ 85°C, tắt máy ở 100°C. Vcore an toàn dưới 1,35V, trên 1,45V làm CPU xuống cấp nhanh.
- **Silicon Lottery:** mỗi CPU có chất lượng silicon 70–100, benchmark mới biết được chip ngon hay dở.
- **Kiểm tra tương thích:** mỗi mainboard ghi rõ socket CPU và loại cùng bus RAM hỗ trợ, CPU và RAM không khớp sẽ bị chặn mua/lắp kèm lý do, mua mainboard mới có cảnh báo nếu CPU/RAM đang lắp không dùng được nữa.
- **Dịch vụ build và ép xung thuê:** tab Dịch Vụ với khách hàng ngẫu nhiên, nhận việc, lắp máy cho khách từ linh kiện trong Kho, ép xung và test đạt yêu cầu rồi giao máy nhận thù lao và uy tín, quá hạn bị trừ uy tín và bồi thường. Người mới luôn có khách khởi nghiệp: khách mang máy đến chỉ thuê ép xung, thay keo và vệ sinh, không cần ứng tiền mua linh kiện.
- **Stress Test và Benchmark:** kiểm tra độ ổn định với biểu đồ nhiệt độ trực tiếp, xem trước kết quả PASS / RISK / CERTAIN CRASH trước khi chạy.
- **Cửa hàng 31 linh kiện:** CPU, GPU, RAM, mainboard, PSU, tản nhiệt. Bán đồ thừa theo độ bền, trao đổi đồ cùng loại để bù tiền chênh.
- **Nhiệm vụ và thành tích:** làm nhiệm vụ kiếm tiền, mở thành tích theo từng mốc ép xung.
- **Gợi ý thông minh:** cảnh báo quá nhiệt, quá áp, nguồn yếu, gợi ý áp dụng một chạm và checklist trước mỗi lần test.

## Tính năng chính

- 8 tab: Tổng Quan, Ép Xung, Stress Test, Benchmark, Cửa Hàng, Kho Linh Kiện, Nhiệm Vụ, Thành Tích.
- Thanh Apply cố định: mọi thay đổi thông số đều hiện thanh xác nhận với xem trước cũ → mới, áp dụng hoặc hoàn tác.
- Giao diện phong cách BIOS/HWMonitor, tối, hiển thị tốt trên điện thoại, máy tính bảng và máy tính.
- Lưu game tự động, chơi tiếp mọi lúc, có nút chơi mới khi muốn làm lại từ đầu.

## Kỹ thuật

- Một file `index.html` duy nhất, không cần build, không cần server.
- Ảnh chia sẻ khi gửi link: `assets/thumbnail.jpg` (1200×630).
- Chạy được trên mọi trình duyệt hiện đại.

## Đóng góp và liên hệ

- Donate / ủng hộ tác giả: https://khahdihdz.github.io
- Góp ý và liên hệ qua Facebook: https://facebook.com/khahdihdz

## Giấy phép

Dự án dùng giấy phép MIT, xem file [LICENSE](LICENSE).
