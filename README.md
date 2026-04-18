# Medical Academic English Trainer

医学論文執筆・学会発表のための学術英語教材（Web App）

## Overview

医学研究者・臨床医が学術英語を体系的に学ぶためのインタラクティブなウェブ教材です。論文執筆（IMRaD形式）から学会発表、救急医のプレゼンテーションまで幅広くカバーしています。

## Features

| セクション | 内容 |
|---|---|
| **論文執筆 Writing** | IMRaD形式に沿った各セクション（Title/Abstract, Introduction, Methods, Results, Discussion, Cover Letter）の定型表現 |
| **学会発表 Presentation** | 口頭発表、ポスター発表、質疑応答、座長（Session Chair）、救急プレゼン（Primary/Secondary Assessment）の表現 |
| **学術文法 Grammar** | 時制、能動態/受動態、Hedging、日本人研究者がよくする間違い、北米英語/英国英語の違い |
| **専門語彙 Vocabulary** | 研究デザイン、統計用語、接続表現、査読対応の用語 |
| **練習問題 Quiz** | 各セクションに対応した選択式クイズ（ランダム出題） |

## Usage

### ローカルで開く

```bash
open index.html
```

ブラウザで `index.html` を直接開くだけで使用できます。サーバーやビルドツールは不要です。

### GitHub Pages で公開する

1. このリポジトリを GitHub にプッシュ
2. Settings → Pages → Source を `main` ブランチ、`/ (root)` に設定
3. `https://<username>.github.io/<repository-name>/` でアクセス可能

## File Structure

```
academic-english/
├── index.html    # アプリ本体（HTML/CSS/JS 単一ファイル）
├── README.md     # このファイル
└── LICENSE       # CC BY-NC-SA 4.0
```

## Technology

- HTML5 / CSS3 / Vanilla JavaScript
- 外部ライブラリ・フレームワーク不使用
- レスポンシブ対応（モバイル・タブレット・デスクトップ）

## References

本教材で言及しているガイドライン・基準の主な出典：

- **ICMJE** — International Committee of Medical Journal Editors. *Recommendations for the Conduct, Reporting, Editing, and Publication of Scholarly Work in Medical Journals.* Updated December 2023.
- **CONSORT** — Schulz KF, et al. CONSORT 2010 statement. *BMJ.* 2010;340:c332.
- **STROBE** — von Elm E, et al. The STROBE statement. *Lancet.* 2007;370(9596):1453-1457.
- **PRISMA** — Page MJ, et al. The PRISMA 2020 statement. *BMJ.* 2021;372:n71.
- **AMA Manual of Style** — 11th ed. Oxford University Press; 2020.
- **GCS** — Teasdale G, Jennett B. *Lancet.* 1974;2(7872):81-84.
- **ABCDEアプローチ** — Thim T, et al. *Int J Gen Med.* 2012;5:117-121; Resuscitation Council UK.

全参考文献はアプリ内フッターの「参考文献・出典」セクションに記載しています。

## Disclaimer

- 本教材のフレーズ・例文はすべてオリジナルに作成した汎用的な学術定型表現です
- 症例・データはすべて架空であり、実在の患者情報は含まれていません
- 本教材は言語学習を目的としており、臨床判断の根拠として使用しないでください

## AI Assistance

本教材の作成にあたり、生成AI（Claude, Anthropic）を活用しました。

## Contributing

Issue や Pull Request を歓迎します。

## License

[CC BY-NC-SA 4.0](LICENSE) — Creative Commons 表示-非営利-継承 4.0 国際

教育目的での利用・改変・再配布は自由です。商用利用はできません。

詳細: https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ja

## Author

Shunichiro Nakao, MD, MSc, PhD  
Department of Traumatology and Acute Critical Medicine, The University of Osaka
