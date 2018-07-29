# Web-development-PhotoGallery
<p>(Permission given by Professor Nina Amenta).<br>
   Link to the class website: <a href="http://web.cs.ucdavis.edu/~amenta/s18/ecs162.html">ECS162(Web Development)</a>
</p>

<p>  In class project, with a partner, I used full stack web development skills to build a website that contains a collection of photos. It has the functionalities: adding and delete tags for every item, suggesting searching words based on first two letters and displaying using react.js.
The project was built from the server side. <br><br>
  It requires APIs of image analysis from Google vision Cloud, creates own database with changeability. It co-operates with Node.js modules and  React.js for self-arranging content to display.<br>
( This website only works when the server is activated.)
</p>

<p>1.The autofill feature for suggesting what tags users might want to search</p>
  
![1361532566310_ pic_hd](https://user-images.githubusercontent.com/33383546/43235497-b3cdb780-9035-11e8-9fb5-4da2565e314d.jpg)

<p>2.Each photo has 6 tags which are landmarks acquired from Google cloud image analysis. They will be display when user click on the image. Users can also add one more tag for the image. The backend database will update the new tag as well</p>

<p>The layout to display photos is implemented by React.js so that it has the reflexibility to handle images of different sizes.</p>
<img src="https://user-images.githubusercontent.com/33383546/43235495-b2e246d8-9035-11e8-9a26-2458cd0f1952.jpg"> <img>

<p>After users click on the arrow, the tags will be added below the search bar. To search photos, users click on the search icon. This website collects all the tags chosen, looks through the backend database and pack all information into an API to send back</p>


![1351532566269_ pic_hd](https://user-images.githubusercontent.com/33383546/43235496-b3b1a39c-9035-11e8-9e0f-71becda0e993.jpg)
