##How Did we Get Here?

This article explores the development of how browsers interpret HTML to show how web standards can change and how we ended up where we are today. It starts with a report on the development of the image tag. Several developers shared various ideas for what they were implementing in their own browsers. Finally, a 'concencious' was reached by a developer who released their product first, and others followed his standard. 

After a while, the standards for HTML had reached a point where insurmountable revision was needed to further update it in its original form. A new combination of HTML as XML, called XHTML, was attempted. However, XHTML ultimately failed, as its ultimate solution was to break sites that didn't perfectly fit its standards. Developers, who were used to the web usually just working, noted that this broke many older websites and therefore refused to properly use the XHTML standards.

Groups of browser developers alternatively collaborated to try and adjust their browser's HTML interpretation to work consistently like other browsers. These groups evolved the web standards by disecting how each browser interpreted the code, and brought browser behaviors closer to a standard, while keeping backwards compatability. Standards are still being developed today, but it seems that HTML will continue to be a retroactively inclusive language, which still can accomodate the future. 

I thought this article was an interesting history, and I have used this site at work to help encoding and displaying videos on a website before (http://diveintohtml5.info/video.html), but I hadn't read this particular page. I found this line particularly interesting.

"...documenting the “forgiving” error-handling algorithms that browsers actually used. Web browsers have always been forgiving of HTML errors, **but nobody had ever bothered to write down exactly how they did it**." 

And that is the primary reason I got interested in technical writing. I want to document the nitty-gritty stuff people know in their heads, but never write down. The program itself needs to be documented, not just how to use it. Otherwise, it totally can get complex enough that people need for form committees to figure out how their product even works.

## An Introduction to Browser Rendering

This video quickly explains how pages are rendered in the browser. It briefly introduces the DOM and CSSDOM, and then shows how the browser plots out how it is going to render the information by making a render tree combining the DOM and the CSSDOM. This creates the website's layout. It ends with showing on a timeline step-by-step calls to functions that the browser makes to visually put this data on the page.

I thought this video was super interesting. My mind has always jumped from 'well, there's a DOM and then that appears on the page.' Seeing how everything is plotted out and ends up visible to the user was interesting. I think it's easy to take some technology for granted as 'just working,' which I was certainly doing before.
