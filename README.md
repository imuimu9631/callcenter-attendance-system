# コールセンター勤怠管理システム - バックアップ

作成日: 2025年6月15日

## 概要
QRコード打刻機能付きのモダンな勤怠管理システム

## 主な機能
- ✅ QRコード生成・スキャン打刻
- ✅ リアルタイム勤務状況表示
- ✅ 時給計算（管理者限定）
- ✅ モダンUI（ダークテーマ・アニメーション）
- ✅ スマートフォン対応
- ✅ 役割ベースアクセス制御

## ファイル構成
- `system-data-export.json` - システムの全データ・設定
- `README.md` - このファイル

## ログイン情報
### 管理者
- ID: CC001
- パスワード: admin123

### オペレーター
- ID: CC002
- パスワード: password123

## 技術スタック
- React 18
- Vite
- Tailwind CSS
- QRコード: qrcode + qr-scanner
- 日付処理: date-fns
- アイコン: lucide-react

## 起動方法
1. プロジェクトフォルダで `npm install`
2. `npm run dev` または `npm run preview`
3. `http://localhost:3000/` でアクセス

## QR打刻の流れ
1. 管理者がQRコード生成（5分間有効）
2. オペレーターがスマホでQRスキャン
3. 自動的に打刻完了

## 開発者
Claude Code & ユーザー協力開発