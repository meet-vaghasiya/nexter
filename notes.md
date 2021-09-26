1. To change default behavior of script to brower,add      `"devserver": "live-server  --browser=firefox"`.
2. use minmax function to minimize width of 
3. what should be use for slight movement of icon from  translate , margin-top and position
4. align items mosty property is  strntch bydefault.
5. replace  ` grid-template-columns: repeat(3, 1fr);` with
   ` grid-template-columns: repeat(auto-fit, minmax(25rem, 1fr));` . so if size of screen is decrese than if card component strech less than 25rem than it will automatically take 2 column. so easy in responsive webdesign.

6. if you find space issue than replace `align-item` with `align-content:center;`
7.  object-fit only work if height and width is define.  genrally give both to 100%. always give image to display block. otherwise act as text and shown some wierd thin white line. 
8.  if we give container to fix width than give margin-right and margin-left auto.   
9.   `::before` and `::after` is also grid items. 
10.   use filter = briteness property for darkedn image.
11.   if you give height to image than no need to give width to image. but if you give max-height than also give max-width to 100%.
12.   `calc(100vh - 6rem)`  put space around minus sign. Other wise show invalid property . `calc(100vh -6rem)` and `calc(100vh- 6rem)` both are wrong.