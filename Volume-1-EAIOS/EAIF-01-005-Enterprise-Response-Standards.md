---
document_title: Tiêu chuẩn Chất lượng Câu trả lời (Enterprise Response Standards)
document_code: EAIF-01-005
version: v1.0
status: Draft
volume: Volume 1 — Enterprise AI Operating System (EAIOS)
classification: Nội bộ
document_owner: AI Center of Excellence
document_reviewer: (chưa gán)
approved_by: (chưa phê duyệt)
purpose: Xác định 5 tiêu chí chất lượng câu trả lời, dùng làm căn cứ đánh giá tại Volume 8
scope: Mọi câu trả lời của 16 Agent
applicable_to: Toàn bộ 16 Agent, đặc biệt Agent Cấp 3 (#09, #12)
dependencies: EAIF-01-003
baseline: EAIF v2.5
effective_date: (chưa ban hành chính thức)
review_cycle: 6 tháng
related_documents: EAIF-08 (Đánh giá chất lượng)
change_history: |
  | Version | Ngày | Người soạn | Thay đổi |
  |---|---|---|---|
  | v1.0 | 2026-07-17 | AI CoE (soạn thảo qua Claude) | Chuyển đổi chuẩn Header v2.5 |
language: vi
---

# EAIF-01-005 — Tiêu chuẩn Chất lượng Câu trả lời (Enterprise Response Standards)

## 1. Purpose
Xác định tiêu chí đánh giá chất lượng câu trả lời, làm căn cứ cho Volume 8 (Đánh giá chất lượng).

## 2. Scope
Áp dụng cho mọi đầu ra của 16 Agent.

## 3. Principles — Năm tiêu chí chất lượng
| Tiêu chí | Mô tả | Cách kiểm tra |
|---|---|---|
| Chính xác | Đúng với nguồn Volume 3 | Đối chiếu ngẫu nhiên |
| Đầy đủ phạm vi | Không bỏ sót khía cạnh quan trọng | Business Owner rà soát mẫu |
| Có thể truy vết | Có trích dẫn nguồn với lĩnh vực rủi ro cao | Kiểm tra bắt buộc |
| Đúng phạm vi Agent | Không vượt Bounded Context | So khớp Volume 2 |
| Rõ ràng, dễ hành động | Người dùng biết bước tiếp theo | Khảo sát người dùng |

## 4. Roles
| Vai trò | Trách nhiệm |
|---|---|
| AI CoE | Xác định ngưỡng chất lượng tối thiểu |
| Business Owner | Kiểm tra mẫu trước khi công bố rộng rãi |

## 5. Responsibilities — Ngưỡng chất lượng tối thiểu
- Agent Cấp 3 (#09, #12): 100% câu trả lời kết luận phải có nguồn trích dẫn, không ngoại lệ.
- Agent Cấp 1-2: đạt "chính xác" và "đúng phạm vi" qua kiểm tra mẫu.

## 6. Standards — Không chấp nhận
- Câu trả lời "có vẻ đúng" không thể kiểm chứng, đặc biệt dữ liệu số.
- Copy nguyên văn nguồn bên ngoài không qua kiểm duyệt.

## 7. Workflows — Xử lý câu trả lời sai
```
Phát hiện câu trả lời sai → Xác định nguyên nhân (dữ liệu nguồn hay Agent suy diễn?)
   → Do dữ liệu → Business Owner cập nhật Volume 3
   → Do Agent suy diễn → AI CoE điều chỉnh Instructions.md
   → Ghi nhận vào ChangeLog của Agent
```

## 8. Outputs
Cơ sở để AI CoE quyết định Agent đủ điều kiện chuyển từ "thí điểm" sang "vận hành chính thức" (Volume 8).

## 9. Exceptions
Không có ngoại lệ với yêu cầu nguồn trích dẫn ở Agent Cấp 3.

## 10. References
- EAIF-01-003-Enterprise-Decision-Framework.md
