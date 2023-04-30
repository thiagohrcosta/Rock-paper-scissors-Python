# Rock Paper Scissors Game (Python)
![enter image description here](https://res.cloudinary.com/dloadb2bx/image/upload/v1682863495/paper1_h3ag9n.png)

## Technologies used
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)  ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 

This project was created using Docker to studying the basic concepts of Python learned at day 04  in the **[100 Days of Code: The Complete Python Pro Bootcamp](https://www.udemy.com/course/100-days-of-code/)**. 

## Summary
**Day 04**: Randomisation and Python Lists

## What player can do?

**Player**: Can choose rock, paper or scissor. After this choice, a random selection is done to select a computer choice. Finally, a if/else statement with logical operations.


## How to run this project
This project was created with Docker, the Dockerfile is:

    FROM  python:3
    
    WORKDIR  /app
    
    COPY  .  .
    
    CMD  ["python",  "app/main.py"]

To run just download this project and run the follow commands:  `docker build -t rock-paper-scissors .`  then run `docker run -it rock-paper-scissors`. 