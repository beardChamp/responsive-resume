Responsive Resume
=================

It's a resume. It's responsive. It's awesome and always in progress

So, I read [A Case for Responsive Résumés](http://alistapart.com/article/a-case-for-responsive-resumes) last year (2012). I had multiple copies of my resume, and I was always having trouble keeping them appropriately up-top-date and finding the *one* version that I needed. A responsive resume seemed like the perfect way, going forward, to keep one synced document that can be viewed anywhere. After seeing another developer who had also mixed in microformats, I figured this was a great opportunity to use those to provide a consistent structure to the whole thing. I also followed along with David Bushell's [Implementing Off-Canvas Navigation For A Responsive Website](http://coding.smashingmagazine.com/2013/01/15/off-canvas-navigation-for-responsive-website/) to help with space management at smaller screen sizes.

Updates
-------
-  Added in-page navigation links to help move to lower sections for smaller screen sizes.
-  Added github address to contact info
-  Cleaned up some tablet breakpoints, to get things where I wanted them.
-  Add a dedicated print media query to duplicate the look of the largest screen version. Printing from Safari or Chrome best.

Future Plans
------------
-  Current oddities with navigation and overflow: hidden applied to outer-wrap div. Not happy with only applying when menu open (potential to side scroll)
-  Printing in Firefox is still ugly using its default settings. Need to see if I can override those styles with CSS.
-  I tried to keep requests down, but I could probably make things more performant and squeeze things down even further.
-  Run this through more IE VMs than I have access to at home.