
** Visit Westminster**

# Introduction

We were given the task of producing a three page site on any topic, as long as it was approved, using only HTML and CSS. No other technologies, such as Java Script, were to be used. The site is to be appealing so the rule of thirds was used where possible and appropriate colours and fonts were used.

After doing some work on a different topic I decided to do a site about the City of Westminster. Being a Westminster resident, and having been one about 40 years ago, travelling by bicycle and public transport, I felt I knew enough about the borough to more than fill the three pages required.

As the site was to have three pages I decided they would be “Home”, “Links” and “FAQ and Contact”. 


# Files

The site is composed of three types of file as follows:

 - HTML files, these are the actual pages
 - Image files. There are three different image types and they have all been optimised
 - CSS file. This containes the styling for the HTML pages that is not taken care of by Bootstrap

The HTML files are in the root directory, the other files are in the assets folder. The assets folder itself contains two subdirectories, one containing all the images (called images) and the other containing the CSS file (called css).


# Technologies used

Only HTML and CSS were allowed and the site had to be fully responsive. Bootstrap 5 was used to make the site resposive, in particular its flexbox and grid technologies and capabilities. Many Bootstrap classes were used as they improved the appearance of the site.

Some Bootstrap classes use Java Script but, as this was invisible to the programmer,  we were told they were allowed.

The head of each page contains meta tags to help the site to be found and improve its rankings in search results and contains information such as author and name.

The project was developed and hosted on Github from several locations using different computers. 

## Requirements and Installation
The site only requires six HTML pages and one style page to be hosted although there are many image files too. Any additional support is called from scripts in those pages.

## Layout
The layout was designed using a wireframe to make sure the main features of the site were:
 - Eye and attention catching
 - Visually appealing
 - Easily accessible for anyone and easy to use and navigate

During the design I made sure to implement the Surface, Skeleton, Structure, Scope, and Strategy planes and this produced a framework which was very helpful in designing the site.

Colour is important and was decided using my own judgement rather than by consulting Internet palettes. As there are so many images on the site only understated colours were used. The page backgrounds are grey and with some panels being white text on black backgrounds and others being different shades of grey and blue grey. These do not distract from the plentiful images and give the site authority. The footer, however, has a coral background to prompt visitors to read all the way down to the foot of the page.

These colours were also selected for a technical reason. The site can be viewed on a phone and darker backgrounds will drain the battery less without losing any visual appeal.

The site was also viewed as it would be seen by someone with protanopia and someone with deuteranopia (colour blindnesses). The images appear differently but all the text, links and instructions are clearly visible.

The screen reader tags were all filled in and can be followed and read by screen readers.

## Wireframe
A wireframe was created, as mentioned above, and the design for each page is reproduced below.

**Home Page**
![image info](../Westminster/assets/images/readme%20images/home_page_wireframe.PNG)

**Links Page**
![image info](../Westminster/assets/images/readme%20images/links.PNG)

**FAQ and Contact Page**
![image info](../Westminster/assets/images/readme%20images/faq.PNG)


## Design Consideratons

As visitors have many temptations to jump to other sites and links it is essential to keep them engaged at all times. The main methods of doing this are:
 - Design
 - Layout
 - Message

The design of each page will be considered in the section which has a detailed analysis of each page. One of the overall design considerations, however, is which font to use. Following convention one font was used for headings and another for text. Actually choosing the actual fonts was easy. 

As sans-serif fonts are considered easier to read than serif fonts on computer screens one was used for headings. Some advantages of serif fonts such as looking elegant, and trustworthy and being confident were conveyed by the font in the longer text where a serif fonts was used.

The choice of actual font was largely left to the legendary designer [Massimo Vignelli](http://www.designculture.it/interview/massimo-vignelli.html#start) who said "In the new computer age, the proliferation of typefaces and type manipulations represents a new level of visual pollution threatening our culture. Out of thousands of typefaces, all we need are a few basic ones, and trash the rest."

He designed the signage for the New York subway and did much other timeless work so I simply used one of his preferred sans serif fonts for headings and one of his preferred serif fonts for the other text which is short anyway so visitors are unlikely to leave having gone that far.

Vignelli also said "The life of a designer is a life of fight: fight against the ugliness" and as there is so much class and beauty in Westminster, fighting ugliness was not difficult. Although not mentioned in the site there were 1,968 rough sleepers in Westminster making it the London borough with the highest number of rough sleepers in 2021/22. Had this been a real website I would have liked to have added a way for visitors to make a donation to a homeless charity like Crisis as I did a couple of voluntary shifts for them over Christmas.

Images were easy to find as Westminster has so many famous sites and such a rich history. Most images were downloaded from Pexels.com although some were downloaded from other sites which allowed them to be used freely and one was downloaded from Adobe who allowed some free images in the first month of membership. No video, graphic or sound files appear on the site.

The three pages produced were a home page, a links page and a contact and FAQ page and were produced for the following reasons:
 - Every site needs a home page
 - As three pages is nowhere near adequate for a site about Westminster it was decided to have a links page leading to other sites with more information about special things in Westminster. Links pages are no longer in fashion so it was implemented in a different way, by having pictures of attractions set up as links.
 - The European Court of Justice has decided electronic contact forms can comply with the E-commerce Directive so a form was put on the FAQ and Contacts page to be compliant and to enable a different technology to be used. That page also has an accordion with Frequently Asked Questions (FAQ) both to show proficiency with a new technology and to enable a lot of textual information to be contained without intimidating the visitor with a visuql barrage of text. 

## Site Map
I produced a site map showing the navigation around and from the site although, being only three pages, it is fairly straightforward. The main complication is the large number of connections from the Links page.
```
```
![image info](../Westminster/assets/images/readme%20images/Site%20Map%20(5).png)
```
```
## Detailed Analysis Of Each Page

**Parts Common To Each Page**
Each page has the same header and footer. The header "logo" was taken from the [Westminster City Council](https://www.westminster.gov.uk/) and put on a transparent background. 

The "Visit Westminster" title is an h1 and the navigation icons are adapted from a Bootstrap navbar.

The footers were also adapted from a Bootstrap footer. They contain links to terms and privacy pages which are only accessible from the footers and cannot be reached by the navbar. 

The footers also contain copyright and publisher information and the opposite side has a link to the top of the page. This was more to provide visual balance than because it is needed although it might be helpful on smaller screens. 

The centre of the footer bears social icons which are links the home page of each site and open in a new browser tab so as not to lose the visitor.

**Home Page** 
The home page uses a carousel in order to attract attention by having images moving and, once a visitor had seen a picture change, they would be likely to wait to see what the next picture is and then become more interested in the site.

One of the pictures is the Abbey Road street sign which most people are acquainted with and will attract the attention of people scanning sites. Another is a picture of the Westminster station sign with the Queen Elizabeth Towere (Big Ben) in the background. The third image is of a group of Bearskins which always draws attention.

These were delivered using the carousel from [the Bootstrap 5 website](https://getbootstrap.com/docs/5.3/components/carousel/#how-it-works) and no additional images were added as three was enough. There is no hero image as such as the three carousel images are attention seeking. For those who are not attracted by them there is a picture of Margaret Thatcher below it which promotes a reaction in most people. She is mentioned as she lived in Westminster for many years but not because of her politics but because of her contribution to ice cream manufacture. As an aside she did enormous damage to the UK dairy industry by closing the Milk Marketing Board. 

On one side of Margaret Thatcer there is a picture of a good looking dog which I had used as a placeholder when constructing the site and whom I did not have the heart to delets. Luckily I managed to make up something about how dog lovers can visit the borough.

On the other side there is a night time view of the Palace of Westminster from accross the Thames which is recognised by almost everyone as one of the sights of London.

The carousel tself is flanked by texts, one of which gives a few of the Westminster attractions and the other gives a very brief history of the borough. The texts are displayed as white text on a black background.

Below Margaret Thatcher there is a group of three cards, the central one containing an image of the late Queen in a horsedrawn carriage in a state event and some interesting facts on either side for visual balance.

At the foot of the page, above the footer, there is, on the full screen display, some text saying how easy it is to get to and from Westminster and an image of a Westminster roundel. The image distorts when it is on smaller screens so it does not show then. 

Below the text there is a button opening a link to a new browser tab opening Google Maps at Trafalgar Square, 

**Links Page**
This has the same header and footer as the other pages with the active page in the navbar appropriately amended.

Below this there is a well emphasised piece of text ensuring visitors know how to reach the links and that the sites linked are not the responsibility of the publisher. The links are to 15 Westminster attractions including Buckingham Palace, Regent Street and WestminsterAbbey as well as many others.

The links are almost all images in a [Masonry display](https://masonry.desandro.com/) with some text below them which also link to the same target. It would have been possible for the image, the subtitle and the text each to be linked to a different target but explaining this would have been too complicated so they all link to the same place.

**FAQ And Contact Page**
The page is in two halves. The top half contains the FAQ's which, as mentioned above, are contained in an accordion to look less intimidating. The accordion was limited to six questions to give visual balance but could easily have been expanded. The questions included are both for visitors to Westminster and those moving to the borough. Opposite the accordion in the top half of the page there is a picture of the Wallace Collection and some text above it saying how much there is to do and see in the borough. 

The bottom half has some information telling site visitors that the publishers are happy to help with any enquiries and opposite this there is a form. Each of the fields of the form must be completed before he form can be submitted.

**The Style Page**
The styling not controlled by Bootstrap is generated in a Cascading Style Sheets (CSS) page.  

**404 Page**
A 404 page was constructed which has an optimised image and some text all of which is linked back to the home page. If a visitor should end up at the 404 page clicking almost anywhere will take them to the home page.

**Minor Pages**
Links to a privacy page and a terms page were put on the footer. Each of these pages is boilerplate taken from Internet sources which are only there for the sake of completeness.

## Further Improvements
The site can easily be improved by adding additional pages covering additional topics. Topics that would benefit the site inlude
 - An email address and maybe a phone number for enquiries although there is a form
 - Information for anyone moving to Westminster
 - Information for anyone visiting Westminster
 - lists of businesses serving the area such as builders, estate agents, restaurants, markets, shops and some of the other information those moving to Westminster might need
 - Additionally there could be similar images for visitors including boarding establishments, tour guides, bureaux de change and other useful information
 - A technical shortcoming of the site is that the carousel gets very small when the viewport gets to the Bootstrap small breakpoint. In a further iteration the layout from this breakdown would be altered to give a better view of the carousel from this breakpoint


## **THANKS 

Much thanks must go to our teacher, Richard Malhotra, for tirelessly helping and instructing us even though we sometimes did not make it easy. I am also indebted to my classmates, in particular Rod Gordon, Alesio Migotti and Rosie Jones, for their help and support throughout the course.

## CONCLUSION**

I hope the site does Westminster justice, is visually appealing and is informative. Creating it has taught me how to create sites without HTML authoring packages such as Dreamweaver or Wordpress, and has given me the ability to create a site from first principles. Learning to use Bootstrap has enabled me to create fully responsive sites so they can be viewed with any device. 

Designing the site really gave me an understanding of the importance of the five planes of user experience and how important it is to start from there rather than from wanting to use a new technology or method and also of the importance of good design.

The groundwork has been laid for a much bigger site and adding pages would not be difficult.


 
