# Qiskit v2.X Developer 認定試験 (C1000-179) 対策ガイド

IBM Certification **C1000-179 / Fundamentals of Quantum Computing Using Qiskit v2.X Developer**
に向けた、日本語の学習用まとめです。単一の HTML ファイルで、依存は MathJax と Google Fonts だけです。

**👉 [ガイドを読む](https://kotaro-okamoto.github.io/qiskit-v2x-exam-guide/)**

## 免責

**個人が作成した非公式の教材です。** IBM が作成・監修・推奨したものではなく、IBM の見解を代表するものでもありません。

**実際の試験問題や試験の構成に関する情報は含みません。** 公式サンプルテストの問題文も再掲していません
（Part A は「どの問題がどのセクションの何を問うているか」の対応表だけで、問題文と解答は IBM の配布物を参照してください）。

内容の正確性は保証しません。試験範囲と API 仕様は変更されるので、最新の情報は
[Qiskit 公式ドキュメント](https://quantum.cloud.ibm.com/docs/) と
[IBM Certification](https://www.ibm.com/training/certification/C0010300) で確認してください。

## 中身

公式ブループリントの8セクションに沿った構成です。括弧内は試験全体に対する配点比率（ブループリント記載）。

| § | セクション | 配点 |
|---|---|---|
| §0 | 実行の全体フロー（service → backend → transpile → primitive → run → result） | — |
| §1 | 量子操作の実行 | 16% |
| §2 | 回路・測定・状態の可視化 | 11% |
| §3 | 量子回路の作成 | 18% |
| §4 | 量子回路の実行 | 15% |
| §5 | Sampler プリミティブ | 12% |
| §6 | Estimator プリミティブ | 12% |
| §7 | 結果の取得と分析 | 10% |
| §8 | OpenQASM | 6% |

- **7日間の学習計画** — 配点の高いセクションから優先する順序で
- **オリジナル予想問題 64問** — Part B（30問）/ C（図問題 8問）/ D（API・コード 14問）/ E（実行順・定義 12問）。
  問題文は試験と同じ英語、解説は日本語
- **図つき問題** — qsphere・回路図・Bloch 球・ヒストグラムを SVG で自作
- **直前チートシート**
- **⚠注意コラム** — 理屈で導けず暗記するしかない箇所（メソッド名・引数名など）を集約

「仕組みを理解すれば解ける」ことを優先し、暗記が必要な箇所は「覚えること」として明示的に分けています。

## 併用をおすすめする教材

- 公式サンプル問題の日本語解説: [前編](https://schrodinteq.github.io/japanese/ibmcertsamplev2x01/) / [後編](https://schrodinteq.github.io/japanese/ibmcertsamplev2x02/)
- 練習問題集（英語）: [Udemy — IBM Certified Quantum Computation Qiskit v2.x Practice Exams](https://www.udemy.com/course/ibm-certified-quantum-computation-qiskit-v2x-practice-exams)

## ローカルで開く

```bash
git clone https://github.com/Kotaro-Okamoto/qiskit-v2x-exam-guide.git
cd qiskit-v2x-exam-guide
open index.html          # macOS（Linux は xdg-open）
```

MathJax と Google Fonts を CDN から読むので、数式とフォントの表示にはネットワークが必要です。

## 誤りの報告

内容の誤りを見つけたら [Issue](https://github.com/Kotaro-Okamoto/qiskit-v2x-exam-guide/issues) で教えてください。
ただし**実際の試験問題や試験内容の書き込みはご遠慮ください** — IBM の認定契約に抵触します。

## ライセンス

文章・図は [CC BY 4.0](./LICENSE)。コード断片は説明用で、自由に使ってかまいません。

Qiskit および IBM は IBM Corp. の商標です。
