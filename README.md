```
npm install -g @angular/cli
ng new angular-electron --routing --style:scss
cd angular-electron
```
更新index.html
```
<base href=”./”>
```
安裝Electron
```
>npm install electron --save-dev
```
開發程式後測試
```
>npm run electron-build
```
佈署
```
>npm install electron-packager -g
>npm install electron-packager --save-dev
```
發佈
```
>electron-packager . --platform=win32
```
產生在angular-electron-win32-x64目錄下
