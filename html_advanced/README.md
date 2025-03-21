# 🌐 Advanced HTML Project

Welcome to the **Advanced HTML** project! 🎉  
In this project, you will learn how to structure web pages using HTML tags. No CSS or styling is involved—so don’t worry if the page looks “ugly.” The focus is on **structure** and **semantics**.  

---

## 📝 Tasks in Detail

### 0️⃣ Create Your First Webpage
- **File:** `0-index.html`
- Add the `<!DOCTYPE>` declaration at the top of the file.
- Create the `<html>` tag with the `lang="en"` and `dir="ltr"` attributes.
- Open the file in your browser (it should be blank).

---

### 1️⃣ Structure Your Webpage
- **File:** `1-index.html`
- Copy the content of `0-index.html`.
- Add `<head>` and `<body>` sections inside the `<html>` tag.

---

### 2️⃣ Add Metadata and Favicons
- **File:** `2-index.html`
- Copy the content of `1-index.html`.
- Add `<meta>` tags for:
  - Charset: `<meta charset="utf-8">`
  - Viewport: `<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">`
  - Description: `<meta name="description" content="Techium is a digital agency">`
- Add a `<title>` tag: `Homepage - Techium`.
- Include favicon files (`favicon.ico` and `favicon.png`) using `<link>` tags.

---

### 3️⃣ Simple Header, Main, Footer
- **File:** `3-index.html`
- Copy the content of `2-index.html`.
- Add `<header>`, `<main>`, and `<footer>` tags inside the `<body>`:
  - `<header>`: Add the text `Header`.
  - `<main>`: Add the text `Main content`.
  - `<footer>`: Add the text `Footer`.

---

### 4️⃣ Add an Aside
- **File:** `article.html`
- Copy the content of `3-index.html`.
- Change the `<title>` to `Article - Techium`.
- Inside `<main>`, add an `<aside>` tag with the text `Aside`.

---

### 5️⃣ Create Sections
- **File:** `5-index.html`
- Copy the content of `3-index.html`.
- Inside `<main>`, replace the text with multiple `<section>` tags:
  - Hero section
  - Services section
  - Works section
  - About section
  - Latest news section
  - Testimonials section
  - Contact section

---

### 6️⃣ Add Articles
- **File:** `6-index.html`
- Copy the content of `5-index.html`.
- Inside the Works, Latest News, and Testimonials sections:
  - Add three `<article>` tags in each section.
  - Add placeholder text like `Work #1`, `Article #1`, and `Testimonial #1`.

---

### 7️⃣ Navigation
- **File:** `7-index.html`
- Copy the content of `6-index.html`.
- Inside `<header>`, replace the text `Header` with a `<nav>` tag (leave it empty for now).

---

### 8️⃣ Add a Level 1 Heading
- **File:** `8-index.html`
- Copy the content of `7-index.html`.
- Inside `<main>`, add an `<h1>` tag before the sections with the text `Homepage`.

---

### 9️⃣ Add Level 2 Headings
- **File:** `9-index.html`
- Copy the content of `8-index.html`.
- Replace the placeholder text in each section with `<h2>` tags:
  - Hero section: `We help you build your brand!`
  - Services section: `Services`
  - Works section: `Works`
  - About section: `About Us`
  - Latest news section: `Latest news`
  - Testimonials section: `Testimonials`
  - Contact section: `Contact`

---

### 🔟 Add Level 3 Headings
- **File:** `10-index.html`
- Copy the content of `9-index.html`.
- Add `<h3>` tags for subsections:
  - Services: Add headings like `Design & Concept`, `Digital Strategy`, etc.
  - Works: Add headings like `Interior Design`, `Web Development`, etc.
  - About Us: Add headings like `Who are we`, `Our culture`, etc.
  - Latest News: Add headings like `Hoc loco tenere se Triarius non potuit.`
  - Testimonials: Add headings for each testimonial.

---

### 1️⃣1️⃣ Styleguide
- **File:** `11-styleguide.html`
- Copy the content of `3-index.html`.
- Create a styleguide page with examples of:
  - Headings (`<h1>` to `<h6>`).
  - Paragraphs.
  - Lists (unordered, ordered, and definition).

---

### 1️⃣2️⃣ Add Paragraphs
- **File:** `12-index.html`
- Copy the content of `10-index.html`.
- Add descriptive paragraphs to sections like About Us, Latest News, and Contact.

---

### 1️⃣3️⃣ Add Comments
- **File:** `17-index.html`
- Add comments to improve code readability:
  - `<!-- Header -->`
  - `<!-- Main -->`
  - `<!-- Footer -->`
  - Add comments for each section (e.g., `<!-- Hero section -->`).

---

### 1️⃣4️⃣ Add Links
- **File:** `20-index.html`
- Add navigation links in the `<nav>`:
  - Home, Services, Works, About, Latest News, Testimonials, Contact.
- Add footer links to social media (Facebook, Twitter, Instagram).

---

### 1️⃣5️⃣ Add Images
- **File:** `36-index.html`
- Add images to sections:
  - Works: Add images for each work.
  - About Us: Add an image before the first heading.
  - Latest News: Add images for each article.
  - Testimonials: Add avatar images for each testimonial.

---

### 1️⃣6️⃣ Add Social Icons
- **File:** `index.html`
- Replace social media text links with SVG icons for Facebook, Twitter, and Instagram.

---

### 1️⃣7️⃣ Add Video and Audio
- **Files:** `38-styleguide.html`, `39-styleguide.html`
- Add a video player with controls, looping, and a thumbnail.
- Add an audio player with controls.

---

### 1️⃣8️⃣ Add an Iframe
- **File:** `styleguide.html`
- Embed a YouTube video using an `<iframe>`.

---

### 1️⃣9️⃣ Create New Pages
- **Files:** `about.html`, `latest_news.html`, `contact.html`
- Copy the content of `18-index.html` into three new files:
  - `about.html`: Change the `<title>` to `About - Techium`.
  - `latest_news.html`: Change the `<title>` to `Latest News - Techium`.
  - `contact.html`: Change the `<title>` to `Contact - Techium`.

---

### 2️⃣0️⃣ Add Links to Navigation
- **File:** `20-index.html`
- Inside the `<nav>` tag, add the following links:
  - Home: Link to `/`.
  - Services: Add an anchor link to `#services`.
  - Works: Add an anchor link to `#works`.
  - About: Link to `about.html`.
  - Latest News: Link to `latest_news.html`.
  - Testimonials: Add an anchor link to `#testimonials`.
  - Contact: Link to `contact.html`.

---

### 2️⃣1️⃣ Add Social Media Links
- **File:** `21-index.html`
- Inside the `<footer>`, add links to social media:
  - Facebook: Link to `https://www.facebook.com/HolbertonSchool/`.
  - Twitter: Link to `https://twitter.com/holbertonschool`.
  - Instagram: Link to `https://www.instagram.com/holbertonschool/`.

---

### 2️⃣2️⃣ Add "Button" Links
- **File:** `22-index.html`
- Add button-like links to specific sections:
  - Hero section: Add a link with the text `Get started` pointing to `#`.
  - About Us section: Add a link with the text `Learn more about us` pointing to `about.html`.
  - Contact section: Add a link with the text `Get in touch` pointing to `contact.html`.

---

### 2️⃣3️⃣ Add Links to Services, Works, and Latest News
- **File:** `23-index.html`
- Add links to headings in specific sections:
  - Services: Wrap each `<h3>` heading with a link pointing to `#`.
  - Works: Wrap each `<h3>` heading with a link pointing to `#`.
  - Latest News: Wrap each `<h3>` heading with a link pointing to `#`.

---

### 2️⃣4️⃣ List the Links
- **File:** `24-index.html`
- Convert navigation and footer links into lists:
  - In the `<nav>`, create an unordered list (`<ul>`) and place each link (`<a>`) inside a list item (`<li>`).
  - In the `<footer>`, create an unordered list for social media links.

---

### 2️⃣5️⃣ Add Secondary Navigation Menu
- **File:** `25-index.html`
- Inside the `<footer>`, after the social media links:
  - Add a new `<div>`.
  - Inside the `<div>`, create an unordered list with the following links:
    - Terms of Use: Link to `#`.
    - Privacy Policy: Link to `#`.
    - Cookie Policy: Link to `#`.

---

### 2️⃣6️⃣ Add Examples of Lists to the Styleguide
- **File:** `26-styleguide.html`
- Add examples of different types of lists:
  - **Unordered List:** Add a list with items like `Item 1`, `Item 2`, `Item 3`.
  - **Ordered List:** Add a list with items like `Step 1`, `Step 2`, `Step 3`.
  - **Definition List:** Add a list with terms and their definitions.

---

### 2️⃣7️⃣ Separate Content with a Horizontal Rule
- **File:** `27-index.html`
- Inside the `<footer>`, between the two `<div>` elements:
  - Add a horizontal rule (`<hr>`).
  - Below the `<hr>`, add a paragraph with the text:  
    `© 2020 Techium, made with ♥ by students at Holberton School.`

---

### 2️⃣8️⃣ Add Horizontal Rule Example to the Styleguide
- **File:** `28-styleguide.html`
- Add a new section titled `Horizontal Rule`:
  - Add a `<header>` with an `<h2>` heading: `Horizontal Rule`.
  - Add a `<div>` containing a horizontal rule (`<hr>`).

---

### 2️⃣9️⃣ Add Client Quotes
- **File:** `29-index.html`
- Inside the Testimonials section:
  - Replace the placeholder text in each `<article>` with a `<blockquote>`:
    - First quote:  
      `I am completely blown away. Thanks to Techium, we've just launched our 5th website!`  
      Cite: `Yuri Y.`
    - Second quote:  
      `Thank you so much for your help. Techium company is awesome!`  
      Cite: `Dorrie S.`
    - Third quote:  
      `I love your system. Definitely worth the investment. I'd be lost without Techium company.`  
      Cite: `Sven H.`

---

### 3️⃣0️⃣ Add Examples of Quotes to the Styleguide
- **File:** `30-styleguide.html`
- Add examples of quotes:
  - **Inline Quote:** Add a `<q>` tag with the text: `Stay hungry. Stay foolish.`
  - **Blockquote:** Add a `<blockquote>` with the text:  
    `I will be the leader of a company that ends up being worth billions of dollars, because I got the answers. I understand culture. I am the nucleus. I think that’s a responsibility that I have, to push possibilities, to show people, this is the level that things could be at.`  
    Cite: `Kanye West, Musician`.

---

### 3️⃣1️⃣ Add Address and Latest News Authors
- **File:** `31-index.html`
- Inside the `<footer>`, add an address:
  - `234 Washington Street` (line break)  
    `Urbana, Illinois`
- Inside the Latest News section:
  - Add the author name in small print (`<small>`) after the last paragraph of each article:
    - First article: `By Kelly D.`
    - Second article: `By William A.`
    - Third article: `By Frances J.`

---

### 3️⃣2️⃣ Add Typography Section to the Styleguide
- **File:** `32-styleguide.html`
- Add a new section titled `Typography`:
  - Add an address with the text:  
    `320 Stewart Avenue, Unit 12` (line break)  
    `New York City NY 10001`
  - Add a `<pre>` block with the following code:  
    ```html
    <h2>My title</h2>
    <p>Proin lacus turpis, feugiat sit amet sollicitudin non, volutpat in libero.</p>
    ```
  - Add a paragraph with highlighted text using `<mark>`.

---

### 3️⃣3️⃣ Add a Table
- **File:** [33-styleguide.html](http://_vscodecontentref_/0)
- Add a table with the following structure:
  - Columns: `Title`, `Director`, `Release Date`.
  - Rows: Add three movies with their respective details.
  - Use `<th>` with `scope="col"` for column headers and `scope="row"` for row headers.

---

### 3️⃣4️⃣ Add Details Section
- **File:** [34-styleguide.html](http://_vscodecontentref_/1)
- Add a new section titled `Details`:
  - Add a `<details>` element with a `<summary>`: `Show/Hide me`.
  - Add text inside the `<details>`:  
    `Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas.`

---

### 3️⃣5️⃣ Replace Text Logo with Image Logo
- **File:** [35-index.html](http://_vscodecontentref_/2)
- Replace the `<span>` logo in the header with an `<img>` tag:
  - Use the image `logo-black.png` with `alt="Techium logo"`.
  - Set the width to `160px` and height to `40px`.

---

### 3️⃣6️⃣ Add Images to Sections
- **File:** [36-index.html](http://_vscodecontentref_/3)
- Add images to the Works, About Us, Latest News, and Testimonials sections:
  - Use appropriate `<img>` tags with `alt` attributes and dimensions.

---

### 3️⃣7️⃣ Add Social Icons
- **File:** [index.html](http://_vscodecontentref_/4)
- Replace social media text links with SVG icons for Facebook, Twitter, and Instagram.

---

### 3️⃣8️⃣ Add a Video Player
- **File:** [38-styleguide.html](http://_vscodecontentref_/5)
- Embed a video with:
  - Controls, looping, and a thumbnail.
  - Alternative text: `Sorry, your browser doesn't support HTML5 video.`

---

### 3️⃣9️⃣ Add an Audio Player
- **File:** [39-styleguide.html](http://_vscodecontentref_/6)
- Embed an audio file with:
  - Controls.
  - Alternative text: `Sorry, your browser doesn't support audio element.`

---

### 4️⃣0️⃣ Add an Iframe
- **File:** [styleguide.html](http://_vscodecontentref_/7)
- Embed a YouTube video using an `<iframe>`:
  - Title: `Holberton School`.
  - Dimensions: `350px` by `200px`.
  - Fallback text: `Holberton Sally`.

---

## 🚀 Let’s Get Started!
Good luck, and have fun building your HTML project! 🎉