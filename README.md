# ✨ neon-aiart.github.io

Official portal for the world-first "Gemini Voice" project: AI-driven RVC bug fix enabling **Direct Transfer** for voice conversion UserScript by neon-aiart.

---

# 🎌 【世界初/RVC修正】AIartクリエイターねおんが実現した究極の音声対話「Gemini to VOICEVOX and RVC」

## AI協調開発の究極の成功事例
Pythonの知識ゼロのAIartクリエイターが、AI（Gemini）と協力して**VOICEVOX/RVCの連携**を実現。RVC本体の核心バグを修正し、**制限なしで好きな音声モデルでの会話**を可能にした、世界初のプロジェクトです。

---

## 💡 問題の提起と解決の動機

### 1. 究極のUXの追求
ねおんの目標は、「**Geminiの回答を、VOICEVOX経由で好きな音声モデル（RVC）で、制限なしで読み上げてほしい**」という、**シームレスな体験**の追求でした。

### 2. 誰も超えられなかった技術の壁
RVCのAPIは存在しましたが、**ある形式のデータ**を送ると必ずエラーになるという**深刻なバグ**が本体コードに存在していました。

**このRVC本体のバグこそが、好きな音声モデルでのダイレクトなAI会話という、理想のUX実現を妨げていた技術の壁だったのです。**

---

## ✅ 成果物とダウンロード：究極のUXを今すぐ体験

このシステムは、以下の２つのファイルをセットで使うことで実現されます。

### 1. UserScript本体 (Gemini to VOICEVOX and RVC)
* **機能:** GeminiのUIを解析し、回答を抽出し、**VOICEVOX**（日本語音声合成）へ、そして**RVC**へデータを**直接転送**します。
* **ライセンス:** **CC BY-NC 4.0 (非営利目的での利用のみ)**
* **[✨ GreasyForkでインストールする (geminiVoice) ✨](https://greasyfork.org/ja/scripts/552996-gemini-to-voicevox)** （準備中）

### 2. RVC修正Pythonファイル
* **機能:** **ダイレクト転送**を可能にするRVC本体の修正コードです。ファイルI/Oによるムダな転送時間をゼロにしました。
* **ライセンス:** **MITライセンス (RVC本体のライセンスに準拠)**
* **ダウンロード:** （準備中）
    * [→ modules.py](modules.py) : `\RVC\infer\modules\vc\modules.py`
    * [→ audio.py](audio.py) : `\RVC\infer\lib\audio.py`
    * [→ infer-web.py](infer-web.py) : `\RVC\infer-web.py`
    * *※ RVCのインストールフォルダにある既存のファイルをこれらのパスに上書きしてください。詳細は[技術の詳細ページ](/details)をご覧ください。*

---

## 📢 技術の詳細（プログラマー向け）

このRVCバグ修正の裏側と、Geminiとの**協調開発の全プロセス**については、**コード公開と同時**に、こちらのページで詳しく解説します。

**[→ 協調開発の物語と技術的詳細を見る (別ページへ)](/details)** （準備中）
