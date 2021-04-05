# 自動下注(判圖版)  
程式最後修改時間：2019/12/07 
效果展示：https://youtu.be/VtQ0DlqO74c?t=5681  
<br />  
使用Java達到類似於按鍵精靈14的"區域找圖"功能  
再利用圖片進行一連串的下注動作  
<br />  
畫面中滑鼠的移動不是固定的座標，而是利用圖片尋找到下注的位置，再算出滑鼠該移動到的位置  
![image](https://github.com/WhiteEyeYan/-/blob/main/img/bet%E5%A4%A7.PNG)  
<br />  
img資料夾內為要搜尋的圖片  
<br />  
  
此版常有無法正確找到圖片、無法正確判讀下注的場次......等問題  
此外因為需控制滑鼠，無法在後台運行，必須使用VM  
<br />  
為了解決這些問題後來寫了selenium版 https://github.com/WhiteEyeYan/AutoBet2.0
