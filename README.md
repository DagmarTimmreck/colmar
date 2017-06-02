Colmar Academy - Codecademy Ready Capstone Project (Week 7)


Open:
- I would ask the designer if she just overlooked the "for companies" entry in the mobile version. (I think it should be accessible on mobile too)
- Start here is a bad name for a link concerning -> accessibility-workaround? (also Read more)
- make images responsive with picture tag? or as background images?
  how to prevent large images from loading?


Layout:
I identified the following patterns (for the desktop) that I will style globally the same using classes:

splitting content into two colums roughly 2:1 -> classes .wide and .narrow

articles with images associated are of two types .split (using the columns approach) and .compound (with the image at 100% width on top) they have the two components .img-box and .txt-box

for setting a maximum width on the content and not on the background there is the .container class applied to all main areas.

Starting with implementing the desktop version

selectors for elements that take place only in certain sections are made specific even if it is not necessary to prevent future surprises. 
