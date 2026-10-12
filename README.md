# Atlas Lab

Atlas Academy の重いラボ（仮想演習）を、自分の PC で動かすアプリです。ラボのダウンロード・起動・停止を、ボタンで行います。

対象のコース：Keycloak・LLM入門・OpenTelemetry・HTTP入門・GitOps・Redis・TLSと証明書（PKI）

## 入れ方

使い方の説明は、Atlas Academy の「手元のラボ」のページにあります。コースの演習の画面で「手元で起動（Atlas Lab）」を押すと、そこから案内します。

1. [Podman Desktop](https://podman-desktop.io/downloads)（無料）を入れます。ラボを動かす土台です。
2. [Releases](https://github.com/atlas-academy-jp/atlas-lab/releases/latest) から、お使いの PC 用の Atlas Lab をダウンロードして入れます。
   - Windows：`AtlasLab-Setup.exe`
   - Mac：`AtlasLab-mac.zip`（Intel と Apple Silicon の両方で動きます。ただし、Apple Silicon 向けのラボは準備中です）
   - Linux：`atlaslab-linux-amd64.tar.gz`（展開して `install.sh` を実行）
3. コースの演習の画面で「手元で起動（Atlas Lab）」を押します。

## 必要なもの

- Windows 10・11（64 ビット）か、Mac（macOS 13 以降）
- メモリ 16GB 以上（ラボに 8GB を使います）、ディスクの空き 30GB 以上
- Atlas Academy の Plus 以上のプラン

## 試験版の注意（署名の準備中）

いまの版は、まだ電子署名をしていません。そのため、初めて開くときに警告が出ます。

- **Windows**：「Windows によって PC が保護されました」と出たら、「詳細情報」→「実行」を押します。
- **Mac**：「開発元を確認できない」と出たら、「システム設定」→「プライバシーとセキュリティ」の下のほうにある「このまま開く」を押します。

ダウンロードしたファイルが本物かは、Releases の `SHA256SUMS` の値と比べて確かめられます。

## 提供

合同会社Flutters（Atlas Academy）
