Hi! My name is Akshit, and I developed a shopping website using the Python Django framework. To run the server, navigate to the project directory, then into the "akkicart" directory, and use the terminal command: python manage.py runserver, then hit enter.

The development process involved several key steps:

Setting up the Django environment: This was the first step in creating the project.
Creating the index.html file: I used Bootstrap to design the navigation bar and structure the main page.
Building the "Contact Us" and "About Us" pages: These were added to enhance the user experience.
Frontend Development: I utilized BootstrapMade for frontend design and created a static folder. The path in index.html was updated from assets to static/assets to correctly link the CSS files stored in the static folder.
Developing the "auth" application: This app handles the authentication process. I wrote the logic for the signup page within the views of the "auth" app.
Admin Setup: I created a superuser in the "akkicart" application using the createsuperuser command, and built the signup and login pages, adding appropriate logic for user authentication.
Creating the Contact Us page: Before that, I designed a database model for the Contact Us page in models.py within the "akkiapp." Migrations were run using makemigrations and migrate commands to update the database.
Adding a Media Folder: A media folder was created and added to models.py in "akkicart" for handling database entries with media files. I also set up the necessary URLs and media directory, followed by migrations.
Product Management: I added products via the admin panel and retrieved product data from the database in views.py to display them on the website.
JavaScript Integration: Finally, I integrated Bootstrap 4’s jQuery for enhanced interactivity.
