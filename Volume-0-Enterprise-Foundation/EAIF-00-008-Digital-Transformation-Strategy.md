---
document_title: Chiến lược Chuyển đổi số (Digital Transformation Strategy)
document_code: EAIF-00-008
version: v1.0
status: Draft
volume: Volume 0 — Nền tảng Doanh nghiệp
classification: Nội bộ
document_owner: CTO Executive Advisor (#01) / AI Center of Excellence
document_reviewer: (chưa gán)
approved_by: (chưa phê duyệt)
purpose: Định vị EAIF trong bức tranh chuyển đổi số tổng thể và nguyên tắc số hóa trước khi triển khai AI
scope: Toàn bộ hạ tầng số của CTG có liên quan đến EAIF
applicable_to: CTO, AI CoE, Business Owner
dependencies: EAIF-00-006, EAIF-00-009
baseline: EAIF v2.5
effective_date: (chưa ban hành chính thức)
review_cycle: 6 tháng
related_documents: EAIF-00-009, EAIF-06 (Data Standards)
change_history: |
  | Version | Ngày | Người soạn | Thay đổi |
  |---|---|---|---|
  | v1.0 | 2026-07-17 | AI CoE (soạn thảo qua Claude) | Chuyển đổi chuẩn Header v2.5 |
language: vi
---

# EAIF-00-008 — Chiến lược Chuyển đổi số (Digital Transformation Strategy)

## 1. Purpose
Xác định vị trí của EAIF như lớp trí tuệ (intelligence layer) trên nền hạ tầng số hiện có, không thay thế hệ thống lõi.

## 2. Scope
Áp dụng khi quyết định thứ tự số hóa quy trình trước khi giao cho Agent xử lý.

## 3. Principles
```
Lớp Trải nghiệm     →  Nhân viên, khách hàng, nhà đầu tư tương tác qua Copilot/Chat
Lớp Trí tuệ (EAIF)  →  16 Agent, tri thức chuẩn hóa (Volume 3), prompt library (Volume 4)
Lớp Dữ liệu         →  ERP, CRM, hồ sơ pháp lý, dữ liệu vận hành Aurora IP
Lớp Hạ tầng         →  Microsoft 365/Copilot, SharePoint, hệ thống nội bộ
```
- Số hóa trước, thông minh hóa sau — không xây Agent cho quy trình còn thủ công.
- Tận dụng hạ tầng sẵn có (Microsoft Copilot) thay vì xây nền tảng riêng tốn kém.

## 4. Roles
| Vai trò | Trách nhiệm |
|---|---|
| CTO Executive Advisor (#01) | Đánh giá mức độ sẵn sàng hạ tầng trước khi triển khai Agent |
| AI CoE | Điều phối lộ trình số hóa theo mảng kinh doanh |

## 5. Responsibilities
| Mảng | Mức độ số hóa (ước tính) | Việc cần làm trước AI |
|---|---|---|
| Dân dụng/Thương mại (Sales & CRM) | Trung bình | Chuẩn hóa dữ liệu khách hàng đa kênh |
| Pháp lý đất đai | Thấp | Số hóa hồ sơ pháp lý dự án |
| Aurora IP — vận hành | Trung bình | Kết nối dữ liệu cảm biến/SLA hạ tầng |
| Aurora IP — xúc tiến đầu tư | Thấp-Trung bình | Chuẩn hóa hồ sơ nhà đầu tư đa ngôn ngữ |

## 6. Standards
Phối hợp chặt chẽ với Data Standards (Volume 6) để dữ liệu được số hóa đúng chuẩn trước khi đưa vào Agent.

## 7. Workflows
```
Đánh giá mức độ số hóa hiện tại → Số hóa nếu chưa đạt chuẩn → Mới triển khai Agent tương ứng
```

## 8. Outputs
Lộ trình số hóa theo mảng kinh doanh (Mục 5) là input cho quyết định thí điểm Agent tại EAIF-00-006 (Giai đoạn 2).

## 9. Exceptions
Rủi ro: triển khai AI trước khi số hóa xong → Agent trả lời dựa trên dữ liệu thiếu/lỗi thời → mất niềm tin người dùng.

## 10. References
- EAIF-00-006-AI-Strategy.md
- EAIF-00-009-Architecture-Principles.md
