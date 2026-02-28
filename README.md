# video_converter
This tool is a Windows batch video conversion application created through dialogue with AI.

English

This tool is a batch video conversion application for Windows created through interaction with Google's AI, Gemini.
It includes FFmpeg and can convert major video file formats such as mp4, mkv, mov, avi, and webm.
During development, we implemented thorough defect fixes and enhanced robustness, including AI-driven automatic support for GPU encoding (NVENC/QSV), crash prevention with Japanese paths, and elimination of orphaned processes. Simply select a preset prioritizing quality preservation or file size, and anyone can achieve optimal results. This highly practical tool combines the precision of AI logic with the versatility of FFmpeg.

日本語

AI（Gemini）との対話を通じて作成した、Windows向けのシンプルな一括動画変換ツールです。
自分自身が使いやすいと感じる機能と、安定した動作を目指して開発しました。

## 💡 特徴

* **設定不要**: 動画変換エンジン「FFmpeg」を本体に同梱しているため、ダウンロードしてすぐに使い始めることができます。
* **AIとの共同開発**: ソースコードの設計、エラーの修正、Windows環境での安定性向上（GPU活用など）において、AI（Gemini）のアドバイスを全面的に採用しています。
* **一括処理に対応**: 複数の動画をまとめてリストに入れ、一度に変換することが可能です

## 📂 対応している拡張子

以下の形式の読み込みと変換に対応しています。

* **入力可能な形式**: `.mp4`, `.mkv`, `.avi`, `.mov`, `.wmv`, `.flv`, `.webm`, `.m4v` など
* **出力可能な形式**: `.mp4`, `.mkv`, `.mov`, `.avi`, `.webm`

## 🛠 使い方

1. Releasesページから最新の `exe` ファイルをダウンロードします。
2. アプリを起動し、「動画ファイルを選択」ボタンからファイルを選びます。
3. 出力形式と、用途に合わせた変換モード（画質や速度の優先度）を選択します。
4. 「一括変換を開始」を押すと処理が始まります。

## 🤖 AIによる制作プロセスについて

本ツールは、個人開発者がAI（Gemini 3 Flash）に対して機能の要望を伝え、それに対するAIのコード提案とデバッグを繰り返すことで完成しました。

* FFmpegの効率的な呼び出し
* 日本語ファイル名によるエラーの回避
* プログレスバー（進捗表示）の正確な反映
など、細かな処理の多くにAIの知見を活用しています。

## ⚖ 免責事項

本ツールは個人の学習および利便性のために作成されたフリーソフトです。

1. **自己責任での利用**: 本ツールの利用によって生じたデータの損失やPCの不具合等について、制作者は一切の責任を負いかねます。大切なデータは必ずバックアップを取ってからご使用ください。
2. **動作の保証**: すべての環境や動画ファイルでの完全な動作を保証するものではありません。
3. **外部ライブラリ**: 本ツールはFFmpeg（LGPL v2.1/v3.0ライセンス等）を利用しています。
4. **非商用推奨**: 本ソフトは実験的プロジェクトとして作成されており、重要な業務等での利用には十分なテストを行った上で、自己責任でご使用ください。

---

*Created by a Human Developer with the assistance of Gemini (AI).*

---
