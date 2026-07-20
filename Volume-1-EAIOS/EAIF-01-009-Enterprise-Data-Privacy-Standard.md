---
document_title: Tiêu chuẩn Bảo mật Dữ liệu Doanh nghiệp (Enterprise Data Privacy Standard)
document_code: EAIF-01-009
version: v1.0
status: Draft — cần IT Risk & Security Advisor và tư vấn pháp lý rà soát
volume: Volume 1 — Enterprise AI Operating System (EAIOS)
classification: Nội bộ — Nhạy cảm
document_owner: IT Risk & Security Advisor (#03)
document_reviewer: (chưa gán)
approved_by: (chưa phê duyệt)
purpose: Quy định phân loại và nguyên tắc xử lý dữ liệu cá nhân trong toàn bộ EAIF
scope: Mọi dữ liệu cá nhân được Agent xử lý
applicable_to: Agent #05, #08, #11, #12, #13
dependencies: EAIF-00-009 (Nguyên tắc 6, 8)
baseline: EAIF v2.5
effective_date: (chưa ban hành chính thức)
review_cycle: Theo quy định pháp luật hiện hành về bảo vệ dữ liệu cá nhân
related_documents: EAIF-00-009, EAIF-01-008
change_history: |
  | Version | Ngày | Người soạn | Thay đổi |
  |---|---|---|---|
  | v1.0 | 2026-07-17 | AI CoE (soạn thảo qua Claude) | Chuyển đổi chuẩn Header v2.5 |
language: vi
---

# EAIF-01-009 — Tiêu chuẩn Bảo mật Dữ liệu Doanh nghiệp (Enterprise Data Privacy Standard)

## 1. Purpose
Đảm bảo mọi dữ liệu cá nhân được Agent xử lý tuân thủ quy định bảo vệ dữ liệu cá nhân hiện hành.

## 2. Scope
Hồ sơ khách hàng (CRM), nhà đầu tư (Aurora IP), nhân sự CTG, lao động nhà đầu tư thứ cấp.

## 3. Principles — Phân loại dữ liệu
| Cấp độ | Ví dụ | Agent xử lý |
|---|---|---|
| Công khai | Tin dự án đã công bố | Tất cả |
| Nội bộ | SOP, số liệu chưa công bố | Đa số |
| Nhạy cảm | Dữ liệu khách hàng, hồ sơ nhân sự | #11, #13, #05 |
| Rất nhạy cảm | CCCD, dữ liệu tài chính cá nhân, hồ sơ tranh chấp | #12, #05, #13 |

## 4. Roles
| Vai trò | Trách nhiệm |
|---|---|
| IT Risk & Security Advisor (#03) | Chủ sở hữu tiêu chuẩn, xử lý sự cố dữ liệu |
| Business Owner từng Agent | Đảm bảo Agent tuân thủ giới hạn truy cập theo vai trò |

## 5. Responsibilities — Nguyên tắc xử lý
- Thu thập đúng mục đích, tối thiểu hóa dữ liệu truy xuất
- Giới hạn truy cập theo vai trò/thẩm quyền công việc
- Lưu trữ có thời hạn theo quy định pháp luật

## 6. Standards — Phân tách dữ liệu đặc thù CTG
- Dữ liệu nhân sự CTG (#13) và lao động nhà đầu tư thứ cấp (Volume 3) tách biệt hoàn toàn
- Dữ liệu nhà đầu tư nước ngoài (#08) lưu ý yêu cầu bảo vệ dữ liệu khác nhau theo quốc gia

## 7. Workflows
Khi chủ thể dữ liệu yêu cầu xem/sửa/xóa dữ liệu cá nhân → Agent không tự xử lý → hướng dẫn đến bộ phận phụ trách.

## 8. Outputs
Bảng phân loại dữ liệu (Mục 3) là căn cứ cấp quyền truy cập cho mọi Agent.

## 9. Exceptions
Sự cố rò rỉ/truy cập sai thẩm quyền phải báo ngay IT Risk & Security Advisor (#03), ghi nhận Volume 8.

## 10. References
- EAIF-00-009-Architecture-Principles.md (Nguyên tắc 6, 8)
- Quy định pháp luật Việt Nam hiện hành về bảo vệ dữ liệu cá nhân (cần tham vấn pháp lý chính thức)
