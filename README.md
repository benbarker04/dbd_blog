# Ben's Dead By Daylight Blog

Ben's Dead By Daylight Blog is a website for all things related to the asymmetrical multiplayer horror game, Dead by Daylight. Ben's Dead By Daylight Blog offers a friendly welcoming enviroment for people to get involved in the community and share their thoughts on the game.

![amiresponisive png](https://github.com/user-attachments/assets/fc26f84c-f71e-4bbc-9f99-876e04d96d33)

## Features
* Navigation
  - Featured at the top of the page, is the blog name in the left corner: Ben's Dead By Daylight Blog which links to the top of the home page from whatever page you are on.
  - To the right is the navigation bar for Home, Register and Log in which links to the other pages of the website.
  - The navigation bar indicates if the user is logged in or not, changing accordingly to reflect the user's status.

### Logged out Navigation Bar
 
![loggedoutnav](https://github.com/user-attachments/assets/cdbb7604-2723-4f72-b9c3-00357e5d1158)

### Logged In Navigation Bar

![loggedinnav](https://github.com/user-attachments/assets/e70dea40-1425-4e7a-9dca-9a7e868e7b38)

* The Home Page
  - the home page includes a paginated list of the posts
  - Each post on the home page shows the user the title of the post, an excerpt of the post and when the post was created.

![content](https://github.com/user-attachments/assets/f93cd377-35ce-4d6d-87cd-7129dd384e06)

* The Post Detail Page
  - The post detail page has all the information for the post that you would see on the home page but it also shows you the content of the post.
  - Underneath the post is the comment section where the community can comment on the post to share their thoughts.
  - When a user comments it will not be posted for others to see until it has been approved by the site admin.
  - The user has the ability to delete or edit their comment. 

![postdetail](https://github.com/user-attachments/assets/bf7b6302-3add-44b2-a82e-713f240d8cae)

* The Log In Page
  - The login page lets the user login to Ben's Dead By Daylight Blog.
  - A message will appear if the form is left empty and the user tries to submit it or if the username and/or password is incorrect.
  - If the user does not have an account there is a link to the register page so that the user can sign up.

![loginpage](https://github.com/user-attachments/assets/d9060ca5-4c39-4532-a83a-ba073931369e)

* Register Page
  - The Register page has a form to collect details from the user so they can sign up to be apart of Ben's Dead By Daylight Blog community and comment on posts.
  - The form collects the username, password and email address.
  - If the form is left empty or password is too short, password is too common or the password is entirely numeric a message will appear saying so.
  - There is a link to the login page for if the user already has an account.
 
![signuppage](https://github.com/user-attachments/assets/cf04fbcf-9d57-4136-8530-04503911f985)


* The Footer
  - The footer includes social media icons so users can find Ben's Dead By Daylight Blog on Facebook, Twitter and Instagram
 
![footer](https://github.com/user-attachments/assets/fe5f8f3e-3122-418c-9dbd-5524f4dc3805)

## Testing
* I tested that this page works on different browsers: Chrome, Microsoft Edge and Safari
* I confirmed that this project is responsive, looks good and functions on all standard screen sizes using the dev tools device toolbar.
* I have confirmed that all sections and pages are all readable and easy to understand.
* I have confirmed that the form works: requires entry in every field.
* I have run tests using Django testing and confirmed that the application behaves as expected.



## Bugs

* When I deployed my project to heroku I discovered that there were no bugs and therefore didn't need to fix any.

* HTML
  - No errors were returned when passing through the official W3C validator.
 
*CSS
  - No errors were found when passing through the official (Jigsaw) validator

*Accessibility
  - I have confirmed that the fonts and colours chosen are easy to read and accessible by running it through the lighthouse in dev tools.

![dbdlighthouse](https://github.com/user-attachments/assets/10155e75-05ba-4b78-a2e3-dc801dc793cc)

## Deployment

This project was deployed using Heroku by doing the following:
- Creating a new Heroku app.
- Linking the Heroku app to the Github repository.
- Click on **Deploy**.

The live link can be found here- [Ben's Dead By Daylight Blog](https://dead-by-daylight-blog-91f72895ccd4.herokuapp.com/)

## Credits

All code was taught to me by [Code Institue](https://learn.codeinstitute.net/dashboard).
