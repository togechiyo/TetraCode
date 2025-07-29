# TetraCode

 Minimal Web Game Sample

**Babylon.js × Tailwind CSS × sql.js × htmx**  
たった1枚のHTMLで、ミニゲーム＋ローカルログ記録を実現するサンプルです。

![](./screenshot.png) <!-- スクショ画像を置く場合 -->

## TetraCodeとは

**TetraCode** は、以下の4つの軽量ライブラリで構成されるスタックです：

- **Babylon.js** … 高機能な3D描画エンジン（WebGL）
- **Tailwind CSS** … ユーティリティベースのスタイリング
- **sql.js** … Pure JS版 SQLite（ローカルDBとして使用）
- **htmx** … HTML中心のUI制御（ボタン連携など）

これらを**CDNで読み込み、単一HTMLで完結**させています。

## 特徴

- モバイル対応（レスポンシブGUI）
- オフライン動作
- ローカルでSQLite風のログ記録
- GitHub Pagesでそのままホスト可能
- 学生PCでも動くレベルの超軽量構成

## 構成

```txt
.
├── index.html     # 全部入りの単一ファイル
```

## 開発メモ

- このサンプルでは、方向キー・A・Bボタンによる入力を記録しています
- 操作はすべてローカルで完結しており、外部にデータは送信しません
- ログは `sql.js` を用いてブラウザ上のSQLite風DBに保存されます

## 未来の展望

- 自作GUI、エフェクト、サウンド対応
- ハイスコア制やアセット差し替えなど
- 小規模イベント・展示向けの応用

## ライセンス

MIT License  
（ただし外部ライブラリは各ライセンスに準拠してください）

---

TetraCodeは、1枚のHTMLに"遊び"と"構造"を詰め込む挑戦です。
