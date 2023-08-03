**Box Model**

- when two div are there one upper and one down, margin actually collapses and it takes only larger margin size.  Ex. if 60px and 70px then it takes 70px
- When you use `box-sizing:border-box`, it cuts content size with border and padding. Ex. if content is 100px and padding 10 border 5 then content only had 100-- 20+10 = 70px.
- Best practice is put `box-sizing:border-box` on your container so that all elements inside it is taking exact width and height provided.
  
- content-most innermost
- padding
- border
- marging outermost







![image](https://github.com/sarthirkjoshi/interview-preparation/assets/46737879/e310b5c9-a71c-437e-bfd7-c90c7f2ae83c)
