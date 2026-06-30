# Notes - Tuần 7 Pilot Experiment

**Đề tài:** Proactive Bug Discovery via Agentic Exploration at Repository-Level  
**Nhóm:** 4  
**GV hướng dẫn:** L.T.Q.Chi  
**Topic:** RT-SWT-005

## Quyết định kỹ thuật

### Pilot Configuration

- **Random seed:** 42
- **Pilot sample size:** 10% (~52 tasks từ 517 samples)
- **Exploration Agent:** GPT-5-mini (temperature=0.8, max_turns=80)
- **Code Fixer:** Claude-Sonnet-4.5 (temperature=0.2)
- **Statistical test:** Wilcoxon signed-rank test (one-tailed, α=0.05)
- **Metric:** Fail-to-Pass Rate (F2P %)

### Dataset

- **Source:** TestExplora-Lite (Microsoft, 2026)
- **URL:** https://github.com/microsoft/TestExplora
- **Scale:** 517 samples from 482 Python repos

## Lỗi gặp phải

- [Chưa có - sẽ cập nhật trong quá trình chạy]

## Progress

- [ ] Tuần 7: Pilot experiment
- [ ] Tuần 8: Full experiment
- [ ] Tuần 9-10: Report & Presentation
