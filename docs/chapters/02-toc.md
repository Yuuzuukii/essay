# 目次（Table of Contents）

出典：`template/guide.tex`「論文の構成 > 目次」「スタイルの使い方 > 目次」。

## 目的

- 特定の章・節の検索だけでなく、論文全体の構成を読者に示す。

## 配置

- **本文の直前**に置く（一般の著書と同様）。

## LaTeX（`kuisthesis`想定）の作り方

- `\tableofcontents` で生成
- 既定では `\section` / `\subsection` / `\subsubsection` が入る
- 目次に入れる深さは `tocdepth` で調整

例：`section` と `subsection` のみにする

```tex
\setcounter{tocdepth}{2}
\tableofcontents
```

## チェック

- 見出しの粒度が不自然に細かすぎない（`subsubsection` を多用しすぎない）
- 章題が内容を反映している（後から見直しても迷わない）

