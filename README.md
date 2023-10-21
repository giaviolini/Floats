# Floats
## What I learned/Practiced
For this assignment, the main goal was to create a website that taught about old and new web technologies that are ever-changing and updating to keep up with the latest needs for developers. However, something we had to add was image floats. 

### Floats 
Image Floats are a type of CSS property that will position an image on a web page that also causes other elements to wrap and break around the float. I don't think I would continue to use this method because it's very finicky, hard to get images in the right spot, and overall not the best way to position things.  \
However, they are pretty simple to add to your code, just harder to make it look good.  \
How I set up my floats is I gave all the images a specific ID to be able to call them up when creating the CSS.  \
ex. ```<img src="../images/tensorflow.png" id="design3">```  
* also not we are adding the ID inside the image tag.  

Next the CSS. After calling up the specific images by their IDs, I decided where I wanted them on the page, either left or right. Then I put the ```float:``` element into my CSS with the corresponding position.   
Depending on the problems I ran into, I changed one thing the margins to the top, bottom, left, and right of the image. Sometimes the text would cut off in a weird place, or where it was cutting off did not look good or how I wanted it, so I changed the margins. This step was my best friend in getting I website I was happier with.   

### Margins
There are a couple of ways to add margins to your images, or in general, but the way I found the easiest at this time was individually calling the different margins.   \
ex. ```margin-right: 40px;```  \
 ```margin-left: 20px;```  \
There is a way to do it to only have one margin element, but I was having trouble grasping it at the time. But it would be like this...  \
ex. ```margin: 20px, 0px, 20px, 0px;```  \
The top and bottom margins are 20 while the left and right margins are 0.  \
You could also shorten this to be...  \
ex. ```margin: 20px, 0px;```   \
You could also just have ```margin: 20;``` and that would give every side a 20 px margin.


[Visit the Site](c)
