---
document_title: Nguyên tắc Kiến trúc (Architecture Principles)
document_code: EAIF-00-009
version: v1.0
status: Draft
volume: Volume 0 — Nền tảng Doanh nghiệp
classification: Nội bộ
document_owner: CTO Executive Advisor (#01) / IT Risk & Security Advisor (#03)
document_reviewer: (chưa gán)
approved_by: (chưa phê duyệt)
purpose: Quy định 8 nguyên tắc kiến trúc bắt buộc cho mọi thiết kế Agent và tích hợp hệ thống
scope: Toàn bộ Volume 2 khi thiết kế Agent mới, toàn bộ tích hợp kỹ thuật
applicable_to: AI CoE, người xây dựng Agent, nhà cung cấp bên ngoài
dependencies: EAIF-00-001, EAIF-00-003
baseline: EAIF v2.5
effective_date: (chưa ban hành chính thức)
review_cycle: 12 tháng
related_documents: EAIF-01-001, EAIF-01-009
change_history: |
  | Version | Ngày | Người soạn | Thay đổi |
  |---|---|---|---|
  | v1.0 | 2026-07-17 | AI CoE (soạn thảo qua Claude) | Chuyển đổi chuẩn Header v2.5 |
language: vi
---

# EAIF-00-009 — Nguyên tắc Kiến trúc (Architecture Principles)

## 1. Purpose
Thiết lập 8 nguyên tắc kỹ thuật/quản trị bắt buộc, là "hiến pháp kỹ thuật" của EAIF.

## 2. Scope
Áp dụng cho mọi quyết định thiết kế Agent, tích hợp hệ thống.

## 3. Principles
| # | Nguyên tắc | Nội dung |
|---|---|---|
| 1 | Single Source of Truth | Mỗi loại tri thức chỉ có 1 nơi lưu trữ chính thức (Volume 3) |
| 2 | Bounded Context | Mỗi Agent có ranh giới trách nhiệm rõ ràng, không chồng chéo |
| 3 | Human-in-the-loop | Agent rủi ro cao chỉ hỗ trợ phân tích, không tự động phê duyệt |
| 4 | Auditability | Câu trả lời rủi ro cao phải truy vết được nguồn gốc |
| 5 | Modularity | 16 Agent độc lập, dễ mở rộng khi có mảng kinh doanh mới |
| 6 | Least Privilege | Dữ liệu nhạy cảm chỉ hiển thị cho Agent/người dùng có thẩm quyền |
| 7 | Đa ngôn ngữ có kiểm soát | Nội dung đa ngôn ngữ (#08) phải qua kiểm tra chất lượng trước khi gửi nhà đầu tư |
| 8 | Phân tách dữ liệu nội bộ/bên thứ ba | Dữ liệu nhân sự CTG và lao động nhà đầu tư thứ cấp tách biệt hoàn toàn |

## 4. Roles
| Vai trò | Trách nhiệm |
|---|---|
| CTO (#01) | Rà soát kỹ thuật mọi thiết kế Agent |
| IT Risk & Security (#03) | Rà soát Nguyên tắc 6-8 (bảo mật/phân tách dữ liệu) |
| AI Transformation Advisor (#14) | Xác nhận tuân thủ đầy đủ trước khi phê duyệt Agent mới |

## 5. Responsibilities
Trước khi phê duyệt Agent mới vào Volume 8, #14 phải xác nhận Agent tuân thủ đầy đủ 8 nguyên tắc.

## 6. Standards
Mỗi nguyên tắc là tiêu chuẩn bắt buộc — không có "nguyên tắc tùy chọn".

## 7. Workflows
```
Thiết kế Agent mới → Checklist 8 nguyên tắc → CTO + IT Risk & Security rà soát
   → AI Transformation Advisor xác nhận → Phê duyệt vào Volume 8
```

## 8. Outputs
Checklist 8 nguyên tắc được nhúng vào Enterprise Prompting Standard (EAIF-01-015).

## 9. Exceptions
Không có ngoại lệ — vi phạm bất kỳ nguyên tắc nào đều phải khắc phục trước khi vận hành chính thức.

## 10. References
- EAIF-01-001-Enterprise-AI-Constitution.md
- EAIF-01-009-Enterprise-Data-Privacy-Standard.md
