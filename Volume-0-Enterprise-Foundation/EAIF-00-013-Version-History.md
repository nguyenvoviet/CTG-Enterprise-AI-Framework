---
document_title: Lịch sử Phiên bản (Version History)
document_code: EAIF-00-013
version: v2.5
status: Draft
volume: Volume 0 — Nền tảng Doanh nghiệp
classification: Nội bộ
document_owner: AI Center of Excellence
document_reviewer: (chưa gán)
approved_by: (chưa phê duyệt)
purpose: Ghi nhận lịch sử thay đổi cấu trúc tổng thể EAIF qua các phiên bản
scope: Cấp cấu trúc tổng thể (không phải lịch sử từng file riêng lẻ)
applicable_to: AI Center of Excellence, Ban Chỉ đạo AI
dependencies: (không có)
baseline: EAIF v2.5
effective_date: (chưa ban hành chính thức)
review_cycle: Mỗi khi có phiên bản cấu trúc mới
related_documents: EAIF-00-012
change_history: |
  | Version | Ngày | Người soạn | Thay đổi |
  |---|---|---|---|
  | v2.5 | 2026-07-17 | AI CoE (soạn thảo qua Claude) | Chuyển đổi chuẩn Header v2.5; cập nhật bảng lịch sử cấu trúc tổng thể |
language: vi
---

# EAIF-00-013 — Lịch sử Phiên bản (Version History)

## 1. Purpose
Theo dõi lịch sử thay đổi cấu trúc tổng thể EAIF, phân biệt với lịch sử nội dung từng file (nằm trong change_history của mỗi file riêng).

## 2. Scope
Chỉ ghi nhận thay đổi cấp CẤU TRÚC (số Volume, số Agent, chuẩn Header) — không lặp lại chi tiết nội dung từng file.

## 3. Principles — Lịch sử cấu trúc EAIF tổng thể
| Phiên bản | Thay đổi chính |
|---|---|
| v1.0 | Cấu trúc gốc: 9 Volume, 10 Agent, tên đầu mục tiếng Anh |
| v2.0 | Rà soát theo thực tế CTG/Aurora IP; bổ sung 6 Agent mới (16 tổng); tái cấu trúc Volume 3 |
| v2.1 | Bổ sung giải thích chi tiết Ý nghĩa/Phạm vi/Use case cho 16 Agent |
| v2.2 | Làm rõ sâu vai trò Agent #04 Chief Risk Advisor |
| v2.3 | Việt hóa toàn bộ đầu mục cấu trúc; sửa lỗi định dạng cây thư mục — **Final trước khi có chuẩn Document Code** |
| v2.4 | Bổ sung Core Values, Enterprise Culture, Leadership Philosophy vào Volume 0 (10→13 mục); giới thiệu Quy tắc số 1-5 (Document Code, Header, DNA kế thừa, cấu trúc 10 mục) |
| **v2.5** | **Baseline chính thức** — hoàn thiện Header 19 trường (đổi field names sang snake_case, bổ sung volume/baseline/effective_date/review_cycle/language); viết lại toàn bộ Volume 0 (13 file) và Volume 1 (15 file) theo chuẩn Document Code + Header + cấu trúc 10 mục |

## 4. Roles
| Vai trò | Trách nhiệm |
|---|---|
| AI Center of Excellence | Cập nhật bảng lịch sử mỗi khi có phiên bản cấu trúc mới |

## 5. Responsibilities
Mọi thay đổi cấu trúc (thêm/bớt Volume, đổi số Agent, đổi chuẩn Header) bắt buộc phải được ghi nhận tại đây trước khi công bố phiên bản mới.

## 6. Standards — Quy ước đánh số phiên bản
- Số nguyên (v1, v2, v3...): thay đổi lớn về cấu trúc
- Số thập phân (v2.1, v2.2...): bổ sung nội dung, làm rõ, sửa lỗi — không đổi cấu trúc tổng thể

## 7. Workflows
```
Đề xuất thay đổi cấu trúc → Ban Chỉ đạo AI phê duyệt → Cập nhật bảng Mục 3
   → Publish baseline mới → Toàn bộ tài liệu tham chiếu "baseline" field cập nhật theo
```

## 8. Outputs
- **Baseline hiện tại: EAIF v2.5** (Quy tắc số 1 — Baseline Architecture)
- 28 file Volume 0-1 hoàn thành theo chuẩn v2.5 tại thời điểm 2026-07-17

## 9. Exceptions
Việc chuyển đổi 25 file Volume 0-1 từ chuẩn v2.3 sang v2.5 không được tính là "thay đổi nội dung cấu trúc" mà là "chuẩn hóa hình thức" — nội dung cốt lõi giữ nguyên trừ khi có ghi chú khác trong change_history từng file.

## 10. References
- EAIF-00-012-Document-Structure.md
- Toàn bộ change_history của 28 file Volume 0-1 v2.5
