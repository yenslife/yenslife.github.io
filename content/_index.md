+++
aliases = ["/about/"]
+++

# 我是誰

我是海狸大師（Chun-Yen Pan / yenslife），目前就讀國立成功大學資訊工程研究所，於 Intelligent System & Media Processing Lab（ISMP Lab）參與研究與產學合作計畫。

目前主要關注 **AI Systems、LLM / Agent Security、分散式系統與 Infrastructure**。我的實作經驗橫跨 LLM 應用、Linux、KVM、Apache Kafka、MongoDB、網路與高可用架構，也參與過電信、資安與醫療領域的實際系統開發。

我特別喜歡處理需求還不明確、需要跨 AI、軟體、Infrastructure 與網路一起解決的工程問題，也習慣使用 Codex、ChatGPT 等 AI 工具協助 implementation、debugging、技術研究、論文閱讀與文件撰寫，再自行完成系統架構設計、驗證與整合。

歡迎到我的[部落格](https://blog.yenslife.top)、[YouTube 頻道](https://www.youtube.com/@yen_s_life)、[GitHub](https://github.com/yenslife)或 [LinkedIn](https://www.linkedin.com/in/yenslife/)看看！

## 工作與研究經驗

**2025/02 - now** | **Research Assistant** - National Cheng Kung University, ISMP Lab

- 參與 AI、資安與大型分散式系統相關的產學合作研究與系統建置。
- 實務工作橫跨 LLM 應用、Linux Infrastructure、KVM、Apache Kafka、MongoDB、Networking 與 High Availability。
- 負責部分產學計畫的技術統籌、系統設計、實作、測試、部署與問題排查。

---

**2025/07 - 2025/08** | **RPA Coach Intern** - [EMILY.RPA](https://www.rpa.emily.tips/)

- 地點：新北市（遠距）
- 協助企業將重複性工作轉換為系統瀏覽器自動化流程，設計並實作端到端 RPA workflow。
- 協助處理 automation workflow 實作與問題排查。
- **Tech：** JavaScript · Robotic Process Automation (RPA)

---

**2024/07 - 2025/06** | **AI Engineering Intern** - [AI Next Mine 采鑛數據科技有限公司](https://ainextmine.com/)

- 地點：台灣台中市（遠距）
- 開發 LLM workflow 並整合 RAG 技術，應用於 AI 永續發展與 ESG 報告助手，協助企業進行資料取得與內容產生。
- 依據客戶需求維護與擴充 AI 應用，主要負責 Python 後端（FastAPI、Flask），並協助維護既有 Next.js 前端。
- 在 AWS 上使用 Docker Compose 部署系統，並根據模型資源需求選擇適當的 EC2 instance。
- 參與 AI+ 創新者選拔賽，開發 ESG 與 AI 相關應用。
- 開發高雄流行音樂中心 LLM-based LINE Bot，協助使用者取得展演與場館相關資訊；作品於 Go Digital 競賽 200 隊中獲得佳作。
- **Tech：** Python · FastAPI · Flask · AWS · Docker · LLM · RAG

## 精選專案

### 大型電信業分散式系統建置

**Role：Infrastructure / Systems Engineering**

參與大型電信業者的多站點分散式系統建置。從初期 Apache Kafka 技術 Survey 與效能實驗開始參與，後續接手 VM / Infrastructure 相關工作，實際投入系統建置、部署、維運與問題排查。

- 參與其中一組包含 **6 台實體 Host、30+ 台 KVM VM** 的環境建置，負責 VM provisioning、Linux / 網路設定、服務部署、自動化與故障排查。
- 處理 Linux、KVM/QEMU、Apache Kafka、MongoDB、Networking 與 High Availability 等系統整合工作。
- 針對 **120 Kafka partitions、40 consumer instances** 的資料處理架構進行效能分析，定位 consumer throughput bottleneck。
- 重新設計非同步資料處理流程，使 Kafka consumer 的處理速度能跟上實際 production workload。
- 分析 **7 個 VIP** 的 Keepalived / VRRP partial failover 問題，設計 coordinator-based group health architecture，使整組 VIP 能維持一致的 failover 行為。
- 參與系統 Change Request、部署驗證、監控設計與大量 VM / Infrastructure 維運工作。

**Tech：** Linux · KVM/QEMU · libvirt · Apache Kafka · MongoDB · Keepalived/VRRP · Bash · Networking

---

### LLM 高擬真自適應資安誘捕系統

**Role：Student Project Lead**

參與產學合作的 AI Cybersecurity R&D Project，研究如何結合 LLM、生成式 AI 與資安 Deception 技術，提升誘捕系統的擬真度、自適應能力與互動性。

- 擔任學生團隊 Project Lead，統籌 **3 人學生團隊**的技術設計、實作、測試與計畫審查項目。
- 參與 LLM-based response generation、擬真誘餌生成、操作模擬與資料隱私保護等模組設計。
- 將研究概念轉換為可實作的系統模組、技術規格與量化評估方法。
- 負責大量計畫文件、技術內容與審查資料的整理與整合。
- 目前也持續關注 LLM Security、Agent Security 與 AI Agent Red Teaming 等相關研究。

**Tech：** LLM · AI Agents · Cybersecurity · Python · Prompt / Workflow Design

---

### 腎臟照護 LLM LINE Bot

**Role：AI Application Developer / Technical Liaison**

與成大醫院護理長合作，將其博士研究中的腎臟疾病與洗腎病患衛教需求，實作為病患可以實際使用的 LINE 聊天機器人。

- 直接與 Domain Expert 對接需求，理解實際醫療使用情境與研究目的。
- 整理與處理護理端提供的腎臟疾病、洗腎與病患衛教相關資料。
- 根據相對固定且受控的問答流程，使用 Dify 建構 LLM workflow，並整合 LINE Bot。
- 負責資料處理、workflow 設計、系統實作與部署。
- 目前系統約有 **50 位註冊使用者**。

**Tech：** Dify · LLM · LINE Messaging API · Prompt / Workflow Design

## 學歷

**2025/09 - 2027/08（預計）** | **國立成功大學 資訊工程學系 碩士班**

- Intelligent System & Media Processing Lab（ISMP Lab）
- 指導教授：郭耀煌 特聘教授
- 研究興趣：LLM Security、Agent Security、AI Systems

**2021/09 - 2025/06** | **國立成功大學 資訊工程學系 學士班**

- GPA：3.92 / 4.3
- 專題：可生成摘要與輔助教學的 Chatbot 及高效學習平台（[介紹影片](https://youtu.be/cuVu4kC0dFI?si=grFKZEH0pUOJw2rX)）
- 研究與實作內容包含 RAG、影片摘要、LLM 教學 Chatbot 與 LoRA fine-tuning。

## 社團與學生自治

**2024/09 - 2025/06** | **GDG on Campus NCKU（成大谷歌軟體開發社）**

- 擔任核心成員、專案組長，帶領成大聊天機器人專案開發。
- 主持社課：[用 GPT & Gemini 打造專屬 Chatbot](https://gdg.community.dev/events/details/google-gdg-on-campus-national-cheng-kung-university-tainan-city-taiwan-presents-yong-gpt-amp-gemini-da-zao-zhuan-shu-chatbot/)

**2024/09 - 2025/06** | **成大宿舍自治委員會** - 主任委員

**2023/09 - 2024/06** | **成大宿舍自治委員會** - 副主任委員

**2023/09 - 2025/04** | **光復第二宿舍樓長**

## 著作與獎項

- 《[零基礎玩轉 LLM 應用全攻略：Python × No-Code 實作 AI 開發超簡單](https://llm-book.yenslife.top)》，博碩文化，2026 年 2 月出版。
- 第 16 屆（2024）iThome 鐵人賽「生成式 AI 組」冠軍：《[Python 新手的 AI 之旅：從零開始打造屬於你的 AI / LLM 應用](https://ithelp.ithome.com.tw/users/20168885/ironman/7699)》。
