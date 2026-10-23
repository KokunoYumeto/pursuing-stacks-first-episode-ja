# 『スタックを追い求めて：第一話——モデル化の物語』日本語完全訳

このリポジトリは、アレクサンドル・グロタンディーク
『スタックを追い求めて：第一話——モデル化の物語』の独立した日本語完全訳を
保存する。英語との対照本ではない。数式、永続的識別子、固有名、原文引用、
文献の原題など、同一性を保つ必要がある内容を除き、読者向けの本文と補助資料は
日本語で記されている。

## 閲覧と入手

- [v1.3.0 完全版リリース](https://github.com/KokunoYumeto/pursuing-stacks-first-episode-ja/releases/tag/v1.3.0)
- [閲覧用 PDF（539頁）](https://github.com/KokunoYumeto/pursuing-stacks-first-episode-ja/releases/download/v1.3.0/01_pursuing-stacks.ja.complete.pdf)
- [原典 arXiv:2111.01000v2](https://arxiv.org/abs/2111.01000)

公開ファイルは次の順序で並ぶ。

1. `01_pursuing-stacks.ja.complete.pdf` — 539頁の完全な閲覧用 PDF。
2. `02_pursuing-stacks.ja.complete.cumulative.tex` — 直接取得・閲覧・編集できる完全な累積 LaTeX。
3. `03_pursuing-stacks.ja.complete.source.zip` — 閲覧版を再現する完全な編集可能ソース一式。
4. `04_pursuing-stacks.ja.revision-review.md` — 版の説明、原典由来の疑義、専門家向け検討案内。
5. `05_pursuing-stacks.ja.translation-choices.jsonl` — 機械可読な翻訳選択台帳。
6. `06_pursuing-stacks.ja.SHA256SUMS.txt` — 前五ファイルの SHA-256 検査和。

## 収録範囲

標題紙と前付、筆耕者の序文、著者序文、第1節から第140節まで（挿入された
16bisを含む141個の番号付き本文単位）、附録「Larry Breen 宛ての三通の書簡」
の導入と全18区分、脚注、欄外注、見出し、図式中の読者向け文字、目次、参考文献、
その他の後付を収録する。

## 原典と編集上の境界

唯一の意味上の原典は arXiv:2111.01000v2 である。数式、ラベル、相互参照、引用、
原頁標識、仮定、論断の強さ、年代、配列順を保存する。日本語の用語、統語、成人向け
数学文体には、実際に参照した日本語の数学文献を用いた。根拠、採否、不確実性は
翻訳選択台帳に記録している。原典自身の疑わしい箇所は訳文だけで推測訂正せず、
版の説明に分離した。原典本文が引用する `SGA3` に対応する項目は付属書誌データに
ないため、出典を推測して補っていない。

本版は Stacks Project の公式版ではなく、その承認を得たとは主張しない。

## 検査範囲と限界

ソース28項目、141個の番号付き単位、附録18区分、353個の追跡標識、ならびに保護
対象の数式・参照・引用・頁・日付マクロ列は構造検査に合格した。モジュール版と
累積版はいずれも539頁の A4 PDF を生成し、逐頁のテキスト抽出と 90 dpi 描画に
相違頁はなかった。最終累積 PDF の第1、5、25、70、130、200、280、360、430、
490、525、539頁を一度だけ有界に目視し、標本頁には裁ち落ち、重なり、意図しない
空白、豆腐字または版面の破断を認めなかった。これは全539頁の人間査読ではない。

30書体はすべて埋込み・部分集合化され、日本語2書体は ToUnicode を備える。
五つの旧来の数式用書体には ToUnicode がないため、数式の純テキスト抽出には
制御文字または置換文字が残りうる。人間の数学専門家による査読・校閲は行われていない。

翻訳、校訂、検証資料は OpenAI Codex — GPT-5.6 Sol（Ultra 推論強度）によって
生成された。人間による編集、査読または承認を示すものではない。

## 他言語版

- [簡体字中国語完全訳](https://github.com/KokunoYumeto/pursuing-stacks-zh-hans-cn)
- [韓国語完全訳](https://github.com/KokunoYumeto/pursuing-stacks-first-episode-ko-kr)

ライセンス：CC0 1.0 Universal。無保証。
