<div align="center">

# 📉 Stock Trade Calculator 🇮🇳

### Position sizing · cost-basis averaging · risk-reward · Indian brokerage & charges

[![View Live Demo](https://img.shields.io/badge/▶_Try_It_Live-1f6f4f?style=for-the-badge&logoColor=white)](https://jithinjolly2000-maker.github.io/stock-trade-calculator/)

![Built with](https://img.shields.io/badge/Built_with-Vanilla_JS-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![No dependencies](https://img.shields.io/badge/Dependencies-none-0a7a52?style=flat-square)
![Privacy](https://img.shields.io/badge/Privacy-100%25_in--browser-17854a?style=flat-square)
![Market](https://img.shields.io/badge/Market-NSE_/_BSE_India-1f6f4f?style=flat-square)

</div>

---

Four calculators every equity trader actually uses, in one page.

## ✨ The four tabs

| Tab | What it does |
|-----|--------------|
| 🎯 **Position Sizing** | How many shares to buy so a stop-out costs only your chosen risk % — `qty = (capital × risk%) ÷ (entry − stop)` |
| ⚖️ **Average / Cost-basis** | Average price across multiple buys; plus *"how many shares at ₹X to pull my average to ₹Y"* |
| 📐 **Risk-Reward** | Risk, reward, R:R ratio and the **break-even win-rate** you'd need; long or short |
| 🧾 **Brokerage & Charges** | Full Indian charge breakdown — brokerage, STT, exchange txn, SEBI, stamp duty, GST — with gross vs **net P&L** and break-even sell price |

## ✅ Verified maths

Checked in a test harness against worked examples:

- Sizing: ₹5L capital, 1% risk, ₹500 entry / ₹485 stop → **333 shares**
- Averaging: 100@₹500 + 50@₹470 → **₹490**; to reach ₹480 buying at ₹450 → **50 shares**
- R:R: ₹500/₹485/₹545 → **1:3**, break-even win-rate **25%**
- Delivery charges on 100 @ ₹500→₹520 → total **₹113.20**, net P&L **₹1,886.80**

*(An early build had a sign error in the average-down formula — caught by the test harness and fixed before release.)*

## ⚠️ Rates & scope

Charge rates follow standard Indian discount-broker structures (2026): STT delivery 0.1% buy+sell /
intraday 0.025% sell, exchange txn ~0.00297% (NSE), SEBI 0.0001%, stamp duty 0.015% delivery /
0.003% intraday (buy side), GST 18% on (brokerage + txn + SEBI). **Your broker's exact plan may differ.**
No live prices — you enter them. For planning, not investment advice.

## 🧰 Tech

- **Vanilla HTML / CSS / JavaScript** — no frameworks, no dependencies, one `index.html`
- Hosted free on **GitHub Pages**; nothing is uploaded

## ▶️ Run locally

```bash
start index.html      # Windows — no build step
```

<div align="center">

---

**Built by Jithin J** · [GitHub](https://github.com/jithinjolly2000-maker) · [LinkedIn](https://www.linkedin.com/in/jithin2k)

</div>
