Django's polls tutorial, with django 3.0.7 and python 3.8.3.
See https://docs.djangoproject.com/en/3.0/intro/tutorial01/.

My files only differ slightly from the official Django site's templates, for backwards compatibility
1) I have added not replaced imports (so that some imports are unnecessary for code to run)
2) I have commented out some previous function/method definitions, especially in ../polls/views.py, at least for some commits
3) import order is in accordance with PEP 8

Repo does include secret key & settings.py but this is not best practice.
I believe that root or front page (at 8000/) is broken by step2 but please let me know if this is not the case.
