<h1 align="center">Milestone Project 1 - Core Gym</h1>

### [View The Live Project Here]()

## ![Text]()

## Introduction

This the website for 'Core Gym', a made up gym located in Leigh-on-Sea, holding the function of informing new and exisiting customers on all of the key information (Location, opening times, prices, etc.). This project was created using HTML and CSS, with the intention of allowing customers the ablility to navigate through it while being responsive on multiple screen sizes

## User Experience (UX)

-  #### First Time Customer Goals

    1. As a first-time visitor I want to easily navigate through the website in order identify what services are being offered.
    2. As a first-time visitor, I want to easily find the different pricing /membership options the gym has to offer.
    3. As a first-time visitor, I want to gain a sense of what the gym is like through attractive pictures.

-   #### Returning Customer Goals

    1. As a returning visitor, I want multiple ways of getting in contact in case I need to ask for extra information.
    2. As a returning visitor, I want easy access to social media links as a means of connecting with the rest of the community.
    3. As a returning visitor, I want readily available open/close times to adjust my plans accordingly.

-   #### Frequent Customer Goals

    1. As a frequent visitor, I want to easily find any deals/offers. 
    2. As a frequent visitor, I want to easily identify what classes/ facilities are on offer to observe any changes.

### Design

-  ### Colour Scheme

      - The main colours used are bright Red, pastel Yellow, pastel Blue and Chalk. 
      - [coolors](https://coolors.co/): Coolors has been used to aid the desision the colour sceme for the project.
      ### ![Text](docs/color-scheme/colors.png)


-   #### Typography

     -   The main fonts on this site are Oswald and Roboto with a fall back font of sans-serif.

-   #### Imagery

    #### [Pixels](https://www.pexels.com/) : Pixels images have been used to show the interior of the shop and the staff portraits.
    
    -  Header video:

    1. [Exercise video](assets/media/200657-913478674_medium.mp4)

     -  About us section images:

    1. [Abount us section image 1](assets/media/woman-6777444_640.webp)
    2. [Abount us section image 2](assets/media/man-8545861_640.webp)

    - Gallery images:

    1. [couple](assets/media/couple-7437534_1920(1).webp)
    2. [woman2](assets/media/gym-7705106_1920.webp)
    3. [bikes](assets/media/sports-1962574_1920.webp)
    4. [woman1](assets/media/gym-3516208_1920.webp)
    5. [treadmill](assets/media/gym-526995_1920.webp)
    6. [man1](assets/media/gym-2793007_1920.webp)
    7. [friends](assets/media/woman-1730325_1920.webp)
    8. [weight](assets/media/gym-2647292_640.webp)
    9. [man2](assets/media/fitness-465205_1280.webp)
    10. [equipment](assets/media/workout-1931107_1280.webp)
    11. [class](assets/media/fitness-4925664_1280.webp)
    12. [workout](assets/media/gym-6894893_640.webp)


### Wireframes

- Main Page Wireframe - [view](docs/wireframes/Main.png)

- Contact Page Wireframe - [view](docs/wireframes/Contact.png)

- Tablet Main Page Wireframe - [view](docs/wireframes/Main-tablet.png)

- Tablet Contact Page Wireframe - [view](docs/wireframes/Contact-tablet.png)

- Mobile Main Page Wireframe - [view](docs/wireframes/Main-mobile.png)

- Mobile Contact Page Wireframe - [view](docs/wireframes/Contact-mobile.png)

## Technologies used 

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 4.2:](https://getbootstrap.com/docs/5.1/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages to add icons forUX purposes.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts was used for all text across the webpage
1. [jQuery:](https://jquery.com/)
    - jQuery came with Bootstrap to make the dropdown menu work.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.

## Testing

### DevTools
<details><summary>Desktop results. Index.html followed by contact.html</summary>
<img src="docs/lighthouse/index.html.desktop-before.png">
<img src="docs/lighthouse/contact.html.desktop-before.png">
</details>
<br>

<details><summary>Mobile results. Index.html followed by contact.html</summary>
<img src="docs/lighthouse/index.html.mobile.png">
<img src="docs/lighthouse/contact.html.mobile-before.png">
</details>

### Improvements

A consistent issue throughout seemed to be revolving around accessibility. I targetted all the link elements and gave them discernible, unique and focusable link text. I also changed all jpeg image documents to webp documents. Lighthouse results after improvement:

<details><summary>Desktop results </summary>
<img src="docs/lighthouse/index.html.desktop-after.png">
<img src="docs/lighthouse/contact.html.desktop-after.png">
</details>
<br>

<details><summary>Mobile results.</summary>
<img src="docs/lighthouse/index.html.mobile.png">
<img src="docs/lighthouse/contact.html.mobile-after.png">
</details>
<br>

However, I found that when i resized the page for the index.html desktop page the best practices score dropped significantly

<br>
<details><summary>Desktop results - resized </summary>
<img src="docs/lighthouse/index.html.desktop-resized.png">
</details>
<br>

### Validator Testing 

HTML
<details><summary>Results No-issues</summary>
<img src="docs/validator-tests/contact.html.png">
<img src="docs/validator-tests/index.html.png">

</details>
<br>

CSS
<details><summary>Results No-issues</summary>
<img src="docs/validator-tests/style.css.png">
</details>
<br>

Color
<details><summary>Results-No issues</summary>
<img src="">
</details>
<br>

### Further testing 

I have tested this site on ...

### Testing User Experience (UX)

-  #### First Time Customer Goals

    1. As a first-time visitor I want to easily navigate through the website in order identify what services are being offered.
       1. Upon entering the website, users are greeted by a navigation bar in the header that they're then able to hover over to reveal locations for them to chose from. 
       2. The about section is close to the top of the page, allowing for a near-immediate insight into what the gym is hoping to provide.

       <details><summary>navigation</summary><img src="docs/screenshots/navigation.png"></details>
       <details><summary>about</summary><img src="docs/screenshots/about-section.png"></details>

    2. As a first-time visitor, I want to easily find the different pricing /membership options the gym has to offer.
       1. Using the navigation bar, users can easily direct themselves to the memberships section, which has all the info on deals and membership prices.
       
       <details><summary>membership</summary><img src="docs/screenshots/membership.png"></details>

    3. As a first-time visitor, I want to gain a sense of what the gym is like through attractive pictures.
       1. The video playing just below the header allows for an immediate view into the gym.
       2. The website also features a gallery, allowing a full insight into the gyms scenery and equipment.
       
       <details><summary>video</summary><img src="docs/screenshots/hero-image.png"></details>
       <details><summary>gallery</summary><img src="docs/screenshots/gallery.png"></details>
       
-   #### Returning Customer Goals

    1. As a returning visitor, I want multiple ways of getting in contact in case I need to ask for extra information.
       1. Customers can be taken to a contact form where they can get in touch with the gym and even leave a personal message for any specific questions.
       2. Just below the opening times is the gyms main email address and phone number.
       
       <details><summary>form</summary><img src="docs/screenshots/form.png"></details>
       <details><summary>number/address</summary><img src="docs/screenshots/number-address.png"></details>
       
    2. As a returning visitor, I want easy access to social media links as a means of connecting with the rest of the community.
       1. Both the main and contact page feature social media links in the footer.
       
       <details><summary>socials</summary><img src="docs/screenshots/social-media.png"></details>
       
    3. As a returning visitor, I want readily available open/close times to adjust my plans accordingly.
       1. Clear opening and closing times, Mon - Sun, are features at the bottom of the page above the footer.
       
       <details><summary>times</summary><img src="docs/screenshots/open-close.png"></details>

-   #### Frequent Customer Goals

    1. As a frequent visitor, I want to easily find any deals/offers. 
       1. The memberships section features all available deals. Also the discount code section on the form presents all accessible codes.
       2. Just below the header is a clickable link, immediatley informing them on a deal available to them.

       <details><summary>discounts</summary><img src="docs/screenshots/discounts.png"></details>
       <details><summary>header link</summary><img src="docs/screenshots/header-link.png"></details>
    
    2. As a frequent visitor, I want to easily identify what classes/ facilities are on offer to observe any changes.
       1. The gallery features faciltities specific to Core Gym.

## Deployment 

### Github Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/CassJBeckford/CoreGym-MP1)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Main Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://github.com/CassJBeckford/CoreGym-MP1/deployments/activity_log?environment=github-pages) in the "GitHub Pages" section.


### Forking the Github repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/CassJBeckford/CoreGym-MP1)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.


### Making a local clone 

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/CassJBeckford/CoreGym-MP1)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.


Alternatively, if using Gitpod, you can click below to create your own workspace using this repository.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/CassJBeckford/CoreGym-MP1)

## Credits