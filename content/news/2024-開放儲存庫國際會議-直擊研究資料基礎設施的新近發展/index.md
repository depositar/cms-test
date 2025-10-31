---
title: 2024 開放儲存庫國際會議 直擊研究資料基礎設施的新近發展
date: 2024-12-03T17:12:00
summary: 文／李承錱（中央研究院資訊科學研究所，研究資料寄存所技術經理）
tags: []
languages:
  - 中文
  - English
thumbnail: feature.jpeg
---
文／李承錱（中央研究院資訊科學研究所，研究資料寄存所技術經理）

本文亦刊登於 [2024-11-14
科技報導](https://www.scimonth.com.tw/archives/11184)

開放儲存庫國際會議（International Conference on Open Repositories，簡稱
OR 會議）是開放儲存庫（open repositories）領域的年度研討會，自 2006
年起已舉辦 19 屆。今（2024）年於 6 月 3～6
日在瑞典的第二大城哥德堡（Gothenburg）舉行。在為期四天、近 50
場次的會議中，共有超過 400
位來自圖書館學、人文社會科學、資訊科學、法律等相關領域的研究人員，交流應用開放原始碼儲存庫套件於研究資料典藏的實務經驗，探討包括學術機構研究資料的管理、開放、再利用、評估、使用權等議題。

今年的大會主題為「推動全球進展」（Empowering Global
Progress），著重於探討如何借助開放儲存庫增進研究透明度、提升少數族群地位，以及實踐環境永續。中研院研究資料寄存所（depositar）團隊過去曾兩次（2015、2023
年）實體參與 OR 會議，不僅在疫情期間多次參加線上會議，今年也躬逢其盛。

## 歷久彌新的開放儲存庫

事實上，OR
會議所指稱的「開放儲存庫」，早年是指以學術著作（學位論文、期刊論文、書籍等）為收錄對象的機構典藏庫（institutional
repository）與主題典藏庫（subject repository）為主。儲存庫服務提供業者
Cottage Labs
便在他的[分享](https://doi.org/10.5281/zenodo.12579359)中，回顧過去
30 年機構與主題典藏庫在開放近用（open access,
OA）運動中所扮演的關鍵角色：由 Fedora、EPrints、DSpace、Samvera、Invenio
等開放原始碼儲存庫套件搭建的線上開放儲存庫，所實踐的綠色
OA（Green OA）[〔註 1〕](#%e8%a8%bb-1)，再加上 OAI-PMH、OAI-ORE、SWORD
等資料交換格式[〔註 2〕](#%e8%a8%bb-2)的概念相繼問世，促使當前研究資訊系統（current
research information system, CRIS）與儲存庫的整合（CRIS/repository
integration），使得知識散播更快且廣。

在大會慣例的[儲存庫競技（Repository
Rodeo）](https://doi.org/10.5281/zenodo.12527422)活動中，來自上述各儲存庫套件的開發與營運團隊，更新儲存庫的最新動態，包括持續識別碼（persistent
identifier,
PID）整合、更細緻的資料權限管理與審核機制、與外部系統的資料交換，以及根據國際圖像互通架構技術（International
Image Interoperability Framework,
IIIF）開發的圖像瀏覽工具等。持續改善的功能與活躍的使用者社群，令開放儲存庫與時俱進。

## 學術研究的基礎設施

如今的開放儲存庫已不再侷限於機構與主題典藏。資料儲存庫（data
repository）為一種開放儲存庫，因新近資料科學熱潮而蓬勃發展；此外，開放儲存庫與研究流程密切相關，更是支持研究的基礎設施。因此如何確保儲存庫得以長期且穩定地運作，是所有儲存庫經營團隊都必須面對的課題，本次也有兩個議程與此直接相關。

在開放與持續的基礎設施（Open and Sustainable
Infrastructure）議程裡，Invest in Open
Infrastructure（IOI）計畫便建立儲存庫目錄網站 [Infra
Finder](https://infrafinder.investinopen.org/)，分析比較
57
個開放儲存庫服務在技術、社群、政策、治理等面向的異同，更據此製作 [2024
開放基礎設施現況報告](https://investinopen.org/state-of-open-infrastructure-2024/sooi-foreword-2024/)（2024
State of Open Infrastructure
Report），提供欲導入儲存庫服務的研究機構或團隊參考。

而在資料儲存庫與經驗傳承（Data Repositories and Lessons
Learned）議程中，[瑞典皇家理工學院](https://doi.org/10.5281/zenodo.12579325)（Kungliga
Tekniska högskolan,
KTH）分享他們在規劃校際研究資料儲存服務時，透過訪談了解校內研究人員在資料管理的痛點與需求，諸如存取方式、權限控管、運算分析、隱私風險、長期保存等細節；同時歸納導入服務期間面臨的資源分配、技術支援、教育訓練、快速應對研究需求等諸多挑戰，並強調重視協作的研究資料治理（data
governance）。

## 藉資料數位化促進學術研究流程自動化

在開放儲存庫將各類與研究相關的資料數位化後，藉由儲存庫間的資料交換，也開啟了學術研究流程自動化的可能性。在本次
OR 會議，德國漢堡大學（University of
Hamburg）[展示](https://doi.org/10.5281/zenodo.12528141)了電子化的實驗室筆記本軟體（Electronic
Laboratory Notebook, ELN），例如 elabFTW、Chemotion
等軟體所記錄的實驗資料，如何透過單一登入（Single Sign-On,
SSO）與應用程式介面（application programming interface,
API）自動匯入資料儲存庫中。

瑞典的查爾摩斯理工大學（Chalmers University of
Technology）也[使用開源套件
DSW](https://doi.org/10.5281/zenodo.11634261)（Data
Stewardship Wizard）內建的機器可操作資料管理方案（machine-actionable
data management plan,
maDMP）功能，將資料管理方案輸出為機器可讀的形式，並與校內 CRIS、資料儲存系統，及瑞典的國家資料儲存庫（Swedish
National Data
Service）串接，讓研究人員僅需輸入一次研究計畫資訊，便能為眾多系統所運用，達成研究計畫管理的自動化。

此外，更有如 [openCost](https://doi.org/10.5281/zenodo.12542602) 專案，正在建立一個完整記錄科學出版成本的[開放標準](https://www.opencost.de/)，包括後設資料規範與
OAI-PMH
介面，將開放儲存庫收錄的學術出版品，與記錄該文章處理費用的 [OpenAPC
資料庫](https://openapc.net/)連結，以期促進科研專案的成本透明化。

## 因應 AI 時代的應用與挑戰攻防

隨著大型語言模型（large language model,
LLM）的流行，人工智慧（artificial intelligence,
AI）相關應用已深刻影響社會，學術研究也不例外。資料儲存庫作為學術數位基礎設施，除資料保存、管理、分享等傳統角色外，近年來也持續探索結合資料探索、分析與運算資源等延伸應用。

例如由美國哈佛大學（Harvard University）開發的 Dataverse
儲存庫套件，便於近期推出基於 ChatGPT
的後設資料填寫輔助工具 [TurboCurator](https://turbocurator.icpsr.umich.edu/tc/adminabout)，以及可使用自然語言詢問表格內容的資料探索工具 [Ask
the
Data](https://github.com/IQSS/askdataverse/tree/main/askthedata)。瑞典
SciLifeLab
也[展示](https://doi.org/10.5281/zenodo.12542615)專為儲存與共享機器學習模型及資料科學程式的儲存庫服務 [SciLifeLab
Serve](https://serve.scilifelab.se/)，並可即時於
Kubernetes 運算叢集中部署與執行模型。而維也納工業大學（Vienna University
of Technology, TU
Wien）的研究資料平臺，也[著手](https://doi.org/10.5281/zenodo.12542572)開發 [vre-repository-connector](https://gitlab.tuwien.ac.at/fairdata/vre-repository-connector) 專案，令使用者得以於
JupyterLab 環境快速載入資料集並進行分析，並將結果回存資料集。

然而，由於 LLM 對訓練語料的需求日增，所引發的 AI 採集（AI
harvests）嚴重衝擊資料儲存庫的系統資源。例如 Archipelago Commons
儲存庫便曾於六小時內承受數以百萬計的採集機器人連線。面對此類相當於阻斷服務（denial-of-service
attack,
DoS）攻擊的不當利用，該儲存庫的營運團隊也在其[報告](https://doi.org/10.5281/zenodo.12579304)中提出具體建議：從
robots.txt 宣告與使用者代理（user agent）判斷等基本技法，到安裝各式 bot
blocker
套件，與設計蜜罐（honeypot）判斷機器人行為，再將它排除等進階手段。

## 來自東亞國家的發表

本屆 OR
會議於北歐舉辦，故與會者多數來自歐洲。但仍有兩個來自日本國立情報學研究所（NII）的團隊，分別介紹他們建置的 [NII
研究資料雲](https://doi.org/10.5281/zenodo.12579617)（NII
Research Data Cloud），與補足學術資訊搜尋平臺 CiNii
Research 紀錄中缺失的 DOI
識別碼等[經驗](https://doi.org/10.5281/zenodo.12579613)。

來自臺灣中研院的研究團隊也於本年度會議分享經營開放儲存庫（研究資料寄存所，data.depositar.io）的近況。在開發者議程軌，筆者介紹研究資料寄存所近期新增的 [Binder
服務建置心得](https://doi.org/10.5281/zenodo.12542595)（完整內容），該服務提供使用者於瀏覽器建立與執行資料分析環境，便於運算、重現與展示藉由程式完成之研究成果。在另一個經驗分享的議程中，帶領研究資料寄存所計畫的莊庭瑞副研究員回顧團隊過去五年在技術開發、社群拓展，與政策推廣的[成果與反思](https://doi.org/10.5281/zenodo.12579625)。

## 展望：資料儲存庫成為開放儲存庫的發展熱點

目前國內科研機構在開放儲存庫的使用上，仍以機構與主題典藏庫為大宗。然而，從筆者過去於OR會議的實際觀察，發現許多國家的科研機構已積極投入資源，建置並維運通用的資料儲存庫（generalist
repository），並以 FAIR
資料原則（可被找到、可被取用、可相互操作、可再次使用）為指引，因應學術研究趨勢與資料管理需求持續改進功能。本團隊身為資料儲存庫的經營者，也期待國內研究資料的管理與流通，能乘著
AI 時代帶來的巨量資料浪潮，獲得更多的關注與討論。

※ 特別感謝一同參與本次會議的中央研究院資訊科學研究所莊庭瑞副研究員，提供部分講題的聽講摘要。

## 註解

### 註 1

開放近用根據付費方式與開放時間，可以分為多種類型，主要有金色 OA
與綠色 OA 兩種。所謂金色
OA，是在著作發表後立即於期刊網站免費提供取用，並由作者支付所需的文章處理費用（article
processing charge, APC）。而綠色
OA，則是由作者自行將著作的預刊本（preprint）典藏於他所屬或接受資助的機構或主題典藏庫，並免費提供取用。

### 註 2

OAI-PMH 與 OAI-ORE 均為開放式檔案協會（Open Archives Initiative,
OAI）所制定的檔案交換協定，PMH（Protocol for Metadata
Harvesting）針對後設資料的擷取；ORE（Object Reuse and
Exchange）更拓展至網路資源的描述與交換。而 SWORD（Simple Web-service
Offering Repository Deposit）標準則提供跨儲存庫的共通傳輸規格。

## 延伸閱讀

\* Jones, R. D. (2024 June 28). Looking up from the weeds: seeing
  what's next for OA by learning from the past. Open Repositories
  2024 (OR2024), Gothenburg, Sweden.
  Zenodo. [https://doi.org/10.5281/zenodo.12579359](https://doi.org/10.5281/zenodo.12579359)
\* Greer Klein, H., et al. (2024 June 25). The Repository Rodeo. Open
  Repositories 2024 (OR2024), Gothenburg, Sweden.
  Zenodo. [https://doi.org/10.5281/zenodo.12527422](https://doi.org/10.5281/zenodo.12527422)
\* Steinhart, G., et al.  (2024). 2024 State of Open Infrastructure:
  Trends in characteristics, funding, governance, adoption, and
  policy. Invest in Open
  Infrastructure. [https://doi.org/10.5281/zenodo.10934089](https://doi.org/10.5281/zenodo.10934089)

> The _depositar_ team attended the _19th International Conference on Open Repositories_ (OR2024) in Göteborg, Sweden, on June 3--6, 2024. [Cheng-Jen Lee wrote a detailed report in Traditional Chinese](https://rdm.depositar.io/zh_TW/news/20241114-OR2024). Below is a report from Tyng-Ruey Chuang in English.

The [19th International Conference on Open Repositories (OR2024)](https://or2024.openrepositories.org/) was held in Göteborg, Sweden, on June 3--6, 2024. Eleven workshops took place on June 3. The main conference was held from June 4th to June 6th and it included keynotes, presentations, panels, DevTrack sessions, 24x7 (7-minute lightning talks with each comprising no more than 24 slides) as well as a repository showdown and a poster session. The conference, hosted by the Chamlers University of Technology, was very well organized. The conference venue was the Clarion Hotel Post in central Göteborg. In total, 425 people from 45 countries attended the conference.

The OR2024 full program is available in [ConfTool](https://www.conftool.net/or2024/sessions.php). Slides from the contributors can be found in the [Open Repositories Community in Zenodo](https://zenodo.org/communities/openrepos/records?q=&f=subject%3AOR2024). In the following, we highlight some of the sessions we attended. Due to limited space, this report can only be considered selective and subjective. 

In the [Repositories Implementations](https://www.conftool.net/or2024/index.php?page=browseSessions&form_session=439&presentations=show) session, researchers from Stanford University, Harvard University, and a team in the Netherlands (Leiden University, DANS, CNR-ISTI/OpenAIRE, and Vrije Universiteit Amsterdam) shared their experience in the planning and migration of existing digital repositories to modern data infrastructures in order to meet new requirements and/or to accommodate unexpected changes. All three presentations offered valuable advice.  In the [Repository Rodeo](https://www.conftool.net/or2024/index.php?page=browseSessions&form_session=448&presentations=show) panel, representatives from several repository software and services (including Dataverse, DSpace, EPrints, Fedora, InvenioRDM, Islandora, and Samvera) all engaged with the audience with the directions of their respective technical and community developments. 

Cheng-Jen Lee, the tech lead of the [_depositar_](https://data.depositar.io/about), the data repository we have been developing in Academia Sinica, gave a presentation on [_Bringing Computation and Reproducibility to a Data Repository Using Binder_](https://pid.depositar.io/ark:37281/k5h2q5h19) at the [Developer Track Session 2](https://www.conftool.net/or2024/index.php?page=browseSessions&form_session=519&presentations=show). In the presentation, he detailed how to extend [BinderHub](https://binderhub.readthedocs.io/) (a Kubernetes-based package powering the Binder service) to CKAN (software for managing and publishing datasets, and from which the _depositar_ is derived) so users can easily create and share executable computing environments from datasets in the repository.  In the [Data Repositories and Lessons Learned](https://www.conftool.net/or2024/index.php?page=browseSessions&form_session=529&presentations=show) session, _depositar_  project lead Tyng-Ruey Chuang gave a presentation on [_Building An Open Repository for FAIR Data: Experience Sharing on Technologies, Communities, and Policies_](https://pid.depositar.io/ark:37281/k5n4c2v0n).  He talked about the _depositar_ team's experience in community outreach and policy dialogue, in addition to the technical development of the open source data repository itself. The other presentations in the session were from Princeton University, KTH Royal Institute of Technology, and a consortium of research libraries in Canada. We feel the presenters all stress the importance of careful planning and long-term commitment of research institutions for the repositories they operate.

In the [24x7: Technical Solutions](https://www.conftool.net/or2024/index.php?page=browseSessions&form_session=523&presentations=show) session, we would like to highlight two enjoyable presentations from the Czech Republic.  Hana Vyčítalová, Petra Černohlávková, and David Gerner from the National Library of Technology shared their experience in moving from Invenio 1 to DSpace 7. [Their presentation is stunning](https://doi.org/10.5281/zenodo.12548342).  Martin Lhotak, Filip Kersch, and Petr Zabicka (Library of the Czech Academy of Sciences and Moravian Library in Brno) presented [Orbis Pictus](https://old.starfos.tacr.cz/en/project/DH23P03OVV033): a project to open up the graphic content of digital libraries to the public, in particular about developing a tool to identify persons by their images in digitized books. The [Trends and the Future of Open](https://www.conftool.net/or2024/index.php?page=browseSessions&form_session=522&presentations=show) session is an overview of the research data landscape in Europe (but the observations are applicable elsewhere in the world).  We recommend the readers to look into [the presentation from Richard David Jones](https://doi.org/10.5281/zenodo.12579359) (Cottage Labs) where he reflected on his involvement in Open Access for the last 25 years. He provided insightful perspective on the current and future roles of repositories in improving global publishing equity. 

We wish to note we finally met John Kunze after corresponding with him for several years. He and Donny Winston organized a workshop on [Getting Running with ARK Persistent Identifiers](https://www.conftool.net/or2024/index.php?page=browseSessions&form_session=496&presentations=show). Using Archival Resource Key (ARK), the _depositar_ team has developed [a CKAN extension](https://github.com/depositar/ckanext-ark) for [assigning persistent identifiers (PIDs) to datasets](https://docs.depositar.io/en/stable/user-guide/ark-identifier.html). It is joyful to be able to meet, in person, the people who have helped us so much.

[The 20th International Conference on Open Repositories (OR2025)](https://or2025.openrepositories.org/) will take place on June 15--18, 2025, in Chicago, Illinois, USA. The theme for the OR2025 conference is _Twenty Years of Progress, a Future of Possibilities_. The [Call for Proposals](https://or2025.openrepositories.org/program/call-for-proposals/) is now open with a submission deadline of December 18, 2024. 

Our travels to attend the conference have been supported by the Institute of Information Science, Academia Sinica, and by the National Science and Technology Council of Taiwan.
