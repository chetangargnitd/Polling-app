===========
Polling-app
===========

Polls is a simple Django app to conduct Web-based polls. For each
question, visitors can choose between a fixed number of answers.

Detailed documentation is in the "docs" directory.

Quick start
-----------

1. Run `python manage.py migrate` to create the votes models.

2. Start the development server and visit http://127.0.0.1:8000/admin/
   to create a poll (you'll need the Admin app enabled).

3. Visit http://127.0.0.1:8000/votes/ to participate in the poll.
