純html&css的動態漢堡選單練習

此次練習遇到Chrome的首次渲染問題(在畫面首次render時畫面會多跑一次"scale從 1 -> 0"的transition)  
目前找到解決方案為:在footer加入<script> </script>(中間要隔一格空格)  
資料來源https://stackoverflow.com/questions/14389566/stop-css-transition-from-firing-on-page-load
