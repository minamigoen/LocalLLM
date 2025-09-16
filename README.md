# LocalLLM

このリポジトリは、Ollamaを使ったローカルLLM環境構築のサンプルです。  
自作HTMLをブラウザから開くことで、`http://localhost:11434/api/chat` に接続し、ローカルのモデルを利用できます。

## セットアップ手順
1. Ollamaをインストール  
[Ollama ダウンロード](https://ollama.com/download){:target="_blank"}

2. モデルをダウンロード
   ```bash
   ollama pull gemma:2b

3.環境変数を設定（Windowsの場合）

- 変数名: OLLAMA_ORIGINS
- 値: *

4.ブラウザで goenmagi.html を開く

## 注意
- ローカルで1台だけの利用なら * でOKです。
- LAN共有する場合は、自分のIPを指定してください。
