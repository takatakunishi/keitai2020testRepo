# 簡易RESTfulAPI
## リクエスト一覧
<details><summary>URL</summary>
<ul>
<li> 名前取得: https://creatorsfantasyfpn.com/aps/server.cgi/getSpotName</li>
<li>スポットのデータ取得: https://creatorsfantasyfpn.com/aps/server.cgi/getSpotsData</li>
<li>リクエストの種類取得: https://creatorsfantasyfpn.com/aps/server.cgi/getMethod</li>
<li>スポットの感情値取得:</li>
<li>悲しみが一番大きいスポット:</li>
<li>喜びが一番大きいスポット:</li>
<li>恐怖が一番大きいスポット:</li>
<li>怒りが一番大きいスポット:</li>
<li>嫌悪が一番大きいスポット:</li>
<li>驚きが一番大きいスポット:</li>
</ul>
</details>

<details><summary>仕様</summary>

  "GetSpotName": "スポットの名前をStringで返す",
  "GetSpotsData": "スポットのデータを返す方はReadme参照か直で聞いてください",
  "GetSpotEmotion": "スポットの感情を数値の配列[angry, sad, dislike, fear, surprise, happy] (最大値) として返す",
  "GetSadSpot": "悲しみが大きいスポットを返す",
  "GetHappySpot": "喜びが大きいスポットを返す",
  "GetFearSpot": "恐怖が大きいスポットを返す",
  "GetAngrySpot": "怒りが大きいスポットを返す",
  "GetDislikeSpot": "嫌悪が大きいスポットを返す",
  "GetSurpriseSpot": "驚きが大きいスポットを返す",
  "GetMthod": "リクエストの種類をすべて教えてくれる"
</details>