# leo-need
A website for a band developed for a milestone project.

# User Goals

- To be able to book tickets to see the band live
- To find out more information about the band
- Find out when the band's next live shows are
- To watch music videos from the band
  
# User Stories

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

| CSS Variable       | Colour  | Comment                                                                                                  |
|--------------------|---------|----------------------------------------------------------------------------------------------------------|
| --primary-color    | #021775 | Primary blue colour, used for background for the majority of the website                                 |
| --secondary-color  | #4560c6 | Secondary blue colour, used for the header and footer                                                    |
| --tertiary-color   | #3e457d | Tertiary blue colour, used for the background of the cards to distinguish them from the main background  |
| --text-color-light | #FFFFFF | Used as the main text colour as it offers good contrast with my chosen colour scheme                     |
| --text-color-dark  | #000000 | Used in some cases to offer better contrast to white text, primarily used in the titles for each section |

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

The navigation was made using Bootstrap's responsive navbar as the base, further customising it to fit the website's color scheme and style. Inside the navbar, each nav element takes the user to the appropriate part of the website by scrolling to the section that the user chooses. For example, clicking "Tickets" takes the user down to the tickets section by scrolling the webpage.

## About

The about section shows an image of the band and describes the band. It also shows the band members individually and gives a description for each of them, including details about their personalities, what they like and dislike, and when their birthdays are.

## Music 

The music section has 3 music videos for users to watch, that showcases the band and their music. On larger screens, the videos are shown side-by-side horizontally, while on smaller screens the videos are stacked vertically.

## Booking form

The booking form leads to a (dummied) success page. The user is required to input their details in each element of the form with the correct layout (e.g. emails must include an @ symbol), and they can then submit their details. Those details are fed back to the user on the dummied success page.

## Footer

The footer uses the same colour as the navbar, as it sandwiches the website content nicely between them. Inside the footer, there are social media links that take the user to the appropriate social media sites. As the website is for a fictional band on tour, the links take the user to the sites but not to a specific account on the social media sites.

# Technologies Used

# Languages
- HTML
- CSS
- JS
  
# Frameworks/Libraries

- [Bootstrap 5](https://getbootstrap.com/) for functionality across the entire website
- FontAwesome
- Google Fonts
  
# Tools
- Visual Studio Code as my chosen IDE
- Git and GitHub for version control
- Colors for the website picked from [coolors](https://coolors.co/)
- [W3Schools CSS Tutorials](https://www.w3schools.com/css/default.asp) used as a resource for various elements (e.g. how to center the hero-image)
- [W3Schools HTML Validation tool](https://validator.w3.org/#validate_by_input)
- [W3Schools CSS Validation tool](https://jigsaw.w3.org/css-validator/)
- Initial code for the navbar from a previous project [Boardwalk Games](https://github.com/yakisoba-bun/boardwalk-games) done as part of the Code Institute course.
- 
# Testing

# Internal and external links
The navigation bar links to each section of the website were tested to ensure that they sent the user to the correct sections, with enough scroll-padding to send the user precisely to the title of the section. The internal links work as intended. The "home" link seems to reload the page when clicked on, while the other links scroll the webpage as needed.
External links work as intended, sending the user to the correct website and opening in a new tab, as is required.

# Lighthouse 1st test
The first lighthouse test I performed, using the Github Pages deployment of the site, returned a score of 81 overall, with an 81 score in performance and an 80 score in accessibility. The best practices score was much lower at 56. As I tested it in Github Pages initially, I suspected that the performance score may have been lower as a result of that.
[The first test results](https://github.com/user-attachments/assets/86d406fe-9170-4f9f-8352-49fa20ca71b5) showed one easy change I could make was to add the meta tags to the head section of the webpage's HTML. I anticipated that this would help to raise the best practices score and raise the overall score as a result.

## Bugs and other known issues
# Issues styling titles
I wanted to more clearly split each section of the website up by giving my titles black backgrounds and stretching them across the page to divide the website up more clearly. I however ran into issues making sure the title backgrounds stretched the full width of the page. With mentor assistance I was able to use `container-fluid ` to fill more space, but it wasn't entirely consistent. It was suggested I use `px` to fill in the remaining space but I wasn't entirely sure on how to do so.

# CSS stylesheet
I had an issue after I began coding where I noticed that the CSS changes were not being added to the repository. I could not figure out a way to make it so that the IDE integration would mean the changes would be automatically uploaded, so I ended up using a workaround. I could instead upload the CSS file with changes I made to it and commit that to the repository.

## Validation

The validation of the HTML and CSS was done using W3Schools' HTML and CSS validation tool.

<details>
  <summary> First HTML validation test </summary>
  <img width="1203" height="643" alt="image" src="https://github.com/user-attachments/assets/8d20fc82-82f8-46ad-9fc4-9624fd44c052" /> 
  <img width="1398" height="315" alt="image" src="https://github.com/user-attachments/assets/09a3da4c-0c1b-4628-ab6d-d83c5ed87770" />
</details>

The first HTML validation test found numerous errors and warnings that I needed to fix in order to pass the test. The easiest to fix were errors related to duplicated element IDs, namely as I initially used "thanks" as a singular ID for all of the thank you images in the Tickets section. There were also some errors with unused tags such as one ending div element that wasn't used. However, I initially retained some duplicate IDs, such as "hero", as I felt it was more convenient and easier to retain them and had no impact on the functionality of the code.

<details>
  <summary> Second HTML validation test</summary>
  <img width="1378" height="174" alt="image" src="https://github.com/user-attachments/assets/7ae7c011-ebab-47d6-a20e-e04ca4f53c61" />
</details>

The second HTML validation test, after I had cut out most other errors, ended up only returning an error with using "frameborder" on the iframe elements that were used to display the music videos. After doing some research, I found that it was an error that could not be avoided in HTML. The other option to fix the error would have been to use "video" elements instead, but I chose to keep the iframe elements and accept that the error was not fixable. The only warning was related to a section element lacking a heading, but this was not causing any issues, so I chose to ignore the warning.

<details>
  <summary>First CSS validation test using the W3Schools CSS validation tool</summary>
  <img width="376" height="80" alt="image" src="https://github.com/user-attachments/assets/efb997e6-e4da-4d23-b452-a5830eef2a15" />
</details>

The first CSS test found no errors with the CSS in my stylesheet, so did not require me to make any further changes to the CSS.
  
## Responsiveness testing

I used [Am I Responsive?](https://ui.dev/amiresponsive) to check what my website would look like on different devices, and then used Google Chrome's Dev Tools and checked how responsive the website was across multiple devices. The table below shows the device examples used, and how good functionality, navigation, alignment, and content were on the website on those devices.

| Device/Size                               | Alignment | Content | Navigation | Functionality | Comments                                                                        |
|-------------------------------------------|-----------|---------|------------|---------------|---------------------------------------------------------------------------------|
| Samsung Galaxy S20 Ultra (sm)             | OK        | Good    | Good       | Good          | Slight concern about alignment, but it is consistent.                           |
| iPhone 14 Pro Max (sm)                    | Good      | Good    | Good       | Good          | Noticed an issue with navigation, requires user to scroll up to close nav menu. |
| iPad Mini (md)                            | Good      | Good    | Good       | Good          | No new concerns.                                                                |
| iPad Air (md)                             | Good      | Good    | Good       | Good          | No new concerns.                                                                |
| iPad Pro (lg)                             | Good      | Good    | Good       | Good          | No new concerns.                                                                |
| Nest Hub Max (xl)                         | Good      | Good    | Good       | Good          | No new concerns.                                                                |
| Laptop (1024px screen size - xl)          | Good      | Good    | Good       | Good          | No new concerns.                                                                |
| Laptop/Desktop (1400px screen size - xxl) | Good      | Good    | Good       | Good          | No new concerns.                                                                |

The initial tests showed I had an issue with my navbar and its functionality. It was requiring the user to scroll up to show the navbar fully after scrolling down, and when opening the dropdown in the navbar, the user would also have to scroll up slightly to be able to close it again.

# Deployment
## Deploying project

The project was deployed very early on through the use of GitHub Pages. This can be done via:
- Going to the repository and clicking on Settings.
- From there, find **Pages** in the navigation.
- Find the dropdown that shows **none**, click on it and select 'main
- Click save. The website is now live [here](https://yakisoba-bun.github.io/leo-need-website)

## Forking project

- Log in to GitHub.
- Locate the repository.
- Click to open it.
- The fork button is located on the right side of the repository menu.
- To copy the repository to your GitHub account, click the button.

## Cloning project

- Log in to GitHub.
- Navigate to the main page of the repository and click **Code**.
- Copy the URL for the repository.
- Open your local IDE.
- Change the current working directory to the location where you want the cloned directory.
- Type git clone, and then paste the URL you copied earlier.
- Press Enter to create your local clone.
  
# Credits

- [Bootstrap's documentation.](https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- Official material used for band logos, members, and music videos from Project SEKAI COLORFUL STAGE! feat. Hatsune Miku.
- Code to help with adding videos to the carousel and styling them came from [this post](https://stackoverflow.com/a/59595248) and was further adjusted.
- My mentor, Simen Daehlin, for help with numerous issues and giving great advice throughout on multiple areas of the development process.
- My tutor, Tom Cowen, for 1-1s during the course of development, and offering help if I struggled while working on the website.

# Disclaimer

This site is entirely fanmade and is **not** in any way affiliated with SEGA, Colorful Palette, or Crypton Future Media. 
