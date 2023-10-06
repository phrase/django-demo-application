# django-phrase Demo (DEPRECATED)

![maintenance-status](https://img.shields.io/badge/maintenance-deprecated-red.svg)

> This repository for the demo app of Phrase Strings In-Context Editor with `django-phrase` has been deprecated and is no longer maintained. Pleas refer to the [django-phrase](https://github.com/phrase/django-phrase) repository, where the demo has been moved to and will be maintained. 
 
<hr />

## Introduction

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

## Get help / support

Please contact [support@phrase.com](mailto:support@phrase.com?subject=[GitHub]%20) and we can take more direct action toward finding a solution.
