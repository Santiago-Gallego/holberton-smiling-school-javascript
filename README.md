# Holberton Smiling School Javascript


## Description

Implement web pages with Bootstrap

-   [Homepage](https://intranet.hbtn.io/rltoken/X5mp-bZwa8Jzi3HI4xqSLA "Homepage")  -  [fig file](https://intranet.hbtn.io/rltoken/zsIWYdFMnWtImWisjLgfTw "fig file")
-   [Pricing](https://intranet.hbtn.io/rltoken/Bbop8wwZOLJsavfT6szqdQ "Pricing")  -  [fig file](https://intranet.hbtn.io/rltoken/5yAyDbQvLAVmm3IC_NRV3g "fig file")
-   [Courses](https://intranet.hbtn.io/rltoken/PSFYeol4NYMEmSBsxUyuoQ "Courses")  -  [fig file](https://intranet.hbtn.io/rltoken/Jzp3WS1dZwYd8Q_wTIYp9Q "fig file")


<p align="center"><img src="https://github.com/afinesami/holberton-smiling-school-javascript/blob/main/3c71cc99d2fc1c12a3d3.jpg" alt="final result"></a></p>

---
# holberton-smiling-school-javascript
* This is a fullstack web specialization project at Holberton school.
* The goal of this project is a implement a Figma design template in HTML, CSS and Bootstrap
* The project has no guiding instructions.
* There are 3 page to implement.
* There are 3 different layout (desktop, tablet and mobile) for each page.


### [Reuse and polish your Bootstrap integration](./0-homepage.html)
* Copy files from [0x0B. Implement a design with bootstrap](https://github.com/Santiago-Gallego/holberton-smiling-school)

### [Homepage - quotes](./1-homepage.html)

Replace static quotes by dynamic loading:

-   URL:  `https://smileschool-api.hbtn.info/quotes`
-   No static quotes should be present in the quotes section
-   During the Ajax request, a loader should be present
-   Carousel should work like before

### [Homepage - popular tutorials](./2-homepage.html)

Replace static video cards by dynamic loading:

-   URL:  `https://smileschool-api.hbtn.info/popular-tutorials`
-   No static video cards should be present in the section
-   During the Ajax request, a loader should be present
-   Carousel should work by sliding card by card (like GIF below) - this kind of carousel is not unique, make it generic to reuse it easily!
-   Don’t forget the responsive part!

### [Homepage - latest videos](./homepage.html)

Replace static video card by dynamic loading:

-   URL:  `https://smileschool-api.hbtn.info/latest-videos`
-   No static video cards should be present in the section
-   During the Ajax request, a loader should be present
-   Carousel should work by sliding card by card (like GIF below) - this kind of carousel is not unique, make it generic to reuse it easily!
-   Don’t forget the responsive part!

### [Pricing - quotes](./pricing.html)

Replace static quotes by dynamic loading:

-   URL:  `https://smileschool-api.hbtn.info/quotes`
-   No static quotes should be present in the quotes section
-   During the Ajax request, a loader should be present
-   Carousel should work like before

### [Courses](./courses.html)

Replace static video card by dynamic loading:

-   URL:  `https://smileschool-api.hbtn.info/courses`
    -   `GET`  parameters:
        -   `q`: search value (in our case, the value of the field KEYWORDS)
        -   `topic`: topic filter value (in our case, the value of the field TOPICS)
        -   `sort`: order of all courses (in our case, the value of the field SORT BY)
-   No static video cards should be present in the section
-   During the Ajax request, a loader should be present
-   Dropdowns are dynamic (coming from the API):
    -   Topic: list of  `topics`
    -   Sort by: list of  `sorts`
-   Search value should be initialized by the value  `q`  in the API response
-   The list of video cards is coming from  `courses`  in the API response
-   API request must be done when:
    -   Search value is changing
    -   A new Topic is selected
    -   A new Sort by is selected


## Author
* **Santiago Gallego** - [Santiago-Gallego](https://github.com/Santiago-Gallego)

## Requirements
* We have to use Bootstrap.
* Our styles.css must be as small as you can - we must use as much as we can Bootstrap classes.
* The web pages have to be responsive.
* Will have import fonts from Google, JQuery and Bootstrap CSS/JS.

## Best practices to follow for this project
* Use Bootstrap as much as possible.
* Use personalized CSS as little as possible.

## Design informations
* Web pages must switch to the tablet version when the screen width is 768px
* Web pages must switch to the mobile version when the screen width is 576px
* button hover/active: opacity: 0.9
