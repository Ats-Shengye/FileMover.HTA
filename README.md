# ファイル一括移動ツール

## 概要
企業環境でのセキュリティ制約下において、実用的なファイル管理ツールとしてHTA（HTML Application）形式で開発しました。

## 技術的制約と解決策
- **制約**: 実行ファイル作成不可、PowerShell制限
- **解決**: HTAとActiveXを活用したローカルファイル操作
- **工夫**: メモ帳編集による設定変更、直感的UI設計

## 主要機能
- フォルダ間でのファイル一括移動
- 拡張子によるフィルタリング
- 一括リネーム（連番自動付与）
- 日付フォルダ自動作成
- エラーハンドリング

## 動作環境
- Windows環境
- ActiveX有効（企業環境想定）
- Internet Explorer エンジン

## 注意事項
ActiveXの制限により、一部環境では動作しない場合があります。
