# FrontEnd Mentor - Space Tourism Website - Solution
Namaste. This is **Abhisek Niraula** and this is my solution to a challenge in [FrontEnd Mentor](https://www.frontendmentor.io/challenges/space-tourism-multipage-website-gRWj1URZ3). Frontend Mentor is a website that helps you sharpen your frontend skill by getting involved in practical and challenging website.

## Preview 
![Preview of the index / intro page of space tourism website!](./preview.png)

## Links
 - View the website [here](https://abhisekniraula3615.github.io/Space-Tourism)

 - View the solution in [FrontEnd Mentor](https://www.frontendmentor.io/solutions/mobile-first-responsive-space-tourism-website-frontend-mentor-html--7IXt_nNFf)

## My Process 
So for the development of this project at first  I became clear with the  fundamentals of frontend web development. I  followed a bootcamp by Angela Yu.  Then I made a proper workflow to tackle the challenge. At first I completed the basic things like setting up the navigation.Then I took on the  individual protions of the project like destination and technology. One of the things I took the most time on was the navigation bar. I had not made such navigation bar before but it was fun to go through it. Although I am still not sure about the horizontal rule running through the navigation. I did the line thing but since for me it was more of stylistic choice so I basically omitted it.

## Built With
- HTML5
- CSS3
- Bootstrap 5
- Mobile first workflow
- JQuery
- Javascript
- [HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [Bootstrap Documentation](https://getbootstrap.com/docs/5.3)

## What I learned 

So although the code used in this project is  not that unique. The project for me came  out preety well. But one of the things in this project I am very proud of is the  way navigation bar is handled. I noticed that I had to copy and paste the navigation layout throughout the project so I though it would be awesome to do it  through javascript. So the navigation bar is kept in separate file and loaded into individual pages.

#### JavaScript
```
Dynamically Generating Navigation bar for each webpage.
$("#nav-placeholder").load("navigation.html", function(){
    $(".nav-link")[0].classList.add("nav-active");
});
```
## Useful resources
 - [Kevin Powell Youtube](https://www.youtube.com/@KevinPowell)
 - [Bootstrap Documentation](https://getbootstrap.com/docs/5.3/)
 - [W3S Schools](https://www.w3schools.com/)
 - [MDN HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
 - Also the other submission of the  project were also especially helpful as well.

## Author
   - Abhisek Niraula
   - Frontend Mentor - [Abhisek Niraula](https://www.frontendmentor.io/profile/AbhisekNiraula3615)
   - YouTube - [Devendra Niraula](https://www.youtube.com/@devendraniraula5855)