## Phoenix Squad — Project Charter & Working Agreement

### I. Thông tin nhóm
#### 1.1. Tên nhóm & Tầm nhìn
- **Tên nhóm:** Phoenix Squad  
- **Slogan:** `Collaborate. Iterate. Deliver.`
- **Ý nghĩa tên nhóm:** Phoenix (Phượng Hoàng) tượng trưng cho sự tái sinh và không ngừng cải tiến — đúng tinh thần Agile: learn, adapt, deliver. Nhóm cam kết biến mỗi sprint thất bại thành bài học, mỗi bài học thành thành công.

#### 1.2. Mục tiêu dự án
- Hoàn thành sản phẩm phần mềm chạy được, đáp ứng đầy đủ yêu cầu trong **Product Backlog**.
- Áp dụng đúng quy trình Agile/Scrum: **sprint planning, daily standup, review, retrospective**.
- Mỗi thành viên đều học được kỹ năng kỹ thuật lẫn kỹ năng làm việc nhóm.
- Nộp báo cáo và thuyết trình cuối kỳ đúng hạn, chất lượng cao.

### II. Thành viên và vai trò
Nhóm gồm **6 thành viên**, mỗi người đảm nhận một vai trò chính theo mô hình Scrum. Vai trò có thể luân chuyển sau mỗi sprint nếu nhóm đồng ý.

| Thành viên | Vai trò | Trách nhiệm chính (tóm tắt) |
|---|---|---|
| Vũ Đức Hiếu | Scrum Master | Điều phối sprint, gỡ bỏ impediment, tổ chức các buổi Agile ceremony |
| Nguyễn Duy Khánh | Product Owner | Quản lý Product Backlog, ưu tiên user stories, đại diện stakeholder |
| Bùi Minh Đức | Lead Developer | Kiến trúc hệ thống, code review, mentor các thành viên junior |
| Phạm Xuân Bách | Backend Developer | Xây dựng API, database, business logic và unit test |
| Trần Ngọc An | Frontend Developer | UI/UX implementation, tích hợp API, responsive design |
| Nguyễn Gia Bảo | QA / DevOps | Test planning, kiểm thử, CI/CD pipeline, quản lý môi trường deploy |

#### 2.1. Trách nhiệm chung của tất cả thành viên
- Tham dự đầy đủ các buổi họp nhóm và Agile ceremony.
- Cập nhật task board (Trello/Jira) hàng ngày.
- Báo sớm cho nhóm nếu gặp vấn đề hoặc không hoàn thành task đúng hạn.
- Review code của nhau trước khi merge vào nhánh chính.
- Đóng góp vào tài liệu dự án (`README`, user stories, test cases).

### III. Kế hoạch 10 tuần
| Sprint | Tuần | Mục tiêu | Deliverable |
|---|---:|---|---|
| Sprint 0 | 1–2 | Kickoff, phân tích yêu cầu, thiết lập môi trường, viết Product Backlog | `Project charter`, `Backlog v1` |
| Sprint 1 | 3–4 | Xây dựng core features (authentication, CRUD cơ bản, UI skeleton) | `Demo v0.1` |
| Sprint 2 | 5–6 | Phát triển tính năng chính, tích hợp API, kiểm thử đơn vị | `Demo v0.5` |
| Sprint 3 | 7–8 | Hoàn thiện tính năng, UI/UX polish, kiểm thử tích hợp | `Demo v0.8` |
| Sprint 4 | 9–10 | Bug fix, UAT, triển khai, chuẩn bị báo cáo và thuyết trình | `Final product`, `Report` |

#### 3.1. Agile Ceremonies
| Ceremony | Thời điểm | Thời gian | Người dẫn |
|---|---|---:|---|
| Sprint Planning | Đầu mỗi sprint (Thứ 2) | 60 phút | Scrum Master + PO |
| Daily Standup | Hàng ngày (9:00 AM) | 15 phút | Scrum Master |
| Sprint Review | Cuối sprint (Thứ 6) | 30 phút | Product Owner |
| Retrospective | Cuối sprint (Thứ 6) | 30 phút | Scrum Master |

### IV. Cam kết làm việc
#### 4.1. Cam kết về thời gian
- Mỗi thành viên cam kết dành tối thiểu **12–15 giờ/tuần** cho dự án.
- Phản hồi tin nhắn trong nhóm trong vòng **3 giờ** (trong giờ hành chính 8:00–22:00).
- Thông báo vắng mặt trước **24 giờ**; nếu khẩn cấp báo ngay khi biết.
- Không được vắng mặt quá **2 buổi** họp trong toàn dự án mà không có lý do chính đáng.

#### 4.2. Cam kết về chất lượng
- Code phải có unit test, đạt coverage tối thiểu **60%**.
- Mỗi task phải có ít nhất **1 người review** trước khi merge.
- Không push thẳng lên nhánh `main` — dùng Pull Request với mô tả rõ ràng.
- Bug severity **P1** phải được fix trong vòng **24 giờ**; **P2** trong cùng sprint.

#### 4.3. Cam kết về tinh thần
- Tôn trọng ý kiến của nhau — không ngắt lời, không phán xét cá nhân.
- Chia sẻ kiến thức và hỗ trợ thành viên gặp khó khăn kỹ thuật.
- Ghi nhận đóng góp của nhau trong retrospective (`shout-outs`).
- Giữ thái độ tích cực, đặc biệt khi sprint không đạt mục tiêu.

### V. Quy tắc giao tiếp
#### 5.1. Kênh giao tiếp
| Kênh | Mục đích | Thời gian phản hồi |
|---|---|---|
| Messenger | Trao đổi nhanh hàng ngày, cập nhật progress | Trong vòng 3 giờ |
| GitHub Issues | Bug report, task tracking, technical discussion | Trong vòng 24 giờ |
| Discord | Sprint ceremony, họp nhóm định kỳ | Đúng giờ theo lịch |
| Email | Báo cáo chính thức, trao đổi với giảng viên | Trong vòng 24 giờ |
| Trello / Jira | Task board, sprint backlog, progress tracking | Cập nhật cuối mỗi ngày |

#### 5.2. Quy tắc họp nhóm
- Bắt đầu và kết thúc đúng giờ.
- Chuẩn bị trước: đọc tài liệu, update task board trước khi vào họp.
- Một người nói tại một thời điểm; không dùng điện thoại khi họp.
- Scrum Master ghi lại meeting notes và chia sẻ trong vòng 1 giờ sau khi họp.
- Mọi quyết định quan trọng phải được ghi vào tài liệu nhóm (Google Docs/Confluence).

#### 5.3. Nguyên tắc giao tiếp
- Nói về vấn đề, không nói về con người — tập trung vào giải pháp.
- Dùng ngôn ngữ rõ ràng, tránh mơ hồ: ghi rõ deadline, người chịu trách nhiệm.
- Feedback phải cụ thể, có ví dụ, và có tính xây dựng (SBI model: *Situation–Behavior–Impact*).
- Báo sớm khi gặp khó khăn — không im lặng chờ đến cuối sprint.

### VI. Giải quyết xung đột
#### 6.1. Quy trình 3 cấp
| Mức độ | Loại xung đột | Cách xử lý |
|---|---|---|
| Cấp 1 – Nhẹ | Bất đồng kỹ thuật, ý kiến khác nhau | Thảo luận trực tiếp trong nhóm, lấy ý kiến đa số (voting) |
| Cấp 2 – Vừa | Phân công công việc, deadline, chất lượng | Scrum Master hòa giải trong vòng 24h; họp retrospective |
| Cấp 3 – Nghiêm trọng | Vi phạm cam kết, xung đột cá nhân kéo dài | Đưa ra trước cả nhóm, có thể nhờ giảng viên hướng dẫn |

#### 6.2. Nguyên tắc ra quyết định
- **Đồng thuận (Consensus):** Cố gắng đạt đồng thuận trước — thảo luận đến khi mọi người đều chấp nhận được.
- **Bỏ phiếu đa số (Majority Vote):** Nếu sau 15 phút không đồng thuận, bỏ phiếu — `4/6` là qua.
- **Quyết định cuối cùng (Final Call):**  
  - Vấn đề kỹ thuật → Lead Developer  
  - Vấn đề product → Product Owner  
  - Vấn đề quy trình → Scrum Master

#### 6.3. Quy định xử lý vi phạm
| Lần vi phạm | Hệ quả |
|---|---|
| Lần 1 | Vắng họp không báo, không update task board, trễ deadline → Nhắc nhở riêng từ Scrum Master |
| Lần 2 | Lặp lại vi phạm sau khi đã nhắc → Thảo luận toàn nhóm, ghi vào retrospective |
| Lần 3+ | Vi phạm nghiêm trọng, ảnh hưởng dự án → Báo cáo giảng viên, điều chỉnh phân công |

### VII. Công cụ và môi trường làm việc
| Danh mục | Công cụ | Ghi chú |
|---|---|---|
| Version Control | Git + GitHub | Nhánh: `main`, `develop`, `feature/*`, `hotfix/*` |
| Project Tracking | Trello hoặc Jira | Sprint board, backlog, burndown chart |
| Giao tiếp | Messenger / Zalo + Meet | Channel riêng cho từng sprint |
| CI/CD | GitHub Actions | Auto-test khi push lên `develop` |
| Tài liệu | Google Docs / Notion | Meeting notes, user stories, API docs |
| IDE | VS Code + extensions | ESLint, Prettier, GitLens |

