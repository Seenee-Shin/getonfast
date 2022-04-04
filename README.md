# 貸して

GitHub: https://github.com/Seenee-Shin/getonfast.git
言語: Java, JavaScript, Oracle
開発期間: 2021.11 ~ 2021.12

[GitHub - Seenee-Shin/getonfast](https://github.com/Seenee-Shin/getonfast.git)

# 💡 Topic

- 空間予約サービス
- ウェブデザインやコンセプトは[スペースクラウド](https://www.spacecloud.kr/)をコピーしました。
    
    HTML／CSS/Javascriptを含めた**ソースコードの模写コーディングは一切なし。**
    

# 📝 Summary

コロナの影響でテレワークが一般化し始めたこの時期に合わせた空間予約サービス。

ホテルや宿泊施設ではなくコワーキングスペースや、セミナールームなど様々な空間を予約できるサイトです。

# 🛠 Tech Stack

`Java`, `JavaScript`,`Gson`,`css`,`HTML5`,`ajax`,`tomcat`,`OracleDB`

# 🧑🏻‍💻 Team

- Web-developer ４人

# 🤚🏻 Part

- ワイヤーフレーム、プロトタイプ作成
- 会議録作成
- メインページフロントエンド
- 検索機能
- 企画売りページ機能
- おすすめ空間機能
- 管理者ぺージ・空間登録

# 🤔 Learned

- プログラミングを学んで参加した初プロジェクトになります。(プログラムの配布 ❌**)**
- 基本的な**ウェブプログラミングのプロセス**を身につけながら進めました。
- **Java MVC２モデル**でプロジェクトを作成しました。
- **Ajax**を利用し**非同期処理**を試してみました。
- データベースから必要な情報を取り出すことができます。

# 📑 Want

- Ajaxを利用するとき、**Jsonデータ型でデータを処理**する練習が必要だと思いました。
- 全体的に**SQLの作成能力を上げて行きたい**と思いました。
- **無限スクロールを実装**できず、普通のページネーションで実装したことが残念でした。
    
    いつかは無限スクロールを実装できるように勉強したいと思いました。
    

## プロトタイプ（Figma）

[https://www.figma.com/embed?embed_host=notion&url=https%3A%2F%2Fwww.figma.com%2Fproto%2F6FqsxkMGUmxUvuAiIXcZiL%2Fproject%3Fpage-id%3D0%253A1%26node-id%3D175%253A961%26starting-point-node-id%3D175%253A961%26scaling%3Dscale-down-width](https://www.figma.com/embed?embed_host=notion&url=https%3A%2F%2Fwww.figma.com%2Fproto%2F6FqsxkMGUmxUvuAiIXcZiL%2Fproject%3Fpage-id%3D0%253A1%26node-id%3D175%253A961%26starting-point-node-id%3D175%253A961%26scaling%3Dscale-down-width)

# 📷 Screenshot

プロジェクトはハングルで作成され、スクリーショットは日本語の自動翻訳を利用しました。 
誤訳がある可能性がございますのでご了承ください。

### **メインページ**

![localhost_12762_hyejinbus_ (1).png](%E8%B2%B8%E3%81%97%E3%81%A6%2042067/localhost_12762_hyejinbus__(1).png)

### **サイドメニュー**

![localhost_12762_hyejinbus_ (4).png](%E8%B2%B8%E3%81%97%E3%81%A6%2042067/localhost_12762_hyejinbus__(4).png)

ハンバーガーメニューをクリックするとサイドメニューが右から左に出現します。

### **企画展**

![localhost_12762_hyejinbus_promotion (2).png](%E8%B2%B8%E3%81%97%E3%81%A6%2042067/localhost_12762_hyejinbus_promotion_(2).png)

### **企画展詳細ページ**

![localhost_12762_hyejinbus_promotion_detail_no=2 (2).png](%E8%B2%B8%E3%81%97%E3%81%A6%2042067/localhost_12762_hyejinbus_promotion_detail_no2_(2).png)

### **検索**

![localhost_12762_hyejinbus_space_search_sv=%EC%B9%B4%ED%8E%98 (2).png](%E8%B2%B8%E3%81%97%E3%81%A6%2042067/localhost_12762_hyejinbus_space_search_svECB9B4ED8E98_(2).png)

### **空間登録ページ**

![localhost_12762_hyejinbus_adminSpace_insert (3).png](%E8%B2%B8%E3%81%97%E3%81%A6%2042067/localhost_12762_hyejinbus_adminSpace_insert_(3).png)

/토
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
