# signal-processing-interactive-tools

信号処理のインタラクティブ教材集（HTML + JavaScript）

## 教材一覧

| #  | 教材名 | 内容 | ファイル |
| --- | --- | --- | --- |
| 01 | フーリエ級数の積み上げ | 方形波・三角波・鋸歯状波を高調波の和で近似 | `dsp_fourier_series.html` |
| 02 | 複素フーリエ級数と回転ベクトル | 正負の周波数で回る回転ベクトルの合成による実数波形 | `dsp_complex_fourier.html` |
| 03 | サンプリング定理とエイリアシング | サンプリング周波数 100 Hz 固定での折り返し（波形・周波数軸・音） | `dsp_aliasing.html` |
| 04 | 量子化とビット数 | 量子化ビット数（1〜16 bit）と量子化ステップ | `dsp_quantization.html` |
| 05 | 畳み込み和（離散時間） | `y[n] = Σ x[k] h[n−k]` を1ステップずつ計算 | `dsp_convolution.html` |
| 06 | 移動平均フィルタの周波数特性 | タップ数 M とインパルス応答・周波数特性 | `dsp_movavg.html` |
| 07 | z平面の極と応答 | 極の絶対値 \|p\| と偏角 θ による応答の変化 | `dsp_zplane.html` |
| 08 | 窓関数とスペクトル漏れ | 矩形・ハニング・ハミング・ブラックマン窓の比較（N = 256） | `dsp_window.html` |
| 09 | 不規則信号の統計量 | 有限個のデータから求めた平均・分散のばらつき | `dsp_statistics.html` |
| 10 | 相関関数による信号の検出 | 自己相関による周期検出，相互相関による遅れの推定 | `dsp_correlation.html` |
| 11 | ピリオドグラムとWelchの方法 | 分割数 K による平均化とスペクトル推定のトレードオフ | `dsp_welch.html` |

## GitHub Pages URL

以下のURLでアクセスできます：

```
https://hiroshi-okajima.github.io/signal-processing-interactive-tools/
```

各教材への直リンク：

- [フーリエ級数](https://hiroshi-okajima.github.io/signal-processing-interactive-tools/dsp_fourier_series.html)
- [複素フーリエ級数](https://hiroshi-okajima.github.io/signal-processing-interactive-tools/dsp_complex_fourier.html)
- [サンプリング定理とエイリアシング](https://hiroshi-okajima.github.io/signal-processing-interactive-tools/dsp_aliasing.html)
- [量子化とビット数](https://hiroshi-okajima.github.io/signal-processing-interactive-tools/dsp_quantization.html)
- [畳み込み和](https://hiroshi-okajima.github.io/signal-processing-interactive-tools/dsp_convolution.html)
- [移動平均フィルタ](https://hiroshi-okajima.github.io/signal-processing-interactive-tools/dsp_movavg.html)
- [z平面の極と応答](https://hiroshi-okajima.github.io/signal-processing-interactive-tools/dsp_zplane.html)
- [窓関数とスペクトル漏れ](https://hiroshi-okajima.github.io/signal-processing-interactive-tools/dsp_window.html)
- [不規則信号の統計量](https://hiroshi-okajima.github.io/signal-processing-interactive-tools/dsp_statistics.html)
- [相関関数による信号の検出](https://hiroshi-okajima.github.io/signal-processing-interactive-tools/dsp_correlation.html)
- [ピリオドグラムとWelchの方法](https://hiroshi-okajima.github.io/signal-processing-interactive-tools/dsp_welch.html)

## 使い方

### GitHub Pages で公開

1. Settings → Pages → Source を `main` ブランチ `/（root）`に設定
2. 数分後に上記URLで公開されます

### はてなブログへの埋め込み

```
<iframe src="https://hiroshi-okajima.github.io/signal-processing-interactive-tools/dsp_aliasing.html"
  width="100%" height="800" frameborder="0" style="border:1px solid #ddd; border-radius:8px;"></iframe>
```

### Moodle・Google Sites

- Moodle: HTMLファイルをリソースとして直接アップロード、またはURLリンク
- Google Sites: 「埋め込み」→「埋め込みコード」でiframeを貼り付け

## 技術仕様

- 単一HTMLファイル（外部依存: CDN経由の Chart.js 4.4.1 と Google Fonts）
- JavaScript でリアルタイム計算
- 一部の教材は Web Audio API による音の再生に対応
- レスポンシブデザイン（PC・タブレット・スマートフォン対応）

## 関連リポジトリ

- [control-interactive-tools](https://github.com/Hiroshi-Okajima/control-interactive-tools)：制御工学のインタラクティブ教材集

<!-- ライセンス決定後に License セクションを追記 -->

## Author

岡島 寛（熊本大学 工学部 情報電気工学科 准教授）

- Web: <https://www.control-theory.com>
- Blog: <https://blog.control-theory.com>
- YouTube: <https://www.youtube.com/@ControlEngineeringChannel>
