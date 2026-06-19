# Portfolio Website

This is my personal portfolio site, made for the Week 2 assignment at The Developers Arena. I built it to get comfortable with HTML5 structure and CSS styling before moving to JS-heavy stuff later.

## What's in here

- `index.html` – the page itself (About, Skills, Contact)
- `style.css` – all the styling, pulled out into its own file
- `images/` – my profile photo
- `screenshots/` – two screenshots of the site running locally
- `README.md` – this file

## Running it

Nothing fancy needed, it's just HTML/CSS.

1. Clone or download this repo
2. Open `index.html` in your browser, or use the Live Server extension in VS Code if you want auto-reload

## How I built it

The page has three sections — About Me, Skills, and Contact Me — with a navbar at the top that scrolls to each one.

For the header I used a blue-to-purple gradient background, mostly because flat headers looked boring once I added it. The About/Skills/Contact sections are styled as separate white "cards" with a bit of shadow so they stand out from the page background instead of blending together.

A few CSS things I used on purpose:
- Flexbox for the navbar and for laying out the skill boxes in a row
- Media queries so things don't break on smaller screens
- `border-radius` + `box-shadow` on the cards and on my profile photo (made it circular)
- A hover effect on the nav links and on the Send Message button

The Send Message button is red/orange on purpose — wanted it to actually stand out from the blue/purple theme so it reads as a clickable action and not just more page content.

## Responsiveness

I mostly used `%` and `rem` instead of fixed pixels so things scale instead of breaking. Tested by resizing the browser window down — the skill boxes and form fields reflow properly instead of overflowing.

## Testing I did

- Clicked through all three navbar links to make sure they scroll to the right section
- Typed into the Name/Email/Message fields to check they behave normally
- Checked the page in both Chrome and Edge
- Resized the window a few times to check nothing breaks

## Screenshots

Top of the page (header, About Me, Skills):

![About and Skills section](screenshots/about-skills.png)

Bottom of the page (Skills grid, Contact form, footer):

![Contact section](screenshots/contact-footer.png)

## Notes / what I'd improve next

- CSS was originally inline, moved it into `style.css` after feedback on the first submission
- Want to add a proper Projects section later
- Contact form doesn't actually send anything yet — it's just front-end for now

---
Arathi Shekhar Munavalli · CSE, VTU
