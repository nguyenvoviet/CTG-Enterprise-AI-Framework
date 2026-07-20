---
document_title: Cấu trúc Tài liệu (Document Structure)
document_code: EAIF-00-012
version: v2.0
status: Draft
volume: Volume 0 — Nền tảng Doanh nghiệp
classification: Nội bộ
document_owner: AI Center of Excellence
document_reviewer: (chưa gán)
approved_by: (chưa phê duyệt)
purpose: Quy định chuẩn Document Code, Header 19 trường, và cấu trúc 10 mục cho mọi tài liệu EAIF
scope: Toàn bộ file .md trong EAIF
applicable_to: Mọi người soạn thảo tài liệu EAIF
dependencies: (không có)
baseline: EAIF v2.5
effective_date: (chưa ban hành chính thức)
review_cycle: Khi Quy tắc số 2/3/5 thay đổi
related_documents: EAIF-01-015
change_history: |
  | Version | Ngày | Người soạn | Thay đổi |
  |---|---|---|---|
  | v1.0 | 2026-07-17 | AI CoE (soạn thảo qua Claude) | Khởi tạo (v2.3) |
  | v2.0 | 2026-07-17 | AI CoE (soạn thảo qua Claude) | Cập nhật theo Quy tắc số 2, 3, 5 của v2.5: Document Code, Header 19 trường, cấu trúc 10 mục |
language: vi
---

# EAIF-00-012 — Cấu trúc Tài liệu (Document Structure)

## 1. Purpose
Quy định chuẩn đặt tên, header, và cấu trúc nội dung để mọi tài liệu EAIF có tính quản trị ngay từ đầu — không còn là "đoạn chat".

## 2. Scope
Áp dụng cho toàn bộ file `.md` trong 9 Volume.

## 3. Principles

### Document Code (Quy tắc số 2)
Định dạng: `EAIF-{Volume:2 chữ số}-{Số thứ tự:3 chữ số}-{Tên-tiếng-Anh}.md`
Ví dụ: `EAIF-00-001-Vision.md`, `EAIF-01-001-Enterprise-AI-Constitution.md`, `EAIF-02-001-CTO-Executive-Advisor-Overview.md`

### Header chuẩn 19 trường (Quy tắc số 3)
`document_title, document_code, version, status, volume, classification, document_owner, document_reviewer, approved_by, purpose, scope, applicable_to, dependencies, baseline, effective_date, review_cycle, related_documents, change_history, language`

### Cấu trúc nội dung 10 mục (Quy tắc số 5)
`1. Purpose · 2. Scope · 3. Principles · 4. Roles · 5. Responsibilities · 6. Standards · 7. Workflows · 8. Outputs · 9. Exceptions · 10. References`

## 4. Roles
| Vai trò | Trách nhiệm |
|---|---|
| AI Center of Excellence | Duy trì và cập nhật chuẩn này |
| Người soạn thảo bất kỳ tài liệu EAIF | Tuân thủ 100% Document Code + Header + cấu trúc 10 mục |

## 5. Responsibilities
Tài liệu không đạt chuẩn Header/Document Code không được xem là tài liệu chính thức của EAIF — chỉ được xem là bản nháp làm việc.

## 6. Standards — Cấu trúc thư mục
```
EAIF/
├── Volume-0-Enterprise-Foundation/
│   ├── EAIF-00-001-Vision.md
│   ├── EAIF-00-002-Mission.md ... EAIF-00-013-Version-History.md
├── Volume-1-EAIOS/
│   ├── EAIF-01-001-Enterprise-AI-Constitution.md ... EAIF-01-015-...
├── Volume-2-Personas/
│   ├── 01-CTO-Executive-Advisor/
│   │   ├── EAIF-02-001-CTO-Executive-Advisor-Overview.md
│   │   ├── EAIF-02-002-...-Instructions.md ...
```

## 7. Workflows
```
Soạn tài liệu mới → Gán Document Code đúng Volume/thứ tự → Điền đủ 19 trường Header
   → Viết nội dung theo 10 mục → AI CoE rà soát → Ban hành (status: Approved)
```

## 8. Outputs
Mọi tài liệu EAIF từ v2.5 trở đi đều có Document Code + Header + 10 mục nhất quán, sẵn sàng tích hợp SharePoint/hệ thống quản lý tài liệu.

## 9. Exceptions
25 file Volume 0-1 soạn theo chuẩn v2.3 (chưa có Document Code/Header 19 trường) — cần lộ trình chuyển đổi riêng, không tự động coi là "không hợp lệ" nhưng cần ưu tiên nâng cấp.

## 10. References
- Quy tắc số 1-5, EAIF v2.5 Project Instructions
- EAIF-01-015-Enterprise-Prompting-Standard.md
