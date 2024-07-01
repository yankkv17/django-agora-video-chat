# Vchat

VChat is a Django-based video chat application that integrates Agora SDK for real-time communication.

# Using

-   Python
-   Django
-   HTML
-   CSS
-   Agora

# Functions

- Group video chat
- Separate rooms
- Display names
- Turn off/on webcam
- Turn off/on microphone
- Leave stream

# Download and Setup

-   git clone https://github.com/yankkv17/django-agora-video-chat/
-   cd django-agora-video-chat
-   Create virtual environment: python -m venv venv
-   venv/scripts/activate
-   pip install -r requirements.txt
-   python manage.py runserver
-   python manage.py createsuperuser (optional)

## How to start

1. Create an account on [Agora](https://www.agora.io/en/).
2. Create a new project within the Agora dashboard.
3. Copy the App ID and App Certificate provided by Agora.
4. Create a `.env` file in the root directory of your Django project.
5. Define the following variables in your `.env` file:
   - `AGORA_APP_ID=Your_Agora_App_ID`
   - `AGORA_APP_CERTIFICATE=Your_Agora_App_Certificate`
   - `DJANGO_SECRET_KEY=Your_Django_secret_key`
6. Paste the corresponding values for each variable in the `.env` file.
7.  python manage.py runserver

<h5 align="center"> If you have any questions, just write me <h5>

# Screenshots

## Home page

![изображение](https://github.com/yankkv17/django-agora-video-chat/assets/166509664/3efe9d62-6d6d-46b1-9c83-88a045d22af8)


## VChat page page

![изображение](https://github.com/yankkv17/django-agora-video-chat/assets/166509664/d97b2303-9648-4f2f-9e75-d4641d378c81)


<h5 align="center"> everything works fine <h5>

