---
name: Countdown 15.12.2026 - Ban Thẩm Định Tín Dụng
description: Giao diện đếm ngược ngày về tinh gọn, trẻ trung, tràn đầy năng lượng tích cực cho đội trưng tập 2026
colors:
  bg: "#F8F9FC"
  surface: "#FFFFFF"
  surface-subtle: "#F1F4F9"
  ink: "#0F172A"
  ink-muted: "#475569"
  ink-soft: "#64748B"
  border: "#E2E8F0"
  border-scroll: "#CBD5E1"
  border-scroll-hover: "#94A3B8"
  vermilion: "#C72C14"
  vermilion-hover: "#A8200C"
  vermilion-bg: "#FDF2F0"
  vermilion-text: "#9E1C0A"
  vermilion-border: "#FECDCA"
  purple: "#5533EA"
  purple-bg: "#F4F0FF"
  purple-text: "#4322C9"
  purple-border: "#D8CEFF"
  forest: "#047857"
  forest-bg: "#ECFDF5"
  forest-text: "#065F46"
  forest-border: "#A7F3D0"
  amber: "#B45309"
  amber-bg: "#FFFBEB"
  amber-text: "#92400E"
  amber-border: "#FDE68A"
  badge-overlay: "rgba(0, 0, 0, 0.24)"
typography:
  display:
    fontFamily: "'Epilogue', 'Be Vietnam Pro', sans-serif"
    fontSize: "clamp(2.4rem, 5.2vw, 4.2rem)"
    fontWeight: 900
    lineHeight: 1.15
    letterSpacing: "-0.035em"
  counter:
    fontFamily: "'Epilogue', sans-serif"
    fontSize: "clamp(3rem, 6.5vw, 5.2rem)"
    fontWeight: 900
    lineHeight: 1
    letterSpacing: "-0.04em"
  body:
    fontFamily: "'Be Vietnam Pro', system-ui, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
  subhead:
    fontFamily: "'Be Vietnam Pro', system-ui, sans-serif"
    fontSize: "clamp(1.05rem, 1.8vw, 1.25rem)"
    fontWeight: 500
    lineHeight: 1.6
  caption:
    fontSize: "0.85rem"
  small:
    fontSize: "0.8rem"
  meta:
    fontSize: "0.875rem"
  lead:
    fontSize: "1.1rem"
  status:
    fontSize: "0.95rem"
  note:
    fontSize: "0.9rem"
rounded:
  sm: "10px"
  md: "20px"
  lg: "32px"
  full: "9999px"
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "36px"
  xxl: "56px"
components:
  button-primary:
    backgroundColor: "{colors.vermilion}"
    textColor: "#FFFFFF"
    rounded: "{rounded.full}"
    padding: "18px 42px"
---

## Overview

Trang đếm ngược trực quan, cao cấp theo phong cách **Liquid Glass (Kính Thể Lỏng)** tập trung vào tâm điểm đồng hồ đếm ngược đến 17:00 ngày 15/12/2026 dành riêng cho Đội Trưng Tập Ban Thẩm Định Tín Dụng 2026. Thiết kế loại bỏ hoàn toàn các lớp phủ mờ đục trên toàn màn hình, giữ trọn vẹn vẻ sắc nét, trong trẻo của bức tranh thiên nhiên (rừng cây và bầu trời xanh), đồng thời đúc kết các bề mặt giao diện bằng kính lỏng với hiệu ứng khúc xạ quang học, viền sáng khúc xạ đỉnh và độ bão hòa cao.

## Colors

- **Nền Thiên Nhiên Sắc Nét (`assets/nature-bg.jpg`):** Phong cảnh rừng thông và bầu trời xanh ngát hiển thị nguyên bản, trong trẻo và sắc nét, không bị làm nhoè hay phủ sương mờ.
- **Bề mặt Kính Thể Lỏng (Liquid Glass):** Sử dụng các tấm kính hữu cơ `linear-gradient(135deg, rgba(255, 255, 255, 0.68) 0%, rgba(255, 255, 255, 0.42) 100%)` kết hợp độ khúc xạ quang học sâu `backdrop-filter: blur(28px) saturate(190%)` và viền khúc xạ phản chiếu ánh sáng đỉnh `border-top: 1.5px solid #FFFFFF`.
- **Màu Vermilion chủ đạo:** `#C72C14` truyền cảm hứng và nhiệt huyết, text `#9E1C0A` trên nền kính đạt chuẩn tương phản cao WCAG AA.
- **Hệ màu thời gian:** 4 khối Ngày (Vermilion), Giờ (Purple `#5533EA`), Phút (Forest `#047857`), Giây (Amber `#B45309`).

## Typography

- **Display Face:** `Epilogue` (Weights 800, 900) - phong cách hiện đại, giàu năng lượng.
- **Body & UI Face:** `Be Vietnam Pro` (Weights 400, 500, 600, 700) - nét chữ chuẩn mực, hiển thị dấu tiếng Việt sắc sảo.

## Layout

- Bố cục trung tâm tập trung vào Hero Countdown, loại bỏ các chi tiết dư thừa nhằm tôn vinh cột mốc thời gian và tương tác xả stress.
- Responsive mượt mà: 4 cột trên desktop co giãn 2x2 trên thiết bị di động.

## Elevation & Depth

- **Liquid Refraction Depth:** Độ sâu quang học chất lỏng được tạo thành từ 3 lớp:
  1. Viền sáng khúc xạ đỉnh (`border-top: 1.5px solid #FFFFFF`).
  2. Ánh phản xạ nội tại (`box-shadow: inset 0 1px 2px rgba(255, 255, 255, 0.95)`).
  3. Bóng đổ tụ quang mềm dưới chân (`box-shadow: 0 24px 48px -12px rgba(15, 23, 42, 0.22)`).
- Không có hiện tượng nested cards (thẻ lồng trong thẻ); các cột số đếm ngược được phân cách bằng các dải khúc xạ ánh sáng mảnh và thoáng đãng.

## Components

- **Countdown Hero Card:** 4 khối số cỡ lớn Ngày - Giờ - Phút - Giây cập nhật thời gian thực từng giây.
- **Thanh tiến trình nhiệm kỳ:** Thể hiện trực quan % chặng đường từ lúc bắt đầu trưng tập đến cột mốc hoàn thành.
- **Nút Tiếp Năng Lượng & Bắn Pháo Hoa:** Tương tác bắn pháo hoa giấy Canvas Confetti kết hợp âm thanh tổng hợp Web Audio API và bộ đếm lượt bấm.
- **Trình phát Nhạc Nền Ambient Lắng Đọng:** Tích hợp bộ tạo âm thanh Piano/Rhodes mộc mạc, nhẹ nhàng qua Web Audio API (vòng hợp âm Cmaj9 - Em7 - Fmaj9 - Gadd9 tempo ~60 BPM) kèm thanh sóng equalizer sinh động.
