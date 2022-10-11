# Software-Design-Architecture
Software Design Architecture - High Level Design

![image](https://user-images.githubusercontent.com/115500959/195122670-59473d64-23cc-48ec-a6fa-2d78e9bdb37b.png)

## Details of Explanations
The diagram below shows how data is stored in column-based DB.

𝐖𝐡𝐞𝐧 𝐭𝐨 𝐮𝐬𝐞
1️⃣ The table is a wide table with many columns.
2️⃣ The queries and calculations are on a small number of columns.
3️⃣ A lot of the columns contain a few distinct values.

𝐁𝐞𝐧𝐞𝐟𝐢𝐭𝐬 𝐨𝐟 𝐜𝐨𝐥𝐮𝐦𝐧-𝐛𝐚𝐬𝐞𝐝 𝐃𝐁
1️⃣ Higher data compression rates. 
2️⃣ Higher performance on OLAP functions.
3️⃣ No need for additional indexes
