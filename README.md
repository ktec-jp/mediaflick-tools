# mediaflick-tools

mediaFlick が自動ダウンロード（および同梱）して**別プロセスとして**利用する外部ツールの
公開配布リポジトリです。mediaFlick 本体（クローズドソース）は、これらをコマンドライン経由で
呼び出すだけで、本体は派生物ではありません（独立プログラムの集合）。

## 配布物（Releases）

| ツール | バージョン | ライセンス | 配布 |
|---|---|---|---|
| dvdauthor | 0.7.1 (Windows x64, MinGW) | GPL v2+ | `dvdauthor-0.7.1` リリースの `dvdauthor-win64.zip` |

ffmpeg は [BtbN/FFmpeg-Builds](https://github.com/BtbN/FFmpeg-Builds) の win64-gpl 最新版を利用します。

## ライセンス順守

- [`COPYING.GPLv2.txt`](COPYING.GPLv2.txt) — GNU GPL v2（dvdauthor / FFmpeg）
- [`COPYING.LGPLv2.1.txt`](COPYING.LGPLv2.1.txt) — GNU LGPL v2.1（libiconv）
- [`THIRD-PARTY-LICENSES.txt`](THIRD-PARTY-LICENSES.txt) — 全同梱物のライセンスと対応ソース入手先
- **対応ソース**: 各リリースに `*-src.tar.gz`（例 `dvdauthor-0.7.1.tar.gz`）を同梱しています。

dvdauthor バイナリは DVDStyler 3.0.4 (win64) 同梱物を抽出したものです。正確なビルド
スクリプト/パッチは [DVDStyler 3.0.4 のソース](https://sourceforge.net/projects/dvdstyler/files/dvdstyler/3.0.4/) を参照してください。
