# $4 的 Debian/Ubuntu 自動化安裝

## 緣起

因為個人的興趣以及工作上的需要，經常不斷重覆地在不同的電腦硬體上面安裝 Debian/Ubuntu 作業系統，因此自己維護了這個 Git repository 來客製自動將系統安裝成想要的結果。

使用的是 Debian preseed.cfg 這樣的技術，可以自行在網路上搜詢這兩個關鍵字。

## 成果

* [Debian 6.0.X](https://fourdollars.github.io/d-i/squeeze/index.html) 使用 auto url=fourdollars.github.io
* [Ubuntu 12.04.X](https://fourdollars.github.io/d-i/precise/index.html) 加上 auto=true url=fourdollars.github.io netcfg/get_hostname=ubuntu
