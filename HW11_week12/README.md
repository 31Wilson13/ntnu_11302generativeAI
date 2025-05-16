# 作業十一（第十二周作業）
## 作業內容 : AI 圖像生成創作任務：打造 Fooocus Workflow 
### 程式：
- 名稱：Fooocus 
- 簡介：生成式圖像平台，內含各種設定與風格可供選擇，同時也提供image input功能

### 本次目標：
- 使用Fooocus創造出一位卡通角色，並為該角色發行各種不同的周邊商品


-------------------------


### 主角介紹：
- 名字：Sparkle
- 年齡： 8 歲
- 出身地： Pixelberry Town
- 角色背景介紹：Sparkle是一位活力四射的小太陽，擁有無限的想像力和停不下來的冒險精神。她出生在Pixelberry Town，她的招牌是小小的身軀卻頂著一頭亮麗且引人注目的金髮，配上一對水汪汪的大眼睛。Sparkle相信，只要有閃亮亮的創意、一顆開朗的心，還有一點點餅乾，就沒有解決不了的難題！

![圖片](https://github.com/31Wilson13/ntnu_11302generativeAI/blob/main/HW11_week12/item1.png)

- Fooocus生成說明：
  - Text Prompt：A cute and energetic little cartoon girl with golden blonde hair, big expressive eyes, a cheerful smile, and a playful pose. She wears a colorful and stylish outfit with whimsical accessories, designed in a vibrant anime-inspired style. The character has a charming and unique look, with soft lighting and a clean background. Her design is suitable for merchandising such as plush toys, stationery, and keychains. The overall style is lively, friendly, and slightly fantastical, with a touch of virtual charm.
  - Styles：Fooocus Enhance、Fooocus V2、Fooocus Sharp

-------------------------
### 周邊商品

 1. Sparkle造型貼紙三入組
 - 商品介紹 : 一起踏上冒險吧！這款Sparkle貼紙三入組，收錄三款不同造型的Sparkle，每一張都充滿活力與童趣，超適合貼在筆記本、手機殼或你的日常驚喜小物上！

  ![圖片](https://github.com/31Wilson13/ntnu_11302generativeAI/blob/main/HW11_week12/item2.png)

- Fooocus生成說明：
  - Text Prompt：three stickers  of the character from the image prompt, every sticker has its own unique pose and style
  - Image Prompt：上方角色照片（Weight：0.6、Stop at：0.5）
  - Styles：Sticker Designs

 2. Sparkle造型T-Shirt
 - 商品介紹 : 穿上陽光女孩Sparkle造型服飾，讓每一天都充滿活力！這款純白T-shirt印有Sparkle的完整造型，色彩鮮明、風格可愛，無論是日常穿搭還是粉絲收藏，都超級亮眼！

  ![圖片](https://github.com/31Wilson13/ntnu_11302generativeAI/blob/main/HW11_week12/item3.png)

- Fooocus生成說明：
  - Text Prompt：A cute T-shirt featuring the character from the image prompt printed on the front.
  - Image Prompt：上方角色照片（Weight：0.6、Stop at：0.5）
  - Styles：Fooocus Enhance、Fooocus V2

 3. Sparkle聯名餅乾
 - 商品介紹 : 甜甜酥酥，冒險開啟！這款Sparkle聯名餅乾，外盒印有她的可愛身影，內含香脆可口的小餅乾，每一口都充滿童趣與想像力，是點心時間最閃亮的選擇！

  ![圖片](https://github.com/31Wilson13/ntnu_11302generativeAI/blob/main/HW11_week12/item4.png)

- Fooocus生成說明：
  - Text Prompt：A colorful cookie box with the character from the image prompt printed on the front, designed for retail packaging.
  - Image Prompt：上方角色照片（Weight：0.6、Stop at：0.5）
  - Styles：Fooocus Enhance、Ads Retail
 
  -------------------------
  ### Fooocus使用心得
  - 使用Image Prompt時，若使用過於複雜或詳細的Text Prompt，在我的嘗試中，新生成的圖像會和Image Prompt中的角色差距較大。因此在製作周邊商品時，採用的Text Prompt則選擇使用簡潔風格
  - 使用Image Prompt時，嘗試產生周邊商品圖片時，在advanced設定中，若將圖片的weight設定過高，生成的圖片永遠只會和Image Prompt相似，無法生成其他內容。因此後續選擇統一將weight設定大約0.6，在根據角色造型設計商品的同時，也讓模型帶有一些自由發揮的空間，如此一來才成功繪製出貼紙、短袖、餅乾包裝的內容
