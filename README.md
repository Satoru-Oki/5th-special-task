# 5th-special-task    
## URL(Uniform Resource Locator)とは
- Web上で取得したいファイルの場所を示す表記方法  
ex)①https:// ②qiita.com/ ③Ohtak/items/ ④ookami.html   
&emsp;①プロトコル②ドメイン名③パス④ファイル名により一意にリソースを特定できる
## パスパラメータ・クエリパラメータとは
- パスパラメータとは  
  特定のリソースを判別する際に必要となる値
- クエリパラメータとは  
  パスパラメータに紐づく特定のリソースを取得する際に必要となる値  
  ex）https // example.com /① right / items / members ② ?id=3  
  ①から②までの部分がパスパラメータであり、②の部分がクエリパラメータとなる  
クエリパラメータは"？"以降を指し、名前＝値の形式で内容を記述する  
パッシブパラメータとアクティブパラメータの2種類がある
## HTTPメソッドとは
### クライアントサーバーシステムの概要
<img width="227" alt="image" src="https://github.com/Satoru-Oki/5th-special-task/assets/143796169/528e0de4-7588-4f95-bc67-f4356eeff001">    
<img width="214" alt="image" src="https://github.com/Satoru-Oki/5th-special-task/assets/143796169/ee97c69b-ed79-48ee-bb79-eb2a6efab950">  

図のようなやりとりをおこなうにあたってのWeb上の決め事（プロトコル）をHTTPプロトコルという
## HTTPメッセージとは
クライアントとサーバーがデータを交換する手段でクライアントが送信するものがリクエスト、サーバーが回答するレスポンスの２種類がある
