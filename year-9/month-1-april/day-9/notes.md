# Year 9 — Day 9

## What I Did

Today was a massive pivot. I finally moved from pure HTML into the world of **CSS**, starting the Cafe Menu project on freeCodeCamp. It’s my first time actually making things look "pro" instead of just plain text. I spent the session learning how to hook up stylesheets and getting the layout to actually sit right on the page. I'm starting to see how the dev side actually comes together to make something people would actually want to use.

## Improvements

1. I got a solid start on the CSS project and learned how to link external files using the `<link>` tag
2. Learned how to center containers using `margin-left: auto` and `margin-right: auto` with a `max-width` so the layout doesn't look mid on mobile
3. Applied `background-image` to the body and used `burlywood` backgrounds to create a proper "cafe" aesthetic
4. Mastered pseudo-classes like `:hover` and `:active` to make my links change color when you interact with them—major level up for UI
5. Used selector grouping (commas) to style `h1`, `h2`, and `p` all at once, which saved me from writing the same code over and over
6. Figured out `display: inline-block` to get the flavor names and prices to sit on the same line, making it actually look like a real menu

---

## Active Recall

**Q1: In CSS, what is the difference between `width: 500px` and `max-width: 500px`, and why does it matter?**

A: If you just use `width`, it stays 500px even on a tiny phone screen, which breaks the layout and makes it scroll sideways. `max-width` lets the menu shrink on small screens but stops it from getting too huge on a desktop, making it responsive.

---

**Q2: What is the point of using a "fallback" font like `serif` after a specific font like `Impact`?**

A: It’s basically a backup plan. If the user doesn't have `Impact` installed on their computer, the browser won't just break; it'll move to the next font in the list so the site still looks decent.

---

**Q3: What does the `:hover` selector do in your CSS menu, and how does it help the user?**

A: It's a pseudo-class that changes the style of an element (like my footer links) only when the mouse is sitting on top of it. It provides visual feedback so the user actually knows the text is a clickable link.

---

**Q4: Why did we put the CSS link in the `<head>` instead of the `<body>`?**

A: You want the browser to load the styling instructions before it starts drawing the content. If you put it in the body, the page might flash unstyled text for a second (FOUC) before the CSS finally kicks in.

---

**Q5: What does `display: inline-block` actually do for your menu items?**

A: It lets elements sit next to each other on the same line like text (inline), but still lets you change their width, height, and margins (block). That’s how I got the flavor name and the price to sit perfectly on the same line.

---

## Reflection

Genuinely gassed about today. Seeing the Cafe Menu actually start to look like a real website instead of a basic HTML skeleton is a great feeling. It’s my first time touching CSS and it already feels way more creative than just writing tags. The hardest part was getting the items to line up, but once I understood the display properties, it all clicked.

---

## Tomorrow

- Keep pushing through the CSS Basics on freeCodeCamp—get deeper into the box model and colors
- Try to customize the cafe menu a bit more with some unique colors to see if I can break and fix the layout
- Start looking into how CSS Grid or Flexbox works since those are the next steps for elite layouts
