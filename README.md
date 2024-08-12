# oop-totoro
Object-oriented results published  
專題內容:  
  是一款解謎取向的闖關遊戲，透過橫向卷軸的方式，操控角色，並透過身上的道具，與場景互動，最終幫助我們的主角Totoro突破重重難關，回到草壁五月(小月)身邊。  
1.人物移動時，面朝不同邊，讀取特定的圖片，停止不動時，也讀取特定圖片，這樣角色便有了等待，面朝左，面朝右，走路，等狀態。  
2.人物跳躍時，有考慮重力加速度的概念，跳起來時，會隨著時間感受到物力的影響，同理下墜時也是。  
3.地圖移動時，由於橫向捲著的緣故，當角色畫面右側一定距離時(上下左同理)，背景也會跟著移動，此處的程式技巧在於，由於當背景跟著移動時，原本在圖中的畫面也要跟著移動，所以為了保持物體位置相對於主角是沒有改變的，因此畫出來的物件須更改相對位置(相對座標 = 絕對座標-縮放倍率*背景座標)  
4.特殊物件-雨傘: 能夠在圖中，並藉由主角觸碰而將該道具拿在手上，能夠將跳躍功能變更成飛越，並且下墜時，會有緩速下墜的效果。  
5. 特殊物件-順移魔法: 能夠射出一條拋物線，並在線條消失前點擊滑鼠右鍵然後移動到著陸點。  
6. 特殊物件-冰塊地板: 不同的摩擦係數，當角色在該地板停止移動時，還會滑行一段距離。  
7. 特殊物件-沙地板: 不同的摩擦係數，當角色在該地板移動時，速度明顯下降。  
8.特殊物件-消失箱子: 當該地板觸碰過角色一瞬間，開始倒數3秒，3秒後地板會消失，並取消碰撞，角色便無法站在上面，且當消失時間經過3秒後，地板會重新顯示，並恢復碰撞。  
9.特殊物件-小鳥: 隨機於地圖任何地方產生，並隨機丟下小碎石，當主角被小碎石觸碰時，快速降低能量條。  
10. 特殊物件-移動地板: 地板會依照設定路線來回上下or左右移動。  
11. 特殊物件-星星: 當主角碰到星星時，會將星星吃掉，並能夠提升1點能量值，且在方向鍵持續下壓時(僅吃到當次有效)，巨幅增加移動速度，直到方向鍵彈起，則取消效果。  
12. 特殊物件-能量條: 主角能夠行動的能量值!!! 當歸零時則遊戲結束。  
13. 特殊物件-移動小碎石: 固定於場景中依照指定路線移動，觸碰到角色時，會快速降低能量值。  
13.Rank排名。  
14.存活時間計時(單位:分,秒,毫秒)。  
15.背景故事與操作手冊。  
