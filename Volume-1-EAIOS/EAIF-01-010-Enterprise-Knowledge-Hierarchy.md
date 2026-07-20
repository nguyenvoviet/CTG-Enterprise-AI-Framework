---
document_title: Thứ bậc Nguồn Tri thức (Enterprise Knowledge Hierarchy)
document_code: EAIF-01-010
version: v1.0
status: Draft
volume: Volume 1 — Enterprise AI Operating System (EAIOS)
classification: Nội bộ
document_owner: AI Center of Excellence
document_reviewer: (chưa gán)
approved_by: (chưa phê duyệt)
purpose: Quy định thứ tự ưu tiên nguồn tri thức khi có mâu thuẫn dữ liệu
scope: Toàn bộ Volume 3 (Enterprise Knowledge Repository)
applicable_to: Toàn bộ 16 Agent, đặc biệt #09, #12, #05, #16
dependencies: EAIF-01-001 (Điều 4 — Single Source of Truth)
baseline: EAIF v2.5
effective_date: (chưa ban hành chính thức)
review_cycle: 12 tháng
related_documents: EAIF-01-001
change_history: |
  | Version | Ngày | Người soạn | Thay đổi |
  |---|---|---|---|
  | v1.0 | 2026-07-17 | AI CoE (soạn thảo qua Claude) | Chuyển đổi chuẩn Header v2.5 |
language: vi
---

# EAIF-01-010 — Thứ bậc Nguồn Tri thức (Enterprise Knowledge Hierarchy)

## 1. Purpose
Quy định cách Agent chọn nguồn đáng tin cậy hơn khi Volume 3 có thông tin mâu thuẫn.

## 2. Scope
Áp dụng khi Agent tra cứu tri thức và phát hiện xung đột giữa nhiều nguồn.

## 3. Principles — Thứ bậc ưu tiên
```
1. Văn bản pháp luật/quy định Nhà nước (Luật Đất đai, Nghị định môi trường...)
2. Văn bản chính thức đã công bố của CTG (cattuonggroup.com.vn, auroraip.vn)
3. Dữ liệu nội bộ đã được Business Owner xác nhận (Volume 3)
4. Quy trình/SOP nội bộ (Volume 5)
5. Suy luận/tổng hợp của Agent (luôn nêu rõ đây là suy luận)
```

## 4. Roles
| Vai trò | Trách nhiệm |
|---|---|
| Business Owner | Đảm bảo Volume 3 phản ánh đúng thứ bậc, không để dữ liệu cấp thấp "ghi đè" |

## 5. Responsibilities — Áp dụng đặc thù theo Agent
| Agent | Nguồn ưu tiên đặc thù |
|---|---|
| #12 | Luật Đất đai, quy hoạch địa phương > hồ sơ dự án nội bộ |
| #09 | Quy chuẩn môi trường quốc gia > tiêu chuẩn tự nguyện quốc tế > báo cáo nội bộ |
| #05 | Báo cáo tài chính đã kiểm toán > số liệu ước tính nội bộ |
| #16 | Dữ liệu đo lường trực tiếp > benchmark bên ngoài > ước tính |

## 6. Standards
Văn bản pháp luật luôn thắng nội bộ; dữ liệu mới hơn ưu tiên dữ liệu cũ cùng cấp bậc.

## 7. Workflows
Khi 2 nguồn cùng cấp bậc mâu thuẫn → Agent không tự chọn → nêu rõ khác biệt → đề xuất người dùng xác nhận Business Owner.

## 8. Outputs
Thứ bậc này là công cụ thực thi Điều 4 (Single Source of Truth) của Hiến pháp AI.

## 9. Exceptions
Không áp dụng.

## 10. References
- EAIF-01-001-Enterprise-AI-Constitution.md (Điều 4)
