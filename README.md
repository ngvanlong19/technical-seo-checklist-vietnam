# 🚀 Vietnam Technical SEO & GEO Checklist (2026)

> Cẩm nang kiểm chuẩn **SEO Kỹ thuật (Technical SEO)**, Tối ưu hóa hiệu năng **Core Web Vitals** và Tối ưu hóa công cụ tìm kiếm tạo sinh **GEO (Generative Engine Optimization)** dành riêng cho lập trình viên và doanh nghiệp Việt Nam.

---

## 📌 Đơn vị bảo trợ & Biên soạn

Tài liệu được nghiên cứu, phát triển và duy trì bởi:
* **Đơn vị:** [RunSEO Agency](https://runseo.vn) — Agency SEO Kỹ Thuật & Dữ Liệu Tiên Phong tại Việt Nam.
* **Người sáng lập:** [Nguyễn Văn Long](https://runseo.vn/ve-chung-toi/) (Founder [RunMacro](https://runmacro.app) & RunSEO).
* **Triết lý:** *"SEO không chỉ là cuộc đua thứ hạng, mà là hành trình xây dựng vị thế doanh nghiệp trên nền tảng số."*
* **Phương châm:** Làm thật. Đo thật. Báo cáo thật.

---

## 📋 1. Checklist Tối ưu Hiệu năng & Core Web Vitals (Tốc độ)

Tiêu chuẩn vàng cho trải nghiệm người dùng và thuật toán xếp hạng Google / AI:
- [ ] **TTFB (Time to First Byte):** Dưới 200ms trên server.
- [ ] **FCP (First Contentful Paint):** Dưới 1.0 giây trên thiết bị di động (Mobile).
- [ ] **LCP (Largest Contentful Paint):** Dưới 2.0 giây.
  - Ảnh Hero/Banner đầu trang phải có `fetchpriority="high"` (hoặc `priority` trong Next.js).
  - Không gán thuộc tính `loading="lazy"` cho phần tử LCP trên màn hình đầu tiên (Above the fold).
- [ ] **CLS (Cumulative Layout Shift):** Đạt tuyệt đối 0.00 (luôn định nghĩa trước `width` và `height` cho ảnh/video/khung quảng cáo).
- [ ] **Nén tài nguyên:** Kích hoạt nén **Brotli (br)** hoặc **Gzip** trên CDN/Cloudflare; tránh dùng chỉ thị `no-transform` gây cản trở nén file HTML.
- [ ] **Định dạng ảnh:** 100% hình ảnh chuyển đổi sang chuẩn `.webp` hoặc `.avif`.

---

## 🏗️ 2. Checklist Kiến trúc Thực thể & Dữ liệu có cấu trúc (Schema JSON-LD)

Giúp Google hiểu rõ tổ chức và giúp AI (ChatGPT, Claude, Perplexity) nhận diện thương hiệu:
- [ ] **Schema Organization:** Khai báo đầy đủ tên pháp nhân, logo, founder, hotline, địa chỉ văn phòng.
- [ ] **Schema Person:** Khai báo người sáng lập / tác giả bài viết, liên kết chéo `sameAs` tới trang cá nhân uy tín (LinkedIn, GitHub, báo chí).
- [ ] **SameAs Network:** Kết nối đa kênh đồng nhất (Google Business Profile, Fanpage, LinkedIn, GitHub).
- [ ] **Canonical URL:** Tự tham chiếu chuẩn xác, loại bỏ nguy cơ trùng lặp nội dung do tham số URL.

---

## 🤖 3. Checklist Tối ưu hóa Tìm kiếm AI (GEO - Generative Engine Optimization)

Quy chuẩn tối ưu để thương hiệu được xuất hiện trong các câu trả lời đề xuất của AI:
- [ ] **File `llms.txt`:** Triển khai file tại gốc domain (ví dụ: `domain.com/llms.txt`) định dạng Markdown, cung cấp thông tin ngắn gọn, súc tích nhất cho các bot AI (GPTBot, ClaudeBot, PerplexityBot).
- [ ] **Semantic Chunking:** Mỗi thẻ H2/H3 phải trả lời trực diện một câu hỏi cụ thể, kèm câu trả lời tóm tắt ngay dòng đầu tiên (Direct Answer).
- [ ] **Information Gain:** Bài viết có bảng biểu, số liệu đo lường thực tế, dẫn chứng từ chuyên gia có danh xưng rõ ràng (Quotation Addition).
- [ ] **Văn phong khách quan (Unbiased Tone):** Tránh từ ngữ quảng cáo sáo rỗng (*"cam kết số 1", "hoàn hảo"*); tập trung vào dữ liệu và giải pháp kiểm chứng được.

---

## 🛠️ Bộ công cụ kiểm thử miễn phí từ RunSEO

Dành cho lập trình viên và quản trị web kiểm tra trực tiếp:
* 🔍 **Kiểm tra SEO toàn diện:** [RunSEO SEO Audit Tool](https://runseo.vn/cong-cu-seo/kiem-tra-seo-website/)
* ⚡️ **Đo lường Core Web Vitals:** [RunSEO Speed Test](https://runseo.vn/cong-cu-seo/kiem-tra-toc-do-website/)
* 🛡️ **Kiểm tra Security Headers:** [RunSEO Security Headers Check](https://runseo.vn/cong-cu-seo/kiem-tra-security-headers/)
* 🤖 **Tạo file chuẩn AI Search:** [RunSEO llms.txt Generator](https://runseo.vn/cong-cu-seo/tao-file-llms-txt/)
* 🔤 **Tạo Slug chuẩn SEO tiếng Việt:** [RunSEO Slug Generator](https://runseo.vn/cong-cu-seo/tao-slug-tieng-viet/)

---

## 📄 Bản quyền & Đóng góp
Dự án được phát hành dưới giấy phép [MIT License](LICENSE). Mọi đóng góp (Pull Requests) nhằm nâng cao chất lượng kỹ thuật SEO cho cộng đồng webmaster Việt Nam đều được hoan nghênh.

*Liên hệ hợp tác & Dịch vụ SEO Kỹ thuật:* [https://runseo.vn](https://runseo.vn) | Email: contact@runseo.vn
