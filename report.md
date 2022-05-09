# Internet of Things Lab Assignment 3

We activated our virtual environment and installed
requirements specified in requirements.txt in the
chapter03. We run both api and ws versions of this lab.

## API Version

We used postman app to send POST requests to api version.

This is GET request and response using postman.
![postmanget](https://user-images.githubusercontent.com/31140894/167370555-f5cb4ea8-be56-4b6e-9fb8-de1f03c59161.png)

This is POST request and response using postman.
![postmanpost](https://user-images.githubusercontent.com/31140894/167370574-5e74fabc-8ecc-4cab-b200-f93718cf0e9a.png)

Level 0:
![api0](https://user-images.githubusercontent.com/31140894/167370596-5d8b19c2-19d0-4f0e-9122-7da1549bd00f.jpeg)

Level 50:
![api50](https://user-images.githubusercontent.com/31140894/167370609-282973a0-c3a6-4756-87fd-44c3ffb9d35f.jpeg)

Level 100:
![api100](https://user-images.githubusercontent.com/31140894/167370626-99f4d6ea-1826-45cf-9a6d-a7f80be5d471.jpeg)

## Web Socket Version

We used the web page served from raspberrypi to change level
in the ws version since it was implemented using sockets,
it requires socket communication. GET and POST requests doesn't
work in this version.

Level 25:
![wspage1](https://user-images.githubusercontent.com/31140894/167370664-19cf86ef-8afe-4bfb-9e34-033b9b720e3d.png)
![ws25](https://user-images.githubusercontent.com/31140894/167370686-2ee31fdd-715e-4d4c-baf2-74270a10e796.jpeg)

Level 100:
![wspage2](https://user-images.githubusercontent.com/31140894/167370697-221c1aa8-074d-4d6d-b1b2-f121b6ac3b36.png)
![ws100](https://user-images.githubusercontent.com/31140894/167370713-b0698575-9656-4e87-a861-1332c6c0e81f.jpeg)
