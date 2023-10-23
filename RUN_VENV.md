
Run venv for this project: django-feed-auth0

In: .../vagrant/django-feed-auth0


---------------------------------

In: .../vagrant/django-feed-auth0

python3 -m venv venv

source ./venv/bin/activate

pip install -r requirements.txt

deactivate

---------------------------------

git init

git add .

git commit -m "comment here"

git remote add origin https://github.com/sjames33/django-feed-auth0.git

git branch -M main   (renames default branch to main)

git push -u origin main

---------------------------------

python manage.py migrate

python manage.py runserver 3000

---------------------------------

removed from requirements.txt:

pkg-resources==0.0.0

cffi==1.14.2

---------------------------------

