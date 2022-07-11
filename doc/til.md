# Go のリリースサイクル
- https://github.com/golang/go/wiki/Go-Release-Cycle  
半年サイクルでリリースサイクルが回っている
  - 3ヶ月で一般的な開発をし、3ヶ月でリリース・フリーズを行う  
  フリーズ期間：この期間はバグ修正とドキュメント更新のみ行われる  
# 標準ライブラリ
一覧は以下
- https://pkg.go.dev/std  
  - fmt  
  C言語でいうprintfやscanfのような機能を有する
  - net/http  
  httpクライアントやhttpサーバ機能を提供する
  - encoding  
  さまざまなフォーマットのデータを操作できる機能
  - os  
  コマンドを実行する機能
  - path  
  OSで定義されたファイルパスなどを得る機能

# ツール
- go build  
ビルドを行うコマンド
- go test  
hoge_test.go に書かれたテストコードを実行する
- go doc(godoc)  
コードからAPIドキュメントを生成する
- gofmt(goimports)  
コードフォーマッター  
go言語のリファクタリングに用いる
- go vet  
コードチェッカー  
コンパイラとは異なる観点で、懸念点をサジェストしてくれる  
- golint  
スタイルの問題を指摘してくれる
