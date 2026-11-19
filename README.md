# ALO Lite — layouts and drawing lists for AutoCAD LT

**[Download the latest version](https://github.com/arcthanhbinhtran-ai/alo-lite/releases/latest)** · **[Website](https://arcthanhbinhtran-ai.github.io/m5studio/chi-tiet.html?id=alo-lite&lang=en)** · by [M5 STUDIO](https://arcthanhbinhtran-ai.github.io/m5studio/?lang=en)

The AutoLISP edition of [ALO](https://github.com/arcthanhbinhtran-ai/alo), for **AutoCAD LT 2024 and later** (LT cannot load .NET plugins, so the full ALO does not run there). Also runs on full AutoCAD 2021+. Free.

- Scan drawing frames in Model space (blocks or rectangles, rotated frames too) and create layouts in bulk from a template layout: viewport centred, standard scale picked to fit the paper, rotated to match, locked
- Drawing list: number, title, scale, date — renumber, write to / read from title block attributes
- Excel round-trip (.csv, keeps Vietnamese text and scales like 1:100)

Not in the Lite edition: Sheet Set (.dst) editing, field linking, whole-set PDF, docked palette — use the full ALO on regular AutoCAD for those.

> **Status:** 0.1 is a first test release. The core (layouts, title blocks, Excel) passes automated tests; the dialog has not yet been tried on a real AutoCAD LT. Interface language: Vietnamese.

## Install

1. Download `ALOLite_vX.Y.zip` from [Releases](https://github.com/arcthanhbinhtran-ai/alo-lite/releases/latest) and **unzip** it.
2. Double-click **`CaiDat.bat`** in the unzipped folder.
3. Open AutoCAD LT (choose **Always Load** if asked) and type **`ALOL`**.

This repository only hosts the release files.

---

## Tiếng Việt

Bản AutoLISP của ALO cho **AutoCAD LT 2024 trở lên** (LT không nạp được plugin .NET nên không dùng được ALO bản đầy đủ). Chạy cả trên AutoCAD bản đầy đủ 2021+. Miễn phí.

- Quét khung trong Model (block hoặc rectang, cả khung xoay) và tạo layout hàng loạt từ một layout mẫu: khung nhìn đặt giữa, tự chọn tỉ lệ chuẩn vừa khổ giấy, xoay theo khung, khoá lại
- Danh sách bản vẽ: số hiệu, tên, tỉ lệ, ngày — đánh số lại, ghi vào / đọc từ khung tên
- Sửa nhiều bằng Excel (.csv, giữ đúng tiếng Việt và tỉ lệ 1:100)

**Cài đặt:** tải file zip ở [Releases](https://github.com/arcthanhbinhtran-ai/alo-lite/releases/latest), giải nén, bấm đúp **`CaiDat.bat`**, mở AutoCAD LT (nếu được hỏi chọn **Always Load**), gõ lệnh **`ALOL`**.

Bản 0.1 là bản thử đầu tiên: phần lõi đã chạy thử tự động đạt, bảng điều khiển chưa thử trên AutoCAD LT thật.
