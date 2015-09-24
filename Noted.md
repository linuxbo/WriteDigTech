Write a post on Prose.io, documenting insights gleaned from this assignment, and save it to your team folder in wk4. I expect you to apply the conceptual framework surrounding mediation and a practice account of writing to your understanding of writing HTML and CSS.


1) Pure.CSS is confusing. I felt like I was typing in random numbers and the text would either: randomly overlap itself, not change, or magically work. I still don't get it.

2) I did the Pure.CSS version first just for the layout, then I added CSS to make it not be just white, then I did the vanilla CSS version to get close to whatever Pure.CSS generated. I wasn't sure how the pure.css version would look or what it could do, so which is why I did that first. 

3) Floating headers has always been a pain, and continued it's tradition. I only tested in Chrome. I have no idea what a mess I made in other browsers.

4) I have no idea what "conceptual framework surrounding mediation" means.

https://en.wikipedia.org/wiki/Mediation_(Marxist_theory_and_media_studies)#Mediation_in_media_studies

"thinkers try to look at how a given medium reconciles the various forces of history, culture, economics or the material world, and how social actors use that medium to navigate these various meanings and values."

------------------------------------

I started this assignment by playing with the pure.CSS framework. I figured I could see what that framework could do, and then I would recode the website as close as I could without a framework. I chose pure.css because I had used bootstrap before, but pure.css was new to me. 

I mostly just used the Grids feature (http://purecss.io/grids/) to position elements on the page. I didn't really set out with a goal, I just wanted to see what it would do.

What is did most of this time was this:

![screen shot 2015-09-24 at 2 03 23 pm](https://cloud.githubusercontent.com/assets/7316321/10083730/6303c916-62c5-11e5-9667-203455165eef.png)

and not gradually. The site works when the cell size is set to class="pure-u-3-8" but does that at class="pure-u-2-8", which should be one size slightly off. It either did that, didn't change, or worked. I tried reading a different tutorial, but still couldn't make much sense out of it.

I don't really understand pure.css grids. I got the website to have a decent layout, but it was a lot of guesswork and number picking. I still don't understand why it goes from 'the text is fine' to 'the text is overlapping' so quickly.

After that, I applied some of my own CSS to 'wrap up' the layout: set the background color, centered the page, set the link color. I didn't see anything in the pure.css documentation that indicated it did those things, but I might have been wrong.

I then copied my file, stripped out all of the pure.css code and tried to match the way the site looked with plain CSS. I got decently close. If you resize the page, or have a small-enough of a screen, the text falls underneath the headers instead of staying along side of it. I probably could have fixed that with enough time, but I didn't have a problem with that being the behavior. I almost think that looks better than the text getting really narrow.

As far as insights, I learned a bit about pure.css. I can see the benefits of using it, it's requires very little extra code and it is nice that it doesn't use Javascript. Bootstrap requires Javascript and, at least when I used it, is a bit less flexible. If I really threw myself into pure.css, I bet it has more flexibility and customization than Bootstrap since it's just CSS. 

I think I'd trust a framework for resizing more than my code. Different devices/browsers can get picky, and I'd rather use something that has been tested by many people rather than just me. It's important for a website to work in any enviornment nowadays, and I don't think one person is capible of testing all of those different environments.
