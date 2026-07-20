---
document_title: Tổng quan Khung (Framework Overview)
document_code: EAIF-00-011
version: v1.0
status: Draft
volume: Volume 0 — Nền tảng Doanh nghiệp
classification: Nội bộ
document_owner: AI Center of Excellence
document_reviewer: (chưa gán)
approved_by: (chưa phê duyệt)
purpose: Cung cấp bản đồ định hướng nhanh cho người đọc mới về toàn bộ 9 Volume của EAIF
scope: Toàn bộ EAIF
applicable_to: Mọi người dùng, mọi vai trò
dependencies: (tổng hợp toàn bộ Volume 0-8)
baseline: EAIF v2.5
effective_date: (chưa ban hành chính thức)
review_cycle: Khi có thay đổi cấu trúc Volume
related_documents: EAIF-00-012, EAIF-00-013
change_history: |
  | Version | Ngày | Người soạn | Thay đổi |
  |---|---|---|---|
  | v1.0 | 2026-07-17 | AI CoE (soạn thảo qua Claude) | Chuyển đổi chuẩn Header v2.5, cập nhật Volume 0 lên 13 mục |
language: vi
---

# EAIF-00-011 — Tổng quan Khung (Framework Overview)

## 1. Purpose
Là "bản đồ" giúp người đọc mới định hướng nhanh trong toàn bộ EAIF trước khi đi sâu từng Volume.

## 2. Scope
Mô tả tổng quan 9 Volume và đối tượng sử dụng chính của mỗi Volume.

## 3. Principles — Cấu trúc 9 Volume
| Volume | Nội dung | Đối tượng chính |
|---|---|---|
| 0 — Nền tảng Doanh nghiệp | Tầm nhìn, sứ mệnh, giá trị, văn hóa, triết lý lãnh đạo, chiến lược AI, nguyên tắc kiến trúc (13 mục) | Ban Điều hành, AI CoE |
| 1 — EAIOS | "Hiến pháp" AI: nguyên tắc, guardrail, tiêu chuẩn giao tiếp (15 mục) | Toàn bộ Agent tham chiếu |
| 2 — Bộ Agent AI (16 Persona) | Phạm vi, năng lực, giới hạn từng Agent | Người dùng cuối, Business Owner |
| 3 — Kho Tri thức Doanh nghiệp | Nguồn dữ liệu chính thức theo lĩnh vực | Agent tra cứu, Business Owner cập nhật |
| 4 — Thư viện Prompt | Prompt mẫu theo phòng ban/Agent | Người dùng cuối |
| 5 — Biểu mẫu Doanh nghiệp | Template chuẩn hóa | Toàn bộ nhân sự |
| 6 — Tiêu chuẩn Doanh nghiệp | Quy chuẩn viết, đặt tên, bảo mật | AI CoE, người tạo nội dung |
| 7 — Sổ tay Người dùng | Hướng dẫn theo nhóm người dùng | Người dùng cuối |
| 8 — Vận hành & Vòng đời AI | Danh mục Agent, KPI, quản lý thay đổi | AI CoE, Ban Chỉ đạo AI |

## 4. Roles
| Nhóm | Volume cần quan tâm nhất |
|---|---|
| Ban Điều hành / HĐQT | 0, 8 |
| AI Center of Excellence | 0, 1, 6, 8 |
| Business Owner từng Agent | 2, 3 |
| Người dùng cuối | 2, 4, 7 |

## 5. Responsibilities
AI CoE chịu trách nhiệm cập nhật tài liệu này ngay khi cấu trúc Volume thay đổi (theo Quy tắc số 1 — Baseline Architecture).

## 6. Standards
- Volume 0-1 đọc trước khi tham gia bất kỳ vai trò nào — nền tảng bắt buộc.
- Volume 2 là nơi tra cứu nhanh "nên hỏi Agent nào cho việc gì".

## 7. Workflows
Người dùng mới → đọc Framework Overview → xác định vai trò → đọc Volume tương ứng theo bảng Mục 4.

## 8. Outputs
Bản đồ định hướng (Mục 3-4) dùng làm trang giới thiệu khi onboard người dùng mới vào EAIF.

## 9. Exceptions
Không áp dụng.

## 10. References
- EAIF-00-012-Document-Structure.md
- EAIF-00-013-Version-History.md
