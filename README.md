# About
A simple static flask web application and demonstration of direct deployment to Azure app service on Linux.

The application is also hosted for a short period [here](http://countries.eu.pythonanywhere.com/)

![](/appcapture.jpg)


# How to Use

## a. Test the web application locally.

1. Clone this repository and cd to the project directory

    `git clone https://github.com/sekhargullapalli/python-azure-app-service-linux.git`

    `cd python-azure-app-service-linux`

2. Create a virtual environment and activate it

    `python -m venv venv --prompt "#countriesenv"`

    `venv\Scripts\activate`

3. Install requirements and run the application
    
    `pip install -r requirements.txt`

    `flask run`

4. Navigate to http://127.0.0.1:5000/ 

## b. Deployment to Azure App Service on Linux

The deployment instructions can be found [here](/azureappdeployment.md)


# Acknowledgement
The images and the data for this applicaiton is cloned from
https://github.com/cristiroma/countries


# Useful Links/ References
Detailed instructions on publishing Python apps to Azure app service can be found [here](https://docs.microsoft.com/en-us/visualstudio/python/publishing-python-web-applications-to-azure-from-visual-studio?view=vs-2017)

[Azure CLI reference](https://docs.microsoft.com/en-us/cli/azure/reference-index?view=azure-cli-latest)

[Flask Reference](https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)


# License

A simple static Flask web application
Copyright (C) 2019  Vijaya Sekhar Gullapalli

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.