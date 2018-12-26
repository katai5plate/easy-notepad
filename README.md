# easy-notepad

https://katai5plate.github.io/easy-notepad/

## 特徴
- ページ全体が **リッチテキスト** のメモ帳
- **１秒毎**にローカルストレージに **オートセーブ**
- **1ファイルのみ** で動作

# 注意
- Chromeでしか動作確認してないです

## 操作方法
- Ctrl(⌘) + B: 太字
- Ctrl(⌘) + U: アンダーライン
- Ctrl(⌘) + I: 斜体
- Ctrl(⌘) + C: コピー
- Ctrl(⌘) + V: 貼り付け

## コンソールコマンド
### コンソールの出し方
- Chromeの場合
  - Windows: F12
  - Mac: ⌘ + ⌥ + I
### タイトルの変更
```js
// 一時的
TITLE = "任意のキーワード" or null;
// 永続的
__editTitle("任意のキーワード" or null)
```
