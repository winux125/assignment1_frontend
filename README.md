# Assignment 1 - HTML & CSS

Baubek Serikbay, group SE-2527, 2nd year Software Engineering at Astana IT University.
Web Technologies I (Front End).

This is my first assignment. 5 tasks, each one is its own page, and the navbar at the
top links all of them.

## How to open it

Clone the repo and open `index.html` in a browser. Nothing to install.

```sh
git clone https://github.com/winux125/assignment1_frontend.git
```

Or just open the live version: https://winux125.github.io/assignment1_frontend/

If you open the files locally and something looks off, run a small server instead and
go to http://localhost:8000

```sh
python3 -m http.server 8000
```

## The pages

- Task 1 - `index.html` - page about me with a profile card
- Task 2 - `task2.html` - layout made with divs and floats, no flexbox
- Task 3 - `exercise1/index.html` - tribute page about Pavel Durov
- Task 4 - `task4.html` - grades table and a feedback form
- Task 5 - `task5.html` - midterm project idea, sitemap and wireframes

Task 5 is the group part, I did it with my groupmate Maussymzhan Makazhan (SE-2527).
The wireframe PNGs are in `wireframes/`.

## About the CSS

`base.css` has the header, footer and cards that every page shares, `navbar.css` is the
menu, and then each task has its own file for its own stuff.

Task 2 is the exception. It repeats the header and footer styles inside `task2.css`
instead of linking `base.css`, because `base.css` uses flexbox and task 2 is not
allowed to use it.

The form in task 4 has no backend, it only shows the HTML input types.
