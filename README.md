# Keanux-Personal

[![Join the chat at https://gitter.im/Keanux/Keanux-Public](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/Keanux/Keanux-Public?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

這是一個一起學習Node.js和React的計畫，透過一起實作，製作個人的開源寫作平台。

- [Hackpad](https://keanux.hackpad.com/INTRO-rDTHFqtALl2)
- [Facebook Page](https://www.facebook.com/trykeanux)
- [Keanux-Personal Demo](http://keanux.com:8080)
- [Keanux](http://keanux.com)

# 功能

目前僅提供顯示範例頁面，編寫及其他功能的部分正在開發，有任何錯誤或功能上的想法都歡迎在[Issue](https://github.com/Keanux/keanux-personal/issues)留言。

# 環境安裝

參考[安裝說明](docs/setup.md)或是使用[Keanux-Vagrant](https://github.com/Keanux/keanux-vagrant)

# 快速開始

將專案clone 至本機

```
$ git clone git@github.com:Keanux/keanux-personal.git
```

啟動 Mongo DB 環境

```
$ mongod --dbpath <資料庫存放位置>
```

準備好 node.js 環境，打開 Terminal 進入專案資料夾，使用以下指令安裝並建立測試資料庫，然後啟動網站

```
$ npm install
$ node data/seed.js
$ node server.js
```

開啟瀏覽器輸入 http://localhost:8080

# 更新到最新版本

新增遠端網址 `upstream`，此名稱可以任意修正

```
$ git remote add upstream https://github.com/Keanux/keanux-personal.git
```

更新遠端最新程式碼

```
$ git pull upstream master
```

# Copyright & License

Copyright (c) 2015 Keanux - Released under the [MIT license](LICENSE).
