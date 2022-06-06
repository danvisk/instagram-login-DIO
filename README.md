### Hi there!

<details>
  <summary>Description of this project</summary>	    
This is a simple exercise I did in the beginning of an online bootcamp, after the HTML and CSS courses were completed. The exercise was to recreate the login page of Instagram. 

I forked the finished exercise (as can be seen here that this is forked), as an instructor with nickname SpruceGabriela here in Github showed all the steps to reach that point. Since everything was cristal clear to me, and I felt I would easily reach that point without much consulting, I decided to fork the work made to that point, and make improvements. </details>

**Improvements/changes I did:**

- The image of the phone doesn't change anymore 
- The distance from the phone image to the elements to the right were fixed/constant

**Learning & Challenges:**

<details>
<summary>Item 1</summary>    
I changed the way the phone was shown. Instead of using the <'img'> HTML tag, I used the background-image property of CSS, inside the 'background' shorthand, as follows:
**background:** url('./img/instagram-celular.png') **no-repeat** right **/** auto **40rem**;

... after quickly consultating some technical content in the internet. This method was used by the instructor (SpruceGabriela) for the **Google Play** and **Apple Store** image buttons, and I played a bit with the code to set this up. It was my first time seeing and working with background images.
</details>

<details>
<summary>Item 2</summary>
- It was also my first time seeing **media queries** being used (this wasn't taught at the CSS course in the Bootcamp). Before I had just seen the term, and knew it was a responsive design one. I changed the original design a bit with this too. Instead of there being 2 breaks made with media queries, one at 650px and another at 1024px for the viewport, **I used only the one at 650px**, as the phone image wasn't changing anymore. 
</details>

The finished exercise can be more easily viewed here:

https://codepen.io/danvisk/full/KKQByPe (right click and "open in new tab" so you don't quit this page)

Obs: Make the width of your browser narrower, to like 1/3 the full-width, so you see that the phone image disappears, as a responsive web page should be.







  

