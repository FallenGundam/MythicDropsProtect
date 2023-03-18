# MythicDropsProtect v1.1.0
可依玩家對怪物造成的傷害來判斷掉落物歸誰  
上個版本因為改動過掉落物的itemmeta導致mm物品NBT資料亂掉，此版本已修復  
另外，此版本經過大量改動，已支持普通怪物、挖礦掉落物的保護  
並且支援掉落物品holo字幕顯示
![2023-03-19_06 02 09](https://user-images.githubusercontent.com/54828956/226142602-8b428962-d034-491c-aaa7-5f374633c57e.png)  
![2023-03-19_06 18 06](https://user-images.githubusercontent.com/54828956/226143163-7e88ccb1-dcbf-46dd-b736-ef015d0601e7.png)


# required:
* paper 1.13.2~1.18.2 
* mythicmobs 4.6~4.13  
* skript 2.3.7 - lastest 
* skript-reflect 
* ItemNBTAPI
* skrayfall
* holographicDisplays

# settings:
  owner_text: &c擁有者  
  blacklist: "&cWolrdBoss" or "&bWorldBoss2"
  ##### 開啟一般怪物掉落物保護
  Enable_MobProtect: false
  ##### 開啟挖礦掉落物保護
  Enable_BlockProtect: false
  ##### 開啟掉落物的holo字幕顯示   
  Enable_itemHolo: true
# API:  
  isMythicMob(entity) - 是否為mm怪物
