---
document_title: Tiêu chuẩn Viết Prompt Doanh nghiệp (Enterprise Prompting Standard)
document_code: EAIF-01-015
version: v1.0
status: Draft
volume: Volume 1 — Enterprise AI Operating System (EAIOS)
classification: Nội bộ
document_owner: AI Center of Excellence
document_reviewer: (chưa gán)
approved_by: (chưa phê duyệt)
purpose: Chuẩn hóa cách soạn Instructions.md cho Agent (Volume 2) và prompt trong Volume 4
scope: Toàn bộ quy trình xây dựng Agent mới
applicable_to: AI CoE, người xây dựng Agent nội bộ/bên ngoài
dependencies: EAIF-01-001, EAIF-01-003, EAIF-01-004, EAIF-01-013
baseline: EAIF v2.5
effective_date: (chưa ban hành chính thức)
review_cycle: 12 tháng
related_documents: EAIF-00-012, Volume 2, Volume 4
change_history: |
  | Version | Ngày | Người soạn | Thay đổi |
  |---|---|---|---|
  | v1.0 | 2026-07-17 | AI CoE (soạn thảo qua Claude) | Chuyển đổi chuẩn Header v2.5 |
language: vi
---

# EAIF-01-015 — Tiêu chuẩn Viết Prompt Doanh nghiệp (Enterprise Prompting Standard)

## 1. Purpose
Chuẩn hóa cách soạn Instructions.md cho mọi Agent, đảm bảo chất lượng và nhất quán ngay từ khâu thiết kế.

## 2. Scope
Áp dụng khi soạn Instructions.md (Volume 2) và prompt (Volume 4).

## 3. Principles — Cấu trúc chuẩn Instructions.md
```markdown
# [Tên Agent]
## Vai trò            [tham chiếu "Ý nghĩa" tại Volume 2]
## Phạm vi (Bounded Context)   [Được làm gì / Không được làm gì]
## Nguồn tri thức tham chiếu   [Trỏ đúng nhánh Volume 3]
## Cấp độ quyết định   [Cấp 1/2/3 theo EAIF-01-003]
## Guardrails đặc thù  [Nếu có, ngoài EAIF-01-008]
## Giọng điệu          [Theo EAIF-01-004]
```

## 4. Roles
| Vai trò | Trách nhiệm |
|---|---|
| AI CoE | Rà soát checklist trước khi Agent vận hành |
| Người xây dựng Agent | Tuân thủ cấu trúc chuẩn |

## 5. Responsibilities — Nguyên tắc viết prompt hiệu quả
- Cụ thể hơn tổng quát; có ví dụ tốt/xấu khi phạm vi dễ nhầm lẫn
- Khuyến khích từng bước (step-by-step) cho Agent phân tích phức tạp (#04, #05, #16)
- Yêu cầu định dạng đầu ra rõ ràng thay vì để Agent tự quyết định

## 6. Standards — Checklist trước khi vận hành
- [ ] Đối chiếu Hiến pháp AI (EAIF-01-001)?
- [ ] Nêu rõ ranh giới với Agent dễ nhầm lẫn nhất?
- [ ] Gắn đúng cấp độ quyết định (EAIF-01-003)?
- [ ] Dùng đúng thuật ngữ (EAIF-01-013)?
- [ ] Có ít nhất 3 câu hỏi mẫu để kiểm thử?

## 7. Workflows
Mọi thay đổi Instructions.md phải ghi vào ChangeLog.md của Agent tương ứng — không sửa "âm thầm" (Điều 7 — Auditability).

## 8. Outputs
Instructions.md đạt chuẩn là điều kiện tiên quyết để Agent được đưa vào Volume 8.

## 9. Exceptions
Không áp dụng.

## 10. References
- EAIF-01-001, EAIF-01-003, EAIF-01-004, EAIF-01-013
- EAIF-00-012-Document-Structure.md
