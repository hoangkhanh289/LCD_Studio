<div align="center">

# 🖥️ LCD_Studio

### **Bộ công cụ thiết kế giao diện đồ họa LCD/TFT & HMI chuyên nghiệp cho Hệ thống Nhúng**
*Thiết kế trực quan — Tối ưu tài nguyên vi điều khiển — Sinh mã C++ / Arduino tự động 1-Click*

[![Executable](https://img.shields.io/badge/Download-LCD__Studio.exe-4f46e5?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/)
[![Portable](https://img.shields.io/badge/Portable-Chạy%20ngay%20(Không%20cần%20cài%20đặt)-059669?style=for-the-badge)](https://github.com/)
[![Windows Support](https://img.shields.io/badge/Hệ%20điều%20hành-Windows%2010%20%2F%2011%20(64--bit)-0284c7?style=for-the-badge&logo=windows11)](https://github.com/)
[![Offline](https://img.shields.io/badge/Offline-100%25%20Độc%20lập-success?style=for-the-badge)](https://github.com/)
[![License](https://img.shields.io/badge/License-MIT-gray?style=for-the-badge)](LICENSE)

---

[Tải về & Chạy ngay](#-tải-về--chạy-ngay) •
[Tính năng nổi bật](#-tính-năng-đột-phá) •
[Phần cứng hỗ trợ](#-phần-cứng--màn-hình-hỗ-trợ) •
[Quy trình 3 bước](#-quy-trình-làm-việc-3-bước) •
[Mã nguồn nhúng sinh ra](#-mã-nguồn-nhúng-sinh-ra) •
[Mở rộng Font chữ](#-tùy-biến--thêm-font-chữ-mới)

---

</div>

## 💡 Giới thiệu

Việc lập trình giao diện màn hình cho vi điều khiển (ESP32, STM32, Arduino, RP2040...) trước đây là một nỗi cực nhọc lớn: kỹ sư phải **ngồi tính từng tọa độ pixel bằng tay**, vất vả tạo nút bấm, căn lề văn bản, xử lý font chữ tiếng Việt bị lỗi dấu, và đau đầu với hiện tượng màn hình nhấp nháy giật lag do phải quét lại toàn bộ màn hình.

**LCD_Studio** sinh ra để xóa bỏ hoàn toàn rào cản đó!

Được phát hành dưới dạng **ứng dụng Portable (`LCD_Studio.exe`) duy nhất**, bạn chỉ cần tải về và nhấp đúp để sử dụng ngay mà **không cần cài đặt bất kỳ môi trường lập trình phức tạp nào** (không cần Node.js, không cần Python). Giao diện kéo-thả mượt mà như Figma, đầu ra là **mã nguồn C++ thuần túy, siêu nhẹ và tối ưu bộ nhớ** cho vi điều khiển.

---

## ⚡ Tải về & Chạy ngay

> 🚀 **Hoàn toàn Portable:** Không cần quyền Administrator, không cài đặt rác vào Registry hệ thống, có thể copy vào USB chạy trên mọi máy tính Windows!

1. **Tải về:** Tải file **`LCD_Studio.exe`** (hoặc gói `LCD_Studio_Portable.zip`) từ mục [Releases](https://github.com/).
2. **Khởi chạy:** Nhấp đúp vào **`LCD_Studio.exe`** để mở ngay phần mềm.
3. **Bắt đầu thiết kế:** Mở dự án mẫu có sẵn tại **File → Mở dự án mẫu IoT** để trải nghiệm ngay lập tức!

---

## 🌟 Tính năng đột phá

### 🎨 1. Không gian thiết kế trực quan (Visual Canvas Designer)
* **Kéo thả mượt mà:** Trải nghiệm thiết kế Canvas 2D siêu tốc, hỗ trợ Pan/Zoom vô cực, thước đo, lưới tọa độ Snap-to-Grid và vạch căn chỉnh thông minh (Smart Guides).
* **Đa màn hình (Multi-Screen Simulator):** Thiết kế nhiều trang màn hình (Home, Settings, Dashboard, Popup...) trong cùng một dự án.
* **Quản lý Layer & Component:** Phân cấp cây thư mục Layer, nhóm (Group), khóa/ẩn, nhân đôi (Duplicate) và lưu Component tái sử dụng.
* **Hoàn tác an toàn (Undo/Redo):** Hỗ trợ lưu lịch sử lên tới **80 bước**, thoải mái thử nghiệm mà không sợ mất thiết kế.

### ⚡ 2. Kho Widget đồ sộ (48+ Widgets chuyên dụng cho IoT)
LCD_Studio tích hợp sẵn hơn 48 loại widget đa dạng:
* **Cơ bản (Basic):** Văn bản (Label/Text), Hình chữ nhật bo góc (Rectangle/Panel), Nút bấm (Button), Vòng tròn (Circle), Đường thẳng (Line), Icon Unicode.
* **Điều khiển & Nhập liệu (Input):** Thanh trượt (Slider), Núm xoay (Knob), Công tắc gạt (Switch/Toggle), Hộp kiểm (Checkbox), Nút chọn (Radio), Danh sách chọn (Dropdown), Hộp nhập liệu số/văn bản.
* **Hiển thị & Giám sát (Display):** Thanh tiến trình (Progress Bar), Vòng tiến trình (Circular Progress), Đồng hồ đo (Gauge/Arc), Báo pin (Battery), Trạng thái kết nối (Status Indicator), Đèn LED.
* **Biểu đồ dữ liệu thời gian thực (Data & Charts):** Biểu đồ đường (Line Chart), Biểu đồ cột (Bar Chart), **Đồ thị thời gian thực (Realtime Graph)** tự động vẽ lại khi có biến thay đổi, Bảng biểu (Table/List).
* **Cảm biến & IoT chuyên sâu:** Nhiệt độ (°C), Độ ẩm (%), Điện áp (V), Dòng điện (A), Tốc độ vòng tua (RPM), Cường độ sóng (WiFi / BLE / Signal).

### 👆 3. Cơ chế cảm ứng & Tương tác thông minh (Touch & Interaction Engine)
* **Tương tác trực quan:** Gán sự kiện cảm ứng (`click`, `press`, `release`, `long-press`, `swipe`, `enter`) chỉ bằng vài cú nhấp chuột.
* **Điều hướng màn hình (Navigation):** Chuyển trang mượt mà, hỗ trợ ngăn xếp Back-stack, mở Popup thông báo và đóng Popup.
* **Ràng buộc dữ liệu (Data Binding):** Gán biến toàn cục hoặc cục bộ (`temperature`, `relay_state`...) vào thuộc tính widget. Khi dữ liệu vi điều khiển cập nhật, giao diện sẽ tự động đổi màu, đổi giá trị hoặc ẩn/hiện.

### 🔤 4. Quản lý Font & Tiếng Việt đỉnh cao (Vietnamese Font Banking)
* **Đọc trực tiếp font TTF/OTF:** Tự động quét kho font, kiểm tra độ phủ Unicode tiếng Việt chuẩn xác.
* **Khắc phục giới hạn 64 KiB của Adafruit_GFX:** Thuật toán **Font Bitmap Banking** độc quyền tự động chia bank 32-bit cho các bộ font chữ lớn và font tiếng Việt đầy đủ dấu mà vẫn giữ nguyên chữ sắc nét, không bao giờ gây tràn bộ nhớ hay lỗi biên dịch.
* **Xuất Header Font (.h) độc lập:** Xuất mã nguồn font bitmap monochrome sắc nét để dùng riêng cho bất kỳ dự án C/C++ nào.

### 🚀 5. Thuật toán làm mới cục bộ (Partial Refresh & Dirty Planner)
* **Nói KHÔNG với nhấp nháy màn hình:** Thuật toán `lcd_dirty.h` tính toán chính xác vùng biên thay đổi (dirty region) giữa trạng thái cũ và mới.
* **Tối ưu DMA:** Chỉ truyền đúng vùng pixel thay đổi qua bus SPI/8080 kết hợp cơ chế DMA (Direct Memory Access), giúp tốc độ khung hình (FPS) mượt mà tối đa ngay cả trên vi điều khiển cấu hình khiêm tốn.

### 📦 6. Xuất mã nguồn trọn gói 1-Click (Native C++ Export)
* **Một cú nhấp chuột — Có ngay toàn bộ Project:**
  * File sketch chính (`.ino`)
  * Cấu hình thiết bị & màn hình riêng biệt (`src/screens/HomeScreen.cpp`, `.h`)
  * Trình điều khiển phần cứng đã tối ưu hóa
  * Toàn bộ mảng font chữ và hình ảnh nhúng (RGB565 PROGMEM)
  * Thư viện nhúng tương thích đi kèm
* **Xuất Offline Web Runtime:** Đóng gói toàn bộ dự án thành file HTML/JS duy nhất mở trực tiếp bằng trình duyệt để demo hoặc nhúng vào web server của thiết bị IoT.

---

## 📟 Phần cứng & Màn hình hỗ trợ

| Thành phần | Danh mục phần cứng hỗ trợ |
| :--- | :--- |
| **Vi điều khiển (MCU)** | ESP32, ESP32-S3, ESP32-C3, STM32 (F1/F4), Raspberry Pi Pico (RP2040), Arduino Due/Mega |
| **IC điều khiển hiển thị (LCD Driver)** | **ST7796S** (SPI & 8080 Parallel), **ST7789**, **ILI9341**, **ST7735**, **SSD1306** (OLED), **GC9A01** (Màn tròn), RGB Parallel panels |
| **IC Cảm ứng (Touch Controller)** | **GT911** (Điện dung đa điểm - Capacitive), **XPT2046** (Điện trở - Resistive), **FT6236** |
| **Độ phân giải chuẩn có sẵn** | 480×320 (3.5"), 320×240 (2.8"), 240×240 (1.28"), 800×480 (5.0"), 160×128 (1.8"), 128×64 (0.96"), Tùy chỉnh tự do (Custom) |

---

## 🛠️ Quy trình làm việc 3 bước

```mermaid
flowchart LR
    A["🎨 1. Thiết kế trực quan<br/>(Kéo thả Widget, Font VN, Layers)"] --> B["⚡ 2. Chạy thử & Gán tương tác<br/>(Simulator, Variables, Touch Event)"]
    B --> C["📦 3. Xuất mã nguồn & Nạp MCU<br/>(C++ Sketch, Header, Dirty DMA)"]
```

1. **Thiết kế:** Kéo thả các widget từ bảng công cụ bên trái vào màn hình LCD. Căn chỉnh vị trí, màu sắc, font chữ và hình ảnh ở bảng Inspector bên phải.
2. **Xem trước (Preview):** Nhấn phím `Shift + Enter` để bật chế độ mô phỏng tương tác. Bấm nút, kéo thanh trượt, thử nghiệm hiệu ứng chuyển trang và thay đổi giá trị cảm biến ảo.
3. **Xuất mã nguồn (Export):** Chọn **Export** -> Đặt tên dự án và chọn thư mục lưu. Ứng dụng sẽ tự động sinh đầy đủ sketch Arduino, font và thư viện tương thích. Chỉ cần mở bằng Arduino IDE / PlatformIO và nạp vào mạch!

---

## 💻 Mã nguồn nhúng sinh ra

Mã nguồn C++ do LCD_Studio sinh ra cực kỳ tinh gọn, dễ hiểu và dễ tích hợp vào firmware hiện có của bạn:

```cpp
#include "lcd_studio.h"

void setup() {
    Serial.begin(115200);
    
    // Khởi tạo phần cứng màn hình & cảm ứng
    ui_init();
}

void loop() {
    // 1. Đọc dữ liệu từ cảm biến thực tế
    float currentTemp = readTemperatureSensor();
    
    // 2. Cập nhật biến giao diện — LCD_Studio tự động phát hiện vùng thay đổi!
    ui_setVariable("temperature", String(currentTemp, 1));
    
    // 3. Xử lý cảm ứng GT911/XPT2046 và quét vẽ lại vùng dirty qua DMA
    ui_tick();
    
    delay(10);
}
```

---

## 🔤 Tùy biến & Thêm Font chữ mới

LCD_Studio đã tích hợp sẵn 20 bộ font tiếng Việt và tiếng Anh tuyển chọn. Nếu bạn muốn thêm font riêng:

1. Tạo thư mục `VN/` (cho font tiếng Việt) hoặc `EN/` (cho font tiếng Anh) **nằm ngay cạnh file `LCD_Studio.exe`**.
2. Sao chép các file font định dạng `.ttf` hoặc `.otf` của bạn vào đó.
3. Mở phần mềm (hoặc bấm **Refresh Fonts** trong tab Fonts), các font mới sẽ tự động xuất hiện trong danh sách để bạn chọn!

---

## ⌨️ Phím tắt tiện ích

| Phím tắt | Chức năng |
| :---: | :--- |
| `Ctrl + N` / `Ctrl + O` | Tạo dự án mới / Mở dự án có sẵn |
| `Ctrl + S` / `Ctrl + Shift + S` | Lưu dự án / Lưu dự án thành bản sao mới |
| `Ctrl + Z` / `Ctrl + Y` | Hoàn tác (Undo) / Làm lại (Redo) |
| `Ctrl + C` / `Ctrl + V` / `Ctrl + D` | Sao chép / Dán / Nhân đôi Widget |
| `Delete` / `Backspace` | Xóa đối tượng đang chọn |
| `Ctrl + G` / `Ctrl + Shift + G` | Nhóm (Group) / Rã nhóm (Ungroup) |
| `Space + Kéo chuột` | Di chuyển vùng làm việc (Pan Canvas) |
| `Ctrl + Phím cuộn chuột` | Phóng to / Thu nhỏ (Zoom in/out) |
| `Ctrl + 0` / `Ctrl + 1` | Xem vừa khung (Fit) / Xem tỉ lệ gốc 100% |
| `Shift + Enter` | Bật / Tắt chế độ chạy thử nghiệm (Live Preview) |
| `Chuột phải` | Mở menu thao tác nhanh ngữ cảnh (Context Menu) |

---

<details>
<summary><strong>🔧 Dành cho Nhà phát triển (Build từ mã nguồn)</strong></summary>

Nếu bạn muốn đóng góp mã nguồn hoặc tự build file executable:

```powershell
# 1. Cài đặt các thư viện cần thiết
npm ci
python -m pip install -r requirements.txt

# 2. Build Frontend
npm run build

# 3. Đóng gói ra file LCD_Studio.exe độc lập
python build_exe.py --onefile
```
File executable thành phẩm sẽ nằm tại thư mục `release/LCD_Studio.exe`.
</details>

---

<div align="center">

**Phát triển với ❤️ dành riêng cho Cộng đồng Kỹ sư Nhúng & IoT**  
*Bản quyền © 2026 LCD_Studio. Giữ toàn quyền phát triển.*

</div>
