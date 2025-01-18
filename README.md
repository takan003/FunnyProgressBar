![Funny Progress Bar](https://www.php-pie.net/images/gas/funnyprogressbar/FunnyProgressBar.png "Funny Progress Bar")

# Features 特色
1. No installations, no bloatware, no updates; this works in any modern browser, including Google Chrome, Firefox, Edge and Safari.  
不需要安裝，不需要外掛，不用升級，適用於最新版本的各種瀏覽器。
2. It allows you to easily change boring progress percentage numbers into interesting, funny image progress bars, which can add fun to your work and enhance the competitive enthusiasm of your users.  
讓您輕鬆地將無聊的進度百分比數字，改成有趣的圖像方式呈現，為您增添工作中的樂趣，也能提升使用對象的競爭熱情。
4. Write simple spreadsheet formulas into cells and apply them to other spreadsheets at any time. No programming knowledge is required.  
用簡易的試算表公式寫入儲存格中，讓您隨時可以套用到其他的試算表，完全不需要程式基礎就能使用。

# Make a Copy 建立副本使用
👉 English version[[Make a Copy](https://docs.google.com/spreadsheets/d/18Adn7nXFnbpVHl_NETAiH9hMYfjmQQvhxtJCEVFNhPQ/copy)][[View Files](https://drive.google.com/drive/folders/10z-uKn4Jczw94kSq-AFHymvMQYKf98-0?usp=sharing)] 👉 中文版本[[建立副本](https://docs.google.com/spreadsheets/d/1FTw_B4OYP1RyF-9w5cmKq7-E1qNijhZkAZPZBgLmiIg/copy)][[瀏覽檔案](https://drive.google.com/drive/folders/1YIvsr2Sa7dYaCIXt7ZTavFk0VcI3NotZ?usp=sharing)] 

# Manual 使用介紹
👉 [English version](#english-version) 👉 [中文版本](#中文版本使用介紹)

# Visit & Sponsor 參觀與贊助
Welcome to my website [Gas Station](https://script.google.com/a/macros/gms.hlgs.hlc.edu.tw/s/AKfycbzS29sVfv6vUKcXY8zhHl8XZKU52VfvjxzqeEQACrAufS7JiWOexlIYgyfgtCusAVJt/exec "GAS Station"), there may be some tools, programs, or even inspiration that can help you. We are more than happy to accept your [sponsor](https://p.ecpay.com.tw/36FF207 "sponsor")ship if you wish.❤️  
歡迎參觀我的網站 [Gas Station](https://script.google.com/a/macros/gms.hlgs.hlc.edu.tw/s/AKfycbzS29sVfv6vUKcXY8zhHl8XZKU52VfvjxzqeEQACrAufS7JiWOexlIYgyfgtCusAVJt/exec "GAS Station")，裡頭也許會有一些能幫助您的工具、程式，甚至是提供您創意的靈感。如果您願意的話，也非常樂意接受您的[打賞](https://p.ecpay.com.tw/36FF207 "打賞")。❤️  
Copyright (c) 2025 Chang, Chia-Cheng 張家誠

# English version
## Quick preview
### Make a copy
Please be sure to use the "Make a copy" method to copy the file to your cloud drive. The file can be renamed at will.  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_e_01.gif" alt="Make a copy。" title="Make a copy" />

### Authorized
The program will access files in your cloud drive when it is executed, so please authorize the use of your cloud drive when you execute it for the first time.  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_e_02.png" alt="Authorized" title="Authorized" />

### Necessary settings
To execute this program, you need 1 designated sheet and 2 corresponding fields, as shown in the figure below:  
1. Specify a sheet "Attend investigation" (custom name) and create a sheet with this name in the spreadsheet.  
2. Assume that the reply collection unit is "Class" (custom name), so the "rightmost column" in the "Attend investigation" sheet is named "class".  
3. The progress of each class's collection has a "Percentage" (custom name), so there needs to be a column named "Percentage" in the "Attend investigation" sheet.  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_e_02-5.png" alt="you need 1 designated sheet and 2 corresponding fields" title="you need 1 designated sheet and 2 corresponding fields" />

### "Icon" progress bar
After confirming that the necessary settings have been completed, try the example immediately. Display mode "icon" and try the progress bar direction left and right. Just use the "Create progress bar" in the "Advanced function" menu, and One-click completion.  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_e_03.gif" alt="Icon progress bar" title="Icon progress bar" />

### "Continuous Picture" progress bar Mode A
Mode A: Prepare a picture file and let each class be the progress bar picture to add fun to the competition. With following picture to explain the points:  
1. In the "Setup" sheet, select "Continuous Picture" in the "Display Mode" field and select "Yes" in the "All groups use one CP" field.  
2. Use cutting software or website to cut the image into 10 equal parts and put them into the "OnlyOne" folder. Please name the image file with numbers 1 to 10.  
3. Use the "Make Bars" in the "Advanced" menu to complete it with one click. (Due to security, your authorization will be requested when you reference the image file for the first time. It can only be displayed normally after authorization is granted)  
4. The image will be automatically scaled according to the cell size. Please adjust the cell column width or row height to achieve the best stitching effect.  
5. The image file cannot be directly placed in the storage cell, so first use the IMAGE function to import it into the storage cell (column O:X), and then use the formula to bring it into the progress bar (column E:N).  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_e_04.gif" alt="Continuous Picture progress bar Mode A" title="Continuous Picture progress bar Mode A" />

### "Continuous Picture" progress bar Mode B-1
Mode B-1: Prepare 3 pictures and let each class use the progress to piece together their own pictures to see who can complete their own first, adding to the fun of progress competition.  With following picture to explain the points:  
1. In the "Setup" sheet, select "Continuous Picture" in the "Display Mode" field and select "No" in the "All groups use one CP" field.  
2. Use cutting software or website to cut the 3 images into 10 equal parts, and put them into the folders of respective classes. Please name the files in each folder with numbers 1 to 10.   
3. According to the length and width of the continuous picture, provide an appropriate storage cell size (column width 50, row height 100), and use the "Make bars" in the "Advanced" menu to complete it with one click.  
4. In order to make the overall layout simple and clean, we will hide the O:X column in this example.  
The picture of the Three Graces is taken from the "[Art Learnings]([https://artlearnings.com/](https://artlearnings.com/2023/10/25/%E7%BE%8E%E6%83%A0%E4%B8%89%E5%A5%B3%E7%A5%9E%EF%BD%89%EF%BC%8E%E4%B8%8D%E5%90%8C%E8%97%9D%E8%A1%93%E5%AE%B6%E7%9C%BC%E4%B8%AD%E7%9A%84%E6%B0%B8%E6%81%86%E9%9D%88%E6%84%9F/)" website.
The picture of the Titanic is taken from the "[wikipedia](https://zh.wikipedia.org/zh-tw/%E6%B3%B0%E5%9D%A6%E5%B0%BC%E5%85%8B%E5%8F%B7)" website.  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_e_05.gif" alt="Continuous Picture progress bar Mode B-1" title="Continuous Picture progress bar Mode B-1" />

# 中文版本使用介紹
## 快速使用預覽
### 取得檔案
請務必使用「建立副本」的方式將檔案複製到您的雲端硬碟中，檔案可以任意重新命名。  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_c_01.gif" alt="請務必使用「建立副本」的方式將檔案複製到您的雲端硬碟中，檔案可以任意重新命名。" title="請務必使用「建立副本」的方式將檔案複製到您的雲端硬碟中，檔案可以任意重新命名。" />

### 授權使用
程式執行時會取用您雲端硬碟中的檔案，所以第1次執行時請先授權允許使用您的雲端硬碟。  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_c_02.png" alt="請先授權允許使用您的雲端硬碟" title="請先授權允許使用您的雲端硬碟" />

### 必要設定
執行這個程式，您需要1個指定的工作表以及2個對應的欄位，配合下圖分點說明：  
1. 指定1個工作表「回條繳交」(自訂名稱)，並以此名稱在試算表中建立工作表。  
2. 假設回條回收單位為「班級」(自訂名稱)，所以在「回條繳交」工作表中需要有一個『必須在最右邊的欄位』，名稱為「班級」。  
3. 每個班級回收的進度有一個「完成百分比」(自訂名稱)，所以在「回條繳交」工作表中需要有一個欄位名稱為「完成百分比」。  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_c_02-5.png" alt="一定要具備的1個工作表，2個欄位" title="一定要具備的1個工作表，2個欄位" />

### 製作「圖示」進度條
確認完成必要的設定之後，立刻以範例試玩看看，顯示模式「圖示」，進度條方向左、右各試一次，只要使用選單「進階功能」中的「製作進度條」，一鍵就能完成。  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_c_03-5.gif" alt="製作「圖示」進度條" title="製作「圖示」進度條" />

### 認識「圖示」進度條的公式
第1格=if(1/10<=百分比,if((2/10)>百分比,引用O欄顯示圖示,""),"")，第2格=if(2/10<百分比,if((3/10)>百分比,引用O欄顯示圖示,""),"")，...以此類推。  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_c_08.gif" alt="製作「圖示」進度條的公式" title="製作「圖示」進度條的公式" />

### 製作「連續圖」進度條 1
第1種方式：準備1個圖檔，讓每個班級用進度來拼接，增添進度競爭的樂趣，配合下圖分點說明：  
1. 在設定工作表的「顯示模式」選擇為「連續圖」，「共用一張連續圖」選擇為「是」。
2. 利用切割軟體或網站將圖檔切成10等分後放入「OnlyOne」的資料夾中，圖檔的檔案名稱請依序用數字1至10來命名。  
3. 使用選單「進階功能」中的「製作進度條」，一鍵就能完成。(因為安全性考量，第1次引用圖檔時會要求您的授權，允許授權後才能正常顯示)。  
4. 圖檔會受到儲存格大小影響而自動縮放，請調整儲存格的欄寬或列高來取得最好的拼接效果。  
5. 圖檔不能直接放進在儲存格中，所以先用IMAGE函式在後面引入儲存格裡(O:X欄)，再用公式帶入進度條之中(E:N欄)。  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_c_04.gif" alt="製作「連續圖」進度條 1" title="製作「連續圖」進度條 1" />

### 製作「連續圖」進度條 2-A
第2種方式：準備3張圖檔，讓每個班級用進度來各自拼接，看看誰能先完成自己的連環圖，增添進度競爭的樂趣，配合下圖分點說明：  
1. 在設定工作表的「顯示模式」選擇為「連續圖」，「共用一張連續圖」選擇為「否」。
2. 利用切割軟體或網站將3張圖檔切成10等分後，分別放入各自的資料夾，每個資料夾中的檔案名稱請依序用數字1至10來命名。   
3. 配合連續圖的長寬，提供適當的儲存格大小(欄寬50，列高100)後，使用選單「進階功能」中的「製作進度條」，一鍵就能完成。  
4. 為了讓整體版面在顯示上單純與乾淨，這次的範例我們將O:X欄隱藏。  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_c_05a.gif" alt="製作「連續圖」進度條 2-A" title="製作「連續圖」進度條 2-A" />

### 製作「連續圖」進度條 2-B
第2種方式：準備1張圖檔切割給每個班級用，全部的班級一起拼揭連續圖，增添進度競爭的樂趣，配合下圖分點說明：  
1. 在設定工作表的「顯示模式」選擇為「連續圖」，「共用一張連續圖」選擇為「否」。
2. 利用切割軟體或網站將1張圖檔切成每個班級10等分後，分別放入各自的資料夾，每個資料夾中的檔案名稱請依序用數字1至10來命名。   
3. 配合連續圖的長寬，提供適當的儲存格大小(欄寬84，列高44)後，使用選單「進階功能」中的「製作進度條」，一鍵就能完成。  
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_c_05-5.gif" alt="製作「連續圖」進度條 2-B" title="製作「連續圖」進度條 2-B" />
4. 只要將設定工作表「進度條方向」改為「右」，就能讓方向改成由左向右。
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_c_06.gif" alt="製作「連續圖」進度條 2-B 方向改成由左向右" title="製作「連續圖」進度條 2-B 方向改成由左向右" />

### 認識「連續圖」進度條 2 的公式
1. 第1格=if(1/10<百分比,引用O欄顯示第1張圖,"")，第2格=if(2/10<百分比,引用P欄顯示第2張圖,"")，...以此類推。
2. 為了讓整體版面在顯示上單純與乾淨，可以將O:X欄隱藏。
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_c_07.gif" alt="製作「連續圖」進度條 2 的公式" title="製作「連續圖」進度條 2 的公式" />

### 移除廣告
希望您能保留，如果不得已要移除，請在設定工作表的「移除廣告」欄位中輸入「張家誠，我金拍謝！」
<img src="https://www.php-pie.net/images/gas/funnyprogressbar/funnyprogressbar_c_09.gif" alt="移除廣告" title="移除廣告" />
