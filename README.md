# DU-HubHub-screen-L
![hubhub](https://user-images.githubusercontent.com/61538051/211265022-0a03073f-4f7d-49f6-ac72-186f6cafbfa6.png)
</br>
Hub Screen L for 12 Container Hubs
</br>
Label texts can be changed in lines 20-26. For example: <i>info[0][0]="my text"</i>
</br>
You can color code special key words by changing line (or adding more):</br>
<i>if ttxt == "PRODUCTS" then setNextFillColor(layer, 0 ,1, 0.2, 1)</i></br></br>
Text is case sensitive! To change color edit <i>setNextFillColor(layer, r ,g, b, a)</i> where:</br></br>
r - RED, g - GREEN, b - BLUE, a - alpha (transparency)</br></br>
Dual Universe uses 0-1 range (for example: 1 or 0.5). This is kinda percent value where 1 is 100% of 255. For more traditional RGB values you can use <i>x/255</i> syntax where 255/255 will be equivalent of 1 and 0/255 will be equivalent of 0. 

