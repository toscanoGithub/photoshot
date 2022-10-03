# photoshot
In this build we're going to build a photo gallery website using HTML5 and bootstrap.
Head to https://getbootstrap.com/docs/5.2/getting-started/introduction/
and scroll down to the second step under the Quick start section.
Copy the markup and create a folder for your project named photoshot.
Create index.html and paste the boilerplate code that you've just copied.
This is your start point.
index.html

<img width="920" alt="index html" src="https://user-images.githubusercontent.com/10692569/193490228-789cccdd-0f0e-4740-8f17-b3999684e3ed.png">

1- Change the document title to "Photoshot".
2- In the body, we're going to replace the heading "Hello world" with the content of our photo gallery.
3- We'll use a grid to layout our shots.
  For this we need 16 images of your choice. You can pick them for free from https://unsplash.com
  Here is our basic layout: 
  col-lg-12 >>> means that a photo will take the whole row in larger devices such as desktops
  col-md-4  >>> means that a photo will take 4 fractions in a row. which means there is space for for 3 photos in medium devices. 4 x 3 = 12
  col-sm-6  >>> You got it, there is a place for only 2 photos in small devices. 6 x 2 = 12
  col-xs-12 >>> A photo will take the whole row in smaller devices.
  
  <img width="920" alt="index html" src="https://user-images.githubusercontent.com/10692569/193490486-cca6ac18-0850-4474-9e69-c73e2309d246.png">


Since we need our content to take the width of the screen, we'll use container-fluid class instead of container class.
To see it in action, add external css file named style.css. dont forget to add the link to the style.css just before </head>.
<!-- custom styles -->
    <link rel="stylesheet" href="style.css" />


style.css
.container {
    background-color: purple;
}

.container-fluid{
    background-color: green;
}

.col-lg-12  {
    margin-bottom: 2px;
    border: 1px solid #ccc;
}

toggle between container and container-fluid in the index.html file. Do you see the padding left and right with container.
Notice no space with container-fluid

************************************************** END OF PART 1 **************************************************

