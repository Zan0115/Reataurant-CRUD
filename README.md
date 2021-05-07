# :hamburger: 我的餐廳清單 :hamburger:
### 一個可以讓你建立最愛餐廳清單的網站。

![image](https://raw.githubusercontent.com/Zan0115/Reataurant-CRUD/master/%E9%A6%96%E9%A0%81%E5%9C%96.PNG)
## :pencil2: 功能

- 使用者可以在首頁看到所有餐廳與它們的簡單資料：
  - 餐廳照片
  - 餐廳名稱
  - 餐廳分類
  - 餐廳評分
- 使用者可以再點進去看餐廳的詳細資訊：
  - 類別
  - 地址
  - 電話
  - 描述
  - 圖片
- 使用者可以透過搜尋餐廳名稱或種類來找到特定的餐廳
- 使用者可自行新增、修改、刪除餐廳

![image](https://raw.githubusercontent.com/Zan0115/Reataurant-CRUD/master/%E5%BB%BA%E7%AB%8B%E8%A1%A8%E5%96%AE%E5%9C%96.PNG)

## 使用步驟
1. 打開你的 terminal，Clone 此專案至本機電腦
```
git clone https://github.com/Zan0115/Reataurant-CRUD.git
```
2. 在終端機上安裝 npm 套件
```
npm install
```
3. 連接資料伺服器至本機，並產生種子檔
```
npm run seed
```
4. 啟用伺服器
```
nodemon app.js
```
5. 在隨意瀏覽器網址列輸入 http://localhost:3000/ 即可進入網站~

## :wrench: 使用的套件版本
- express：4.17.1
- express-handlebars：5.3.1
- bootstrap：4.3.1
- jquery：3.6.0
- popper.js：2.9.1
- body-parser：1.19.0
- mongoose：5.12.7

