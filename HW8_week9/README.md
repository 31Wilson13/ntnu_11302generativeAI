# 作業八（第九周作業） 
## 作業內容 : Reflection 任務設計(AI 漫才對話創作小工具)
🎤 漫才（Manzai）介紹： 漫才是日本傳統的雙人搞笑表演形式，通常由兩個角色組成：

  - ボケ（Boke）：負責講出荒謬、無厘頭或誇張的言論，製造笑點。

  - ツッコミ（Tsukkomi）：負責即時吐槽 Boke 的荒謬發言，以常識或無奈的角度回應，形成節奏感強烈的對話。

本任務透過大型語言模型（LLM），模擬 Boke 和 Tsukkomi 的互動，讓使用者輸入一個日常主題，即可自動生成一段完整且有趣的即興漫才對話。

**🎯 流程說明：**
使用者輸入一個日常主題（例如：今天中午吃了什麼）

1. model_boke 根據主題，生成第一段誇張、搞笑的 Boke 發言（風格荒謬、有趣）

2. model_tsukkomi 針對 Boke 的內容進行吐槽，指出荒謬之處並做出節奏明快的回應

3. model_boke 看到吐槽後，再次以 Boke 的身份做出更荒謬的反擊，讓對話升級更有層次

4. Gradio 呈現：三個欄位分別顯示：

    - 第一段 Boke 搞笑發言

    - Tsukkomi 的吐槽

    - Boke 的二次反擊
- 模型：llama-3.3-70b-versatile

## 系統截圖 : 
- 角色設定與說明文字
  ![圖片](https://github.com/31Wilson13/ntnu_11302generativeAI/blob/main/HW8_week9/setting.jpg)
- Gradio對話結果範例
  - 第一次測試（過於冗長版本） 
  ![圖片](https://github.com/31Wilson13/ntnu_11302generativeAI/blob/main/HW8_week9/example1.png)
  - 第二次測試（修正後簡潔版本）
  ![圖片](https://github.com/31Wilson13/ntnu_11302generativeAI/blob/main/HW8_week9/example2.png)
