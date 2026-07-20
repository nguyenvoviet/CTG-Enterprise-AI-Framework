---
document_title: Quản trị AI (AI Governance)
document_code: EAIF-01-007
version: v1.0
status: Draft
volume: Volume 1 — Enterprise AI Operating System (EAIOS)
classification: Nội bộ
document_owner: AI Transformation Advisor (#14) / IT Risk & Security Advisor (#03)
document_reviewer: (chưa gán)
approved_by: (chưa phê duyệt)
purpose: Quản trị rủi ro kỹ thuật đặc thù của AI — vòng đời Agent, giám sát, kiểm tra định kỳ
scope: Toàn bộ vòng đời kỹ thuật của 16 Agent
applicable_to: AI CoE, IT Risk & Security Advisor
dependencies: EAIF-01-006
baseline: EAIF v2.5
effective_date: (chưa ban hành chính thức)
review_cycle: Hàng quý
related_documents: EAIF-01-006, EAIF-01-008
change_history: |
  | Version | Ngày | Người soạn | Thay đổi |
  |---|---|---|---|
  | v1.0 | 2026-07-17 | AI CoE (soạn thảo qua Claude) | Chuyển đổi chuẩn Header v2.5 |
language: vi
---

# EAIF-01-007 — Quản trị AI (AI Governance)

## 1. Purpose
Quản trị các rủi ro đặc thù công nghệ AI: chất lượng mô hình, an toàn dữ liệu ngữ cảnh, giám sát hiệu năng — khác Enterprise Governance (EAIF-01-006) là quản trị tổ chức tổng thể.

## 2. Scope
Vòng đời kỹ thuật của Agent từ đề xuất đến ngừng hoạt động.

## 3. Principles — Vòng đời quản trị một Agent
```
Đề xuất → Thẩm định (#14) → Thí điểm có giám sát → Đánh giá chất lượng (EAIF-01-005)
   → Phê duyệt chính thức (Volume 8) → Giám sát định kỳ → Ngừng/Nâng cấp khi cần
```

## 4. Roles
| Vai trò | Trách nhiệm |
|---|---|
| AI Transformation Advisor (#14) | "Người gác cổng" — xác nhận mọi Agent mới/thay đổi lớn |
| IT Risk & Security Advisor (#03) | Rà soát rủi ro hạ tầng/an ninh mạng |

## 5. Responsibilities — Rủi ro AI cần giám sát
| Rủi ro | Biện pháp kiểm soát |
|---|---|
| Dữ liệu nguồn lỗi thời | Business Owner cập nhật định kỳ; Agent cảnh báo khi dữ liệu quá hạn |
| Prompt injection | Áp dụng Enterprise Guardrails (EAIF-01-008) |
| Scope creep | Giám sát định kỳ đối chiếu Bounded Context |
| Phụ thuộc 1 nhà cung cấp | CoE theo dõi định kỳ (EAIF-00-006) |
| Thiên lệch (bias) dữ liệu | Đối chiếu nhiều nguồn trước khi dùng cho quyết định lớn |

## 6. Standards
Hàng quý rà soát ngẫu nhiên mẫu câu trả lời của Agent Cấp 3 (#09, #12).

## 7. Workflows
Khi có sự cố: điều tra root cause theo quy trình tại EAIF-01-005 (Response Standards).

## 8. Outputs
Báo cáo audit định kỳ là input cho báo cáo quý của Enterprise Governance (EAIF-01-006).

## 9. Exceptions
Không áp dụng.

## 10. References
- EAIF-01-006-Enterprise-Governance.md
- EAIF-01-008-Enterprise-Guardrails.md
