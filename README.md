# Raspberry Pi 教育用ツール（利用者向け）

このリポジトリは、Raspberry Pi 上で教育用ツールを **Docker** で起動し、利用者が **別PCのブラウザ（Scratch）** から操作できるようにするための「配布用」です。  
**git clone は不要**です（ワンライナー導入）。

---

## できること（概要）

- Raspberry Pi 上で以下が自動起動します
  - Scratch（ブラウザで開く画面）
  - Python WebSocket サーバ（Scratch ↔ ハードウェア制御）
  - PIOLED（IP表示など）
- 利用者は、別PCのブラウザから Raspberry Pi の Scratch にアクセスして学習・操作できます

---

## 対象環境

- Raspberry Pi OS（64-bit 推奨）
- インターネット接続（初回のみ：Dockerイメージ取得のため）

---

## 1分で導入（コピペ）

Raspberry Pi で次を実行してください：

```bash
curl -fsSL https://github.com/kaitoaa07/rpi_tool/releases/latest/download/install.sh | bash
