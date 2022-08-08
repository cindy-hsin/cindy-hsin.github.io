## Link to repo:
	https://github.com/cindy-hsin/cindy-hsin.github.io
## Lin to personal website:
	https://cindy-hsin.github.io/

## Most challenging piece of this assignment:
Mobile friendliness, especially when involving embedded images/icons. I spent lots of time adjusting the sizing and position of images, and ended up using different techniques for different situations. (See the next question.) In the later stage of development, I sort of turned to "mobile-first" desgin, to avoid spending too much time on re-arranging contents. Overall, I find it a bit challenging to work with pure HTML and CSS, especially when trying to develop a mobile friendly website. I hope in the future, we can learn to use seom 3rd party frameworks or libraries that can ease the pain.

## Mobile-friendly related decisions:
1. Menu links in the Navbar will be hidden when screen size decreases. User can then drop down the menu links by clicking the hamburger bar.
2. Images:
	- Background image of Contact page: To make sure that the "holding-hands"(the center part of the image) is always shown on the page regardless of screen sizes, I attached a horizontal image file for screens that are "flat" (i.e. having a larger width and smaller height), and a vertical image for screens that are "tall" (i.e. having a larger height and smaller width).
	- The performance image on Hobbies page: Similarly, to make sure that the "performers"(the center part of the image) are always shown on the page, I adjusted the margin of the image when screen size decreases. This is the first time I found that I could use a minus margin and it's super useful for "re-centering" an image!

3. Font sizes, as well as the spacing between body and viewport are adjusted for different screen sizes. A tip that I found for adjusting font sizes, is to size all fonts with rem unit, so that by simply adjusting the font size of root element (i.e. html) in media rules, all fonts will be adjusted proportionally.


## Design choices:
1. Accessibility/Readability:
	- Color contrasts: All words on the websites(except for my name in the navbar) has a good color contrast, checked by Developer Tools-Select Element-Accessibility.
	- Font contrasts: I spent much time adding diffent font styles for the Homepage. Some important info are given a higher font-weight. The locations and dates are set as italic, while school/company names are larger, bolder and underlined, so that they could be easily distinguished especially when the screen size gets small and the spacings between them also shrink.
	- Spacing: I‘ve paid much attention to separating sections. E.g. For Homepage and Projects page, in addition to ordinary spacings, I even added box-shadow effect to "hightlight" the border of different sections. Also, I've intentionally left whitespaces on the left and right sides of the viewport.
	- Avoided long lines using "max-width". All lines don't exceed 70 characters in any screen size.
	- Use of icons: I used lots of svg icons to indicate different types of contents, so that users can easily distinguish and target the information they're interested in. (e.g. On Homepage-Education/Work Experience, I used different icons for degree, GPA, Relevant coureses, Job position, Job description.)
2. Branding:
	- I added a "C-logo" next to my name in the navbar, which uniquely represents myself as I have many "C"s in my name. :) Also, in the <head> tag, I also added an icon that will be displayed on the webpage tab.
3. Content diversity:
	- For the Hobbies page, instead of simply writing a paragraph about what I like, I added the Youtube link to my performances, which I believe will leave an impression on the users(potentially, recruiters).
4. Interesting/User-friendly animations: 
	- Navbar: When hovering onto the menu links, the page that is being targeted will be rendered with a different background color. When hovering onto the name title, it will have a "shake" effect.
	- Homepage-About me: The profile photo will be zoomed in when user hovers onto it.



## Additional features I would add if given more time or resources:
1. On Hobbies page, embed the video directory into my webpage instead of putting an image that links to Youtube website, which is my current solution.
2. Currently, the 4 pages don't follow a consistent color style. Some used background image and some used background. While this choice is deliberatedly made for practicing more ways of styling pages, I'd like to choose a similar color palette or background images of the same vibe to make the whole website more consistent.
3. The fonts in Projects page lacks styling. I'd add some "bold" or "italic" styles to emphasize some keywords if given more time. Also, I'll fill up the github repo of Othello Game project in the future.


## Total time spent: 3-4 days.

## References:
- Fonts library: Google fonts.
- Icon library: Flaticon: https://www.flaticon.com
- Name Logo: https://brandcrowd.com
- Background images: https://www.pexels.com/
- Navbar Styling: https://www.youtube.com/watch?v=At4B7A4GOPg