# fcc-tribute-page

Just making this repos for fcc projects, because I dont like inbuilt text editor...

Don`t like the projects either, becauze they tell me what to do...
but I guess it`s usefull sometimes, if you don`t get whats going on

well ok..the projects are good...

but I passed this project with minimal styling and all

and when i styled it and it looks nice it wont check cuz...

"Your #image should be centered within its parent"

though I left it the same when  I have passed it...like so
#image {display: block;
max-width: 100%;
height:auto;
margin:auto;}

somehow now it wont register...though the image is centered and the page looks pretty descent....lol

btw i use visual studio code and import it to fcc

photo -Ben Zinner, USAID - http://www.usaid.gov/; source; exact image URL

So the solution was to put the image in a wrapper so the wrapper is  flex item, but the image itself is not....LOL

<div class=hack><img id="image" src="https://upload.wikimedia.org/wikipedia/commons/e/e2/Norman_Borlaug%2C_2004_%28cropped%29.jpg"></div>
    <figcaption id="img-caption">Dr. Norman Borlaug, trained biologists in Mexico on how to increase wheat yields - part of his life-long war on hunger.</figcaption>
    </figure>
    
    thanks to: admit8490 from fcc forums ;) :
    
   https://forum.freecodecamp.org/t/tribute-page-your-image-should-be-centered-within-its-parent/528961?u=batoru
