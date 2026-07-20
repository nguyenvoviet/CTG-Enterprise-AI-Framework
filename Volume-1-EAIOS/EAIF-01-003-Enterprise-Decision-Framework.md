---
document_title: Khung Ra quyết định cho mọi Agent (Enterprise Decision Framework)
document_code: EAIF-01-003
version: v1.0
status: Draft
volume: Volume 1 — Enterprise AI Operating System (EAIOS)
classification: Nội bộ
document_owner: AI Center of Excellence / Chief Risk Advisor (#04)
document_reviewer: (chưa gán)
approved_by: (chưa phê duyệt)
purpose: Xác định 3 cấp độ quyết định AI được phép thực hiện, phân loại cho cả 16 Agent
scope: Toàn bộ quyết định do Agent đưa ra
applicable_to: Toàn bộ 16 Agent
dependencies: EAIF-01-001
baseline: EAIF v2.5
effective_date: (chưa ban hành chính thức)
review_cycle: 6 tháng, cùng chu kỳ đánh giá chất lượng Agent
related_documents: EAIF-01-002, EAIF-01-008
change_history: |
  | Version | Ngày | Người soạn | Thay đổi |
  |---|---|---|---|
  | v1.0 | 2026-07-17 | AI CoE (soạn thảo qua Claude) | Chuyển đổi chuẩn Header v2.5 |
language: vi
---

# EAIF-01-003 — Khung Ra quyết định cho mọi Agent (Enterprise Decision Framework)

## 1. Purpose
Xác định rõ AI được quyết định gì, đề xuất gì, và không bao giờ được động vào gì.

## 2. Scope
Áp dụng cho mọi đầu ra của 16 Agent.

## 3. Principles — Ba cấp độ quyết định
| Cấp độ | Định nghĩa | Ví dụ |
|---|---|---|
| Cấp 1 — Tự động hoàn toàn | Trả lời/thực hiện trực tiếp | Tra cứu, tổng hợp dữ liệu có sẵn, soạn nháp văn bản |
| Cấp 2 — Đề xuất, người dùng xác nhận | Khuyến nghị, người dùng quyết định | Đề xuất phân khúc giá, so sánh phương án tài chính |
| Cấp 3 — Chỉ phân tích | Không đề xuất hành động cụ thể | Tình trạng pháp lý đất đai (#12), tuân thủ môi trường (#09) |

## 4. Roles
| Vai trò | Trách nhiệm |
|---|---|
| Chief Risk Advisor (#04) | Dùng khung này xây dựng risk appetite statement |
| Business Owner | Phê duyệt thay đổi cấp độ, ghi nhận tại Volume 8 |

## 5. Responsibilities — Phân loại 16 Agent theo cấp độ mặc định
| Agent | Cấp độ |
|---|---|
| #01, #03, #04, #05, #08, #13, #14, #15 | Cấp 2 |
| #02, #06, #07, #10, #11, #16 | Cấp 1-2 |
| **#09, #12** | **Cấp 3** (hậu quả sai sót nghiêm trọng, khó đảo ngược nhất) |

## 6. Standards
Không Agent nào được tự nâng cấp độ quyết định của mình — thay đổi phải do Business Owner phê duyệt.

## 7. Workflows
Một Agent có thể tạm hạ xuống Cấp 3 nếu dữ liệu nguồn (Volume 3) chưa đủ tin cậy.

## 8. Outputs
Bảng phân loại (Mục 5) là input trực tiếp cho Instructions.md mỗi Agent.

## 9. Exceptions
Agent #09 và #12 không có ngoại lệ nâng cấp — luôn ở Cấp 3 do tính chất lĩnh vực.

## 10. References
- EAIF-01-001-Enterprise-AI-Constitution.md
- EAIF-01-008-Enterprise-Guardrails.md
