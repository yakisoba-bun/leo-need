# leo-need
A website for a band developed for a milestone project.

# User Goals

- To be able to book tickets to see the band live
- To find out more information about the band
- Find out when the band's next live shows are
- To watch music videos from the band
  
# User Stories

(Initial ideas for user stories)

- As a user, I want to find information about the band.
- As a user, I want to find out about the band's members.
- As a user, I want to be able to see some of the band's music videos and songs.
- As a user, I want to be able to book tickets to see the band.
- As a user, I want navigation to be easy and intuitive.
- As a user, I want the website to be accessible and responsive across multiple devices.

# Website goals/objectives

- Allow users to book tickets for the band
- Provide information to both fans and potential fans about the band
- Provide information about the band's individual members
- Allow users to watch the band's music videos
- Allow users to interact with the website on multiple platforms and screen sizes.
  
# Wireframes

Wireframes for this website were made using [Balsamiq](https://balsamiq.com/), which made it easier to plan the design for the website with functionality across multiple devices in mind. I first prioritised designing the website for mobile in line with the principle of mobile-first design, as it helps to make the website accessible and allowed me to scale up the website for larger screen sizes easier. The initial wireframes were mostly similar to what ended up being developed, with some key changes.

In the initial design, there was a carousel for band members on the tablet/laptop and desktop versions, along with information next to the carousel on each member. There was also a carousel for music videos with information on each music video, but the carousels were difficult to implement correctly without some issues with functionality. For example, the carousel scroll buttons would prevent the user from pausing or adjusting the volume for the music videos.

<details>
  <summary>**Initial wireframe for mobile version of website**</summary> 
<img width="576" height="3221" alt="Image of a wireframe of the website" src="https://github.com/user-attachments/assets/dfab9fcd-55c9-462b-b8a8-9fac0d728585" />
</details>

<details>
  <summary>**Initial wireframe for tablet/laptop version of website</summary>
<img width="1331" height="2609" alt="Homepage (Tablet)" src="https://github.com/user-attachments/assets/6a1a7675-31b3-45f0-9650-e14093535e1d" />
</details>

<details>
  <summary>**Initial wireframe for desktop version of website**</summary>
<img width="1415" height="2355" alt="Homepage (Desktop)" src="https://github.com/user-attachments/assets/e1e6b445-857b-44af-8d1b-6801db68f0b7" />
</details>


# Design choices
## Typography

I chose to use the Noto font family for the website as I wanted to use a font that looked professional, while also looking good. I used Google Fonts to find the font, using the filters to look for "Feeling - Business" and "Feeling - Calm" fonts as my main criteria. The font in question was sourced from [here](https://fonts.google.com/noto/specimen/Noto+Sans?lang=en_Latn&categoryFilters=Feeling:%2FExpressive%2FCalm).

## Colour Scheme

<img width="1600" height="1200" alt="leoneed site colour scheme" src="https://github.com/user-attachments/assets/4aa97081-8fb2-468e-868e-6300b82aa565" />

I chose these colours for the website as I wanted to use different shades of blue for the primary and secondary colours, and a darker shade for the tertiary colour. I then wanted to use black and white as they contrast each other well and would help contribute to good accessibility and readability for the website.

I also utilised EightShapes Contrast Grid as it gave me an easy to understand visualisation of how my chosen colours would contrast each other and how I could best meet accessiblity needs with the colours chosen.
<img width="615" height="593" alt="image" src="https://github.com/user-attachments/assets/f532480e-9545-4918-b6da-ebaf22c8b29e" />

## Images

Images used for band members and the band logo are official material from the game Project SEKAI COLORFUL STAGE! feat. Hatsune Miku, sourced from [Sekaipedia](https://www.sekaipedia.org/wiki/Main_Page).

## Responsiveness

I chose to incorporate responsiveness through the use of Bootstrap's breakpoints for viewport size, using media queries to adjust the website based on the viewport size. The breakpoints used are shown below:

<img width="819" height="271" alt="image" src="https://github.com/user-attachments/assets/f2b20749-a5f3-40ed-9fd7-85988cd118e7" />

# Features
# Existing features
## Navigation
The navigation was made using Bootstrap's responsive navbar as the base, further customising it to fit the website's color scheme and style.
## Header
(Describe styling used and how it links to other sections on the website)
## About
The about section shows an image of the band and describes the band. It also shows the band members individually and gives a description for each of them.
## Music 
The music section has a carousel where the user can watch music videos, being able to click through the carousel at their own pace.
## Booking form
The booking form leads to a (dummied) success page.
## Footer
(Describe styling)
# Technologies Used

- [Bootstrap Version 5.3](https://getbootstrap.com/) for (features that used bootstrap go here)
- Visual Studio Code (link here) as my chosen IDE
- Colors for the website picked from [coolors](https://coolors.co/)
- [W3Schools CSS Tutorials](https://www.w3schools.com/css/default.asp) used as a resource for various elements (e.g. how to center the hero-image)
- Initial code for the navbar from a previous project [Boardwalk Games](https://github.com/yakisoba-bun/boardwalk-games) done as part of the Code Institute course.
  
# Testing
# Internal and external links
The navigation bar links to each section of the website were tested to ensure that they sent the user to the correct sections, with enough scroll-padding to send the user precisely to the title of the section. The internal links work as intended. The "home" link seems to reload the page when clicked on, while the other links scroll the webpage as needed.
External links work as intended, sending the user to the correct website and opening in a new tab, as is required.
# Lighthouse 1st test
The first lighthouse test I performed, using the Github Pages deployment of the site, returned a score of 81 overall, with an 81 score in performance and an 80 score in accessibility. The best practices score was much lower at 56. As I tested it in Github Pages initially, I suspected that the performance score may have been lower as a result of that.
[The first test results](https://github.com/user-attachments/assets/86d406fe-9170-4f9f-8352-49fa20ca71b5) showed one easy change I could make was to add the meta tags to the head section of the webpage's HTML. I anticipated that this would help to raise the best practices score and raise the overall score as a result.
## Bugs and other issues
# CSS stylesheet
I had an issue after I began coding where I noticed that the CSS changes were not being added to the repository. I could not figure out a way to make it so that the IDE integration would mean the changes would be automatically uploaded, so I ended up using a workaround. I could instead upload the CSS file with changes I made to it and commit that to the repository.
## Validation

- HTML validation carried out via the W3Schools HTML validation tool
- CSS validation carried out via the W3Schools CSS validation tool
  
## Responsiveness testing
# Deployment
## Deploying project

The project was deployed very early on through the use of GitHub Pages. This can be done via:
- Going to the repository and clicking on Settings.
- From there, find "Pages" in the navigation.
- Find the dropdown that shows "none", click on it and select "main"
- Click save. The website is now live [here](https://yakisoba-bun.github.io/leo-need-website)

## Forking project
## Cloning project
# Credits
- Bootstrap's documentation](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- Official material used for band logos, members, and music videos from Project SEKAI COLORFUL STAGE! feat. Hatsune Miku
- Code to help with adding videos to the carousel and styling them came from [this post](https://stackoverflow.com/a/59595248) and was further adjusted
# Disclaimer
This site is entirely fanmade and is not in any way affiliated with SEGA, Colorful Palette, or Crypton Future Media.
