Car-rental-management-System-
Get a new car rental in a simple way!

Overview The necessity for a system that links car owners with tourists was the driving force behind the creation of the car rental management system. Its purpose is to address the issue of tourists searching the entire town for a new car property. From the comfort of their homes, car owners will be able to market their cars, and tourists will be able to identify available cars right away. It will give car owners access to an extra premium package for managing the financial aspects of the rentals, such as collecting fees.

Features No Entry Barrier: Car-rental-management-System welcomes everyone, regardless of their level of expertise or field of study.

Diverse Community: Engage with experts from various domains and students from around the globe.

Real-Time Assistance: Receive immediate help from professionals by sharing your screen.

Installation Follow these simple steps to set up and run Sofpital locally on your machine:

Cloning the Repositories Clone the main application repository:

https://github.com/asoud80/Car-rental-management-System-.git

Minimum system configuration: The operating system requirements include Windows 7 or later, macOS 10.11 or later, or a modern operating system. Linux distribution. Processor: Intel Core i3 or equivalent. RAM: 4 GB or more Disk Space: 5 GB or more. You have the flexibility to utilize browsers like Google Chrome, Mozilla Firefox, or Microsoft Edge for your browsing needs.

Here’s a brief explanation of each step, along with the commands to execute:
To ensure Python is installed, please download and install the most recent version of Python from the official website. Follow the installation instructions provided for your specific operating system.
Install pip: Download the get-pip.py script and run python get-pip.py to install pip.
Create a virtual environment: Run python -m venv myenv to create a new virtual environment named ‘myenv’.
Activate the virtual environment: Run source myenv/bin/activate on Linux/Mac or myenv\Scripts\activate on Windows to activate the virtual environment.
Install Django: Run pip install django to install the latest stable version of Django.
Verify installation: Run python -m django –version to verify that Django is installed correctly.
Create a new Django project: Run Django-admin start project project to create a new Django project named ‘project’.
Start the development server: Run python manage.py runserver to start the development server. That’s it! A working installation of Django should now be in place, and you should be ready to start building your web application.
Steps to Create “ Car Rental System” Project"
Open the terminal from the folder where we want to create the project. Right-click on mouse -> open in terminal -> write “code .” (space is mandatory between code and “.”)
Then go to the project folder -> urls.py and inside urls.py of project, do this -> add “include” in import as shown in the code below and add “path(“”, include(“app.urls”))”
Create urls.py in the app of the Online Car Rental System project(urls.py is mandatory in both project and app).
In setting.py, add the ‘app name”.
Now, runserver to check if everything is working or not. If you see the below image, then we are done with the installation part. To runserver, run command in terminal as follows “py manage.py runserver”.
Now, create the models.py using the ORM technique as follows. To create the above field in the database, run the following commands as follows: ● Py manage.py makemigrations ● Py manage.py migrate
