# 秋の優光泉 味くらべフェア｜飲みくらべBOX 特集ページ

断食道場shop（楽天）向け、個包装「ポケット優光泉」5つの味・6包の飲みくらべBOX（1,000円ポッキリ／数量限定）の特集ページです。

販売期間：2026年10月12日(月)10:00〜11月10日(火)23:59

プレビュー：https://sakikohatakeyama.github.io/danjiki-ajikurabe-2026autumn/

## ファイル構成
- `index.html` … ページ本体（CSS・JavaScriptもこの1ファイルに入っています）
- `img/` … 画像（index.html と同じ階層に、フォルダごとアップしてください）
  - `pk-std.webp` スタンダード／`pk-mik.webp` ミカン／`pk-ume.webp` 梅／`pk-zak.webp` ザクローズ／`pk-wak.webp` 濃縮和漢発酵
  - `logo-wide.webp` 断食道場ショップ ロゴ（ヘッダー・フッター）

## 仕様
- PC：コンテンツ幅800px（左右はオレンジ背景）／スマホ：767px以下で専用レイアウト
- フォント：Noto Sans JP（日本語）＋ Jost（数字・英字）／Google Fonts から読み込み
- JavaScript：スクロール時のフェード表示、メニュー、固定バー、TOPボタン、推し味ノート
  （楽天GOLDなどJavaScriptが使える場所に設置してください。商品ページの説明文に貼るとJavaScriptと一部のCSSが動きません）

## ページ構成
1. 看板：数量限定／5つの味を飲みくらべ／味くらべフェア限定価格 1,000円ポッキリ 送料無料／販売期間
2. ABOUT：はじめての方／いつもの方
3. たのしみ1：5つの味がぜんぶ入って1,000円ポッキリ（BOXの中身）
4. たのしみ2：気になる味から自由に（DAY1〜DAY6の例）
5. たのしみ3：推し味ノート（5段階で好き度をつけると推し味と商品リンクを表示）
6. 推し味が決まったら：各味の個包装（20ml×15包）とボトル（600ml）へのリンク
7. 購入エリア・商品概要
8. フッター：特集トップページに戻る／ショップロゴ

## 公開前に差し替えが必要な箇所
- 「飲みくらべBOXを買う」「購入する」ボタンのリンク先（計3か所：看板・上部の固定バー・購入エリア）
  - `index.html` 内の `<!-- BOX_URL -->` コメントの直後にあります
  - 現在は仮で「お試しポケット」カテゴリ https://item.rakuten.co.jp/danjiki-dojo/c/0000000211/ を設定しています
  - 飲みくらべBOXの商品ページができたら、そのURLに差し替えてください

## リンク先一覧
| 味 | 個包装 20ml×15包 | ボトル 600ml |
|---|---|---|
| スタンダード／梅 | https://item.rakuten.co.jp/danjiki-dojo/0002/ | https://item.rakuten.co.jp/danjiki-dojo/0090/ |
| ミカン | https://item.rakuten.co.jp/danjiki-dojo/7003/ | https://item.rakuten.co.jp/danjiki-dojo/7001/ |
| ザクローズ | https://item.rakuten.co.jp/danjiki-dojo/0058/ | https://item.rakuten.co.jp/danjiki-dojo/0063/ |
| 濃縮和漢発酵 | https://item.rakuten.co.jp/danjiki-dojo/0046/ | https://item.rakuten.co.jp/danjiki-dojo/0037_1/ |

- レギュラーボトル 1200ml（スタンダード／梅）：https://item.rakuten.co.jp/danjiki-dojo/0001/
- ショップTOP（ロゴのリンク先）：https://www.rakuten.co.jp/danjiki-dojo/
