# 小型APP練習
## Flutter介紹
參考[【Flutter基礎概念與實作】](https://ithelp.ithome.com.tw/articles/10215158)
Flutter是一個能建立原生跨平台的框架，一種程式語言(dart)能同時讓iOS與Android平台使用，也支援Web以及桌面應用程式。  
> Dart是Google開發的程式語言，主要針對前端介面開發所使用的程式語言(mobile apps, web)，屬於物件導向語言
Flutter的SDK(Software Development Kit)會將我們寫的程式碼編譯成native machine code，轉換成Android或iOS讀得懂的code。  
### 下載Flutter(Mac版本)
1. 從官網下載Flutter SDK https://flutter.dev/docs/get-started/install  
2. 解壓縮後放到想要的location，在terminal打入以下指令，把flutter暫時加入path
``` export PATH="$PATH:`pwd`/flutter/bin" ```
3. 在terminal打入``` flutter doctor ```，檢查flutter是否正常運行
4. 用pwd指令來得知目前位置，再打上``` export PATH="$PATH:[PATH_TO_FLUTTER_GIT_DIRECTORY]/flutter/bin" ```來update PATH。(要重新開機來更新PATH)
### Android Studio & VS code
1. 下載Android Studio，新建一部虛擬機，[【Flutter基礎概念與實作】](https://ithelp.ithome.com.tw/articles/10215158)中有詳細步驟。
2. VS Code 安裝 Flutter and Dart plugins
	1. Start VS Code.
	2. Invoke View > Command Palette….
	3. Type “install”, and select Extensions: Install Extensions.
	4. Type “flutter” in the extensions search field, select Flutter in the list, and click Install. This also installs the required Dart plugin.
可以參考[官網文件](https://flutter.dev/docs/get-started/editor?tab=vscode)步驟
