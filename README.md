# Magical Mystery Tours

So, you're a Beatles fan, are you? You've got all the albums and love everything about them, I'm sure. But have you ever considered visiting some of the towns and cities that made them what they are today? You're probably curious as to where they first met, where they found love, where they called home? We have the answers! So, book a tour with us and together we'll explore some of the well-known (and some of the lesser known) places of interest that helped sculpt the fabulous foursome in becoming the most decorated and idolised band the world has ever seen.

### [Live Site](https://justwhitegit.github.io/magical_mystery_tour/)

## UX 

This website has been developed for fans of the Beatles. A site to book sight-seeing tours in different locations across the globe delivered by experts and lifetime fans of the band. To experience first-hand the various locales, venues, lifestyles and important historical landmarks that influenced the bands success. 

#### Strategy

The aim was to create a site with an exciting interface with exaggerated colour and psychedelic content to compliment one of the bands most iconic eras. Images, typography and styling has been presented to reinforce Beatles nostalgia. 

#### Scope

For users, I provided a site that could captivate intrigue in order to sell sight-seeing tours providing interesting content on each of the band members and their lives. 

#### Structure

Ease of use was important, so a single page site was created with sectional content to scroll through. Each section is presented with intuitive presentation with clickable extensions to view more information on individual content when desired. 

#### Skeleton

The use of Balsamic wireframe mock-ups helped with the initial design and continued development of the site. 

* [Home](https://github.com/JustWhiteGit/magical_mystery_tour/tree/master/wireframes/home)
* [About](https://github.com/JustWhiteGit/magical_mystery_tour/tree/master/wireframes/about-us)
* [Band](https://github.com/JustWhiteGit/magical_mystery_tour/tree/master/wireframes/the-band)
* [Packages](https://github.com/JustWhiteGit/magical_mystery_tour/tree/master/wireframes/tour-packages)
* [Contact Us](https://github.com/JustWhiteGit/magical_mystery_tour/tree/master/wireframes/contact-us)

#### Surface

Presented with eye-catching colours and bold typography applicable to the band genre. 

## Features 

#### Implemented
* Presented with full title screen home page and a single menu toggle to find each section. Whereas for desktop/large screen viewports an expanded centralised menu to navigate the site which remains fixed for user transparency. 

* Smooth scroll configuration provides clean transition from section to section in both mobile and desktop display. This allows the viewport to display each section independently and snaps back to the relevant section with the most content in the user’s viewport display. 

* Factual biopics of each band member is displayed with a corresponding silhouette image to contrast with the busy multicoloured backdrops. Each member has expandable content available for the user to toggle. 

* Tour packages presented cleanly with contrasting simplicity against the bold background, maintaining consistent user experience. Each tour has more content available that can be switched on/off with the use of more info buttons.

* The contact us section provides a simple form structure with free-text space and selectable drop-down options. This area also provides usable links to social media sites within a new tab, to further improve user experience. 

* Due to the visually stimulating style of the site, scroll bars have been removed to reduce unnecessary visual noise. The use of the fixed menu bar and smooth scrolling pages provides ample options for navigation. 

#### Future release
* Interactive Google map interface with highlighted areas of interest in conjunction with the available tour packages. 

* Enriched testimonial section for further user reviews.

* Gallery with tour images/fan's photos.

## Technologies
* [Gitpod](https://www.gitpod.io/) Online IDE for GitHub & GitLab.
* [HTML](https://www.w3schoolshttps://www.gitpod.io/.com/html/) The standard markup language for Web pages.
* [CSS](https://www.w3schools.com/css/) Language that describes the style of an HTML document.
* [Bootstrap](https://getbootstrap.com/) An open source toolkit for developing with HTML, CSS, and JS.
* [FontAwesome](https://fontawesome.com/) Popular icon set and toolkit.
* [Balsamic](https://balsamiq.com/) A user interface design tool for creating wireframes. Use it to generate digital sketches of your product ideas.
* [Canva](https://www.canva.com/)/[Pixabay](https://pixabay.com/)/[Pexels](https://pixabay.com/) Free stock image libraries.


## Testing

The aim to produce a vibrant site promoting the business' sight-seeing tour packages has been achieved. The user can review available tours and make contact with the business directly. 

The site has been tested thoroughly throughout its production with the support of both the [HTML](https://validator.w3.org/#validate_by_input) and [CSS](https://jigsaw.w3.org/css-validator/#validate_by_input) Validation Services run by [W3.org](https://www.w3.org/). They have been used to identify errors (such as stray divs) and as a tool to promote confidence in producing legitimate code.

Initial intentions of having a site with parallax scrolling pages were abandoned in lieu of a smooth scroll design with snap-back actions. This was the favoured choice owing to the lack of textual content outside of the cards/modals deployed for styling this site. I opted for bold backgrounds to fill each section and initially found the images were rendering as zoomed-in which had poor resolution and was hindering the load speed; fixed with the ```background-size:cover;``` command within the CSS.

Working with a fixed navbar for full screen devices and opting for a 'hamburger' menu for small devices I encountered some issues with the responsiveness. The toggler would not present the list cleanly and would nestle within the section display. Although not highlighted using the validation, I was able to identify and remove an unnecessary ```nav``` class which remedied the issue. 

I was able to utilise Bootstraps cards and modals to present content cleanly however I encountered many issues with size and responsiveness on smaller devices. With the cards possessing different volumes of content, the cards would not display in linear form. Despite stacking on reduced resolutions, the cards would occupy varied space and looked haphazard. I introduced flex utilities and a height modify ```h-100``` to the columns to repair this which resulted in a more pleasing appearance of similarity. A new version release of Bootstrap has addressed known issues with its card deck functionality. 

I have tested this site with Google Chrome throughout its development; making use of the dev-tools supplied through the Inspect options, to adjust my code where applicable. I have also tested the site manually with Mozilla Firefox, Opera Browser and Microsoft Edge. I found that the smooth scrolling effect applied was not supported by Edge. Although this has removed the smooth transitions (between pages) for the Edge user, a scroll bar becomes active to navigate the sections and the site can be used as intended. The other browsers worked fine.

Further responsiveness testing has been conducted with the use of [mediaGenesis'](https://responsivedesignchecker.com/) responsive website design checker which renders this site in 27 different viewport resolutions; including extra small devices such as the iPhone 5/SE.

All navbar menu items direct the user to the correct destination.
Menu items, buttons and social media icons have ```hover``` functionality working effectively.
Each link will open in a new tab using the ```target="_blank``` command. 
The contact us form is not connected to an API and will not allow submission.






## Deployment

This site has been built using the Gitpod IDE via the Code Institutes 'gitpod-full-template' and hosted on GitHub. It is deployed directly from the master branch and the site will update automatically upon new commits to the master branch. For the site to deploy correctly on GitHub pages, the landing page must be named ```index.html```

To run locally, you can clone this repository directly into the editor of your choice by pasting ```git clone https://github.com/JustWhiteGit/magical_mystery_tour``` into your terminal. To cut ties with this GitHub repository, type ```git remote rm origin``` into the terminal.




## Credits/Acknowledgments

I have used the learning from the Full Stack Web Developer course to build this website. I have utilised many platforms to develop this learning and improve my understanding of the core structures in this build.

* In principle, the learnings from [Bootstrap](https://getbootstrap.com/) and [W3Schools](https://www.w3schools.com/) and their libraries of content have been essential. 
* I have used [Material Design for Bootstrap (mdbootstrap)](https://mdbootstrap.com/) and [Stack Overflow](https://stackoverflow.com/) to seek public viewpoints on issues that I encountered when Bootstrap and W3School did not present an answer. 
* YouTube content has helped me understand HTML and CSS behaviours to a greater depth. Special mention to [_DevTips_](https://www.youtube.com/user/DevTipsForDesigners/videos), [_Traversy Media_](https://www.youtube.com/user/TechGuyWeb/videos), [_Academind_](https://www.youtube.com/channel/UCSJbGtTlrDami-tDGPUV9-w/videos), [_Kevin Powell_](https://www.youtube.com/user/KepowOb/videos), [_w3newbie_](https://www.youtube.com/user/TheMACinTUTS/videos), [_Codersbite_](https://www.youtube.com/channel/UC8c4OFeOvNGmUlHLfQb9TVg) and [_Clever Techie_](https://www.youtube.com/channel/UC1WxZFhq56xs1oxXH-XveSQ) for their tutorials.
* I have sought advice from Slack and Tutor Support and would like to acknowledge in particular, _Tim Nelson_ and _Anna Greaves_ for their patience and assistance. 
* All textual content has been provided by myself.
* Any code utilised from the aforementioned sources has been modified to support my site. With exception of some JavaScript code I used for the navbar's auto closing behaviour found here at [mdbootstrap.com](https://mdbootstrap.com/support/general/auto-close-navbar-when-click-on-link-responsive-mode/).
* Images have been obtained from the free stock libraries mentioned above.


**-This is for educational use-**
