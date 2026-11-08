<p align="center"><a href="README.md">English</a> · <b>日本語</b></p>

<h1 align="center">Constellations</h1>

<p align="center"><b>After Effects の中に、本物の夜空を。</b></p>

<p align="center">
  <a href="https://sensemv.gumroad.com/l/constellations"><img src="https://img.shields.io/badge/Gumroad%E3%81%A7%E8%B3%BC%E5%85%A5-FF90E8?style=for-the-badge&logo=gumroad&logoColor=black" alt="Gumroadで購入"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0-7EA1F1?style=flat-square" alt="Version 1.0">
  <img src="https://img.shields.io/badge/After%20Effects-2024%2B-9999FF?style=flat-square&logo=adobeaftereffects&logoColor=white" alt="After Effects 2024+">
  <img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=flat-square" alt="Windows 10 | 11">
  <img src="https://img.shields.io/badge/macOS-beta-lightgrey?style=flat-square&logo=apple" alt="macOS beta">
</p>

![天の川を背景にした星座](assets/constellations.png)

星座を描く、星空を作る、オーロラを動かす。Constellations は、実在する 88 星座と 5,045 個の星をひとつのエフェクトにまとめ、見た目・アニメーション・カメラをまとめてコントロールできるプラグインです。

<p align="center">
  <a href="https://sensemv.gumroad.com/l/constellations"><b>購入する</b></a> ·
  <a href="#クイックスタート">クイックスタート</a> ·
  <a href="#動作環境">動作環境</a> ·
  <a href="https://github.com/SonArtyom/Constellations-Plugin/issues">不具合を報告</a>
</p>

## 星図からイラストまで

ひとつの星座、黄道十二星座、または全天から選べます。星の位置・明るさ・色は実際のデータに基づいています。そのままのリアルな見た目で使うことも、形・色・線を変えて作品に合わせることもできます。

8 種類のプリセットから始めて、それぞれ自由に調整できます。

| Night Blue Sparkle | Flat Star Connectors |
| :---: | :---: |
| ![青い星と細い線](assets/night-blue-sparkle.png) | ![白い星をつなぐ線](assets/flat-star-connectors.png) |
| **Golden Flat Stars** | **Blueprint Dashes** |
| ![金色の星](assets/golden-flat-stars.png) | ![シアンの星と破線](assets/blueprint-dashes.png) |
| **Neon Glow** | **Minimal Dots** |
| ![ピンクの輝きとシアンの線](assets/neon-glow.png) | ![小さな点と細い線](assets/minimal-dots.png) |
| **Realistic Sky** | **Flat Illustration** |
| ![自然な星の色と大きさ](assets/realistic-sky.png) | ![青地に金色のフラットな星](assets/flat-illustration.png) |

## 線を描いていくアニメーション

**Lines Progress** を 0% から 100% までアニメーションさせると、星座の線が順番に描かれ、線が届いたところで星が現れます。描く順番・重なり・イージングを変えたり、**Stars Progress** で星だけを別にアニメーションさせることもできます。

| 25% | 50% | 75% | 100% |
| :---: | :---: | :---: | :---: |
| ![25%](assets/build-25.png) | ![50%](assets/build-50.png) | ![75%](assets/build-75.png) | ![100%](assets/build-100.png) |

常に動きをつけたいときは、瞬き（twinkle）・脈動（pulse）・浮遊（float）・揺れ（wobble）・空の流れ（sky drift）を追加できます。線にはテーパー、アニメーションする破線、トリムパスも使えます。

## 星座のまわりに空を作る

天の川、星雲、渦巻銀河、オーロラを追加できます。それぞれに専用のコントロールと動きが用意されています。

| 天の川 | 星雲 |
| :---: | :---: |
| ![天の川](assets/milky-way.png) | ![星雲](assets/nebula.png) |
| **渦巻銀河** | **オーロラ** |
| ![渦巻銀河](assets/spiral-galaxy.png) | ![青緑と紫のオーロラ](assets/aurora.png) |

エフェクトはコンポジションのカメラに追従できます。星座・背景の星・銀河・オーロラにそれぞれ別の奥行きを設定すると、カメラの動きに合わせて視差（パララックス）が生まれます。エフェクトは **2D の平面レイヤー** に適用してください。カメラはエフェクト側で読み取ります。

## 購入

Constellations は **[Gumroad](https://sensemv.gumroad.com/l/constellations)** で販売しています。購入すると、Windows 用インストーラー、macOS ベータ版、ユーザーガイド（英語・日本語）、ライセンスキーが届きます。1.x のアップデートはすべて無料です。

ライセンスキーを有効化するまでは、ウォーターマーク付きでレンダリングされます。有効化は **エフェクトコントロール → オプション** から行えます。

## クイックスタート

1. [Constellations を購入](https://sensemv.gumroad.com/l/constellations)し、After Effects を終了してから、ダウンロードしたインストーラーを実行します。After Effects のバージョンを選んでインストールを完了し、After Effects を再起動します。
2. コンポジションと同じサイズの平面レイヤーを作成します。
3. **エフェクト → Sky → Constellations** を適用します。透明な背景にオリオン座が表示されます。
4. **Look Preset** を選び、星座を選択します。
5. **Lines Progress** に **0%** から **100%** までキーフレームを打ちます。

細かい調整の前にプリセットを選んでください。プリセットを変更すると、星・線・グローなどのスタイル設定が置き換わります。星座、表示範囲、Progress のキーフレーム、銀河、オーロラ、カメラの設定はそのまま残ります。

## 動作環境

| | |
| --- | --- |
| **After Effects** | 2024 以降（24.5 と 26.3 で動作確認済み） |
| **Windows** | Windows 10 / 11（64 ビット） |
| **macOS** | ベータ版：macOS 11 以降、Apple Silicon / Intel。実機の Mac 版 After Effects ではまだ未検証です。 |
| **色深度** | 8 / 16 / 32 bpc |
| **レンダリング** | CPU レンダリング、マルチフレームレンダリング対応。GPU 不要 |
| **出力** | 透明、元のレイヤー、または単色背景 |

プレビューを速くしたいときは、解像度を 1/2 または 1/4 にしてください。銀河とオーロラが最も重い要素です。

## サポート

プラグインに付属のユーザーガイドで、インストール、プリセット、アニメーション、カメラ設定、すべてのパラメーターを解説しています。

不具合や機能のリクエストは [Issue を作成](https://github.com/SonArtyom/Constellations-Plugin/issues)してください（日本語で大丈夫です）。プラグインのバージョン、After Effects のバージョン、OS、再現手順を書いていただけると助かります。エフェクト設定のスクリーンショットもあると便利です。ライセンスキー、注文情報、非公開のプロジェクトファイルは公開の Issue に載せないでください。

購入・ダウンロード・ライセンスに関するお問い合わせは、[Gumroad](https://sensemv.gumroad.com/l/constellations) からご連絡ください。

このリポジトリには製品の紹介、プレビュー画像、クイックスタートのみが含まれています。Constellations は有料のプラグインで、ソースコードとインストーラーはここでは配布していません。

---

制作：**sense**。プレビュー画像は Constellations 1.0 ユーザーガイドからのものです。

星・星座・天の川のデータ：**d3-celestial（Olaf Frohn）**、BSD 3-Clause License に基づいて使用しています。ライセンス全文はプラグイン付属のユーザーガイドに記載しています。

Constellations © 2026 sense. Adobe および After Effects は Adobe の商標です。
