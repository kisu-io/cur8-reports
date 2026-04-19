# CUR8 — Strategic Reports

Phân tích chiến lược cho dự án CUR8 rooftop multi-concept venue tại 49 Phạm Đăng Cảng.

## Mở local

```bash
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

## Cấu trúc

| File | Nội dung |
|------|----------|
| `index.html` | Master dashboard với executive summary, integrated outlook, methodology |
| `01_risk_analysis.html` | 8 rủi ro chính + benchmark cross-check (12 metrics) + stress test |
| `02_revenue_diversification.html` | Risk mitigation + 4-channel diversification roadmap (+36% Y2 rev) |
| `03_daypart_simulation.html` | 5 tầng × 5 daypart turn/cover simulation + cross-check finance model |
| `04_hr_rampup_strategy.html` | 5-phase hiring plan + HR cost reduction levers (212M cash preserved) |

## Push lên GitHub

Repo đã được initialize ở local. Để push lên GitHub:

```bash
cd /path/to/Cur-8/reports
git remote add origin https://github.com/<your-username>/cur8-reports.git
git branch -M main
git push -u origin main
```

Trước khi push: vào https://github.com/new tạo repo mới (private/public tuỳ ý), copy URL vào lệnh trên.

## Deploy lên GitHub Pages (optional)

Sau khi push:
1. Settings → Pages → Source: Deploy from branch
2. Branch: `main`, folder: `/ (root)`
3. Save → URL sẽ là `https://<username>.github.io/cur8-reports/`

## Tech Stack

- HTML5 + vanilla CSS (Helvetica)
- Chart.js 4.4 (CDN)
- Brand color: #8B0000 (wine red) · Background: #faf7f2 (cream)
- Responsive (breakpoint 900px)

---
Generated 19/04/2026 · CUR8 Strategic Analysis
