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
### クライアントサーバーシステムの概要
<img width="227" alt="image" src="https://github.com/Satoru-Oki/5th-special-task/assets/143796169/528e0de4-7588-4f95-bc67-f4356eeff001">    
<img width="214" alt="image" src="https://github.com/Satoru-Oki/5th-special-task/assets/143796169/ee97c69b-ed79-48ee-bb79-eb2a6efab950">  

図のようなやりとりをおこなうにあたってWeb上の決め事（プロトコル）をHTTPプロトコルという
## HTTPメッセージとは
クライアントとサーバーがデータを交換する手段でクライアントが送信するものがリクエスト、サーバーが回答するレスポンスの２種類がある  

<img width="104" alt="image" src="https://github.com/Satoru-Oki/5th-special-task/assets/143796169/d04f2403-c244-4fa5-bf56-de7f4b183852">  

リクエストとレスポンスそれぞれで図の構造をもつ
#### リスエストヘッダ
クライアント側が送るブラウザの名前や言語、文字などの付加情報が記載されている。一つのメッセージは複数のヘッダを持つことができる  
#### リクエストボディ  
メッセージを表す本文が記載されている。POSTの場合は受け渡されるパラメータの値が記載される。GETの場合はなにも記載されない  
#### レスポンスヘッダ  
レスポンスのデータの内容がどのようなものかを示す情報が記載されている。（テキスト形式、HTML形式であるなど）
#### レスポンスボディ  
HTMLの内容など本文が記載されている。
#### JSONとは
JavaScript Object Notationの略、データ交換のために設計された軽量なテキスト形式のデータの表現。主にWebアプリケーションなどでクライアントとサーバー間でデータをやり取りする際に使用される
#### HTTPステータスコード
レスポンスメッセージの中で現在の通信の状態を伝達するもの  
３桁の数字で表され先頭の数字で意味が分類されている  
<img width="500" alt="image" src="https://github.com/Satoru-Oki/5th-special-task/assets/143796169/958a3249-eb30-42db-82a4-39177d1a194a">  
その他  
201：リクエストが成功し、その結果新たなリソースが作成されたことを表す  
404：サーバーがリクエストされたリソースを発見できないことを表す  

## HTTPメソッドとは
クライアントが行いたい処理をサーバー側に伝えるもの  
<img width="500" alt="image" src="https://github.com/Satoru-Oki/5th-special-task/assets/143796169/d87c1613-6505-4816-bd70-8b4a1c321451">  
以上、９つのメソッドがある

