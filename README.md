# Hack And Write Django Project

## GETTING STARTED

**Clone the repository into a folder, you can swap `<your_folder>` with any name of your choice, do not include the comparison signs as they are text placeholder operators**
  ```
  bash
  $ mkdir <your_foler> && cd <your_folder>
  $ git clone https://github.com/student-ambassadors-futo/hnw-django-apps
  ```
**Spin up a virtual environment to run our django app and activate it.
In the folder containing the repo, as in, run the following in the CLI which uses the pre-installed Python virtual environment module**
  ```
  bash
  $ python -m venv env
  $ source env/bin/activate
  ```
**Go back into the repo folder and then install the dependencies**
  ```
  bash
  $ cd django-ecommerce
  $ pip install -r requirements.txt
  ```

**Synchronize django and dependencies**
  ```
  bash
  $ python manage.py migrate
  ```
**Start development server**
  ```
  bash
  $ python manage.py runserver
  ```
 **AND HACK AWAY** :wink:
