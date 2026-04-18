# Medical English Presentation Trainer / 医学英語プレゼンテーション トレーナー

NEJM (New England Journal of Medicine) の Case Records 形式に基づく英語症例提示と、国際学会での座長英語を学ぶためのインタラクティブ教材です。日本人の若手救急医を主な対象としています。

## 特徴

- **NEJM 症例提示テンプレート** — 標準的な NEJM Case Records の構成と定型表現を解説
- **救急医の症例提示テンプレート** — Primary Survey (ABCDE) → 蘇生 → Secondary Survey の流れを NEJM 形式と融合
- **セクション別重要フレーズ集** — 日本語対訳・音声読み上げ付き
- **練習問題（計10症例）** — 日本語の症例情報から英語プレゼンを書く練習（模範解答・音声付き）
  - NEJM 形式 5症例：胸痛、呼吸困難と発熱、意識障害、腹痛、脳卒中
  - 救急医の型 5症例：多発外傷、敗血症性ショック、急性冠症候群、アナフィラキシー、心肺停止後
- **確認テスト** — NEJM の表現規則に関する 10 問のクイズ（解説付き）
- **自己評価チェックリスト** — 構成・表現・デリバリーの到達度管理
- **国際学会 座長英語** — セッション開会から閉会までの全場面の定型表現と 6 場面のシミュレーション練習

## 使い方

単一の HTML ファイルで動作します。サーバー不要で、ブラウザで直接開けます。

```bash
# ローカルで開く
open index.html

# または任意の HTTP サーバーで配信
python3 -m http.server 8000
```

### 音声読み上げ

Web Speech API を使用しています。Chrome / Safari / Edge など主要ブラウザで動作します。
スピーカーボタンをクリックすると、英語フレーズの発音を確認できます。

### 進捗の保存

自己評価チェックリストと座長準備チェックリストの進捗は、ブラウザの localStorage に保存されます。

## 対象

- 英語での症例プレゼンテーションを学ぶ日本人の若手救急医
- 国際学会で座長を務める予定の医師
- 医学英語教育に携わる指導医

## ファイル構成

```
case-presentation-app/
├── index.html   # アプリ本体（HTML + CSS + JavaScript の単一ファイル）
├── README.md    # このファイル
└── LICENSE      # CC BY-NC-SA 4.0 ライセンス
```

## 免責事項・帰属表示

本教材は、*New England Journal of Medicine* (NEJM) の「Case Records of the Massachusetts General Hospital」シリーズの**公開されている構成形式・文体上の慣行**を参考に、教育目的で独自に作成したものです。

- NEJM に掲載された症例報告の原文を引用・転載したものではありません
- 掲載されている練習症例は**全て架空**のものです
- NEJM、Massachusetts General Hospital、Massachusetts Medical Society とは一切関係がなく、これらの組織による承認・推薦を受けたものではありません

### 参考にした概念・ガイドライン

| 概念 | 出典 |
|------|------|
| NEJM Case Records の構成形式 | *N Engl J Med* — Case Records of the Massachusetts General Hospital (ongoing series) |
| Primary Survey (ABCDE) アプローチ | ATLS (Advanced Trauma Life Support), American College of Surgeons |
| 敗血症管理 | Evans L, et al. Surviving Sepsis Campaign: International Guidelines for Management of Sepsis and Septic Shock 2021. *Crit Care Med*. 2021;49(11):e1063-e1143. |
| 脳卒中急性期管理 | Powers WJ, et al. Guidelines for the Early Management of Patients With Acute Ischemic Stroke. *Stroke*. 2019;50(12):e344-e418. |
| 心肺蘇生 | Panchal AR, et al. 2020 AHA Guidelines for CPR and ECC. *Circulation*. 2020;142(16_suppl_2). |
| アナフィラキシー管理 | Cardona V, et al. World Allergy Organization Anaphylaxis Guidance 2020. *World Allergy Organ J*. 2020;13(10):100472. |

## ライセンス

[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ja) (Creative Commons 表示-非営利-継承 4.0 国際)

教育目的での利用・改変・再配布は自由です。商用利用はできません。

## 作成者

**Shunichiro Nakao, MD, MSc, PhD**<br>
Department of Traumatology and Acute Critical Medicine, The University of Osaka

本教材の作成にあたり、生成AI（Claude, Anthropic）を活用しました。
