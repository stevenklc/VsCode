#  常用套件

* Bracket Pair Colorizer 2
  增加程式碼區塊辨識度

&nbsp;

* Material Icon Theme
  好看的icon主題

&nbsp;

* GlassIt-VSC
  vscode背景透明度調整
  快速鍵```Ctr+Alt+Z```提高透明度,```Ctr+Alt+C```降低透明度

&nbsp;

* background
  可在vscode背景套用自己選換的背景圖
  1.進入settings.json
  2.貼上以下程式碼
  ```json
  {
    "background.enabled": true,
    "background.useDefault": false,
    "background.customImages": [
    


    "相片路徑" //相片路徑
    ],
    "background.style": {
    "content": "''",
    "pointer-events": "none",
    "position": "absolute",
    "z-index": "99999",
    "width": "100%",
    "height": "100%",
    "background-position": "center",
    "background-repeat": "no-repeat",
    "background-size": "100%,100%",
    "opacity": 0.2 //調整透明度
    },
    "glassit.alpha": 200,
    "editor.fontSize": 16,
    "editor.fontLigatures": null
  }
    ```