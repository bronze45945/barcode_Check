# 國際條碼檢核
>檢核原則：
>>A.UPC(12碼)：

>>>1.位數由左到右，奇數碼 (1.3.5.7.9.11)、偶數碼 (2.4.6.8.10)、檢核碼(第12碼)

>>>2.(奇數碼加總*3) + (偶數碼加總) = 比對碼

>>>3.10-比對碼個位數 = 檢核碼則為UPC條碼

>>範例：185245896844

>>>a.((1+5+4+8+6+4)*3)+(8+2+5+9+8) = 116(比對碼)

>>>b.10-6=4 與檢核碼相同

>>>c.此序號為UPC條碼

>>B.EAN、APN/GTIN(13碼)：

>>>1.位數由左到右

>>>2.奇數碼 (1.3.5.7.9.11)、偶數碼 (2.4.6.8.10.12)、檢核碼(第13碼)

>>>3.(奇數碼加總) + (偶數碼加總*3) = 比對碼

>>>4.10-比對碼個位數 = 檢核碼則為EAN或APN

>>範例：9852475211136

>>>a.(9+5+4+5+1+1)+((8+2+7+2+1+3)*3) = 94(比對碼)

>>>b.10-4=6與檢核碼相同

>>>c.此序號為EAN或APN條碼
