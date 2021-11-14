## 安裝nodejs步驟:
- 1 到nodejs官網https://nodejs.org/en/, 在16.13.0 LTS這欄的下方, 點選 Other Downloads.
- 2 進入到https://nodejs.org/en/download/的網頁, 下拉網頁, 找到倉庫式的安裝, 點選 Installing Node.js via package manager.
- 3, 進入到https://nodejs.org/en/download/package-manager/套件式管理的網頁, 點選Debian and Ubuntu based Linux distributions
- 4, 這時網頁會自動下拉至Node.js binary distributions are available from NodeSource., 然後點選 Node.js binary distributions.
- 5, 這時會開啟另一個網頁--->github網頁https://github.com/nodesource/distributions/blob/master/README.md
- 6, 然後網頁下拉, 找到Debian and Ubuntu based distributions (deb), 點選Installation instructions
- 7, 進入到Installation instructions項目, 找到Node.js v16.x:下面的# Using Debian, as root, 
- 8, 複製指令列curl -fsSL https://deb.nodesource.com/setup_16.x | bash -, 記得後面那個'-'不要拷貝, 自己手動打, 避免複製到不必要的命令字元.
- 9, 回到ubuntu的command line,
    :~# cd
    :~# curl -fsSL https://deb.nodesource.com/setup_16.x | bash - (安裝好後, 會自動更新倉庫清單.)
- 10, apt install curl (如果系統沒有curl套件, 需安裝)
- 11, apt autoremove (如果系統提示要autoremove, 須執行這一行, 移除系統不必要的套件)
- 12, ls -l /etc/apt/sources.list.d (查詢nodejs倉庫是否有建起來 nodesource.list)
- 13, apt install nodejs (安裝nodejs套件)

...待整理