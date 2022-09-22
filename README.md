# Inner Peace

This website is aimed at users that want to view meditation techniques and yoga positions that would be relevant to their skill level. There is a page for beginners, intermediates and advanced experience, as well as a sign up page for a newsletter.

### Features

![Responsive Mockup](media/mockup.png)

- The inital mockup was to have a large image with a small motto to really introduce what the website was going to be all about. I did want a more fluid layout with the pictures and decription boxes next to them with a slight overlap, but during testing that proved to be an issue when styling the different window sizes. So I went with a stacked and side by side view.

![Nav Bar](media/nav-bar.png)

- I went with a simple nav bar that had each page available from the start so you can get straight to where you want to go. This bar is available on every page in the same order to allow ease of access to where you need to be. When switchin to a tablet or mobile view the bar becomes stacked to still allow users to navigate to where they'd like to go. 

![Main Page](media/main-page.png)

- I wanted the main picture to have the image of a silhouette of a person and kept her in the middle of the screen during the responsive tests and have the motto in the middle of her. 
- The image and descriptions below give an idea of why and how you can be performing yoga and meditation to really emphasize to the user why they would want to come to this site for assistance no matter the experience level.

![Experience Level Links](media/experience-level.png)

- Here I have presented an easy way for users progressing through the website to go straight to their level without having to go back to the top of the page. They can click the entire box rather than just the text itself. I also gave the font a black outline to make it easier to read as the backgrounds had many colours to them. They are all responsive and the text gets smaller to accomodate the smaller size on tablet/mobile.

![Footer](media/footer.png)

- I used a simple design for the footer where the images of the social medias could be easily seen and clicked on. They will link the user to the appropriate website and in a new tab. That way they don't lose where they were on the website if they wanted to come back.

![Experience content](media/example-routine.png)

- On each of the experience pages I wrote a simple title to introduce the user to the page that they are on and made it appropriate to their skill level. Then used a description box on the left with an example image on the right so they user has an idea in their mind of how to do it. The description includes how to do it with how many repetitions they may want to do as an example.

![Newsletter Sign Up](media/sign-up.png)

- The Sign-Up page is used for the user to stay engaged with updates on the page which would include new exercises and additions they may want to see in the future. The sign-up form includes their name and email address which are all required. There is also a checkbox to agree to receiving emails from the website which is also a required box. 

### Testing

- During testing there were lots of bugs that had to be completely overhauled. I have managed to fix almost all of them. 

- The images on the homescreen kept getting stuck outside the browser window or kept overlapping with the text boxes. Was due to using background-image: url(''). Changed it to an img tag. Also the initial id I was using for the div id="exercises" was a class and causing more issues down the road. Especially when starting on the mobile view. When I was working on the experience pages, I made a id which worked a lot better. When applied to the homepage it worked a lot nicer. 

- Working on the skill section at the bottom. Initially the images would have black lines where the aspect ratio was getting too far. Found out there is a "resize: cover" which scales the image as the page is resized. It still isn't as perfect as I'd like, as some images are panned to the wrong place I'd like them to be (Like in the experience pages in some views you can only see the top of the picture when ideally I'd like to have the bottom).

- When introducing mobile and tablet sizes, the nav bar is initially in the top right, but with resizing, it becomes vertical. Making it horizontal again stretches it across two lines. For now I'm fine with this as it isn't hideous. But for future reference I'd write the rest of the page more "correct" to avoid this issue.

- The footer bar when resized would stack up unless the font size for i would be reduced and padding/margin edited. 

- The nav bar was also reversing the order unless changed to flex and column-reverse. I realised I had also changed to id so when looking at the other pages it wasn't applying the changes and took a while to figure out a simple solution. 

- Deploying the page initially the img's weren't loading even though they were in the assets/images folder. I had linked using '/assets/images/...' and took a minute to realise the /assets/ was supposed to be assets/images. 

- I've used Nu HTML checker and have no errors after testing - https://8000-kuurosu-myfulltemplate-d71f970sp90.ws-eu60.gitpod.io/stream-one.html

- I've used W3C CSS Validation Service to confirm no errors after multiple testing and finding bugs - https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fkuurosu.github.io%2Finner_peace%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en

### Unfixed Bugs

- I can't get the footer to stretch across the entire page unless it is fixed. Ideally I'd like to come back and fix the issue which I suspect is because of the layout I have done with the rest of index.html. 

- I'd like to have the content boxes more center. At the moment I have to adjust the positon using padding and margin to keep it center when viewed on mobile/tablet.

## Deployment

After I had the initial site and styling applied for desktop. I deployed the page to GitHub pages. The live version can be found here - https://kuurosu.github.io/inner_peace/

## Credits

### Content

- The routine and description content of the page was written by me using pre-existing knowledge.

- I used form layout from the Love-Awesome project.

- The icons and script found in the footer bar were taken from https://fontawesome.com/

- I used a text shadow technique from a stackoverflow page found here https://stackoverflow.com/questions/2570972/css-font-border

### Media

- The media used was taken from https://www.pexels.com/. I found images that suited my needs and wrote a simple routine to go along with them. 

- The colour scheme used was from a website https://coolors.co/ to generate a similar and complimenting colour scheme.