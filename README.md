BUG REPORT
Bug Status – On hold
Description: I tried to create API key to create a 2D map. It was not working, and the map was not displayed. Then I created another API key by deleting the first one. I added the referrer to my GitHub account and repository. In this case the map and the point, polygon, polyline and the 2D map was displayed but the base map was not displayed. The initial base map was topographic which was not displayed. Then I changed the base map topographic to imagery which returned a good result. The imagery base map was displayed perfectly.
![image of 2D map](picture1.png)
![error](picture2.png)
![image of map with point,line](picture3.png)
![error](picture4.png)
 

Steps to reduce bug: A console error should appear after enabling the API key for “arcgis/topographic”
Results: The world topographic map can be seen only with hill shade and the other parameters. The 2D map and the map with polygon, line and point also displayed in the same way.

  

 

Environment settings: Browser: Microsoft edge, Visual Studio Code and GITHUB
Issue Reported: Affected by many students

 
