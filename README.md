Colmar Academy - Codecademy Ready Capstone Project (Week 7)


Open:
- I would ask the designer if she just overlooked the "for companies" entry in the mobile version. (I think it should be accessible on mobile too)
- Start here is a bad name for a link concerning accessibility -> workaround? (also Read more)
- make images responsive with picture tag? or as background images?
  how to prevent images from loading twise on mobile?


Layout:
I identified the following patterns (for the desktop) that I will style globally the same using classes:

splitting content into two colums roughly 2:1 -> classes .wide and .narrow

articles with images associated are of two types .split (using the columns approach) and .compound (with the image at 100% width on top) they have the two components .img-box and .txt-box

for setting a maximum width on the content and not on the background there is the .container class applied to all main areas.

Decisions:
- most images are decoration so they get alt=""
- links have clear hover/active/focus settings



Color & Font choices:
I want to transport:
- campus athmosphere (nature and inspiring surroundings) -> green
- joy of learning and creating -> Playful (but readable) font for the headings
- respectability/reliability -> not too bright

colors:
green #5bca00
light-green #8ce83f
gold  #ffc10e
black (for text)
