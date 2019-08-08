# Demy website through Django.
this is my first Django project
first we have to create project(django-admin startproject projectname).
then we have to create app(py manage.py startapp appname).
now,run sever
create superuser
import django.contrib.auth in views.py
we have to create forms.py in appliction level direct.
in this file we have to-
   class Userform(forms.ModelForm):
	     class Meta:
		       model=User
		       fields=['username','email','password','first_name','last_name'] through fetch  fields.
In Templates folder we have to create regiestration folder in this we have to create login.html
now,in urls.py file-
  we have add some additional files.
  from django.conf.urls import url,include
    path('accounts/', include('django.contrib.auth.urls'))
All reamining process same in all projects.connections are connect in same way.i m show you only main files.
#thankyou
  
     
