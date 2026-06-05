# Restaurant QR Code Generator

A simple Django application that generates QR codes for restaurant menu URLs.

## Features

* Enter restaurant name and menu URL
* Generate QR code instantly
* Save QR code image to media folder
* Display and download generated QR code

## Tech Stack

* Django
* Python
* qrcode Library

## Installation

```bash
git clone https://github.com/dhurka832/restaurant-qr-generator.git
cd restaurant-qr-generator

pip install -r requirements.txt
```

## Run Project

```bash
python manage.py migrate
python manage.py runserver
```

Open:

```text
http://127.0.0.1:8000/
```

## Usage

1. Enter the restaurant name.
2. Enter the menu URL.
3. Click Generate.
4. Download or share the generated QR code.

## Screenshots:  

![1](https://github.com/user-attachments/assets/9aa2e5af-b5f7-46eb-9f69-e621d14d582b)

![2](https://github.com/user-attachments/assets/d35a33cf-8314-4f85-a826-0e471b0c2928)
