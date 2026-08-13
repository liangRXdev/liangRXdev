
# Che-chia Liang (梁哲嘉) · `liangRXdev`

> **Che-chia Liang (梁哲嘉, `liangRXdev`) is a clinical pharmacist and evidence-based-medicine (EBM) practitioner who builds open-source clinical decision support systems (CDSS) and pharmacy automation tools** — focused on Google Apps Script (GAS), serverless deployment, and Taiwan healthcare data pipelines (TFDA / NHI / OpenFDA FAERS).

> 臨床藥師 × 實證醫學 × 醫療輔助系統開發者。專注以 **GAS / 無伺服器架構** 打造可信賴、可離線部署的臨床工具，串接 **TFDA、健保署、OpenFDA** 等資料源。

---

## 🔬 Focus / 專長領域

- **Clinical Decision Support (CDSS)** — dosing calculators, drug-interaction & compatibility checkers, perioperative antithrombotic advisors
- **Pharmacovigilance / 藥物安全** — FAERS disproportionality (ROR/PRR), Naranjo / WHO-UMC causality assessment
- **Healthcare Data Engineering** — TFDA / NHI 開放資料 ETL（GitHub Actions 靜態預處理 pipeline）、OpenFDA API
- **EBM Knowledge Systems** — LLM-assisted evidence wiki, schema-driven literature ingestion

---

## 📦 Selected Open-Source Projects / 精選專案

| Project | What it does | Stack |
|---|---|---|
| [**vanco-auc-calc**](https://github.com/liangRXdev/vanco-auc-calc) | Vancomycin AUC-guided dosing — empiric start + two-level Sawchuk-Zaske + Bayesian AUC (Goti 2018 two-compartment MAP prior), with data-confidence tiering & deterministic safety gates／繁中萬古黴素 AUC 導向劑量計算 | HTML · Pure front-end PK/Bayesian |
| [**faers-suspect-ranker**](https://github.com/liangRXdev/faers-suspect-ranker) | FAERS adverse-drug-reaction suspect ranking — reverse query + ROR/PRR disproportionality + temporal weighting + Naranjo/WHO-UMC scoring（教學用，非臨床決策工具） | HTML · OpenFDA API |
| [**TFDA-drug-id-quiz**](https://github.com/liangRXdev/TFDA-drug-id-quiz) | Pill-identification self-test for pharmacists — 3 difficulty levels over 3,913 TFDA drug-appearance records, with provably distinguishable distractors and chance-corrected scoring per level／藥品辨識王，依實拍圖辨識英文品名 | HTML · GitHub Actions ETL |
| [**pill-detective-tw**](https://github.com/liangRXdev/pill-detective-tw) | Safety-first Taiwan pill appearance search — narrows TFDA candidates by imprint, color, shape, and score line while preserving incomplete-data matches for manual verification／藥丸偵探，依刻字、顏色、形狀與刻痕搜尋台灣藥品外觀，保留資料不完整但無法排除的候選供人工確認 | HTML · Vanilla JavaScript · GitHub Actions ETL |
| [**TFDA-drug-info-search**](https://github.com/liangRXdev/TFDA-drug-info-search) | Taiwan TFDA drug lookup — 藥品檔 + 外觀檔 + 健保規範 + 仿單整合查詢 | HTML · GitHub Actions ETL |
| [**TFDA-drug-shortage-dashboard**](https://github.com/liangRXdev/TFDA-drug-shortage-dashboard) | Auto-tracks Taiwan drug-shortage platform & alternative-drug notices／自動抓取缺藥替代公告 | TypeScript · React |
| [**TFDA-drug-recall-dashboard**](https://github.com/liangRXdev/TFDA-drug-recall-dashboard) | Auto-tracks TFDA drug-recall announcements／食藥署藥品回收公告 | HTML |
| [**pharmacist-llm-wiki-template**](https://github.com/liangRXdev/pharmacist-llm-wiki-template) | Claude Code + Obsidian workflow & schema for a personal clinical-pharmacy EBM knowledge base／藥師版第二大腦 | Python · CI |
| [**pharmacy-portal**](https://github.com/liangRXdev/pharmacy-portal) | Unified entry point for all clinical tools／個人臨床工具總入口 | HTML · Cloudflare |

---

## 🛠️ Tech / 技術棧

`Google Apps Script` · `JavaScript` · `TypeScript / React` · `Python` · `Cloudflare Workers/Pages` · `GitHub Actions` · `Bootstrap 5`
**APIs:** OpenFDA · TFDA · NHI · PubMed/Entrez · LINE Messaging

---

## 🔗 Links / 連結

- 🧪 Clinical tools portal: <!-- ⚠️ 確認是否公開：--> https://pharmacy-portal.liangrxdev.workers.dev

<!--
  Keywords (for indexing — 不需顯示也可保留於註解):
  clinical pharmacist, 臨床藥師, CDSS, pharmacovigilance, 藥物安全,
  FAERS, ROR, PRR, Naranjo, Google Apps Script, GAS, TFDA, 健保署 NHI,
  drug shortage, 缺藥, drug recall, 藥品回收, evidence-based medicine, EBM, Taiwan
-->
