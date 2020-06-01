# InstaByDuncan

## Built By Duncan Kiragu

## Description
InstaByDuncan is a clone of Instagram [web app], a popular social media site. The application allows users to upload, like and comment on other peoples images. Django crispy forms were used to render and customise all forms and the django_rest_framework was employed for building the web api



## User Stories
The user stories below have been met but if there's an issue file a pull request and propose a change ;I'll be glad to look into it

Users can:
* View all images submitted by any user.
* Click on images to display more details.
* Search for users.
* Receive email when signing up.
* Follow others.
* Like Images.


## Admin Features
Features that are accessible to the admin side of the web application

Admin can:
* Sign in to the application
* Add, Edit and Delete images
* Delete images
* Manage the application.


## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Admin Authentication | **On demand** | Access Admin dashboard |
| User Authentication | **On demand, verify emails before proceeding** | Access Admin dashboard |
| Display all images | **Home page** | Clickable links to open any images in a modal |
| To add an image  | **Through Admin dashboard and homepage** | Click on add and image upload respectively|
| To edit image  | **Through Admin dashboard** | Redirected to the  image form details and editing happens|
| To delete an image  | **Through Admin dashboard** | click on image object and confirm delete action|
| To search  | **Enter text in search bar** | Users can search by username|
| View other users profiles via suggestions span | **Click username on user stories navigation** | Users can view all images posted by any user|
| Comment on images | **Add comments below respective image** | Users can add comments on any image|
| Like images | **Add likes to an image** | Users can add likes to images they like|


## SetUp / Installation Requirements
### Prerequisites

* python3.8
* pip3
* virtualenv / Vim
* requirements.txt
* Understanding of django


## Running the Application
* Creating the virtual environment

        $ pip3 install virtualenv
        $ virtualenv virtual
        $ source virtual/bin/activate
        $ curl https://bootstrap.pypa.io/get-pip.py | python

* Installing Django and other Modules

        $ pip install -r requirements.txt

* To run the application, in your terminal:
        
        $ puthon3.8 manage.py check
        $ python3.8 manage.py runserver

## Testing the Application
* To run the tests for the models in the database:

        $ python3.8 manage.py test instagram

## Technologies Used
* Python3.8
* Django  framework
* Postgresql database
* Stackoverflow(https://stackoverflow.com/)
* Coolors(https://coolors.co/)
* Wireframe - Mockup design
* MDBootstrap
* Heroku
* jQuery

## Resources used
* Django documentation
-------------------------------------------
> (https://docs.djangoproject.com/en/3.0/)
> (https://docs.djangoproject.com/en/3.0/)
> (https://django-tinymce.readthedocs.io/en/)
> (https://gitter.im/DjangoGirls/tutorial?at=548efdd8a6abd16b7d6c2907)
> (https://www.django-rest-framework.org/)
------------------------------------------
* Youtube
* (https://dev.to)
* StackOverflow


## Known Bugs
* The modal for liking section does not have a close button

## Contact Information
* For further collaboration send an email to [Duncan-Kiragu](mathenge089@gmail.com)

## License

Copyright (c) 2020 Duncan Kiragu

----------------------------------------------------------------------------

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sub-license, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.