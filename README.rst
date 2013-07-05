=================================
Django PhraseApp Demo Application
=================================

PhraseApp_ makes it easy and fast to localize you mobile app or website.

This is an exmple application that uses django-phrase_ to integrate the PhraseApp In-Context-Editor with a basic Django application.

.. _django-phrase: https://github.com/phrase/django-phrase

Installation
------------

First, install a recent Django version as showin in the `install guide`_.

Install the required dependencies::

    pip install -r requirements.txt

Add your PhraseApp Auth Token to ``settings.py``::

    PHRASE_AUTH_TOKEN = 'YOUR_AUTH_TOKEN'

Start the django application::

    python manage.py runserver

That's it! You should now be able to see the demo application with the integrated PhraseApp In-Context-Editor.

Browse to the `examples page <http://localhost:8000/de/polls/examples/>`_ to see the editor in action.

More Information
----------------

* Signup_
* Documentation_
* Support_

.. _PhraseApp: https://phraseapp.com
.. _install guide: https://docs.djangoproject.com/en/1.5/topics/install/#installing-development-version
.. _i18n template tags: https://docs.djangoproject.com/en/1.5/topics/i18n/translation/#internationalization-in-template-code
.. _Signup: https://phraseapp.com/docs
.. _Documentation: https://phraseapp.com/docs
.. _Support: https://phraseapp.com/support
