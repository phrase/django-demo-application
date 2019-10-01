# Django Phrase Demo Application

[Phrase](https://phraseapp.com) makes it easy and fast to localize you mobile app or website.

This is an exmple application that uses [django-phrase](https://github.com/phrase/django-phrase) to integrate the Phrase In-Context-Editor with a basic Django application.


## Installation

Install the required dependencies::

    pip install -r requirements.txt

Apply migrations:

    python manage.py migrate

Add your Phrase Project ID to ``settings.py``::

    PHRASE_PROJECT_ID = 'PHRASE_PROJECT_ID'

Start the django application::

    python manage.py runserver

That's it! You should now be able to see the demo application with the integrated Phrase In-Context-Editor.

Browse to localhost:8000/polls to see the editor in action.

## Further reading

* [Phrase](https://phrase.com/)
* [Phrase Documentation](https://help.phrase.com/)
* [Phrase Support](https://phrase.com/en/contact)
