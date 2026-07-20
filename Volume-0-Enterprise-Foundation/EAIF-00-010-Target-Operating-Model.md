---
document_title: Mô hình Vận hành Mục tiêu (Target Operating Model)
document_code: EAIF-00-010
version: v1.0
status: Draft
volume: Volume 0 — Nền tảng Doanh nghiệp
classification: Nội bộ
document_owner: AI Center of Excellence
document_reviewer: (chưa gán)
approved_by: (chưa phê duyệt)
purpose: Xác định cơ cấu quản trị, vai trò, và quy trình phê duyệt Agent cho chương trình AI
scope: Toàn bộ vòng đời quản trị chương trình AI
applicable_to: Ban Chỉ đạo AI, AI CoE, Business Owner, người dùng cuối
dependencies: EAIF-00-006, EAIF-00-009
baseline: EAIF v2.5
effective_date: (chưa ban hành chính thức)
review_cycle: 6 tháng
related_documents: EAIF-01-006, EAIF-08
change_history: |
  | Version | Ngày | Người soạn | Thay đổi |
  |---|---|---|---|
  | v1.0 | 2026-07-17 | AI CoE (soạn thảo qua Claude) | Chuyển đổi chuẩn Header v2.5 |
language: vi
---

# EAIF-00-010 — Mô hình Vận hành Mục tiêu (Target Operating Model)

## 1. Purpose
Xác định cơ cấu quản trị đề xuất và quy trình phê duyệt Agent mới.

## 2. Scope
Áp dụng cho toàn bộ quy trình quản trị chương trình AI từ đề xuất đến vận hành.

## 3. Principles — Mô hình quản trị đề xuất
```
Ban Chỉ đạo AI (Ban Điều hành + đại diện mảng KD) → phê duyệt chiến lược, ngân sách
   → AI Center of Excellence (#14 + #01) → quản trị danh mục Agent, chuẩn hóa Volume 1/3/6
      → Business Owner theo mảng (Dân dụng/TM, Aurora IP, Tài chính/RR, Nhân sự/CSKH)
         → sở hữu Agent tương ứng
```

## 4. Roles
| Vai trò | Trách nhiệm chính |
|---|---|
| Ban Chỉ đạo AI | Phê duyệt ngân sách, chọn Agent ưu tiên theo giai đoạn |
| AI Center of Excellence | Quản lý danh mục Agent, đảm bảo tuân thủ Architecture Principles, đào tạo người dùng |
| Business Owner | Xác nhận nội dung tri thức đúng và cập nhật |
| Người dùng cuối | Sử dụng đúng phạm vi, phản hồi chất lượng |

## 5. Responsibilities — Quy trình đề xuất & phê duyệt Agent mới
1. Phòng ban đề xuất qua AI Transformation Advisor (#14)
2. #14 đánh giá trùng lặp và tuân thủ Architecture Principles (EAIF-00-009)
3. Trình Ban Chỉ đạo AI phê duyệt nếu vượt ngưỡng đầu tư/rủi ro
4. Agent được thêm vào Volume 2 + Volume 8 với đầy đủ hồ sơ

## 6. Standards
Mọi vai trò và quy trình trên phải khớp với cơ cấu tổ chức thực tế của CTG — cần điều chỉnh trước khi ban hành.

## 7. Workflows — Chu kỳ vận hành định kỳ
| Tần suất | Hoạt động |
|---|---|
| Hàng tuần | CoE theo dõi KPI sử dụng cơ bản |
| Hàng tháng | Business Owner rà soát chất lượng câu trả lời |
| Hàng quý | Ban Chỉ đạo AI đánh giá tổng thể, quyết định mở rộng/điều chỉnh |

## 8. Outputs
Danh mục Agent chính thức (Volume 8) với đầy đủ chủ sở hữu, phiên bản, KPI.

## 9. Exceptions
Mô hình cần điều chỉnh phù hợp cơ cấu tổ chức thực tế hiện tại của CTG trước khi ban hành chính thức.

## 10. References
- EAIF-00-006-AI-Strategy.md
- EAIF-01-006-Enterprise-Governance.md
