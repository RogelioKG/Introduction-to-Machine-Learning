1. 比賽的選擇

    原本是想說找個比賽，能用上作業一裡有試成功的神經網路迴歸模型。\
    但後來想想，還是希望自己每個作業裡都有學到一點新東西。因此決定選擇其他主題。\
    自己對自然語言處理有點興趣，因而第一次挑的比賽就是 [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started/overview)，\
    一開始就有想到應該是用 BERT 之類的預訓練模型然後做 fine-tuning，\
    但我後來發現 keras-nlp 好像出現了某些版本問題，\
    導致我的 pip 載不到有 DistilBERT 的較新版 keras-nlp 及其相依函式庫。\
    因為時間有限，所以我只好改選另外一個比賽 [Digit Recognizer](https://www.kaggle.com/competitions/digit-recognizer)。

2. 資料集

    MNIST 手寫數字資料集

3. 實作

    後來才發現這比賽和課堂上的主題撞了🥲，所以決定找找看其他的實作方式。
    剛好 Code Notebook 第一個就很酷，它是直接手刻一個 Transformer 出來，
    雖然還沒有仔細研究，不過這是一個很好的 example code，\
    可以供我未來補完[李宏毅老師](https://youtube.com/@HungyiLeeNTU) transformer 的課程後再回來研究。
    最後還是有寫一兩個小函數，讓模型對圖片進行預測。

4. 感想

    這次沒有親手實作到，覺得有點可惜。\
    在自己的學習歷程中有領悟到：如果這些東西我一眼掃過去，無法心領神會，\
    那必然是有我尚未突破的知識點 (因為我以前會下意識怪我自己太笨)，這在我後來的學習歷程都有了印證。\
    關於機器學習這方面的知識，我還未有時間將其脈絡化地整理在 Notion 中。\
    脈絡化的整理對我來說幫助很多，讓我知其然亦知其所然，即便這有些費時。(這學期也是爆學了一堆模組，還有多到滿出來的筆記)\
    老師的缺空值填補的教學，對剛進入機器學習這個領域的我而言，幫助也很大。(很實用的方法論！)\
    個人的自學規劃應該會把機器學習放在二下的暑假，期望能紮實的學好這個酷酷的技術。
