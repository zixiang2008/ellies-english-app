<!-- multilingual-project-guide:start -->
<p align="center">
  <strong>Multilingual project guide</strong><br>
  <a href="PROJECT_GUIDE.md#简体中文">简体中文</a> ·
  <a href="PROJECT_GUIDE.md#english">English</a> ·
  <a href="PROJECT_GUIDE.md#日本語">日本語</a> ·
  <a href="PROJECT_GUIDE.md#ภาษาไทย">ภาษาไทย</a>
</p>
<!-- multilingual-project-guide:end -->

# Ellie's English · 逐句精听英语学习工具

A free, offline-first macOS app for **intensive listening** practice in English.
Drop in any audio (or paste a podcast link), and it splits the audio sentence by
sentence, transcribes it locally, adds Chinese translations, and lets you look up
any word with one click.

一款**免费**的 Mac 精听工具：把音频逐句拆分、本机离线识别英文、自动配上中文翻译，
点任意单词即弹出词典。所有识别与查词都在本机进行，无需联网。

> Free / 公益软件。Made by [Shengqiao Lin](https://shengqiaolin.com).

---

## Download / 下载

**[⬇︎ Download the latest release](../../releases/latest)**

- **Requirements / 系统要求:** Apple Silicon Mac (M1/M2/M3/M4 or newer), macOS 12+
- The app is **not** paid-signed by Apple, so macOS will warn you the first time.
  This is expected — see *First launch* below.

## First launch / 第一次打开

Because the app isn't notarized, macOS blocks it the first time. Any one of these works:

1. **Recommended:** double-click the app → click **Done** on the warning (do *not* move
   to Trash) → open **System Settings → Privacy & Security**, scroll down, find
   *"Ellie's English was blocked"*, click **Open Anyway** → confirm.
2. In the Applications folder, **right-click** (or Control-click) the icon → **Open** → **Open**.
3. If it says *"damaged"*, open **Terminal** and run:
   ```
   xattr -cr "/Applications/Ellie's English.app"
   ```
   then open it normally.

## What it does / 功能

- **Import:** drag in MP3 / m4a / wav, or paste an MP3 direct link, Apple Podcasts /
  小宇宙 episode link, or a podcast RSS feed. 音频由你自己提供或粘贴链接导入。
- **Sentence-by-sentence:** automatic segmentation + English transcription, done
  **entirely on-device** (takes seconds).
- **Click any word** for an instant dictionary (IPA, definitions, exam tags); save it
  to your notebook.
- **Chinese translation** appears under each line (the only feature that uses the
  network; playback and transcription work fully offline).
- Loop a sentence (3 / 5 / ∞), adjust speed (0.5×–1.5×), hide the English or Chinese
  subtitle for pure listening, star sentences, and export sentences + notes to
  `.md` / `.txt`.

## Privacy / 隐私

Speech recognition and the dictionary are **fully offline**. Only translation calls
the network. Your audio, subtitles, and notes stay on your machine at
`~/Library/Application Support/ellies-english/`.

## License / 许可

Free to download and use. This repository distributes the macOS build only.
