# FotagDemo

A small android app writen in Java. A school project of CS349 University of Waterloo Summer 2019  (https://www.student.cs.uwaterloo.ca/~cs349/s19/assignments/a3.html)

The repository only shows the demo UI. The source code is set private to prevent plagiarism, please contact me if you want to see the code. :)

### /******************** Synopsis ********************/

A  application that can allow a user to select photo, rate photo and zoom in photo.


### /******************** Usage for Toolbar ********************/

##### Toolbar<br />
  |<br />
  ----- Filter rating bar: showing 5-stars, used to filter the image list based on rating. Could either press on each star to set the rating or press at one star and drag the mouse left to decrease the rating or drag the mouse right to increase the rating. (Rating range 0-5)<br />
  |<br />
  ----- Load button: loads a set of 10 images over the network from this URL: https://www.student.cs.uwaterloo.ca/~cs349/s19/assignments/images. If the list already contains images, clicking on this button should clear the list and replace with a fresh set of images from that URL.<br />
  |<br />
  ----- Clear button: removes all images from the list.<br />
  <br />

### /******************** Main activity UI ********************/

When first launched, the application should show a toolbar along the top of the screen, and an empty list (image grid).
(Press Load button in menu, would load 10 new images in the image grid)

Each image in the grid is shown as a thumbnail, with a set of 5-stars beneath it. Users can touch a star to select a rating, or press at one star and drag the mouse left to decrease the rating or drag the mouse right to increase the rating. (Rating range 0-5). 

Clear the rating: Press at one star and drag the mouse left could decrease the rating to 0.

Change the rating might influence the whether or not the image shown on the current grid. For example, if user choose the filter rating bar to 3 stars, and image A (with 4 stars) show up. If user change image A to 1 star, then A would disappear from current filter (cause image A now is less than 3 stars)


##### Supported Layouts<br />
  |<br />
  ----- Horizontal orientation: show a 2-columns image grid, Adding images would add more rows as required. User could use finger to scroll content.<br />
  |<br />
  ----- Vertical orientation: show a single column, and sufficient rows to accommodate the number of images User could use finger to scroll content.<br />


### /******************** Zoom-in activity UI ********************/

When in the image grid, if user touches the image thumbnail in the grid, the image will be enlarged to full-screen. Touching it a second time dismiss this window, and return to the image grid. Press back in the phone could also return to the image grid.



### /******************** Others ********************/

Phone: Pixel (Google Phone) AVD using API 28.

Android SDK: API 28.


### /******************** Screenshot ********************/

Launch:

<img src="https://github.com/irenelrc/FotagDemo/blob/master/start.png" width="300">
