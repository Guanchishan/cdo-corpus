# Eastern Min corpus / 閩東語語料庫

本倉庫公開展示，旨在便利學術研究、語料整理、社群協作與版本追蹤。公開展示不代表本倉庫內的文本、標註、音頻、元資料或其他材料已被授予自由取用、複製、再散布、改作、商業使用、模型訓練、資料庫整合或其他二次利用之權利。

除非另有明確書面授權，任何個人或機構如欲將本倉庫之資料用於自己的項目、產品、研究資料集、語言資源、輸入法、詞典、語音技術、機器學習 / AI 訓練、公開發布內容或其他衍生作品，均須事先與藍尾星小組聯絡並取得許可。

請勿將本倉庫的公開狀態理解爲「可任意取用」或「放棄權利」。未經許可使用、搬運、重發布、改編或整合本倉庫資料者，我們保留追究其責任及要求停止使用、刪除資料、補正署名或作出其他處理之權利。

This repository is publicly accessible for research, corpus maintenance, community collaboration, and version tracking. Public access does not mean that the texts, annotations, audio files, metadata, or other materials in this repository are freely licensed for copying, redistribution, modification, commercial use, model training, dataset integration, or other forms of reuse.

Unless explicitly authorized in writing, any individual or organization wishing to use materials from this repository in their own project, product, research dataset, language resource, input method, dictionary, speech technology, machine-learning / AI training pipeline, public release, or other derivative work must contact Nang-muoi-sing and obtain permission in advance.

Do not interpret the public availability of this repository as permission for unrestricted use. Nang-muoi-sing reserves the right to request cessation of use, removal of copied materials, correction of attribution, or other appropriate remedies for unauthorized use.

詳見 [Wiki](https://github.com/Nang-muoi-sing/cdo-corpus/wiki)。

Visit our [Wiki page](https://github.com/Nang-muoi-sing/cdo-corpus/wiki) for more information.

## Directory tree 目錄結構

### Plaintext 純文本語料

- `/plaintext` 純文本語料的母目錄，下含語句、詩歌、文章、書籍等類。
  - `/.../word-alignment` 以XML格式標註、精度爲詞的純文本語料。

### Spoken corpus 有聲語料

- `/essay` 朗讀文章。
- `/music` 歌曲。
- `/opera` 戲曲。請參閱[相關工作流](https://github.com/Nang-muoi-sing/cdo-corpus/projects/3)。
  - `/.../Min opera` 閩劇（包括其選段）。
- `/poem` 詩歌、謠讖。
- `/video` 影片。請參閱[相關工作流](https://github.com/Nang-muoi-sing/cdo-corpus/projects/1)。
- `/sentences` 語句。請參閱[句料分類規範](https://github.com/Nang-muoi-sing/cdo-corpus/wiki/Info-of-Sentences-%E5%8F%A5%E6%96%99%E8%B3%87%E8%A8%8A)。
  - `/.../info.tsv` 語料信息表。查閱、編輯前應看此表，以瞭解語料的整理、標註狀態。
  - `/.../template.etf` ELAN模板。

純文本、有聲語料目錄，除`/sentences`以外，會以語料狀態各設不同的子文件夾：

文件夾名 | 含義
-- | --
Machine-unreadable | 暫未整理出機器可讀的文本。
Working on sentence alignment (cdo) | 正在整理句對齊的閩東語文本。
Sentence-aligned (cdo) | 具備已經句對齊的閩東語文本。
Sentence-aligned (cdo, cmn) | 具備已經句對齊的原語爲閩東語、譯語爲官話的文本。
Sentence-aligned (cmn, cdo) | 具備已經句對齊的原語爲官話、譯語爲閩東語的文本。

### Other 其他材料

- `/audio` 擬用於榕典的音頻文件。請參閱[相關工作流](https://github.com/Nang-muoi-sing/cdo-corpus/projects/4)。
  - `/.../audio contrib` 用戶貢獻詞彙的音頻文件。
    - `/.../Audio Source.tsv` 音頻信息。
  - `/.../audio contrib sentences` 用戶貢獻詞彙的例句音頻文件。
  - `/.../audio feng` 具備Zingzeu ID的馮愛珍版《福州方言詞典》詞彙音頻。
    - `/.../Audio Prepared for Yng Dieng` 音頻信息。
  - `/.../audio li` 具備Zingzeu ID的李如龍版《福州方言詞典》詞彙音頻。
    - `/.../Audio Prepared for Yng Dieng` 音頻信息。
- `/timing` 記錄志願者的標記工作時長，以資安排任務之參考。
