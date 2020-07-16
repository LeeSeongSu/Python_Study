# Python_Study_1
멋쟁이사자처럼(장고 공부)


1. 가상환경 생성 : python -m venv 가상환경이름(python에서 제공하는 독립된 공간)
2. 가상환경 실행 : source 가상환경이름/scripts/activate 
3. 장고 설치 : pip install django
4. 프로젝트 시작 : django-admin startproject 프로젝트이름
5. 서버 실행 : (프로젝트이름)으로 이동한 후 python manage.py runserver
6. 앱 생성 : python manage.py startapp 앱이름

앱 작업 순서 
1. manage.py와 같은 위치에 앱을 생성
2. 앱 폴더 안에 templates 폴더를 만들어주고 html파일들을생성 및 작성
3. views.py로가서 필요한 함수들을 작성
4. 마지막으로urls.py에서경로를 지정
