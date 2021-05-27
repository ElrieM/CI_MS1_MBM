# Mind Body Motion Wellness Centre Website

[View live project here](https://elriem.github.io/CI_MS1_MBM/)

This is a business website for the Mind Body Motion Wellness Centre, a fictional fitness centre offering yoga, meditation and tai chi classes. It is designed to be responsive on a range of devices, making it easy to navigate for prospective students and existing students.

The website provides users with information about the process for joining classes, where to locate the gym, instructor biographies and a downloadable timetable.

![mockup](docs/readme/responsivescreens.png)

- [Mind Body Motion Wellness Centre Website](#mind-body-motion-wellness-centre-website)
  - [User Experience (UX)](#user-experience-ux)
    - [User Stories](#user-stories)
      - [First Time Visitor Goals](#first-time-visitor-goals)
      - [Returning Visitor Goals](#returning-visitor-goals)
      - [Frequent User Goals](#frequent-user-goals)
    - [Site Owner Stories](#site-owner-stories)
      - [Site Owner Goals](#site-owner-goals)
    - [Design](#design)
      - [Colour Scheme](#colour-scheme)
      - [Typography](#typography)
      - [Imagery](#imagery)
    - [Wireframes](#wireframes)
  - [Features](#features)
    - [Existing Features](#existing-features)
    - [Features Left to Implement](#features-left-to-implement)
  - [Technologies Used](#technologies-used)
    - [Language Used](#language-used)
    - [Frameworks, Libraries & Programs Used](#frameworks-libraries--programs-used)
  - [Testing](#testing)
    - [Testing User Stories from User Experience (UX) Section](#testing-user-stories-from-user-experience-ux-section)
    - [Further Testing](#further-testing)
    - [Known Bugs](#known-bugs)
  - [Deployment](#deployment)
    - [GitHub Pages](#github-pages)
    - [Forking the GitHub Repository](#forking-the-github-repository)
    - [Making a Local Clone](#making-a-local-clone)
  - [Credits](#credits)
    - [Code](#code)
    - [Content](#content)
    - [Media](#media)
    - [Acknowledgements](#acknowledgements)

## User Experience (UX)

### User Stories

#### First Time Visitor Goals

  1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the fitness centre.
  2. As a First Time Visitor, I want to be able to easily navigate throughout the website to find more information about which classes are available, their suitability and what to expect.
  3. As a First Time Visitor, I want to be able to easily navigate throughout the website to find out more about the instructors, ensuring that I am in the class I expected to attend.
  4. As a First Time Visitor, I want to be able to easily navigate throughout the website to find more information about the tariffs and package deals available.
  5. As a First Time Visitor, I want to locate social media links to see the fitness centre's social presence and find out more about other students' experiences.
  
#### Returning Visitor Goals
  
  1. As a Returning Visitor, I want to find the best way to get in contact for any queries I might have.
  2. As a Returning Visitor, I want to find information regarding registering for upcoming events.
  3. As a Returning Visitor, I want to find information about prices and buy additional class bundles.

#### Frequent User Goals
  
  1. As a Frequent User, I want to sign up to the Newsletter to be informed of upcoming events and receive health and wellbeing advice.
  2. As a Frequent User, I want to be able to view changes to the timetable and new classes becoming available.
  3. As a Frequent User, I want to register for classes or events, and / or buy additional class bundles.

### Site Owner Stories

#### Site Owner Goals

1. As the Site Owner, I want to make information easily accessable to prospective and existing students, thereby reducing the number of queries sent and the time spent on administrative tasks.
2. As the Site Owner, I want to provide students with the centre's processes and procedures to allow them to prepare for their visit.
3. As the Site Owner, I want to inform students (existing and prospective) of upcoming events.

### Design

#### Colour Scheme

- The main colours, generated from colormind.io, are:
  - Light Shades - Fresh Linen #e1dbcf (header, accents)
  - Light Accent - Calm Pink #f2e5dd (background and accents)
  - Main brand colour - Garden Air #d4e0d6
  - Dark accent - Grateful Green #acbba6 (accents)
  - Dark shades - Moonlight Forest #334545 (text)

#### Typography

- Predominantly 2 fonts were used throughout the website:
  - The Lato font is the main font used throughout the whole website, with Sans Serif as the fallback font in case the font does not import correctly into the site. It is summarised as "Male and female, serious but friendly. With the feeling of the Summer". This fits well with the fitness centre, which should have a calm and inviting feeling, but also reflects the seriousness of wellbeing and health.
  - The Dancing Script font was selected for the quotes and class descriptions. It is described as "a lively casual script where the letters bounce and change size slightly" and ideal for a friendly, informal and spontaneous look. I selected it to bring an elegant playfulness to the design, as a compliment to the seriousness of the Lato font.

#### Imagery

- To make the website stand out, I opted for a full page background on the landing page. For responsiveness, I opted to use different background pictures for tablets and mobiles that scaled better to the device. The bright colours of the outfits, the muted backgrounds and the general beauty of the pictures engages with site visitors, immediately telling the visitor what the organisation is about.

### Wireframes

- Home page wireframe - [view](docs/wireframes/home.png)
- About page - [view](docs/wireframes/about.png)
- Classes page - [view](docs/wireframes/classes.png)
- Schedule and Rates page - [view](docs/wireframes/schedule.png)
- Contact page - [view](docs/wireframes/contact.png)

## Features

### Existing Features

- Responsive on all device sizes
- Interactive elements
- Form to register for events and / or classes
- Download timetable from website

### Features Left to Implement

- Interactive event registration - allows users to register for events directly from website
- Interactive class booking - allows users to book, or cancel, directly from the website
- Adding information about additional therapies (massage, sauna, reiki, etc.)
- Incorporating advertising for partners with yoga retreats, through social media feed.

## Technologies Used

### Language Used

- HTML 5
- CSS

### Frameworks, Libraries & Programs Used

- Bootstrap 5:
  - Bootstrap was used to assist with the responsiveness and styling of the website:
    - Horizontal alignment navs & tabs used for navbar
    - Used stacked to horizontal grid for introduction section on home page
    - For the image gallery on About page, used Carousel
    - Sign up for newsletter form created with modals
    - Classes layout uses List Group, with headings as disabled items
    - Contact form elements
  - Google Fonts:
    - Google Fonts were used to import the "Lato" and "Dancing Script" fonts into the style.css file used on all pages throughout the website.
  - Font Awesome:
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
  - jQuery:
    - jQuery in conjunction with Bootstrap make the navbar, modal, accordion and carousel responsive.
  - Git:
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
  - GitHub:
    - GitHub is used to store the projects code after being pushed from Git.
  - Microsoft Paint and Microsoft Photos:
    - Used to crop and resize images where required.
  - Microsoft Excel:
    - Used to prepared PDF schedule available for download from Schedule page.
  - Balsamiq:
    - Balsamiq was used to create the wireframes during the design process.

## Testing

The following tools were used to validate every page of porject to ensure there were no syntax errors in the project:

- HTML - W3C Markup Validator. Report can be found [here](docs/readme/html-validation.pdf)
- CSS - W3C CSS Validator. All errors / warnings relate to Bootstrap and Font Awesome, no errors or warnings from CSS style file. Report can be found [here](docs/readme/css-validation.png)
- Accessibility - WAVE Web Accessibility Evaluation Tool. Report can be found [here](docs/readme/wave-validation.pdf)
- Performance - Chrome Lighthouse. Report can be found [here](docs/readme/lighthouse-validation.pdf)

### Testing User Stories from User Experience (UX) Section

- First Time Visitor Goals

  1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the fitness centre.
     1. Upon landing on the site, users see women practicing yoga in the background, with a short introduction, overview of what to expect and benefits of yoga and meditation.

     2. In the navigation bar, users have the option to find out more about the wellness centre in the About tab, learn more about classes in the Classes tab or view the Schedule and Rates if they are ready to start attending.
  2. As a First Time Visitor, I want to be able to easily navigate throughout the website to find more information about which classes are available, their suitability and what to expect.
     1. The website is designed to flow, easily returning to the main page or any other page that the user visited / wants to visit.

     2. A link to the Classes tab is included in the top navigation bar as well as in the footer to make it easiest for users to access.

     3. The Classes page is presented in different "phases" of yoga, from beginner to looking for something a bit more relaxing to a more intense workout. It also includes a class picture and a short description.

     4. To make them more easily distinguishable from the "normal" yoga classes, the prenatal yoga, pilates and taichi classes are presented separately under Other Classes.
  3. As a First Time Visitor, I want to be able to easily navigate throughout the website to find out more about the instructors, ensuring that I am in the class I expected to attend.
     1. On the About page, users can view pictures of the instructors along with a short inspirational quote to give the user a sense of the instructor, and a list of classes that the instructor leads.
  4. As a First Time Visitor, I want to be able to easily navigate throughout the website to find more information about the tariffs and package deals available.
     1. In the navigation bar, users can follow the link to the Schedule and Rates page to view the rates per class as well as bundle options.
  5. As a First Time Visitor, I want to locate social media links to see the fitness centre's social presence and find out more about other students' experiences.
     1. In the footer, links to the wellness centre's social media pages are available.

     2. Social media icons are included to draw users' attention.

     3. Social media links open on a new page, so that the user does not navigate off the site. This hopefully will remind the user, when they return to the site, to either sign up for a class or get in contact if they require more information.
  
- Returning Visitor Goals
  
  1. As a Returning Visitor, I want to find the best way to get in contact for any queries I might have.
     1. A Contact link is included in the upper navigation bar as well as in the footer bar.

     2. The contact page includes an enquiry form, which has dropdown options for the subject, to ensure that their query is directed to the best person to assist.
  2. As a Returning Visitor, I want to find information regarding registering for upcoming events.
     1. An Upcoming Events section is included in the lower part of the landing page, showing upcoming events.

     2. Users are able to submit a booking request for events in the contact form.

     3. Users also have the option to sign up for the newsletter, which will allow them to be notified of upcoming events automatically.
  3. As a Returning Visitor, I want to find information about prices and buy additional class bundles.
     1. As with new users, users can follow the link in the navigation bar to the Schedule and Rates page to view the rates per class as well as bundle options.

     2. For users registered for the newsletter, announcements of price changes and bundle rates will automatically be communicated.

     3. In the Contact page's Enquiry form, users have the option to select Membership queries for additional questions about rates or renewing class bundles.

- Frequent User Goals
  
  1. As a Frequent User, I want to sign up to the Newsletter to be informed of upcoming events and receive health and wellbeing advice.
     1. A Sign Up Here link is included on the upper navigation bar, in inverted colours to draw the user's attention.

     2. The Sign Up Here link opens a modal, where users can include their contact details.

     3. There is also a requirement for the user to agree to privacy terms, which mention GDPR and its information use conditions.
  2. As a Frequent User, I want to be able to view changes to the timetable and new classes becoming available.
     1. In the upper navigation bar and the footer, users can navigate to the Schedule.

     2. Users also have the option to download the timetable in PDF to view offline.
  3. As a Frequent User, I want to register for classes or events, and / or buy additional class bundles.
     1. The Contact page's Enquiry form allows for the options to Book a Class, Register for an event, or Membership queries.

     2. Users can also user the email address, telephone number or WhatsApp to reach out for assistance.

- Site Owner Goals

1. As the Site Owner, I want to make information easily accessable to prospective and existing students, thereby reducing the number of queries sent and the time spent on administrative tasks.
   1. Prospective and existing students can find information about classes, instructors, the working rules, what to bring along etc. from the website.

2. As the Site Owner, I want to provide students with the centre's processes and procedures to allow them to prepare for their visit.
   1. On the About page, prospective and existing students can view expectations for before, during and after class.

   2. Prospective and existing students can find out what equipment is available in order to best prepare for the class.
3. As the Site Owner, I want to inform students (existing and prospective) of upcoming events.
   1. Events are included on the landing page, among the first content visible to prospective and existing student.

### Further Testing

- The website was tested on Google Chrome, Internet Explorer and Microsoft Edge.
- The website was viewed on a variety of devices, such as a Desktop, Laptop, iPhone Xs and iPhone 11s.
- Significant testing was performed to ensure all pages linked correctly.
- Friends and family were asked to review the site and documentation to point out bugs and /or user experience issues.

### Known Bugs

- The website is not optimised for Internet Explorer. No additional work was performed to optimise the site for IE as (extended) support has ended for customers since January 2020 and no further development of IE is expected.

- On Home page, on Desktop, there is a pink strip covering the background image that doesn't belong there.

- Layout of instructors on About page doesn't break into 2 rows.

- Class schedule becomes very small, with text spilling into other blocks. Attempt to make table scroll across not successful.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages as follows:

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/ElrieM/CI_MS1_MBM)
2. Locate the "Settings" button in the menu above the Repository.
   - Alternatively, click [here](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site) from the "Creating your site" section for a description of the process.
3. Scroll down the Settings page until you locate the "GitHub Pages" section.
4. In the "Source" section, select the dropdown "Branch:" dropdown and select "Main".
5. The page refreshes automatically.
6. Scroll to "Your site is published at..." for the puslished site link in the "GitHub Pages" section.

### Forking the GitHub Repository

A fork is a copy of the repository, allowing you to experiment with changes without affecting the original project.

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/ElrieM/CI_MS1_MBM)
2. In the banner above the Repository, click on the "Fork" button.
3. If you have succeeded, you now have a copy of the original repository in your GitHub account.

### Making a Local Clone

A clone allows you to create a local copy of a repository on your computer and sync between your computer and the GitHub repository.

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/ElrieM/CI_MS1_MBM)
2. Click on Code, click on the copy button  next to HTTPS to copy the URL.
3. Open Git Bash.
4. Change the current working directory to the location where the cloned directory should be stored.
5. Type "git clone', then paste the URL copied in step 2.
6. Press Enter to create a local clone.

Alternatively, click [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository) for a guide to clone a repository.

## Credits

### Code

- Bootstrap 5: Bootstrap Library used to make the site responsive using the Bootstrap Grid System
- W3schools.com used for making changes to formatting and customising Bootstrap content used.
- mdbootstrap.com for Carousel multiple items [here](https://mdbootstrap.com/snippets/jquery/ascensus/135508#html-tab-view)
- freecodecamp.org for understanding why the footer won't stay put [here](https://www.freecodecamp.org/news/how-to-keep-your-footer-where-it-belongs-59c6aa05c59c/) and [here](https://css-tricks.com/couple-takes-sticky-footer/)

### Content

- Home page:
  - "Introduction" section was adapted from [here](https://www.nhs.uk/live-well/exercise/guide-to-yoga/).
  - "What to Expect" section was adapted from [here](https://www.nhs.uk/live-well/exercise/guide-to-yoga/) and [here](https://www.nytimes.com/guides/well/beginner-yoga).
  - "Benefits" section was adapted from [here](https://www.nytimes.com/guides/well/beginner-yoga).
  - Events were adapted from [here](https://delightyoga.com/studio/workshops/)
  - Instructor names were randomly generated [here](https://www.name-generator.org.uk/)

- About page:
  - Instructor names (5 to 12) were randomly generated [here](https://www.name-generator.org.uk/)
  - Address randomly generated from [here](https://www.fakeaddressgenerator.com/World/Netherlands_address_generator)
  - "Quotes" copied from [here](https://www.therandomvibez.com/short-quote/)
  
  - Facilities and house rules adapted from [here](https://www.thewellnesscenter.org/newstudents)

- Classes page:
  - Class descriptions were adapted from [here](https://www.thewellnesscenter.org/class-descriptions) and [here](https://delightyoga.com/studio/yoga/styles) for yoga and [here](https://www.evolvewellnesscentre.com/yoga) for pilates.

- Schedule page:
  - Timetable inspiration from [here](https://www.evolvewellnesscentre.com/timetable) for the purpose of getting a more realistic weekly class schedule.

- Contact page:
  - Phone number, email address and WhatsApp contact numbers are fictional.
  - Address randomly generated from [here](https://www.fakeaddressgenerator.com/World/Netherlands_address_generator)
  - Guidance on how to embed Google Maps on website from [here](https://www.geeksforgeeks.org/how-to-add-google-map-inside-html-page-without-using-api-key/)

### Media

- Logo used in header
  - Lotus flower person vector from [here](https://www.pngkey.com/download/u2e6a9t4t4i1o0u2_lotus-zen-comments-you-need-care-too-self/)

- Cover page(s):

  - Desktop - Photo by Elly Fairytale from [Pexels](https://www.pexels.com/photo/woman-in-blue-sports-bra-and-white-leggings-doing-yoga-3822166/)

  - Tablet - Photo by Elly Fairytale from [Pexels](https://www.pexels.com/photo/woman-practicing-yoga-3822457/)

  - Mobile - Photo by Elly Fairytale from [Pexels](https://www.pexels.com/photo/woman-practicing-yoga-3822369/)

- Sign-up modal background - Photo by Eternal Happiness from [Pexels](https://www.pexels.com/photo/photo-of-woman-posing-during-golden-hour-3326362/)

- Instructor photos were randomly generated from [here](https://thispersondoesnotexist.com/) and saved as image files.

- Gallery images:
  - Pilates_ball (slide 2) - Photo by Andrea Piacquadio from [Pexels](https://www.pexels.com/photo/young-ethnic-woman-with-fit-ball-sitting-on-floor-while-training-in-modern-gym-3768593/)
  - Prenatal_yoga (slide7) - Photo by Gustavo Fring from [Pexels](https://www.pexels.com/photo/women-doing-yoga-3984363/)
  - Yoga_pose (slide 5) - Photo by cottonbro from [Pexels](https://www.pexels.com/photo/2-topless-women-in-black-leggings-and-black-sunglasses-4327139/)
  - Yoga_supplies (slide 6) - Photo by cottonbro from [Pexels](https://www.pexels.com/photo/woman-in-black-sports-bra-and-black-leggings-standing-beside-brown-wooden-chair-4327007/)
  - Yoga_assistance (slide 4) - Photo by Cliff Booth from [Pexels](https://www.pexels.com/photo/women-doing-yoga-4057067/)
  - Yoga_class (slide 3) - Photo by Andrea Piacquadio from [Pexels](https://www.pexels.com/photo/women-doing-a-yoga-on-yoga-mat-3775587/)
  - Yoga_class_2 (slide 1) - Photo by Elly Fairytale from [Pexels](https://www.pexels.com/photo/woman-practicing-yoga-3822692/)
  - Lounge (slide 8) - Photo by KoolShooters from [Pexels](https://www.pexels.com/photo/healthy-light-relaxation-relaxing-6246210/)
  - Locker_room (slide 9) - Photo by Polina Tankilevitch from [Pexels](https://www.pexels.com/photo/changing-room-3875514/)

- Images for class descriptions:
  - Ashtanga Photo by Elly Fairytale from [Pexels](https://www.pexels.com/photo/women-practicing-yoga-3822305/)
  - Yoga Basics Photo by Elly Fairytale from [Pexels](https://www.pexels.com/photo/yoga-instructor-helping-a-student-3822689/)
  - Hatha Photo by Elly Fairytale from [Pexels](https://www.pexels.com/photo/women-in-sports-bras-and-leggings-doing-yoga-3822356/)
  - Vinyasa Flow Photo by Elly Fairytale from [Pexels](https://www.pexels.com/photo/yoga-instructor-helping-a-student-3822691/)
  - Restorative Yoga Photo by Elly Fairytale from [Pexels](https://www.pexels.com/photo/women-practicing-yoga-3822164/)
  - Tai Chi picture, used image of similar yoga position. Photo by Elly Fairytale from [Pexels](https://www.pexels.com/photo/women-practicing-yoga-3822171/)
  - Pilates Photo by Andrea Piacquadio from [Pexels](https://www.pexels.com/photo/three-woman-doing-an-exercises-868757/)
  - Yin Yoga Photo by Elly Fairytale from [Pexels](https://www.pexels.com/photo/women-practicing-yoga-3822165/)
  - Prenatal Yoga Photo by Gustavo Fring from [Pexels](https://www.pexels.com/photo/cheerful-group-of-pregnant-women-practicing-yoga-in-modern-studio-3984367/)

### Acknowledgements

- My mentor for helpful feedback and some supportive words when I was overwhelmed.
- My partner for enduring countless "poepie, wat van die" (loosely translates to "honey, what do you think of this") and patience.
- My brothers for words of encouragement and their support.
