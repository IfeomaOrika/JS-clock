# JS-clock
This project is a JS clock inspired by Wes Bos's 30 days of JavaScript challenge.

**My process** 

I downloaded the starter files from 

https://github.com/wesbos/JavaScript30/blob/master/02%20-%20JS%20and%20CSS%20Clock/index-START.html

There was already pre-written html and css code files.

Then I used the transform element in css to make the clock hands active. 

Finally, I wrote js code to manipulate my html and make my clock fully functional.

I used the DOM for this purpose with the document.querylSelector Object.

 I utilized The date object to get the current time. I used the getMinutes method, getSeconds and getHours methods to get the exact time. 

I had to divide the seconds element by 60 and multiply by 360° so that every minutes the second hand turns a full 360° to signify a minute has passed. 

I did similar to the minute object by dividing it by 60 minutes and multiplying by 360° to signify the passing of an hour 

However for the hour hand I had to multiply by 12 hours even though there are 24 hours in a day. This is because this clock is a 12 hour clock. So I had to divide by 12.  

**Live Site**   

**My stack for the project**  

My stack was HTML CSS and vanilla JavaScript           

**What I learned**, 

This project helped me understand the date time object in js. I understand now that the date() object is a function.

When it is called, it returns a string representation of the current date and time.

The new date function is called as a constructor, returns a new Date object. I also learnt the various methods the date object has. 

**What I realized I need to improve on**.

My knowledge of JavaScript objects.  Continued development  This is one of the various projects I plan to do with JS to improve my knowledge. Doing subsequent projects should expand my knowledge of JavaScript.                      

**Useful resources**

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Date
