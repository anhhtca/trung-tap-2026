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
    fontSize: "clamp(2.8rem, 6vw, 4.6rem)"
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

Trang đếm ngược trực quan, tinh gọn tập trung vào tâm điểm đồng hồ đếm ngược đến 17:00 ngày 15/12/2026 dành riêng cho Đội Trưng Tập Ban Thẩm Định Tín Dụng 2026. Thiết kế mang phong cách Pop Festival ấm áp, năng động, mang tinh thần tích cực, trân trọng hành trình đã qua và háo hức hướng về đích hoàn thành xuất sắc nhiệm kỳ.

## Colors

- **Nền & Khung thẻ:** `#F8F9FC` kết hợp `#FFFFFF` cho bề mặt thẻ số.
- **Màu Vermilion chủ đạo:** `#C72C14` truyền cảm hứng và nhiệt huyết, text `#9E1C0A` trên nền `#FDF2F0` đạt chuẩn tương phản cao WCAG AA.
- **Hệ màu thời gian:** 4 khối Ngày (Vermilion), Giờ (Purple `#5533EA`), Phút (Forest `#047857`), Giây (Amber `#B45309`).

## Typography

- **Display Face:** `Epilogue` (Weights 800, 900) - phong cách hiện đại, giàu năng lượng.
- **Body & UI Face:** `Be Vietnam Pro` (Weights 400, 500, 600, 700) - nét chữ chuẩn mực, hiển thị dấu tiếng Việt sắc sảo.

## Layout

- Bố cục trung tâm tập trung vào Hero Countdown, loại bỏ các chi tiết dư thừa nhằm tôn vinh cột mốc thời gian và tương tác xả stress.
- Responsive mượt mà: 4 cột trên desktop co giãn 2x2 trên thiết bị di động.

## Elevation & Depth

- Chiều sâu chân thực (Physical Depth) với bóng đổ phân lớp tự nhiên, nhẹ nhàng, không dùng hiệu ứng glow viền nhân tạo.

## Components

- **Countdown Hero Card:** 4 khối số cỡ lớn Ngày - Giờ - Phút - Giây cập nhật thời gian thực từng giây.
- **Thanh tiến trình nhiệm kỳ:** Thể hiện trực quan % chặng đường từ lúc bắt đầu trưng tập đến cột mốc hoàn thành.
- **Nút Tiếp Năng Lượng & Bắn Pháo Hoa:** Tương tác bắn pháo hoa giấy Canvas Confetti kết hợp âm thanh tổng hợp Web Audio API và bộ đếm lượt bấm.
