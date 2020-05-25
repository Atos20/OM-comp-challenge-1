# OM-comp-challenge-1
###
OM comp challenge-1 is the first solo project that I finished using HTML and CSS to replicate a webpage. This challenge focused strictly on practicing HTML and CSS languages as well as building a website layout based strictly on an image provided by Turing's instructors. This project challenges the use of layout systems such as CSS Grid and flexbox and required an understanding of wireframing to define the website's structure. 

## Project Status
###
The static comp challenge looks like it is based on a webpage structure that focuses on providing data about individuals who appeared on what seems to be an informational card.

This project has been adapted to meet the requirements of an animal hospital that provides care for small house pets. The website's structure was designed with users in mind. To better understand the needs of the users it was important to talk to potential users as well as with the veterinarians who provide these services.

![original static comp](https://user-images.githubusercontent.com/56229864/82806887-f5ad6380-9e43-11ea-8ea3-0355a31ea0ad.png)

![Screen Shot 2020-05-25 at 4 58 43 AM](https://user-images.githubusercontent.com/56229864/82807147-73716f00-9e44-11ea-89d1-a1ee54bf8540.png)

## Webpage Structure

Navigation bar:
This section of the webpages holds the about, services, appointments, and log-in button. Here I have decided to make use of a single icon in the log-in button instead of using icons on the rest of the buttons.

![Navigation bar](https://user-images.githubusercontent.com/56229864/82798059-410c4580-9e35-11ea-80e7-e81778af5fec.png)

Right after the navigation bar, we can identify the patient's title that indicates where the user is located on the website.

![Patients](https://user-images.githubusercontent.com/56229864/82798234-7add4c00-9e35-11ea-9f66-9694475386b4.png)

On the page body, the user can find and look at current and/or old patients and identify a specific pet who might be under special care or undergoing a specific treatment.
#
![Main page](https://user-images.githubusercontent.com/56229864/82797390-4026e400-9e34-11ea-8993-37d211e7b074.png)

On the informational card the user finds more buttons to interact with. On the left side of the picture of each patient the **top button** or **diagnostic** button allows the user to find out more about what kind of treatment the patient currently is undertaking as well as the health status. The second buttons or **bill button** lets the user know of current bills or past due bills. The third button shows the current medications prescribed by the doctor.

![Screen Shot 2020-05-25 at 3 14 45 AM](https://user-images.githubusercontent.com/56229864/82798573-ec1cff00-9e35-11ea-8261-a4ff494a58a2.png)

## Technical organization

The main layout structure used to make this project was the CSS grid. This layout was implemented mainly in two sections, the navigation bar was the first one and then the container section in the page body.

![Main container](https://user-images.githubusercontent.com/56229864/82802317-e9bda380-9e3b-11ea-8a86-2636357d52b6.png)

I was able to have more practice with the grid structure while making the informational cards, these required careful organization to apply properties and values to the grid and accomplish the desired results.

![A container within the container](https://user-images.githubusercontent.com/56229864/82802765-a6b00000-9e3c-11ea-87a8-9d9ca2619e38.png)

## Media queries

The responsiveness to the website was accomplished by using media queries and setting this property to a minimum width of 700px.


![Screen Shot 2020-05-25 at 2 55 25 AM](https://user-images.githubusercontent.com/56229864/82803427-bbd95e80-9e3d-11ea-8dc0-5828ef391150.png)

The main changes that I targeted with media queries were the navigation bar and the body container. These two sections needed to become more dynamic with the screen size. On the navigation bar, the grid structure changes from `1fr 1fr 1fr` to `1fr 1fr`. This allows for better readability. On the informational card, the main change using media queries was moving the `URL` element to the bottom line of the grind. Making such a move let the user have more space to read the text.

![Width less than 700px](https://user-images.githubusercontent.com/56229864/82803216-5dac7b80-9e3d-11ea-94d8-1eb7f1688d4e.png)

## Reflection
###
+Animal hospital is the product of [Orlando Murcio](https://www.github.com/atos20) and it is the first solo project as a deliverable for Module 1 at the Turing School of Software and Design. It's an exercise that focused primarily on HTML and CSS concepts.

### Future Goals
As I worked on this project I was exposed to more ideas from users and doctor's and I believe that more features could be added to ameliorate the user experience. There is more work to be done about defining more what kind of information can be provided to the public so that information is clear and satisfies the needs of the clients and doctors. 

Technically speaking,  I believe that the CSS file can be refactored so it looks cleaner and less repetitive. I also think that the HTML file could have been structured better and that the name classes could haven been defined better. As a software developer I am always looking for ways to become more productive and I believe that this project has created a foundation for how I will structure the HTML and CSS files.

The next step would be to add the functionality using Javascript.

### In Closing

Not having any prior experience creating HTML and CSS files before this project made it challenging to create a webpage with all the characteristics that I implemented. I believe that there is so much I still need to work on but I am proud of the result I  obtained today. I will work on refactoring. The implementations of media queries were important in the making of this project and I am looking forward to keeping increasing my knowledge on this topic.
