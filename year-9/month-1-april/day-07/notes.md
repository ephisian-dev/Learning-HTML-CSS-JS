# Year 9 — Day 7

## What I Did
Today I focused heavily on HTML structure, accessibility, forms, and semantic layout. I also completed my first TryHackMe rooms, including Intro to Offensive Security, Defensive Security, and a career path quiz to 
better understand my cybersecurity direction.

## Improvements
1. Built accessible audio controls using `aria-labelledby` and proper labeling techniques
2. Created a structured checkout form using required inputs and semantic form elements
3. Designed a fully semantic blog layout using `<nav>`, `<main>`, `<article>`, and `<footer>`
4. Built a donation form with validation using email, number, checkbox, and submit input types
5. Created a fully structured conference schedule table using `<thead>`, `<tbody>`, `<th scope>`, and `colspan`
6. Completed TryHackMe Intro to Offensive Security, Defensive Security, and career path quiz

---

## Active Recall

**Q1: Why is `aria-labelledby` useful, and how is it different from a normal `<label>`?**  
A: aria-labelledby is used to link a description to what it describes for example saying that a <label> is connected to an <input>. A difference between aria-labelled by and <label> is that with <label> the user is able to
   select the input box (checkbox, radio e.g.) by clicking on the text while aria-describedby only provides a label for assisstive technology

**Q2: In your volume slider example, why is it better to use IDs instead of just text inside a `<span>`?**  
A: It is better to use IDs because they create a unique and reliable reference that can be used by accessibility tools and JavaScript to clearly connect labels and descriptions to specific inputs. Plain text inside a 
   `<span>` is only visual and has no structured relationship with the input element, meaning it cannot be reliably linked or referenced.

**Q3: What is the purpose of `required`, and what happens if you remove it?**  
A: The attribute 'required' is used in an <input> element to make it so that the <input> has to have something in it, like the user put data into it, before the user can submit it

**Q4: Why do we match `label for="id"` with `input id="..."` instead of using name?**  
A: We match <label> and <input> using ID's as ID's are different for everything meaning you cant use the same ID twice so it's clearer and more safer to use just one ID over names which you can use the same name for 
   more than one element

**Q5: Why is `<thead>`, `<tbody>`, and `<tfoot>` important for accessibility and structure?**  
A: These elements are important for tables so that screen readers can easily identify what data in the table is meant to represent and also, in plain HTML, these elements visually change where the contents are within the
   page

---

## Reflection
  1. I got FIVE projects done, a HUGE jump from last session's one project
  2. After alot of procrastinating, I finally created a TryHackMe account and completed three rooms, I'll start doing TryHackMe in my Sessions alongside still learning Front-End Developement

---

## Tomorrow
- Try hit the Milestone of ten TryHackMe Rooms Completed
- Finally get Started on the CSS Course within FreeCodeCamp, I am SO close, only a few more labs and reviews until I'm done with the Basic HTML course!
