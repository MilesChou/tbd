---
date: 2024-06-21T22:00:00+08:00
title: 翻譯詞彙表
weight: 211
---

主幹開發相關的中英對照詞彙表，照英文字母排序。

## binary file

**二進位檔**

指讀取出來是非文字的檔案，代表檔案內容不是人類可以透過文字訊息可以直接理解的。例如可執行檔是給電腦看；圖片儲存了顏色資訊，需轉換成螢幕的顯示等。

## bot Activity

**自動機制**

## branch

**分支**

版本控制的專有術語。開發者可以使用分支，讓原始碼的狀態與主幹隔離。

分支在版本控制的流程中，會有不同意義而產生的分支，如：

- Topic Branch - 主題分支
- Release Branch - 發布分支

## branching model

**分支模型**

版本控制的專有術語，指的是管理分支的方法。

## build

**建置**

指的是軟體開發生命週期中，從原始碼轉換成可發布軟體的動作。

## checkout

不翻譯。

## cherry-pick

不翻譯。

## clone

不翻譯。

## code freeze

**凍結版本**

## code review

**程式碼審查**

透過另一個協作者或機制來檢查交付出來的程式碼。

## codebase

**基準程式碼**

## continuous delivery

**持續交付**

## continuous integration

**持續整合**

## database migrations

**資料庫遷移**

## daemon

**常駐程式**

通常我們在講常駐程式，是指的像防毒軟體的東西。文章的例子提到的是 CI 服務，會隨時待命處理整合的任務，這也算是一種「常駐」的概念，因此翻譯為常駐程式。

## DVCS

**分散式版本控制系統**

指分散式（Distributed）的 VCS。分散式代表提交程式碼版本的位置不用像中央式一樣，只能在唯一的一個地方提交。

## feature flags

**功能標誌**

## fork

**分叉**

動詞用原文 Fork，名詞用分叉。

## IDE

**整合開發環境**

此翻譯參考中文維基。

## monorepo

**單一版本庫**

與其相對的是 Multirepo（多版本庫），差異在於多版本庫會依特定邏輯劃分版本庫，即可做到程式碼隔離。單一版本庫的做法則相反，會打破這個隔離將所有版本庫統一成一個。

## pair programming

**配對開發**

程式碼審查的方案之一。藉由一人使用一台電腦，另一人來做檢查，來達到即時的程式碼審查效果。

## patch

**修補程式**

此翻譯是參考中文維基翻譯。

## pipeline

**流水線**

## production code

**產品程式碼**

## production environment

**正式環境**

## pull request

**拉取請求**

通常被簡稱為 *PR*。是 GitHub 上的協作開發模型裡，當協作者完成開發後，向擁有者提交變更的行為。

其他系統上有可能會稱之為 Merge Request，簡稱 *MR*，意義是完全相同的。

## race to push

**推送競賽**

文章有些地方的用詞是 *race condition*，就版本控制的領域裡，與 race to push 的意境是相同的。

## release

**發布**

指的是軟體開發生命週期中，將軟體價值交付出去的動作。

> 參考[教育部 重編國語辭典修訂本](https://dict.revised.moe.edu.tw/dictView.jsp?ID=33265&la=0&powerMode=0)。

## repository

**程式碼版本庫**

這個單字在不同的前後文中，會有不同的意義。因主幹開發在討論的是版本控制系統的程式版本相關資料儲存倉庫，因此翻釋為「程式碼版本庫」。

## rollback

**回滾**

## short-lived feature branches

**短期功能分支**

原文有縮寫 SLFB，指的是時效的長短。中文可以用「短期」來表達時間區間是短的。

## source control

**原始碼版本控制**

## textual source

**文字資源**

## trunk

**主幹**

Trunk 的原意是樹幹，是在比喻版本控制中，所有協作者會在上面一起維護的主要版本。

在原文有時候不一定會叫 trunk，有可能會叫 master、main、mainline，但意義相同的時候會翻譯成主幹。

與它相對意義的名詞即為 branch。

## Trunk‐Based Development

**主幹開發**

原文的直譯為「基於主幹的開發」，了解所有相關文章可以理解，這是指大家都基於主幹上做開發的意思。因為中文特性可以省略部分形容詞和介系詞，所以可以簡稱為「主幹開發」。

有些文章會縮寫成 *TBD*，但可能會跟「有待討論」的縮寫「To Be Discussed」搞混，因此翻譯上統一使用中文全名。

## update/pull/sync

**同步**

因為不同的版本控制系統，所解釋的行為稍有不同，但以抽象概念來說，都是屬於「同步」的行為。因此除非在介紹不同版本控制系統的行為，不然文中如果同時提到這三者時，會翻譯成「同步」。

## VCS

**版本控制系統**

原文為 *version control system*。可以管理文件、程式碼等資源的變更歷史的工具。如 Git、Subversion、Mercurial 等。

## workstation

**個人電腦**

從現代的開發流程，與原文的前後文中，使用個人電腦會比較好理解。

另外也會視前後文改譯為開發主機。