# Hexstring_Tranformer
為十六進至轉換之系統，由C#進行撰寫。

=======系統說明========
前端架構分為 狀態顯示區、功能區(Hex string轉換存入資料庫 及 查詢資料庫ID 取得Hex string轉回原文)
初次開啟會於檔案位置1120121_hexString\bin\Debug建置資料庫，使用的資料庫為SQLite3。

---操作說明---
1.首先點選Menu=>Load可讀取.txt文字檔，可勾選是否要逐行讀取或整個文字檔進行讀取。
2.點選右方功能區的Hexstring Trasform可察看先前所讀取的原文內容，並進行轉換。轉換結束會自動存入資料庫。
3.存入資料庫的內容可透過功能區Database Search進行檢視，輸入ID或亂數查詢皆可。
