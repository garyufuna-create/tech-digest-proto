# 情報収集くん Digest（試作プロトタイプ）

単一ファイルの静的 HTML プロトタイプです。ビルド不要・CDN 不要（システムフォント使用）。

## 開き方

### 方法 A: ブラウザで直接開く

```bash
# macOS
open /workspace/tech-digest-proto/index.html

# Linux
xdg-open /workspace/tech-digest-proto/index.html
```

またはエクスプローラーから `index.html` をダブルクリック（`file://` で開きます）。

### 方法 B: ローカル HTTP サーバー

```bash
cd /workspace/tech-digest-proto
python3 -m http.server 8080
```

ブラウザで http://127.0.0.1:8080/ を開く。

## 含まれるもの

- ダークカード UI（モバイル対応）
- フィルタ: すべて / AI / システムトレード / AIエージェント / X投稿
- 収集日時表記のシード記事（Web + X、試作サンプル）

フッター表記どおり、X コネクタ連携前のサンプルを含みます。
