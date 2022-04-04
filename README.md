# 貸して
![혜진이가_버스기사조_(제출용)-001](https://user-images.githubusercontent.com/86164711/161538945-cef0b83a-4061-46a8-b392-2cb553784b05.jpg)

## ⏱開発期間

2021.11 ~ 2021.12
<br></br>

## 🛠 Tech Stack

`Java`, `JavaScript`,`Gson`,`css`,`HTML5`,`AJAX`,`Tomcat`,`OracleDB`
<br></br>

## 💡 Topic

- 空間予約サービス
- ウェブデザインやコンセプトは[スペースクラウド](https://www.spacecloud.kr/)をコピーしました。
    
    HTML／CSS/Javascriptを含めた**ソースコードの模写コーディングはしておりません。**
<br></br>

## 📝 Summary

コロナの影響でテレワークが一般化し始めたこの時期に合わせた空間予約サービス。

ホテルや宿泊施設ではなくコワーキングスペースや、セミナールームなど様々な空間を予約できるサイトです。
<br></br>


## 🧑🏻‍💻 Team

- Web-developer ４人
<br></br>

## 🤚🏻 Part

- ワイヤーフレーム、プロトタイプ作成
- 会議録作成
- メインページフロントエンド
- 検索機能
- 企画売りページ機能
- おすすめ空間機能
- 管理者ぺージ・空間登録
<br></br>
## 🤔 Learned

- プログラミングを学んで参加した初プロジェクトになります。(プログラムの配布 ❌**)**
- 基本的な**ウェブプログラミングのプロセス**を身につけながら進めました。
- **Java MVC２モデル**でプロジェクトを作成しました。
- **Ajax**を利用し**非同期処理**を試してみました。
- データベースから必要な情報を取り出すことができます。
<br></br>

## 📑 Review

- Ajaxを利用するとき、**Jsonデータ型でデータを処理**する練習が必要だと思いました。
- 全体的に**SQLの作成能力を上げて行きたい**と思いました。
- **無限スクロールを実装**できず、普通のページネーションで実装したことが残念でした。
    
    いつかは無限スクロールを実装できるように勉強したいと思いました。
<br></br>

## 📜プロトタイプ（Figma）

[https://www.figma.com/embed?embed_host=notion&url=https%3A%2F%2Fwww.figma.com%2Fproto%2F6FqsxkMGUmxUvuAiIXcZiL%2Fproject%3Fpage-id%3D0%253A1%26node-id%3D175%253A961%26starting-point-node-id%3D175%253A961%26scaling%3Dscale-down-width](https://www.figma.com/embed?embed_host=notion&url=https%3A%2F%2Fwww.figma.com%2Fproto%2F6FqsxkMGUmxUvuAiIXcZiL%2Fproject%3Fpage-id%3D0%253A1%26node-id%3D175%253A961%26starting-point-node-id%3D175%253A961%26scaling%3Dscale-down-width)
<br></br>

## 📷 Screenshot

プロジェクトは韓国語で作成され、スクリーショットは日本語の自動翻訳を利用しました。 
誤訳がある可能性がございますのでご了承ください。

### **メインページ**

![localhost_12762_hyejinbus__(1)](https://user-images.githubusercontent.com/86164711/161538928-1e6b16c5-ab80-4ece-8f5e-7827a090414c.png)

### **サイドメニュー**

![localhost_12762_hyejinbus__(4)](https://user-images.githubusercontent.com/86164711/161538934-a3273326-9194-4515-9c98-ae30662709ef.png)

ハンバーガーメニューをクリックするとサイドメニューが右から左に出現します。

### **企画展**
![localhost_12762_hyejinbus_promotion_(2)](https://user-images.githubusercontent.com/86164711/161538938-112ed3a8-f16f-41db-bcd8-f18de99082ed.png)

### **企画展詳細ページ**

![localhost_12762_hyejinbus_promotion_detail_no2_(2)](https://user-images.githubusercontent.com/86164711/161538941-3dca5f42-8db0-491e-94b0-7f9c01856502.png)

### **検索**

![localhost_12762_hyejinbus_space_search_svECB9B4ED8E98_(2)](https://user-images.githubusercontent.com/86164711/161538942-29d5a134-83d8-4d1a-b58d-43f670af4d93.png)

### **空間登録ページ**

![localhost_12762_hyejinbus_adminSpace_insert_(3)](https://user-images.githubusercontent.com/86164711/161538935-4238e069-7878-4ef7-bef9-f1225b1b3e5b.png)

-----------
###### SiteMap
```
메인
http://localhost:8080/getonFast/        

***********************************************************************

프로필 관리
- http://localhost:8080/getonFast/my
찜한 공간
- http://localhost:8080/getonFast/my/favorites
문의 관리
- http://localhost:8080/getonFast/my/qna
이용 후기
- http://localhost:8080/getonFast/my/review


예약 리스트
- http://localhost:8080/getonFast/res/reserve
예약 상세
- http://localhost:8080/getonFast/res/reservation_detail


로그인
- http://localhost:8080/getonFast/member/login
회원가입
- http://localhost:8080/getonFast/member/signup


기획전
- http://localhost:8080/getonFast/promotion
기획전 리스트
- http://localhost:8080/getonFast/promotion_detail


공간 리스트
- http://localhost:8080/getonFast/space/search
공간 상세
- http://localhost:8080/getonFast/space/detail
공간 예약
- http://localhost:8080/getonFast/space/reservation

***********************************************************************

관리자 

-공간 등록 
http://localhost:8080/getonFast/adminSpace/insert
