# quiz
online quiz

クイズの問題を追加・変更する場合は、quiz.json を修正して、必要があれば画像ファイルを追加します。
ひとつの問題は、以下のようなオブジェクトとして、定義します。
｛
  "name": "s1", // 短い名前
  "text1":"スクラッチの公式（こうしき）キャラクターの名前（なまえ）は？", // クイズの問題
  "image1":"s1.jpg",  // 画像ファイル名
  "A":"スクラッチ キャット", // 回答A
  "B":"スクラッチ ドッグ",  // 回答B
  "correct":"A" // 正解（"A" または "B"）
}
        
