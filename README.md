
# Table of Content
- [User Experience](#user-experience)
  * [Initial Discussion](#initial-discussion)
  * [User Stories](#user-stories)
- [Design](#design)
  * [Colours](#colours)
  * [Wireframes](#wireframes)

# User Experience

## Initial Discussion
Hacks4Life is a website to teach people useful lifehacks to make their lives easier. 
The lifehacks shown on this site are considered the most useful lifehacks around.
Due to the discussion of which lifehack is more useful than the other, Hacks4Life provides a feedback/ contact form to reach out to us and state your case why your lifehack is more useful.

### Key information for the site
* What are the most useful lifehacks of present-day
* Which Lifehack is more useful than the other
* A way for people to contact the website with questions, recommendations and discussions.
---
## User Stories

### Client Goals
* To have a readable and an responsive website 
* To teach users genuinely useful lifehacks
* To allow users to give feedback on the showcased lifehacks
* To allow users to send their own lifehacks 

### First Time Visitor Goals
* I want to know what Hacks4Life is
* I want to learn the most useful lifehacks
* I want to know where to find Hacks4Life on social media
* I want an easy to navigate website

### Returning Visitor Goals
* I want to see an updated website with new useful lifehacks
* I want to contact Hacks4Life to contribute to the content
* I want to contact Hacks4Life to comment on the content

### Frequent Visitor Goals
* I want to see new content with new lifehacks
* I want to know if my suggested content is posted on the site

---

# Design
## Colours
![Hacks4Life Colour Palette](wireframes/hacks4life-color-palette.png)
The website uses a colour palette reaching from Rich Black to Gainsboro (lightly grey white) with 3 shades of blue to give the website a light theme. The colour palette was created using the [Coolors](https://coolors.co/) website.

## Typography
[Google fonts](https://fonts.google.com/) was used for the following fonts:
* Ubuntu is used for the headings. It's a sans-serif font.
* Cabin is used for the paragraphs. It's also a sans-serif font.

## Imagery

## Wireframes
These wireframes were created using [Balsamiq Wireframes](https://balsamiq.com/wireframes/)
* [Computer screen Wireframe](https://github.com/Jdzelhorst/Hacks4Life/blob/main/wireframes/hacks4life-computer-screen.png)
* [Tablet screen Wireframe](https://github.com/Jdzelhorst/Hacks4Life/blob/main/wireframes/hacks4life-tablet-screen.png)
* [Phone screen Wireframe](https://github.com/Jdzelhorst/Hacks4Life/blob/main/wireframes/hacks4life-phone-screen.png)

## Testing
The website was tested using the [W3C html validator](https://validator.w3.org/) for the html-code and [Css-validator from jigsaw](https://jigsaw.w3.org/css-validator/) for the css-code.

### HTML
In the html-validator there were 8 errors in total:

#1: "Start tag seen without seeing a doctype first. Expected < !DOCTYPE html>".
Possible cause: a rookie mistake, never to happen again.
Fix: Implemented the !Doctype element at the top of the html page.

#2 and #3: "End tag section seen, but there were open elements" and "unclosed element div". (on line 46 and 55)
Possible cause: I added the div element later on in the section and it seems I forgot the closing tag.
Fix: Added a closing tag to the div on line 46

#4 and #5: 2 time the "The frameborder attribute on the iframe element is obsolete. Use CSS instead." (on line 95 and 98)
Possible cause: I copied the element from the "copy embed" function on youtube. The frameborder seems to be implemented by default.
Fix: Removed the frameborder attributes on both iframe elements.

#6: "Attribute type not allowed on element textarea at this point." (on line 122)
Possible cause: Initially I implemented the text-type as input for the contact-form, I changed it to textarea to make the possible feedback message larger.
Fix: Removed the type attribute from the textarea element in the contact-form

#7 and #8: Two times "The value of the for attribute of the label element must be the ID of a non-hidden form control." (on line 114 and 116)
Possible cause: I changed the IDs for the first and last name text-input in the contact-form and did not change the for attribute of the labels accordingly.
Fix: Changed the for attributes of both labels to the proper ID.


#
## Credentials
* https://pikwizard.com/photo/happy-businessman-holding-smart-phone-against-green-background/c972f265ab0010274338ac90aeaeda52
https://howtonestforless.com/20-amazing-diy-life-hacks/
https://howtonestforless.com/20-organizing-life-hacks/
https://www.youtube.com/watch?v=vws8zmRT_T8
https://www.youtube.com/watch?v=pCTv9xHuPc8
https://www.packtoiran.com/media/20190703-190052-2711.jpg
