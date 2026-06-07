# GotchaPins ガイド（GitHub Pages 公開用）

VRChat向け3Dピンズ「GotchaPins」の取扱いガイド。商品パッケージ同梱のランディングカードからこのガイドへ遷移する。

## 公開URL
https://yukilens.github.io/gotchapins-guide/

## 構成
| パス | 内容 |
|---|---|
| `index.html` | トップ（アバター用／ワールド用への振り分け） |
| `avatar/` | アバターに付けるガイド（目次＋5ページ） |
| `world/` | ワールドに設置するガイド（目次＋5ページ） |
| `terms.html` | 利用規約・クレジット |
| `assets/` | CSS・ロゴ・バナー・操作スクショ（`shots/`） |

## 編集方針（重要）
- **このフォルダが共通ガイドのマスター**。
- 商品パッケージ同梱のランディングカードは、このガイドへ **Pages URL** でリンクしている。
- したがって **ガイドの更新は push するだけで全商品に反映**される（パッケージの再配布は不要）。
- 操作スクショ（`assets/shots/`）の差し替えもここで行う。

## Pages 公開手順
1. GitHub で `gotchapins-guide` リポジトリを作成（yukilens アカウント）。
2. このフォルダを push（`git remote add origin ...` → `git push -u origin main`）。
3. リポジトリ Settings > Pages > Source を `main` / `(root)` に設定して公開。
4. 公開URL `https://yukilens.github.io/gotchapins-guide/` が有効になる。

## メモ
- `.meta` はUnity専用のため本リポジトリでは `.gitignore` で除外。
- フォント Noto Sans JP は Google Fonts から読込（オンライン時）。
