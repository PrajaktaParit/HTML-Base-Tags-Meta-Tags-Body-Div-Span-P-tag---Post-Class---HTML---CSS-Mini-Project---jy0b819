This Mini Project is about Parallax-Website created from scratch

A.	Content

1. The website contains 4 images including a front page and these following cities
    a)Mumbai
    b)Shanghai
    c) Dubai 
2. I have generated random text (lorem100) to represent the description

B.  About html

1. IMAGES: The Images are included in div tag having class of pimg1, pimg2, pimg3, pimg4 for first, second, third and fourth image respectively
2. TITLE: Title of each image is enclosed in span tag with class name "border”. This span is in another div tag with class name as "ptext"
3. DESRCRIPTION: Below every image there is a section which contains a heading tag representing the section number and a p tag consisting of description 
4. SECTION: The sections are classified into 2 categories one has class name as section-light and other as section-dark

C. About CSS 

1.	HTML & BODY: The html and body tags are given some basic css properites like min-height, margin, font-properties, color etc.

2.	IMAGES
a.	The images are added in background with an opacity of 0.7 .The first and last image are given a minimum height of 100% to cover the entire screen and the remaining images have height of 400px 

b.	All the images have position set as relative and aligned to center of the screen. The background size is set to cover so that the image does not get cropped and covers the entire space. They are given no-repeat background property so the image won’t repeat itself horizontally or vertically.

3.	PARALLAX-EFFECT: To bring the Parallax effect the background-attachment is set to fixed.

4.	SECTIONS: 

a.	The sections containing the description is aligned to center with padding of 50px from top and bottom and 80px from left and right.
b.	The sections are of two types (i.e light and dark) placed alternately
c.	The section-light class has following properties:-
i.	background-color:rgb(246, 226, 199) ;
ii.	color: rgb(39, 32, 32);
d.	The section-dark class has following properties:-
i.	background-color: rgb(47, 40, 40);
ii.	color: antiquewhite;

5.	TITLE : The title representing the city name is under ptext class having following CSS properties
a.	    Position is set to absolute 
b.	    top:50%;
c.	    width: 100%;
d.	    color: #000000;
e.	    font-size: 25px;
f.	    text-align: center;
g.	    letter-spacing: 3px;

6.	SPAN:  To add elegance to the title the span has given background with a light color







