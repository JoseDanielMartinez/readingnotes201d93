# ***Overview***

Before developers get to work designing websites, it's important they have ideal computer set ups, understand the basics, and apply solid programming fundamentals.  Understanding how to structure, style and animate webpages using HTML, CSS, and Javascript helps enhance users' experiences.  Arrays and loops also help developers interact with users.  Developers use both to create code that helps pull information and put it to use.  For example, correcting user responses.  Writing loops of code helps save time and minimizes errors.  Arrays help retrieve contained data for deployment.  Understanding HTML links, JS functions, and CSS layouts are important to know because as a developer, you'll be given problems to fix and knowing the areas well reduces time looking back through notes and having to research other's fixes, which may not be reliable to begin with.  Some problems you'll be called upon to troubleshoot are images and texts.  Learning to manipulate both makes user's web pages more appealing which increases more site visits and other metrics, e.g. views, hits, check-ins, etc.  Understanding Javascript objects helps developers save time when using functions in their code.  For example knowing when to use dot notations versus brackets and their advantages versus disadvantages. Constructors also save time.  They streamline the object process.  Having background knowledge about the document object model is important for developers to know because it gives them a visual representation of how their programming languages medify webpages.  Developers must be able to navigate DOM modeling so they can work on specific code issues.  Knowing tables is good because it's a rudimentary way of back up methods when our primaries are down.  Constuctors simply reduce time for productivity and lines of code for readability.  Flexbox is good to know for those beginner developers and bloggers.  It's a good starting point to understand the basics of how you can structure pages without always have to manipulate margins, borders, padding, and content manually.  Bloggers can add content to their pages easily to make them easily readible and add a little pop.  Personal business owners could also beneifit from learning flexbox as well.  They can save a little money being their own developer and graphic designer.  Learning forms helps developers interact and collect data from users.  Although collecting user data can become a rudimentary task, developers can manipulate forms to make them less boring or unappealing.  When users react to events, developers get an inside look at their behaviors.  This helps developers structure their pages to meet user needs, for example off the number of clicks, scrolls, or times a user visits urls.  Knowing how to debug code helps developers test processes before going live.  Working out small kinks goes a long way before deployment and degrading users' experiences.  ***Video and audio technologies have transformed the web's accessibility in several ways.  Both alone have revolutionalized how we spend the majorities of our days, whether it be watching videos to pass time or listen to playlists while we work out on mobile devices.  Knowing how to leverage both types of mediums helps developers reach end users in their daily activities whether as consumers, students, or any other type of practioners.  CSS grid is another great area to master for just it's two-dimensional feature alone.  Aside from developers, its mastery can benefit other non-tech populations, e.g. small business owners, bloggers, and writers in creating simple webpage designs and layouts.***

# Class 11 Assignment

1. Explain how the ability to use video and audio on the web has evolved since the early 2000s.

   In the early days video and audio files relied on third party plug in technology.  Today, they've evolved due to accessibility and security issues and now are easier to program into code through native HTML elements and other APIs (application programming interfaces).

   [Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

2. Describe the use of the src and controls attributes in the \<video> element.

    The src or source attribute works the same way as for an image.  It contains the video the programmer wants to imbed in the page's body using internal paths or external links.

    The controls attribute allows the user to manipulate payback.  This is especially important for those with disabilities whom rely on accessibilty features to navigate the web.  They can be constructed by the browser's interface or by the developer using APIs.

   [Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

3. Why is it important to have fallback content inside the \<video> element?

   It's important to provide fallback content inside the video element because if the user's browser doesn't support playback they can be directed to another medium that may work instead.  It adds another layer of accessibility.

    [Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)

4. Write a very short story where \<audio> and \<video> are characters.

   Video and audio are both salesman offering different deals.  Video is the better looking salesman whom consumers typically turn to because he's more appealing, tangible, and is better known.  Audio is a less traveled salesman that pitches to a smaller audience and hence posseses less global appeal.

5. How does Grid layout differ from Flex?

   CSS grid differs from Flex in that it is two dimensional, containing both columns and rows.  It is more widely used to layout webpages as templates than flex.  While both have similar features, CSS has more options built into it out of the box.

6. Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

   Grid container; typically serves as the parent to all its items.  This can be used to format all items or to reference items around.

   Grid item; these are the children or direct descendants of their parent elements.  They can be given classes or ids to specifically target.

   Grid line; these are the disguishing lines which structure CSS grids.  They can be either horizontal rows or vertical columns.

   [Source: CSS-TRICKS](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)
   
7. Besides making a site visually appealing across different screen sizes, why should developers make images responsive?

   It increases accessibilty, reduces art direction conflicts, and resolution switching problems.

   [Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

8. Define the following \<img> attributes srcset and sizes. Write an example of how they are used.

   srcset; defines the set of images allowed by the browser to choose between, and what size each image will be.

   srcset="elva-fairy-480w.jpg 480w, elva-fairy-800w.jpg 800w"

   sizes; defines media condition sets (e.g. screen widths) and indicates what image size would be best to choose when certain media conditions are true.

   sizes="(max-width: 600px) 480px, 800px"

   [Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

9. How is srcset more helpful for responsive images than CSS or JavaScript?

   Srcsets allow users to load \<img> elements, detects the viewport width, then dynamically changes the source image to a smaller one if desired.  Javascript alone can't do that.

   [Source: mdn web docs](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

   ## Things I want to know more about