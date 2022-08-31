# Special Topics on Information Management
The special topic is **Billiards Guidance Applied To Hololens 2 (Mixed Reality)**.\
This special topic was a collaboration between me and our teammates from Sep 2021 to May 2022.\
I am responsible for designing an algorithm with the law of reflection and BFS to provide users guided path, and its detailed implementation are listed in this repository.\
The full version report is uploaded as [應用 Hololens 2 於撞球運動輔助系統.pdf](https://github.com/mattcy0514/special-topics-pool/blob/main/%E6%87%89%E7%94%A8%20Hololens%202%20%E6%96%BC%E6%92%9E%E7%90%83%E9%81%8B%E5%8B%95%E8%BC%94%E5%8A%A9%E7%B3%BB%E7%B5%B1.pdf).\
As for the presentation slide, it is uploaded as [pool.pdf](https://github.com/mattcy0514/special-topics-pool/blob/main/pool.pdf).

# Abstract
運動科技在近幾年逐漸有抬頭的趨勢，如今的運動競技不僅是選手之間的較量，更是考驗科技對於選手的輔佐程度，善用科技進行輔佐訓練、測量選手狀態等，不僅能夠提升訓練的品質，也能通過不同於以往的策略來進行教學，研發新的比賽策略等。因此我們組做的專題題目為「應用 AR 的撞球輔助系統」，就是為了解決新手對於撞球的進攻、防守策略不清楚，以及無法確定打擊位置的問題，這些問題都能借由輔助系 統進行計算，並將計算成果返回到 AR 的顯示畫面，指引選手找到最佳的打擊路徑。\
如今的混合實境趨勢明顯在快速增長中，未來的主流移動設備或許會從現在的手機替換成混合實境的裝置，因此透過這個專題，我們學習到關於混合實境的開發知識，以及延伸探索運動科技領域的其他應用。其中輔助系統的計算除了傳統的演算法之外，也可能需要用到人工智慧，去捕捉到更多的變數。為此，我們需要完成一款 UWP(Universal Windows Platform) 應用的開發，並且將它搭載到 Microsoft 的混合實境裝置 Hololens 2 上，選手在穿戴 Hololens 2 進行撞球運動的時候，前方的感測器會感應到臺面上的情況，並將圖像進行分析傳送到後臺進行演算，最後再將推薦的最佳打擊路線透過 AR 的方式讓選手直觀的看到並且模仿。
