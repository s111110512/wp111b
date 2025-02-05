# 1.前言
## 關於本書
本書旨在提供HTML入門者所需要的基礎知識，並包含了HTML標籤、元素、屬性和應用，以及HTML5的新特性。本書將通過實例來說明HTML的基礎，幫助讀者更好地理解HTML的應用和工作原理。
### HTML 的歷史
HTML是一種標記語言，用於描述網頁內容的結構和外觀。HTML最初由Tim Berners-Lee和他的同事在1989年開發出來，當時只有很基本的功能。隨著互聯網的發展，HTML也不斷演進，現在的HTML5已經成為了互聯網發展的標準之一。
### 為什麼要學習 HTML
在當今的數字化時代，網頁已成為了人們獲取信息和互相交流的主要途徑。了解HTML，可以讓你更好地編寫網頁，並掌握如何呈現和組織網頁內容。熟練掌握HTML，可以讓你更好地展示自己的技能和才華，並為網頁設計和開發做好準備。

# 2.HTML 的基礎
## HTML 是什麼
HTML（超文本標記語言）是一種用於描述網頁內容的標記語言。它使用標籤和屬性來描述網頁中的各種元素，例如文本、圖像、連結等。
## HTML 文件的結構
HTML文件通常由三部分組成：head、body和doctype聲明。doctype聲明用於定義HTML版本，head元素通常用於包含網頁的元數據，而body元素則包含網頁的主要內容。

### HTML 標籤和屬性
#### (1)HTML標籤
通常由一對標籤組成，其中包括開始標籤和結束標籤。開始標籤和結束標籤都是由尖括號包圍的，開始標籤以“<”開頭，結束並以“/”結尾，有些HTML標籤只有一個開始標籤，沒有對應的結束標籤。這些標籤通常被稱為空元素。例如，/img/標籤用於插入圖像，它沒有結束標籤。
#### (2)HTML屬性
用於定義標籤的附加信息，它們通常包含在開始標籤中。屬性有一個名稱和一個值，中間用等號隔開，大多數HTML標籤都有一些可用的屬性，可以用於控制標籤的行為和外觀。例如，/a/標籤用於定義超鏈接，它有一個href屬性用於指定要鏈接到的URL。還有其他許多標籤和屬性可供使用，可以根據需要選擇使用。

### 常用的 HTML 元素
#### (1)段落和標題
/p/：用於定義段落。
/h1/ 到 /h6/：用於定義標題，其中h1是最高級別的標題，h6是最低級別的標題。
#### (2)文本樣式
/strong/：用於強調文本，通常顯示為加粗。
/em/：用於斜體文本強調。
/u/：用於下劃線文本。
/s/：用於刪除線文本。
/sup/：用於上標。
/sub/：用於下標。
#### (3)列表
/ul/：用於定義無序列表。
/ol/：用於定義有序列表。
/li/：用於定義列表項。
#### (4)超鏈接和圖像
/a/：用於定義超鏈接。
/img/：用於插入圖像。
#### (5)表格
/table/：用於定義表格。
/tr/：用於定義表格行。
/th/：用於定義表格標題單元格。
/td/：用於定義表格數據單元格。
#### (6)表單
/form/：用於定義表單。
/input/：用於定義表單中的輸入字段，如文本框、單選按鈕、多選框等。
/select/：用於定義下拉列表框。
/option/：用於定義下拉列表框中的選項。
/button/：用於定義按鈕。
#### (7)其他
/div/：用於定義文檔中的區域或分段。
/span/：用於定義文本中的區域或分段。
/br/：用於插入換行符。
/hr/：用於插入水平線。
/iframe/：用於插入其他網頁或文檔的內嵌框架。
# 3.標題和段落
## 使用標題元素
在HTML中，標題元素用於定義文檔或章節的標題。HTML提供了6個標題元素，從h1到h6，h1是最高級別的標題，h6是最低級別的標題。通常，標題元素應按照結構嵌套，即h1只能包含h2，h2只能包含h3，以此類推。
## 使用段落元素
在HTML中，段落元素用於定義一個段落。可以在段落元素中放置文本，並且可以使用CSS來控制段落的外觀和排版。段落元素通常用於結構化文本，使其易於閱讀和理解。
文字格式化
/strong/：將文本加粗。
/em/：將文本斜體化，用於強調文本。
/u/：將文本下劃線化。
/s/：將文本加上刪除線。
/sup/：將文本
# 4.列表
## 有序列表
在HTML中，有序列表用/ol/標籤定義，列表項用/li/標籤定義。有序列表會在每個列表項前面加上一個編號。
## 無序列表
在HTML中，無序列表用/ul/標籤定義，列表項用/li/標籤定義。無序列表會在每個列表項前面加上一個點。
自定義列表
在HTML中，自定義列表用/dl/標籤定義，列表項用/dt/標籤定義，列表描述用/dd/標籤定義。自定義列表通常用於定義術語和其相應的定義。
# 5.圖片和連結
## 圖片元素
在HTML中，要在網頁上顯示圖片，可以使用/img/元素。/img/元素必須具有src屬性，該屬性指定圖片的URL。
## 連結元素
在HTML中，要在網頁上創建連結，可以使用/a/元素。/a/元素必須具有href屬性，該屬性指定鏈接的URL。
### 圖片和連結的屬性
#### (1)圖片的屬性
src：必須屬性，指定圖片的URL。
alt：可選屬性，指定圖片的替代文本。如果圖片無法顯示，替代文本會顯示在其位置上。
width：可選屬性，指定圖片的寬度。
height：可選屬性，指定圖片的高度。
#### (2)連結的屬性
href：必須屬性，指定鏈接的URL。
target：可選屬性，指定在哪個窗口中打開鏈接。如果值為_blank，則在新窗口中打開鏈接。
# 6.表格
## 創建表格
在HTML中，要創建表格，可以使用/table/元素。表格中的每行都使用/tr/元素定義，每列都使用/td/元素定義。
表格的行和列
在HTML中，表格的每行都使用/tr/元素定義，每列都使用/td/元素定義。可以使用/th/元素定義表格的表頭。
## 表格的屬性
表格元素/table/可以使用以下屬性：
border：指定表格的邊框寬度。
width：指定表格的寬度。
height：指定表格的高度。
cellspacing：指定單元格之間的間距。
cellpadding：指定單元格內容與單元格邊框之間的間距。
# 7.表單
## 創建表單
在HTML中，可以使用表單來收集使用者輸入的資料。要創建表單，可以使用/form/元素。表單中的輸入欄位可以使用多種元素來定義，例如/input/、/select/和/textarea/等。
## 表單元素
/input/：定義一個輸入欄位，可以使用type屬性指定輸入欄位的類型，例如文字輸入欄位、密碼輸入欄位、勾選方塊等。
/select/：定義一個下拉式選單。
/textarea/：定義一個文字區域，讓使用者輸入多行文字。
/label/：定義一個表單標籤，通常用於描述輸入欄位的用途。
/button/：定義一個按鈕，可以用於提交表單或執行其他操作。
## 表單的屬性
action：指定表單提交的URL。
method：指定提交表單時使用的HTTP方法，可以是GET或POST。
enctype：指定提交表單時使用的編碼方式，通常用於支持上傳文件。
name：指定表單的名稱。
target：指定表單提交後顯示回應的位置，可以是_self、_blank、_parent或_top。
autocomplete：指定表單是否啟用自動完成功能，可以是on或off。
novalidate：指定表單是否不進行驗證，通常用於自行處理表單驗證。
required：指定表單中的輸入欄位是否必填。
pattern：指定表單中的輸入欄位需要符合的正則表達式模式。
min、max、step：用於限制輸入欄位的最小值、最大值和增量。
readonly：指定表單中的輸入欄位是否為唯讀模式。
disabled：指定表單中的輸入欄位是否禁用。
size、maxlength：用於限制輸入欄位的長度和顯示寬度。
# 8.HTML5 新特性
## 語意化標籤
語意化標籤是指使用具有特定意義的HTML標籤來描述網頁內容的結構和含義，這樣可以讓搜索引擎更好地理解網頁內容，也方便屏幕閱讀器等輔助技術識別網頁結構，從而提高網頁的可訪問性和可搜尋性。
## 視頻和音頻
使用/video/和/audio/元素可以在HTML文檔中嵌入視頻和音頻文件。這些元素可以指定音頻或視頻文件的URL、標題、文本替代內容等信息。
## 地理位置
使用/map/和/area/元素可以在HTML文檔中定義圖像地圖。/map/元素指定一個圖像地圖，而/area/元素定義圖像地圖上的區域，並指定與該區域相關聯的URL或JavaScript操作。
## Web 存儲
Cookie：是一種在用戶計算機中存儲數據的小文件，可以在用戶訪問網站時存儲和檢索用戶信息，如登錄狀態、購物車內容等。Cookie 由瀏覽器自動管理，可以通過JavaScript 進行訪問和操作。
Web Storage：是HTML5 新增的一種Web 存儲機制，分為sessionStorage 和localStorage 二種。sessionStorage 用於在瀏覽器會話期間存儲數據，當瀏覽器關閉後數據會被自動清空；localStorage 用於永久性存儲數據，即使瀏覽器關閉後數據仍然保留。Web Storage 可以存儲JSON 對象、字符串等數據類型，通過JavaScript API 進行操作。
IndexedDB：是HTML5 新增的一種Web 數據庫，可以在瀏覽器中存儲大量的結構化數據，如離線應用程序、圖書館目錄等。IndexedDB 使用JavaScript API 進行操作，支持多種數據類型，包括字符串、數字、日期、二進制數據等。
Web Workers：是一種在瀏覽器後台運行的JavaScript 程序，可以用於執行耗時的操作，如數據加載、圖像處理等。Web Workers 可以在獨立的線程中運行，避免阻塞主線程，從而提高用戶體驗。
Service Worker：是一種在瀏覽器背景中運行的JavaScript 程序，可以用於實現離線應用程序、推送通知等功能。Service Worker 可以攔截網絡請求、緩存數據，從而實現離線瀏覽和加快網頁載入速度。
# 9.高級主題
## CSS 樣式和 HTML
CSS（Cascading Style Sheets）是一種用於描述HTML 元素樣式的語言，可以將HTML 元素的外觀和排版進行美化和定制。CSS 樣式通常儲存在CSS 檔案中，並通過HTML 中的link 元素引入。在HTML 中，可以使用style 屬性來直接定義元素的樣式，也可以使用class 和id 屬性來引用CSS 中定義的樣式。
## JavaScript 和 HTML
JavaScript 是一種用於網頁互動和動態效果實現的編程語言，可以與HTML 結合使用，實現複雜的功能和交互效果。在HTML 中，可以通過script 元素引入JavaScript 代碼，並通過JavaScript API 操作HTML 元素和屬性，實現網頁的動態效果和互動。
## 响應式設計
响應式設計是一種網頁設計技術，旨在實現網頁在不同設備和屏幕大小下的自適應和最佳顯示效果。响應式設計通常使用CSS3 的媒體查詢功能，根據設備的屏幕寬度和高度，自動調整網頁元素的排版和樣式，實現最佳的顯示效果。
## 跨瀏覽器兼容性
跨瀏覽器兼容性是指網頁在不同瀏覽器上的顯示效果和功能表現一致的能力。由於不同瀏覽器對HTML、CSS 和JavaScript 的解釋和支持程度不同，因此網頁在不同瀏覽器上可能存在顯示錯誤、樣式失真或功能失效等問題。為了實現跨瀏覽器兼容性，開發人員可以使用CSS Reset 樣式重置、瀏覽器樣式前綴、JavaScript Polyfill 兼容性輔助庫等技術，從而確保網頁在不同瀏覽器上的一致性和穩定性。
# 10.附錄
### HTML 元素和屬性的參考
#### (1)HTML 元素
/html/
/head/
/body/
/h1/ - /h6/
/p/
/a/
/img/
/ul/
/ol/
/li/
/table/
/tr/
/td/
/form/
/input/
/textarea/
/button/
/select/
/option/
/label/
/span/
/div/
/header/
/nav/
/section/
/article/
/aside/
/footer/
#### (2)HTML 屬性
id
class
style
src
href
alt
title
width
height
name
value
placeholder
checked
selected
disabled
readonly
multiple
瀏覽器支持的 HTML 版本
瀏覽器對 HTML 的支持不僅取決於瀏覽器本身，還取決於用戶使用的瀏覽器版本。以下是各種瀏覽器對 HTML 版本的支持情況：
Internet Explorer: 支持 HTML 5，但需要使用最新版本的 IE。
Microsoft Edge: 支持 HTML 5。
Firefox: 支持 HTML 5。
Chrome: 支持 HTML 5。
Safari: 支持 HTML 5。
Opera: 支持 HTML 5。
### HTML 開發工具
 以下是一些常用的 HTML 開發工具：
文本編輯器：例如 Notepad++、Sublime Text、Atom 等。
IDE：例如 Visual Studio Code、Eclipse、NetBeans 等。
在線 HTML 編輯器：例如 CodePen、JSFiddle、JS Bin 等。
框架：例如 Bootstrap、Foundation、Semantic UI 等。
### 參考資源和學習建議
以下是一些學習 HTML 的參考資源：
W3Schools：https://www.w3schools.com/html/
MDN Web Docs：https://developer.mozilla.org/en-US/docs/Web/HTML
HTML Dog：https://htmldog.com/guides/html/
HTML5 Rocks：https://www.html5rocks.com/
WebPlatform.org：https://webplatform.github.io/docs/html/
學習 HTML 的最佳方法是實踐。嘗試編寫一些基本的 HTML 網頁，並隨著時間的推移不斷提高自己的技能。此外，建議多閱讀和實驗各種 HTML 屬性和元素的用法，以便更好地掌握它們的工作原理。
