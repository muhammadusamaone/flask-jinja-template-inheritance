# Flask Template Inheritance

A beginner-friendly Flask project demonstrating **Jinja2 Template Inheritance** using a reusable `base.html` template.

## Features

* Flask Routing
* Multiple Web Pages
* Template Inheritance using `extends`
* Reusable Layout with `base.html`
* Jinja2 Blocks (`title` and `content`)
* Navigation Bar
* Footer
* Dynamic Page Titles

## Pages Included

* Home
* About
* Admissions
* Contact

## Technologies Used

* Python 3
* Flask
* HTML5
* Jinja2

## Project Structure

```text
Flask-Template-Inheritance/
│
├── app.py
│
└── templates/
    ├── base.html
    ├── home.html
    ├── about.html
    ├── admissions.html
    └── contact.html
```

## How It Works

* `base.html` contains the common website layout.
* Every page extends `base.html`.
* Each page provides its own title and content using Jinja2 blocks.
* Navigation links are generated using Flask's `url_for()` function.

## Learning Objectives

This project helps beginners understand:

* Flask routing
* Template inheritance
* `extends`
* `block`
* `url_for()`
* Reusable layouts
* Clean project organization

## Run the Project

Install Flask:

```bash
pip install flask
```

Run the application:

```bash
python app.py
```

Open your browser:

```text
http://127.0.0.1:5000/
```
