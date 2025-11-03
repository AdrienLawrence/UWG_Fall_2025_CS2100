# ScribeAI - A Better Way to Take Notes

- A notebook based application designed for long, aggregated notes as opposed to traditional one-off documents such as Google Docs or Microsoft Word

# Project Overview

- ScribeAI mimics the structure and traversability of traditional paper notebooks allowing for a better experience and addressing current document application limitations

# Use Cases 

- Journaling

- Meeting transcripts

- Class/Lecture notes

- Any scenario where a traditional paper notebook would be used

# The Problem with Modern Document Apps

Traditional document applications lack the UX for longer notes. Without page references or variable page sizes documents can get 

- Disorganized: No clear structure or page identity. Continuous vertical document

- Hard to navigate: Difficult to find specific pages in long documents

- Visually cluttered: Fixed page sizes break up content unnaturally

# Example Problem Scenario

- Let's say you are taking lecture notes for a class in Docs or Word. By about day 45 you want to find a concept you covered around day 15 in order to refresh for an exam. With no page references or naming system, you would have to scroll all the way back up through 45+ pages through visual word static, then scroll down until you find the page you are looking for. 

- Another issue is that with fixed A4 page sizes a lot of content can overflow onto new pages which not only adds to the traversal issue by introducing more pages to traverse, but also breaks up content which may make it harder to read through cohesively

# Solutions

## ScribeAI Solution #1: Mandatory Page Headers and 'Read' mode

- ScribeAI uses a mandatory header on every page within a notebook. This header serves as the page reference so that in the notebook editor, a user may switch the sidebar to 'Read' mode which changes the sidebar to display a bulleted list of every page. If a user named their pages "Lecture Day x", their bulleted list would be listed in chronological order for every day they took notes. This would allow near instant traversal to any desired page with not searching. Simply click on the bullet with the page name matching what you are looking for. 

## ScribeAI Solution #2: Variable Page Length

- ScribeAI Solution #2: ScribeAI also uses a 'flow' style of page length as opposed to a fixed size. This allows for pages to extend with more content as the bottom of the page is reached, as opposed to moving to a new page. This keeps page references ordered without any 'cont.' pages cluttering up the sidebar as well as keeping desired notes clustered on the same page. The tradeoff is that printing notebook pages will be harder to implement but I can simply allow a switch between 'flow' and 'fixed' page lengths later on or the print button may cut the pages down to the correct size then as opposed to visually in the editor.

# About this Repository

- This repository represents solely the front-end of this project, as it is the capstone project for my CS2100 class which focuses on web design. 

- Consider this repo a working visual demo

- There is no API and no connected database which are crucial for full function, including text editing and user profiles. The pages included are merely representative of the UI, not UX inclusive.

# Technologies Used

- HTML5

- CSS3

- JavaScript
