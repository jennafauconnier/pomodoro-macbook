# Pomodoro Macbook Bar

## Overview
This Python script creates a Pomodoro timer as a macOS menu bar app using the rumps library.

## Features
- Start, pause, continue, and stop the timer.
- Notification when the timer reaches zero.
- Easy setup and execution.

## Installation 
1. Clone the repository
2. Install the dependencies
    ``pip install rumps``

## The first Usage
1. Execute the python program via : ``python pomodoro.py``

### Bundling as MacOS App
To create a standalone macOS application, follow these steps:

Create a setup.py file with the provided code.
Make sure you have an icon file (.icns format).
Execute the following command in your terminal: ``python setup.py py2app``


The application bundle will be created in your project directory under ./dist/*.

