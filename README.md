# 《Solana 完全解析》 - Solana 中文書計畫

## 為何 Solana 需要中文化？

「投資比特幣最好的時間點只有兩個：十年前，或者現在」

這個幣圈笑話大家都聽過，同樣的道理也適用於 Solana 中文書計畫：現在正是 Solana 中文書出現的完美時機點！不過如果一定要給出一個積極理由，那我想會是 Solana 基金會在亞洲（特別是中文母語人士為主的市場）的積極佈局，而其中一項重要的指標便是 2024 年的 Solana Breakpoint 年會即將移師至新加坡舉行。

然而比起商業上的佈局，Solana 在中文母語開發者之間的傳播卻是相對來說薄弱的：如果比較每年「發現」以太坊與「發現」Solana 的開發者人數，會發現仍存在一定差距。在我兩年前（2021）第一次接觸 Solana 時，並沒有太多中文原創內容，但直到兩年後的現在，中文母語開發者仍只能透過碎片化的內容學習 Solana 開發。這其實是一件很可惜的事情，更何況是自帶性能光環的 Solana，其本身就是一個對區塊鏈技術的優化教科書。

因此，對 Solana 進行中文化，讓更多以中文為母語的「開發者」認識 Solana 便成了一個必然的結果。那麼下一個問題是：要進行怎樣的中文化呢？

## 為何需要一本「書」？

Solana 中文內容並不是沒有，然而目前我們所能觸及的中文內容有下列幾點問題：多為翻譯文章，翻譯品質參差不齊；內容也缺乏結構，沒有深入潛出的系統論述。**事實上，比起「中文化」，Solana 的內容更需要的是「結構化」。** 因此我們認為：讓 Solana 體系的知識進行中文的「結構化 / 模組化 / 文字化」，成為可進一步被利用轉換的「文本」，才能一舉解決當前中文內容的問題。

在所有的內容形式中，書能發揮的槓桿最大。一本 Solana 的中文書，可以達成三個目標：**結構化 / 更容易被發現 / 更容易被利用。**一本好書的引導，基本上會奠定學習者對整個體系的認知框架與觀點。我的第一本書就是《精通比特幣》中文版（Mastering Bitcoin），很難想像若沒有這本書的幫助，我會多花多少時間建構區塊鏈知識體系。

## 這本「書」應該談些什麼？

作為一本 Solana 中文書，技術絕對是一個必須被詳加闡述的主題，而談 Solana 技術時其實也不是在談 Solana 本身，而是整個區塊鏈技術，因為 Solana 的設計思想本身就是對原有區塊鏈技術的包袱的全面改進與優化。

而當我們提到區塊鏈技術，我們指的是下列模組的集合（包含但不侷限）：

- **共識機制（Consensus）**
- **抗女巫機制（Sybil-resistance）**
- **帳戶模型（Account Model）**
- **執行環境（Run-time）**
- **交易驗證（Transaction Validation）**
- **資料傳輸（Data Propagation）**
- **狀態管理（State Management）**

經過 10 多年發展，區塊鏈技術早已不再是密碼極客與駭客的玩具，而是數學 / 物理學 / 經濟學 / 軟體工程學 / 社會學 / 政治學 / 商業的多方交融產物。因此，若單純談論技術，而忽略了其在商業價值的貢獻，這樣的內容結構將會是不完整的。因此除了技術，我們也會著重於討論「OPOS - Only Possible on Solana」，那些唯有在 Solana 才能實現的商業應用案例。

事實上，**探討技術邊界的其中一個目的就在於探索商業價值邊界。** 商業價值其實很大一部分是技術邊界決定的，舉例來說，網路串流影音只有在頻寬夠大時才有實現的可能；而網路頻寬的提升也不是一朝一夕的事，而是技術 / 資金 / 人才在一定時間內的大規模投入的結果，而這些投入也必須有賴於商業價值的證明。

這種「商業價值邊界 / 技術邊界」互相擴展的模式，也是本書想要推動的目標之一：探討 Solana 技術優勢所創造出的邊界 > 進一步擴展商業價值邊界 > 證明商業價值 > 拉動更多的資源（技術 / 資金 / 人才）投入。

## 為何是我們（Gen3）

雖然在 Solana 的投入不算到非常早（2021 年中），但在過去兩年中算是留下了一些痕跡：

- 寫了 [Anchor 教學](https://github.com/ironaddicteddog/anchor-escrow) ，傳播度還算不錯
- 曾經籌辦線下技術聚會長達一年
- Solana Foundation 的長期合作夥伴，並協助籌劃 Taipei Hacker House
- 我們的使命：「探索邊界」

## 預期架構

- 發展歷史
- 性能論述
    - PoH
    - Tower BFT
    - Turbine
    - Gulf Stream
    - Sealevel
    - Pipelining
    - Cloudbreak
    - Archivers
- 商業價值（OPOS）
    - DeFi
    - Open Loyalty
    - 鏈上奢侈品
    - RWA
    - Gaming
    - 隱私
- 基本概念（參考 Solana Cookbook）
- 進階概念 / 原生開發（參考 PaulX 文章）
- Anchor 開發（參考 Anchor Cookbook / SolMeet Book）
- 實戰（參考 SolMeet Book）

## 貢獻方式

- 寫作
- 搜集素材
- 製圖
- 線上 AMA / 線下聚會
- 審稿 / Peer Reviewer
- 內容分發合作（Content Distribution）

## 參考資料

- https://paulx.dev/blog/2021/01/14/programming-on-solana-an-introduction/
- https://solanacookbook.com/
- https://book.anchor-lang.com/
- https://www.theblockbeats.info/news/36742
- https://www.canva.com/design/DAFp5tDXsMU/HkP1zmBff4La76ghY7A4qQ/edit?utm_content=DAFp5tDXsMU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
- https://solmeet.gen3.network/
- https://github.com/ironaddicteddog/anchor-escrow
