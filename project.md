# MIS3690 Web Technologies - Term Project (subject to changes)

## What is the Term Project?

The term project requires you to conceptualize, design, and implement a website. This is an individual effort. 

The website must be published using following hosts: 
1. GitHub project repository
2. ~~the internal FTP server provided to you by Babson as part of this course~~
3. (Optional) external web host or cloud service (if you want to use backend programs, i.e. PHP or Python.) It is important that the web hosting service must provide ad-free service. .

You will be required to 
1. purchase a domain
2. (optional) use web hosting service. You can
   - pay a hosting fee for the service such as GoDaddy or BlueHost, which is total to about \$10-\$30   
   - or use (free) cloud service such as Heroku, Amazon Web Services (AWS), Google Cloud Platform, or DigitalOcean.

The project is to be developed throughout the term and completed in two intermediate stages plus the final submission. The project must be completed and submitted to the instructor by the last day of class. All intermediate stages must be submitted on the day it is due. Each intermediate deliverable is graded and late submissions are penalized 3 points for every day it is late. Extensions may be granted at the instructor’s discretion provided you make the request before the due-date. Every deliverable is mandatory and has to be submitted, even if it is late.

## Examples of Term Project:

Your term project website may be based on any topic that conforms to [Babson’s Policy on Terms of Use](https://www.babson.edu/terms-of-use/). Also remember that the course only addresses browser-side development. The course does not cover back-end databases, middleware or e-commerce. So, users will not be able to provide comments on your site that can be stored and retrieved later, upload images or multimedia to your website and, not be able to buy/sell products using your website. You can, however, design your site so that it can be extended to support these features at a later stage (beyond this course).

## Examples of Term Projects (to give you a flavor):

1. travel2hk – a site dedicated to informing travelers about Hong Kong and its attractions. It includes night-life, dining options, sites to see, weather, fashion, and even a converter to covert temperature and currency (between Hong Kong currency and any other currencies of the world).
2. JRC Interiors – a website to support a family-owned interior design business. Besides information about the owners, it also presents a portfolio of projects completed, artwork available for sale and creative ideas for decorating your home/office.
3. The Jaucy Store – a website for making and selling clothing and accessories made from recycled products. It offers a catalog of products that the users can browse and insights into making some of these products.
4. Paulina’s DR – a site dedicated to highlighting the lifestyles of people in the Dominican Republic.
5. All About Red Sox – you guessed it and it even has video links to some best moments in history!
6. Tie-Off – a site for the Babson Tie-Off organization that helps international students in Babson improve their logical, analytical and persuasive skills. The site includes pictures from past events, information on how to become a member, events scheduled for the semester/year and details about their executive board.
7. Enzo Ferrari – a website dedicated to the life and inventions of Enzo Ferrari.
8. Trip of the Century – a complete description of places, sights, food and experiences of a student that traveled to Italy on a study-abroad program. It is designed for conveying the student’s perspective on the trip and includes a gallery of pictures that you can purchase.

## Things You Cannot Do:

- technologies that are covered in this course generally

Some items that are strictly prohibited are:

- Adobe Flash files
- Server-side scripts (except for _mailer.php_ and _index.php_).
- JavaScript files that you have not developed
- CSS templates that are not customized 
  - you need to customize it at least by removing all of the CSS elements that you have not used in your website pages.
- Website templates or pages developed by any Content Management Systems (CMS) such as WordPress, Drupal or Joomla.

All the HTML code must be your own.

---

## Getting Started

To start your project, you need to create a **_new public_** repository in GitHub.

## Project Proposal

Due: **Monday 2/22/2021, by 11:59 PM**

This is a webpage that answers the following questions:

- What is your website about?
- What is the objective of your website? (Also read as why would this site be important?)
- Who is your target audience set?
- What content do you plan to include in each page of your website?

As you think through your website, please remember that the website must have at least 4 pages of content besides the homepage, sitemap, and contact/feedback pages.

This first version is worth **5 points**.

### Submission:

- Create a webpage, _proposal.html_, save it to project repository (not **_WebTech_** repository).
- Use necessary CSS to style this page.
- **_Commit/push_** to GitHub.

---
## Website Planning
Due **Sunday 2/28/2021, by 11:59 PM**

This part is worth 5 points.

### What you need to do:
1. Read [Planning a simple website](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure#Planning_a_simple_website).
2. Create a folder called "*website-design*" under your project repository. This folder should at least contain files for the following items:
   1. Draw a sketch of your project homepage (index.html) as step 2 in the [article](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure#Planning_a_simple_website). Use any tool such as figma.com, moqups.com, or PowerPoint, or even simply draw on a paper and take a photo.
   2. Create a rough sitemap as step 5 in the [article](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Document_and_website_structure#Planning_a_simple_website).


---

## Project Version 1

Due **Wednesday 3/10/2021, by 11:59 PM**

This must be your complete website, including all of the content that you expect to have in your final submission. Note, only the content must be in place. CSS, JavaScript and jQuery elements are not required for this version. All navigation (links) must be in place. So, please DO NOT TREAT IT LIKE A FIRST DRAFT.

This first version is worth **30 points**.

### Grading Rubric:

- Objective of the website clearly evident upon entry and content supports the overall objective. (3 points)
- Use of a table. (3)
- Use of a form. (3)
- Images are appropriately used and adequate to support the website. (2)
- Images are defined using both `alt` and `title`. (2)
- Video/YouTube video included. (optional)
- Audio file included on the home page with controls. (optional)
- Homepage should be called _index.html_. (1)
- Sitemap included (see sample site map at [Apple Site Map](https://www.apple.com/sitemap)). (5)
- Contact page included with a feedback form. (3)
- At least 2 of the 4 content pages are completed with informative and relevant content. (3)
- Navigation bar is located in the same place on each page. (3)
- Links to the sitemap page and the contact/feedback page must be available from the navigation bar or from links at the bottom of the page. (2)

### Submission:

- Save all the files in project repository.
- **_Commit/push_** to GitHub.
- Create tag `'v1.0'` for current release. Learn [creating a release](https://help.github.com/en/github/administering-a-repository/managing-releases-in-a-repository).
- Link your own domain to GitHub pages of project repository. Add Description and Website to your project repository on GitHub (see below).
![](https://i.imgur.com/QAhOGVJ.gif)
- Submit the URL to your website (not GitHub) on Canvas.

---

## Project Version 2

Due **Wednesday 3/31/2021, by 11:59 PM**

This version has two parts.

1. Extend Version 1 by adding styles and by filling in the gaps that may exist.
2. ~~Have your web host (or cloud) and domain name available with all the files uploaded.~~ 
   
This deliverable is worth **25 points**.

### Grading Rubric:

- If you are using web host/cloud, all the pages must be hosted on web host/cloud. Add the website domain to _sitemap.html_ in _WebTech_ repository. (6)
- Look and feel of your site (use of colors, fonts, backgrounds and consistency of styles across the pages) (7) 
  - This is a relative assessment and is based on how well you have used the combination of external style sheet and internal styles to provide consistency across pages and to differentiate individual pages, in addition to the cheerful and welcoming feel that the website creates based on all the styles.
- Create a [favicon](https://developer.mozilla.org/en-US/docs/Glossary/Favicon) and add it to your site. See [how to](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/The_head_metadata_in_HTML#Adding_custom_icons_to_your_site) and [online favicon generator](https://favicon.io/). (3)
- Attention to SEO principles. Check out `<meta>` part in [*Publishing your website*](https://github.com/MIS3690/resources/blob/master/slides/lec10-publish-website.pdf). (3)
- A separate credits page included if credits are due to sources for images, multimedia, or content. If no credits are due, then add the following statement at the end of your sitemap page _"All intellectual property at this website is in the public domain or is the property of the site-owner."_ (3)
- Include the honor code at the end of the sitemap page: "I, \<_your name_\>, pledge my honor that I have neither received nor provided unauthorized assistance during the completion of this work. I have read the term project instructions and observed all the restrictions and limitations specified therein." (2)
- The remaining content pages are completed and linked to the website. (2)

### Submission:

- Save all the files in project repository.
- **_Commit/push_** to GitHub.
- Create tag `'v2.0'` for this release.
- If you are using web host/cloud, upload all the files to web host (or cloud).

---

## Project Final

Due **Friday 4/23/2021, by 11:59 PM**

The final version of the project must have the full set of project files on GitHub and linked to _sitemap.html_ in _WebTech_ repository (both GitHub URL and website domain). If you are using web host/cloud, upload/update all the files to the web host/cloud.

This deliverable is worth **40 points**.

### Grading Rubric:

- Improvement on content and styles.
- JavaScript is used for the following functionalities/effects:
  - Change the text on a page in response to the user’s action. (2)
  - Change the style of some element in response to the user’s action. (2)
  - Validate a form. (2)
  - Change image(s) using mouseover and mouseout. (2)
  - Present a slide-show. (optional, but recommended) (2)
  - Animate something or add some other functionalities besides what is listed above. (3)
- ~~Some jQuery elements are present on the website. (3)~~
- Responses to peer review feedback

### Submission:

- Save all the files in project repository.
- **_Commit/push_** to GitHub.
- Create tag `'final'` for this release.
- If you are using web host/cloud, upload/update all the files to the web host/cloud.


---
*updated: 1/17/2021*