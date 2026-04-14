# mtm6201-final
[Github link](https://enda0006.github.io/mtm6201-final/)

[Prototype](https://www.figma.com/design/OnH5h7UyteTzViIJsrMecf/Untitled?node-id=3-728&t=Pv9co1BCPrZ7ApuQ-1)

# Plant Palette – Web Portfolio
## Project Overview
Plant Palette is a responsive restaurant website I built to show a modern plant-based dining experience. The main goal of this project was to take my Figma design and actually turn it into a real working website using HTML and CSS.

The site has 3 main pages:

- Home (branding, values, featured dishes)
- Menu (full list of food and categories)
- Contact (form, hours, location)

---

## My Process
I started by using my Figma wireframes and high fidelity designs as my guide. I didnt want to just start coding randomly because that usually makes things messy.

So first I built my HTML structure using semantic tags like `<header>`, `<main>`, `<section>`, and `<footer>` just to keep everything organized and easier to understand.

After that I moved into CSS. I used a **mobile-first approach**, so I designed everything for phone first and then used media queries to scale it up for tablet and desktop.

For layout I mostly used flexbox because it just made it easier to control spacing and alignment. I also used CSS variables so my colors stay consistent across the whole site instead of rewriting them every time.

---

## Challenges & Solutions

### 1. Responsive Layout Issues
One of the biggest problems I had was making everything look good on different screen sizes. It would look fine on mobile but then on tablet everything felt off or too stacked.

**Solution:**

I used media queries and adjusted widths, spacing, and flex directions. In some cases I had to completely rethink how a section was structured just to get it to match my design better.

---

### 2. Image Layout and Orientation
I didnt want to crop my images because I felt like I was losing important parts of them, especially in the specials section.

**Solution:**
Instead of cropping I used `transform: rotate()` and scaling to basically turn the images and make them fit better while still keeping everything visible.

---

### 3. Navigation Menu (Mobile)
The mobile menu gave me some trouble at first, like it wouldnt open properly or it would show in the wrong place.

**Solution:**
I used JavaScript to toggle a class (`show-menu`) and then controlled everything with CSS. Once I got the positioning right it worked way better.

---

### 4. Keeping Design Consistent
At some point things started to feel inconsistent like spacing, font sizes, and colors werent matching across pages.

**Solution:**
I used CSS variables and reused classes instead of making new ones every time. That helped keep everything looking the same and cleaner.

---

## What I Learned
From this project I learned alot more than I expected honestly:

- how to build a responsive website properly
- why planning before coding actually matters
- how to structure HTML in a clean way
- how to use flexbox way better
- how to fix layout issues instead of just guessing

I also got better at taking a design from Figma and actually making it real which was probably the biggest thing.

---

## Accessibility Features
I added some accessibility features to make the site easier to use:

- skip links for keyboard users
- semantic HTML structure
- alt text on all images
- ARIA labels for navigation and buttons
- responsive layout so it works on different devices

---

## Assets & Resources

### Fonts
- [Google Fonts – Merienda](https://fonts.google.com/)

### Images
- Food images and icons from Pintrest [Images](https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://ca.pinterest.com/&ved=2ahUKEwjgseyvs-6TAxWCL1kFHUucKnYQFnoECA0QAQ&usg=AOvVaw2FaZWgQ7gUEpP9bI21uZsz)

### Icons
- Values section icons sourced from [The Noun Project](https://thenounproject.com/)
- Social media icons (Instagram, Facebook, Snapchat) were taken from free icon resources online (I wasnt able to find the exact source again but they are free-use icons)

### Tools & Technologies

- HTML5
- CSS3
- JavaScript (for menu)
- Figma (for design)

---

## Reflection
Overall this project helped me understand what it actually takes to build a full website from start to finish. At the beginning it was kinda confusing but once I got used to the structure it started to make more sense.

If I had to improve it I would probably work more on the responsiveness and maybe try using something like Bootstrap just to compare.

But overall I feel way more confident now building websites and solving problems on my own which is probably the biggest takeaway.

