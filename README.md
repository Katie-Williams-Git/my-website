# my-website
I am a member of the POSDA church and will soon be working with
 the website developer to freshen up the current website, I am using a lot of the wording
 and formatting from the original website but plan to modify it more and more

After the Mod 8 Website critque I received these comments:

1) On the About page, the link for "Come Experience Hope" is broken, as is the link at the very bottom of the "Connect" page. The "Give Online" feels hidden in that dark text with a smaller font. You might consider making it the same size as the rest of the font. In the upper left-hand corner, there is some kind of link, but I'm not sure what it is. On Safari, it looks like a broken image, and on Chrome, there is a bunch of what look like links all mooshed up together in the corner, on top of a broken image:

Editor Response:
So I think the words with a link in the top left were my logo with the alt text displayed in the limited space for my logo. I'm going to work on enlarging the give button. 

 

2) In the middle of the front page there is some text with a couple of bullet points - I don't think those are needed for that particular set of text. They look great on the list of Children's classes. Also, I would consider separating the footer from the rest of the page, even if just with a simple <hr>. I'd also include that same footer on all your pages and add a "Home" button to your top navigational menu to take guests back there. 

"All your web pages should have a clear, consistent, and functional navigation menu between pages."


Editor Response:
So I took the suggestion and added an <hr> on the footer and removed the bullets from the <ul>. And I've added the footer to all of my pages with a back to home link.



3) Line 14 of your About page has a syntax error. All three pages are showing that, actually, and I think it's the same error for each page. I believe it's a missing closing parenthesis in the $(document) . ready .... part of your script source. You have some Java in there, but we didn't learn any, and that might count against you. Well, I mean, it's in the book, but it wasn't in our learning modules. I don't know. 

"HTML & CSS code does not contain syntax errors."

Editor's Response:
This one is a little trickier. The Java is supposed to be linked to getting my slickNav to work for the mobile menu. If time eludes me I'm going to remove this feature and settle for mobile queries instead. 