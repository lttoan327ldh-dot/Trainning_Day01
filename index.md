# Tổng hợp Training — Cuộc thi "Khởi Nguyên" Vòng 2
*Nghiên cứu thị trường & Xây dựng Mô hình kinh doanh cho đề án EdTech*

---

##  Bối cảnh đề bài Vòng 2

**Mục tiêu:** Tạo ra một sản phẩm công nghệ để giải quyết một bài toán/nỗi đau trong thực tế (ưu tiên lĩnh vực Giáo dục - EdTech). Mỗi đội thi gồm SV Quản trị Kinh doanh (Project Manager, Business Analyst) và SV CNTT (Product Developer, Software Engineer).

**Đề án phải giải quyết trọn vẹn 4 phần:**
1. Xác định vấn đề — "nỗi đau" cụ thể của khách hàng/thị trường
2. Phân tích thị trường — chứng minh nỗi đau đủ lớn (cung-cầu, khách hàng mục tiêu, đối thủ)
3. Giải pháp công nghệ — tính năng cốt lõi, tính khả thi kỹ thuật
4. Bản Demo UX/UI — mockup/prototype trực quan hóa luồng trải nghiệm

**Tiêu chí chấm điểm:**
| Hạng mục | Tỷ trọng | Chi tiết |
|---|---|---|
| Hình thức | 10% | Bố cục rõ ràng, không lỗi chính tả/ngữ pháp, đúng quy định BTC |
| Kinh doanh & Thị trường (QTKD) | 60% | Định vị vấn đề (20đ), Nghiên cứu thị trường (25đ), Tính khả thi (15đ) |
| Công nghệ & Sản phẩm (CNTT) | 30% | Giải pháp công nghệ (20đ), UI (10đ) |
| Điểm cộng | +5đ | Dự án thuộc mảng Giáo dục/EdTech |

**Quy chế nộp bài:**
- File PDF ≤15MB, tối đa 20 slides, kèm link demo UX/UI (Figma/Adobe XD, public)
- Tên file/tiêu đề email: `[KHOINGUYEN - Vong 2] - Tên đội thi`
- Hạn nộp: **12h00, ngày 08/07/2026**
- Trễ mỗi 30 phút: trừ 10% tổng điểm. Trễ quá 2 tiếng: hủy kết quả

---

## Phần I — Quy trình 5 bước Nghiên cứu Thị trường

### Bước 1: Giả thuyết về khách hàng
- Định hình chân dung khách hàng mục tiêu **trước khi** thu thập dữ liệu (tránh khảo sát đại trà làm loãng số liệu, lãng phí ngân sách)
- Khoanh vùng theo **nhân khẩu học** (demographics: tuổi, giới tính, nghề nghiệp, thu nhập...) & **hành vi** (behavior: thói quen sử dụng, kênh tiếp cận, mức sẵn sàng chi trả...)
- Đặt giả thuyết về vấn đề lớn nhất của khách hàng
- *Nền tảng lý thuyết:* áp dụng tư duy Lean Startup (Eric Ries) — đặt giả thuyết có căn cứ trước, xác minh (validate) sau, thay vì khảo sát đại trà ngay từ đầu
- *Lưu ý cho EdTech:* thường có 2 lớp khách hàng — **end-user** (học sinh/sinh viên dùng sản phẩm) và **buyer** (phụ huynh/nhà trường trả tiền). Cần tách rõ 2 nhóm này khi đặt giả thuyết.

### Bước 2: Xác định "nỗi đau" (Pain point)
- Đi sâu thế giới quan khách hàng qua **phỏng vấn sâu (IDI - In-Depth Interview)** hoặc **thảo luận nhóm nhỏ 3-4 người (FGD - Focus Group Discussion)**
- 4 nhóm nỗi đau cần khai thác (mô hình "4 loại Buyer's Pain Points"):
  - **Tài chính:** chi quá nhiều cho giải pháp hiện tại
  - **Năng suất:** tốn quá nhiều thời gian, công sức
  - **Quy trình:** cách mua hàng/tiếp cận quá rắc rối
  - **Hỗ trợ:** không được tư vấn chu đáo
- Gợi ý ví dụ EdTech: tài chính (phụ huynh chi nhiều học thêm không hiệu quả), năng suất (SV mất thời gian tìm tài liệu ôn tập phù hợp), quy trình (đăng ký môn học rắc rối), hỗ trợ (giảng viên không theo sát từng SV)

### Bước 3: Đánh giá Cung - Cầu
**Phân tích CUNG (Supply side analysis):**
- Lập danh sách đối thủ **trực tiếp** (cùng bài toán, cùng cách giải quyết) & **gián tiếp** (cùng nhu cầu, khác cách giải quyết — VD: gia sư truyền thống, nhóm học Facebook)
- Mua thử sản phẩm để phân tích: chiến lược giá, điểm mạnh/yếu, lỗi vận hành
- Quy trình: direct/indirect competitors → competitor product experience → pricing strategy comparison

**Phân tích CẦU (Demand side analysis):**
- **Google Trends** (free): đánh giá xu hướng tìm kiếm từ khóa theo thời gian/khu vực
- **SimilarWeb** (có bản free giới hạn): kiểm tra lưu lượng truy cập & nguồn traffic của đối thủ
- **Social Listening**: đo lường mức độ quan tâm thực tế qua MXH/forum (group Facebook, TikTok...)

### Bước 4: Tính toán Dung lượng Thị trường — TAM - SAM - SOM
Mô hình phễu thu hẹp dần: **TAM > SAM > SOM**

| Tầng | Ý nghĩa | Cách tính gợi ý |
|---|---|---|
| **TAM** (Total Addressable Market) | Tổng thị trường khả dụng — toàn bộ cơ hội doanh thu tối đa nếu chiếm 100% thị trường, không đối thủ. Xác định tiềm năng dài hạn | Tổng số người có nhu cầu × giá trị trung bình họ có thể chi |
| **SAM** (Serviceable Available Market) | Thị trường có thể phục vụ — thu hẹp theo mô hình kinh doanh, phân khúc giá, khu vực địa lý | TAM thu hẹp theo phân khúc mục tiêu cụ thể (VD: SV các trường CNTT/QTKD tại HCMC) |
| **SOM** (Serviceable Obtainable Market) | Thị trường thực tế chiếm lĩnh — mục tiêu doanh thu 1-3 năm đầu, dựa trên năng lực vận hành & ngân sách tiếp thị | Phần SAM nhóm thực sự có thể tiếp cận với nguồn lực hiện có |

- Lưu ý: số liệu không cần chính xác tuyệt đối nhưng phải có **nguồn tham chiếu hợp lý** (Bộ GD&ĐT, GSO, báo cáo ngành EdTech...), tránh số liệu bịa đặt.
- Đây là phần cốt lõi để đáp ứng tiêu chí "Nghiên cứu thị trường (25 điểm)".

### Bước 5
*(Chưa có nội dung — buổi training kết thúc ở Bước 4, chuyển sang Phần II)*

---

## Phần II — Mô hình kinh doanh: Business Model Canvas (BMC)

**Định nghĩa:** Công cụ quản trị chiến lược do Alexander Osterwalder và Yves Pigneur phát triển (2010), trực quan hóa toàn bộ mô hình kinh doanh trên **một trang giấy**. Với startup, BMC là "kim chỉ nam" giúp đơn giản hóa lập kế hoạch, tập trung vào tính linh hoạt và kiểm chứng nhanh các giả thuyết thực tế.

### Cấu trúc 9 khối, chia theo 4 cụm

**(I) Khách hàng** *(mặt hướng ra thị trường)*
- **Phân khúc khách hàng** (Customer Segments): Chúng ta đang tạo giá trị cho ai? Ai là khách hàng quan trọng nhất?
- **Quan hệ khách hàng** (Customer Relationships): Thiết lập & duy trì quan hệ với từng nhóm khách hàng (VD: trợ giúp cá nhân, dịch vụ tự động, cộng đồng)
- **Các kênh** (Channels): Giải pháp giá trị được đưa đến khách hàng bằng cách nào? (truyền thông và phân phối)

**(II) Sản phẩm dịch vụ**
- **Giá trị/Chất lượng** (Value Proposition): Giải pháp (tuyên bố - cam kết) giá trị dành cho khách hàng. Với mỗi phân khúc, ta đưa tới sản phẩm/dịch vụ nào? Thỏa mãn nhu cầu nào?

**(III) Hạ tầng kinh doanh** *(mặt vận hành nội bộ)*
- **Đối tác chính** (Key Partnerships): Quan hệ đối tác (thuê ngoài, tổ chức, cá nhân, nhà cung cấp...) ngoài phạm vi công ty
- **Các hành động** (Key Activities): Hành động trọng yếu cần thực hiện
- **Nguồn lực chủ chốt** (Key Resources): Vật chất, trí tuệ (bản quyền, dữ liệu), nhân lực, tài chính

**(IV) Tài chính**
- **Cơ cấu chi phí** (Cost Structure): Chi phí trong toàn bộ mô hình, xác định hoạt động nào có chi phí chính, phương thức định giá
- **Dòng doanh thu** (Revenue Stream): Các dòng doanh thu có được từ việc mang giá trị sản phẩm/dịch vụ đến khách hàng

### Ghi chú vận dụng
- **Mạch tư duy khi thuyết trình:** Khách hàng là ai → Ta mang lại giá trị gì cho họ → Ta cần gì để làm điều đó → Ta kiếm tiền và tốn tiền ra sao
- **Thứ tự điền canvas gợi ý:**
  1. Customer Segments (dựa vào chân dung khách hàng — Bước 1)
  2. Value Propositions (dựa vào pain point — Bước 2, mỗi pain point nên có 1 value proposition tương ứng)
  3. Channels & Customer Relationship
  4. Revenue Streams (mô hình thu tiền: subscription, freemium, one-time, hoa hồng...)
  5. Key Activities / Resources / Partners
  6. Cost Structure (tổng hợp từ các khối trên)
- **Liên kết dữ liệu Phần I → Phần II:** Pain Point (Bước 2) → đổ vào ô *Value Propositions*; Customer Persona (Bước 1) → đổ vào ô *Customer Segments*
- **Lưu ý riêng cho EdTech:** phần **Revenue Streams** hay bị làm sơ sài nhất — vì "người dùng" và "người trả tiền" thường không phải cùng một đối tượng (end-user là học sinh/SV, buyer là phụ huynh/nhà trường). Cần làm rõ dòng tiền đến từ ai.
- BMC là công cụ trực tiếp trả lời tiêu chí **"Tính khả thi (15 điểm)"** trong đề bài — đặc biệt qua 2 ô Cost Structure và Revenue Stream, chứng minh mô hình có thể sống được về tài chính.

---


