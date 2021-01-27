# World-Health-Statistics-2020
以下是透過kaggle的數據來做分析 資料跟程式放資料夾內


首先我對 Afghanistan(阿富汗)的預期壽命的時間變化做分析 而數據是把三個值(male female both)做平均 可以看出預期壽命是逐漸上升的
![Afghanistan lifeExpectancy over time](https://user-images.githubusercontent.com/49279418/105993428-5da5ff00-60e1-11eb-8b16-66283f1f3900.png)


之後我對非洲地區去做分析 這次把male female both 三項數據分開來看 可以看出非洲整體的預期壽命也是逐步上升 
其中女性的預期壽命比男性高

![Africa's LifeExpectancy over time](https://user-images.githubusercontent.com/49279418/105993507-76aeb000-60e1-11eb-84fa-12450d480591.png)



為證實以上的趨勢(女性預期壽命大於男性)是整體的 且證實平均餘命 真實壽命都是女性大於男性 所以對全部地區 全部時間去做平均 
可以發現 不論是平均餘命 還是預期壽命 都是女性高於男性(預期壽命差4年 預期餘命差2年)

![Healthy VS Total Life Expactancy](https://user-images.githubusercontent.com/49279418/105993492-73b3bf80-60e1-11eb-9521-07b5cba073f9.png)






在此驗證在小地區是否會有不同 因此取了六大區域的男女做預期壽命的比較 可以發現差距最小也是3年最多到7年 且不論平均年齡的大小皆是 而且根據整體開發程度(開發程度一定影響健康) 
可以發現確實非洲落後許多 而歐美則是走在前端 西太平洋則是意外的高
![Life Expactancy of Male and Female of different region](https://user-images.githubusercontent.com/49279418/105993498-744c5600-60e1-11eb-8127-5504de60dd99.png)





之前的分析是取平均 本次選擇去看趨勢 基本上可以看出預期壽命都是不斷上升的
![life expectancy of region over time](https://user-images.githubusercontent.com/49279418/105993499-74e4ec80-60e1-11eb-8736-a191bcc0dde6.png)


但整體成長幅度卻是相反 已開發國家上升的反而較少 非洲及東南亞上升較多
![life expectancy over time](https://user-images.githubusercontent.com/49279418/105997090-28e87680-60e6-11eb-90a7-28a9ed8e6f78.png)


從上面兩張圖可以去做猜測 是否2019年的預期壽命皆是最大 因此比較了預期壽命最高(低)的20個國家 意外的第1與第3竟然並非歐美國家而是韓國與日本
加拿大則是特殊情況 最大預期壽命竟然是1920年 本人猜測是輸入錯誤導致 其他都與預期的一樣都是2019年的預期壽命最大
![TOP(BOT)20 lifeExpectancy](https://user-images.githubusercontent.com/49279418/105993503-757d8300-60e1-11eb-9028-e079d4833fb6.png)





但是否所有國家都符合逐漸上升的趨勢 因此做了2019跟2000年的預期壽命差 可以發現前20大部分都跟上面的分析一樣 以非洲國家佔多
而有兩個國家預期壽命是下降的 委內瑞拉 多明尼加
![TOP(BOT)20 progress](https://user-images.githubusercontent.com/49279418/105993504-76161980-60e1-11eb-8664-727e2db012ac.png)



結論:可以透過上面的分析很清楚看出人類的壽命是逐步再增加的 以往對老人的定義可能也要慢慢改變 也可以得到結論全球的醫療是再逐漸進步的


