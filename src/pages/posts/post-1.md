---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Building a CLI schedule in Python'
pubDate: 2024-02-12
description: First post and greetings!
author: Allan Rodrigues
image:
    url: 'https://res.cloudinary.com/dnot31hiv/image/upload/v1708127110/blog/w1v3rg4evbfceynthcap.png'
    alt: 'Picture of my schedule displayed on the terminal'
---

## What I've accomplished

**Context**: To steer my life in a new direction and fully transition into the tech world, I've enrolled in a Computer Science university program. A few days before the semester started, I realized I needed a schedule that I could quickly and easily access. That's when I decided to explore the feasibility of building one with ChatGPT. The answer turned out to be: quite feasible!

**Goal(s)**: The application's core idea was simple - to create, view, update, and delete class schedule entries using Python. Python, known for its simplicity and readability, seemed like a natural choice. The initial step involved setting up a SQLite database, a lightweight database perfect for small projects like this. The learning curve here involved understanding SQL queries and how Python interacts with databases.

**Modifications:**: For adding some pizzazz to the app, I stumbled upon Python's Rich library. It was perfect for jazzing up the class schedule display with a splash of color and style in the table format.

## What's next

**Exploring CSV Integration**: The next objective for the project is to enable Python to read data from a CSV file and output the results. This approach is particularly appealing due to the portability and ease of editing that CSV files offer. It's a format widely recognized and easily managed in various environments, making it an ideal choice for handling and updating class schedules efficiently.