# drf-api-permissions-postgres
https://github.com/HaneenHaashlamoun/drf-api-permissions-postgres/pulls/1

# Feature Tasks and Requirements

## Features - General
- [x] You have been supplied with two demos, each presenting a key new feature.
- [x] blogapi-permissions demonstrates how to restrict access to portions of your APIs data.
- [x] blogapi-postgres demonstrates switching over to using postgres vs sqlite
- [x] Your job is to merge the functionality of both demos.
- [x] Customize your project to use different application features/models than Blog and Post

## Features - Django REST Framework
- [x] Make your site a DRF powered API as you did in previous lab.
- [x] Adjust project’s permissions so that only authenticated user’s have access to API.
- [x] Add a custom permission so that only author of blog post can update or delete it.
- [x] Add ability to switch user’s directly from browsable API.

## Features - Docker
NOTE Refer to demo for built out Dockerfile and docker-compose.yml examples.
- [x] create Dockerfile based off python:3.8-slim
- [x] create docker-compose.yml to run Django app as a web service.
- [x] enter docker-compose up --build to start your site.
- [x] add postgres 11 as a service
- [x] Note: It is not required to include a volume so that data can persist when container is shut down.
- [x] Go to browsable api and confirm site properly restricts users based on their permissions.
- [x] Stretch Goals
- [x] Try different permission levels, including custom ones.
- [x] Figure out how to directly access postgres running inside container. Hint: it will take research.
- [x] Add a volume to persist data when container is shut down.