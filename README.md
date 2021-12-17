# eBooksAPIs

## Folder Structure
```
    eBooksAPIs
        |\_____ apiebooks
        |         |\_____ __pycache__
        |         |         |\_____ __init__.cpython-39.pyc
        |         |         |\_____ settings.cpython-39.pyc
        |         |         |\_____ urls.cpython-39.pyc
        |         |          \_____ wsgi.cpython-39.pyc
        |         |
        |         |\_____ __init__.py
        |         |\_____ settings.py
        |          \_____ wsgi.py
        |
        |\_____ ebooks
        |         |\_____ __pycache__
        |         |         |\_____ __init__.cpython-39.pyc
        |         |         |\_____ admin.cpython-39.pyc
        |         |          \_____ models.cpython-39.pyc
        |         |
        |         |\_____ api
        |         |         |\_____ __pycache__
        |         |         |         |\_____ serializers.cpython-39.pyc
        |         |         |         |\_____ urls.cpython-39.pyc
        |         |         |          \_____ views.cpython-39.pyc
        |         |         |
        |         |         |\_____ serializers.py        
        |         |         |\_____ urls.py        
        |         |          \_____ views.py    
        |         |
        |         |\_____ migrations
        |         |         |\_____ __pycache__
        |         |         |         |\_____ __init__.cpython-39.pyc
        |         |         |         |\_____ 0001_initial.cpython-39.pyc
        |         |         |          \_____ 0002_auto_20211217_1519.cpython-39.pyc
        |         |         |
        |         |         |\_____ __init__.py        
        |         |         |\_____ 0001_initial.py        
        |         |          \_____ 0002_auto_20211217_1519.py    
        |
         \_____ manage.py       
```

## Only two model is needed for the project, you can call it Ebook and Review. It must have the following fields:
```
♬  title  
♫  author  
♩  description
♪  publication_date
```
```
♬  created_at
♫  updated_at
♩  review_author
♪  review
♬  rating
♫  ebook
```