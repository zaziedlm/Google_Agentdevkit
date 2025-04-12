# Google Agent Development Kit (ADK) Project

このプロジェクトは、[Google Agent Development Kit (ADK)](https://google.github.io/adk-docs/get-started/quickstart/) を基にしたエージェント開発のためのツールキットです。

## 概要

Google Agent Development Kit (ADK) を活用して、AIエージェントの開発と実行を簡略化します。このプロジェクトでは、ADKを使用して、独自のAIエージェントを作成・学習させるための基本的な構成とサンプルコードを提供します。

## 特徴

- **使いやすさ**: 初心者から上級者まで、誰でも簡単にエージェントを開発可能。
- **拡張性**: 必要に応じてカスタマイズ可能で、さまざまなユースケースに対応。
- **統合**: Googleのツールやサービスとのシームレスな統合。

## 必要条件

このプロジェクトを利用するには、以下が必要です：

- Python 3.8以上
- Poetry
- 必要なライブラリ（詳細は `pyproject.toml` をご確認ください）
- Google Cloud アカウント（ADKの一部機能を使用する場合）

## クイックスタート

1. **リポジトリのクローン**:
    ```bash
    git clone https://github.com/zaziedlm/Google_Agentdevkit.git
    cd Google_Agentdevkit
    ```

2. **依存パッケージのインストール**:
    ```bash
    poetry install
    ```

3. **設定ファイルの準備**:
    プロジェクトに必要な設定ファイルを作成してください（例: `.env` ファイル）。

4. **エージェントの実行**:
    以下のコマンドでエージェントを開始します。
    ```bash
    adk run multi_tool_agent
    ```
    そのほかの実行方法は、以下のQuickstart 4. Run Your Agent を参照ください  
   https://google.github.io/adk-docs/get-started/quickstart/#run-your-agent

## ライセンス

このプロジェクトは、[MITライセンス](LICENSE)の下で公開されています。

---

上記の内容を基に、必要に応じて変更や追加を行ってください。また、Quickstartの具体的な手順を含める際は、Googleのライセンスや利用規約に従い、適切に表記するようにしてください。
