# LLM_based_Customer_Intent_Understanding
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/SWhite4han/LLM_based_Customer_Intent_Understanding/blob/main/LLM.ipynb)

## 目標說明：
規劃銀行客服分析工具，運用STT+NLP/LLM模型完成客戶文字辨識，將客服語音經由數據分析後，產出客戶意圖與行銷名單運用

## 工具選用：

STT：[whisper](https://github.com/openai/whisper#available-models-and-languages)

|Size|Parameters|English-only model|Multilingual model|Required VRAM|Relative speed|
|----|----|----|----|----|----|
|tiny|39 M|tiny.en|tiny|~1 GB|~32x|
|base|74 M|base.en|base|~1 GB|~16x|
|<ul><li>- [x] small</li>|244 M|small.en|small|~2 GB|~6x|
|medium|769 M|medium.en|medium|~5 GB|~2x|
|large|1550 M|N/A|large|~10 GB|1x|

LLM：[Gemini pro](https://deepmind.google/technologies/gemini/#introduction)

- [ ] Gemini Ultra：最強大，適用高度複雜的任務
- [x] Gemini Pro：最通用
- [ ] Gemini Nano：可於行動裝置上運作

## 參數設置：
到[Google AI Studio](https://makersuite.google.com/app/apikey)取得API_KEY，免費仔每分鐘具有 60 次查詢額度

請於colab頁面左方設置取用API_KEY參數

![image](https://github.com/SWhite4han/LLM_based_Customer_Intent_Understanding/blob/main/src/images/API_KEY.PNG)

## 模擬數據：
[Click here to download](https://drive.google.com/drive/folders/1jPWk3mf_NvkubCNWWNZYust0bmrs5CiP?usp=sharing)

執行uploaded程式碼，上傳模擬數據檔案至colab

![image](https://github.com/SWhite4han/LLM_based_Customer_Intent_Understanding/blob/main/src/images/upload_tts_file.PNG)

Data generated by [TTSMaker](https://ttsmaker.com/)

## 架構設計：
![image](https://github.com/SWhite4han/LLM_based_Customer_Intent_Understanding/blob/main/src/images/%E6%9E%B6%E6%A7%8B%E5%9C%96.png)

註：藍色為本repo主要內容，黃色為模擬數據，淺灰色為未完成


