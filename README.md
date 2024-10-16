# Umair
h2>User Interface</h2>
<p>
The user interface of the application is designed to be user-friendly and intuitive.
1: Homepage: Features a grid of images, a search bar, and easy navigation.
2: earch Results: Allows filtering by orientation, color, and supports infinite scrolling.
3: Image Details: Displays larger previews, download options, photographer info, and related images.
4: User Profiles: Showcases photographers' portfolios and their image stats.
5: Collections: Lets users organize and explore images in collections.
6: Login/Sign-Up: Simple, user-friendly forms with social login options.
7: Responsive Design: Optimized for both desktop and mobile devices.
</p>
<h2>Backend</h2>
<p>
1: Storing Images: The backend keeps all the images and their details (like who took them) in a database. When you search for a picture, the backend finds it for you.
2: User Login: When you log in or sign up, the backend checks your info to make sure you’re allowed to access your account.
3: Searching for Images: When you type something in the search bar, the backend looks through the database to find the right pictures that match your keywords.
4: Uploading Photos: When photographers add their pictures, the backend saves them, resizes them if needed, and keeps track of the details.
5: User Profiles: The backend manages user profiles, collections of favorite images, and any settings you have.
6: Tracking Downloads: It tracks how many times an image has been downloaded or viewed, which helps understand what users like.
7: Speeding Up the Site: The backend uses special techniques to make the website load faster and handle many users at once.
</p>
<h2>Recurring</h2>
<p> 
function dispenser(a){
    //This function takes an argument a and returns another function that takes a second argument b.
  return function(b){
    //he second function returns yet another function, glass, which takes a third argument g.
    return function glass (g){
      return "You can drink Water"
      //The glass function always returns the string "You can drink Water," regardless of the arguments passed.
    }
  }
};
let dis= dispenser("yes")
//Calling dispenser("yes") returns a new function that expects the next argument, b.
dis now holds a function waiting for b.
let water=dis("cold water")
//Calling dis("cold water") returns another function waiting for the third argument, g.
water now holds a function that expects g
let cup=water("present")
//Calling water("present") returns the string "You can drink Water".
console.log(cup)
So, cup is set to "You can drink Water."
</p>