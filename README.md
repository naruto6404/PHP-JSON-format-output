# PHP-JSON format-output

　　相信PHP和MYSQL這兩個東西大家一定不陌生，而這兩樣搭配在一起就可以建立一個很輕巧方便的伺服器(多半都是配合Apache)，在很多作業系統上都直接有軟體可以一次安裝完，例如：

- Windows - Appserv、XAMPP
- Linux - LAMP
- Mac - MAMP、XAMPP  (其實系統有內建，教學可以參考這裡)

　　而因為前陣子五月初時去比賽，久違的又寫起了PHP、以及最近在教一些學生做專題時也有用到，所以重新審視一下以前寫的一些專案和網頁，有了點感觸。

　　我專案的做法大多都是用PHP將資料庫輸出為JSON格式，方便網頁以AJAX或是APP的HttpRequest取用，所以無論是對資料庫的查詢、新增、修改還是刪除，都靠PHP執行後並回傳結果。執行畫面例如：

![](https://1.bp.blogspot.com/-fX2ts3d7Ixk/XO5d7MLOj9I/AAAAAAAACx8/LM1z19CZqH8Ir62yrGZb46HkscIZT03qACLcBGAs/s400/Pic_072.png)
