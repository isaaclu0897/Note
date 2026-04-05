# Note

## TOC

- [Directory Structure](#directory-structure)
- [Note-Taking Philosophy](#note-taking-philosophy)
- [Writing Guidelines](#writing-guidelines)
- [Done Notes](#done-notes)
  - [Systems & Virtualization](#systems--virtualization)
  - [Server & Protocols](#server--protocols)
  - [Windows & System Administration](#windows--system-administration)
  - [Linux & Package Management](#linux--package-management)
  - [Development & Tools](#development--tools)
  - [Categorized Notes](#categorized-notes)

## Directory Structure

筆記的目錄結構：

- `done/`：已完成筆記（暫存或歸檔）
- `What-is/`：名詞解釋（原子性、不可分割）
- `How-to/`：應用型文章（由名詞組合而成）
- `todo/`：撰寫中筆記、靈感與想法
- `README`：筆記架構說明
- `Tags/`：標籤整理

## Note-Taking Philosophy

寫筆記有時候真的會怠惰，但是如果是隨手記錄，閑暇之餘在串起來可能會好很多。

然後就是最近一直想剛開始入門obsidian，一直在想寫筆記的架構要怎麽規劃。網上一直說這就是[[卡片盒]]筆記法，但是看半天還是看不是很懂。最後在洗澡的時候終於給我想到一條適合我的路。

原則就是，寫筆記其實就是寫程式！

一開始寫程式的時候會有模糊的需求，產生模糊的目標，這樣的情況就可以邊做邊學，從中獲取一些關鍵字記錄下來，這些關鍵字就是名詞筆記。這些名詞筆記可以被應用在其他的筆記中。名詞筆記也是就是物件導向的物件。

然而當我們要完成一個需求的時候，我們會需要知道完成這個目標需要什麽，這時候就會延伸出應用筆記，這些應用筆記串聯一個一個的名詞、概念。這個就是應用筆記。應用筆記就是物件導向的方法，通過調用物件達到我們想到的目的。

但通常只是應用還不夠，需要在將這些目標串聯成完整的項目。也就是專案筆記，專案筆記使用應用筆記與名詞筆記，完整我們的目標。在物件導向中，也就是我們調用物件、方法達到我們要的目的。

重點在於持續的迭代更新，舊的筆記一定會越來愈完整

名詞筆記：原子性、獨立性
應用筆記：一步一步的教你做
專案筆記：會有目標目的等
關鍵字筆記：有時候在學習陌生領域，可以直接將陌生的名詞加起來，建立一個知識系統

## Writing Guidelines

1. 名詞筆記最好使用英文術語，如IPMI，以後比較好鏈接。
2. 名詞筆記最好不要超過一頁，快速簡介他是什麽、它可以做什麽？可能可以怎麽用？
3. 應用筆記最好不要超過兩頁，説明動機，要準備什麽、怎麽做？可以在放上一些過程中遇到的問題

寫筆記可以正向寫也可以反向寫，正向的時候是因爲清楚的知道目標，這時候可以先規劃出架構與大綱。反向寫的時候是因爲不熟悉這個領域、不知道要做什麽但是想學，這時候可以先把基本名詞掌握，用到的時候就會串聯起來。

## Done Notes

### Systems & Virtualization
- [How to setup WDS as PXE Boot Server on Windows Server](./done/How%20to%20setup%20WDS%20as%20PXE%20Boot%20Server%20on%20Windows%20Server.md)
- [How to setup PXE Boot Server on Ubuntu using iPXE](./done/How%20to%20setup%20PXE%20Boot%20Server%20on%20Ubuntu%20using%20iPXE.md)
- [How to setup iPXE](./done/How%20to%20setup%20iPXE.md)
- [How to boot from PXE on HyperV](./done/How%20to%20boot%20from%20PXE%20on%20HyperV.md)
- [How to enable Hyper-V on Windows Server](./done/How%20to%20enable%20Hyper-V%20on%20Windows%20Server.md)
- [How to manage Hyper-V hosts remotely](./done/How%20to%20manage%20Hyper-V%20hosts%20remotely.md)
- [How to enable and use RDP on Windows](./done/How%20to%20enable%20and%20use%20RDP%20on%20Windows.md)

### Server & Protocols
- [How IPMI packets work on the real server](./done/How%20IPMI%20packets%20work%20on%20the%20real%20server.md)
- [How to decode IPMI packet](./done/How%20to%20decode%20IPMI%20packet.md)
- [How to install HiveMQ 4.x on CentOS](./done/How%20to%20install%20HiveMQ%204.x%20on%20CentOS.md)

### Windows & System Administration
- [How to enable Hyper-V on Windows Server](./done/How%20to%20enable%20Hyper-V%20on%20Windows%20Server.md)
- [How to force change password on Windows](./done/How%20to%20force%20change%20password%20on%20Windows.md)
- [How to create Chocolatey package for 7-Zip](./done/How%20to%20create%20Chocolatey%20package%20for%207-Zip.md)

### Linux & Package Management
- [How to manage YUM Repositories](./done/How%20to%20manage%20YUM%20Repositories.md)
- [How to manage YUM Repository using Git](./done/How%20to%20manage%20YUM%20Repository%20using%20Git.md)
- [How to reduce the size of LVM partition with XFS filesystem](./done/How%20to%20reduce%20the%20size%20of%20LVM%20partition%20with%20XFS%20filesystem.md)
- [grub 多重開機](./done/grub%20多重開機.md)
- [如何在Ubuntu中使用pipenv管理python套件](./done/如何在Ubuntu中使用pipenv管理python套件.md)
- [如何在Ubuntu建立Systemd Service](./done/如何在Ubuntu建立Systemd%20Service.md)

### Development & Tools
- [How to connect Github Using SSH over HTTPS](./done/How%20to%20connect%20Github%20Using%20SSH%20over%20HTTPS.md)
- [How to Use Remote Debug in Java with Eclipse](./done/How%20to%20Use%20Remote%20Debug%20in%20Java%20with%20Eclipse.md)
- [Git Command](./done/Git%20Command.md)

### Categorized Notes
- [What-is/](./done/What-is/) - 名詞解釋
- [實戰Web 應用Go/](./done/實戰Web%20應用Go/) - Go 語言 Web 應用教學
