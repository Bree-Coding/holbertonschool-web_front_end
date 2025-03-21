# 🌟 Advanced CSS Project

## 📖 Description

This project focuses on mastering **CSS fundamentals** and diving into **CSS advanced concepts**.  
You will learn how to create visually appealing and responsive designs using modern CSS techniques.



## 📚 Resources

- [CSS Reference - A free visual guide to CSS](https://cssreference.io/)
- [Can I use... Support tables for HTML5, CSS3, etc](https://caniuse.com/)
- [CSS Properties | HTML Dog](https://htmldog.com/references/css/properties/)
- [Box Sizing](https://css-tricks.com/box-sizing/)
- [CSS Specificity Calculator](https://specificity.keegan.st/)
- [Play with CSS selector](https://flukeout.github.io/)




## 🛠️ Requirements
You can save it in a index.html file and replace the
```html <link rel='stylesheet' href='#'>``` by the right CSS file.

```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
    <title>Homepage - Techium</title>
    <meta name="description" content="Description of the page less than 150 characters">
    <link rel="icon" type="image/png" href="images/favicon.jpg">
    <link href="https://fonts.googleapis.com/css?family=Open+Sans:400,700|Raleway:700&display=swap" rel="stylesheet">
    <link rel='stylesheet' href='#'>
  </head>
  <body>
    <!-- Header -->
    <header class="header" data-section-theme="dark">
      <div class="container">
        <div class="header-logo">
          <a href="#">
            <img src="images/logo-white.png" alt="Techium logo" width="160" height="40">
          </a>
        </div>
        <nav class="navbar-menu">
          <ul class="nav">
            <li class="nav-item">
              <a href="#" class="nav-link">Home</a>
            </li>
            <li class="nav-item">
              <a href="#services" class="nav-link">Services</a>
            </li>
            <li class="nav-item">
              <a href="#works" class="nav-link">Works</a>
            </li>
            <li class="nav-item">
              <a href="#about" class="nav-link">About</a>
            </li>
            <li class="nav-item">
              <a href="#latest_news" class="nav-link">Latest news</a>
            </li>
            <li class="nav-item">
              <a href="#testimonials" class="nav-link">Testimonials</a>
            </li>
            <li class="nav-item">
              <a href="#contact" class="nav-link">Contact</a>
            </li>
          </ul>
        </nav>
      </div>
    </header>
    <!-- Main -->
    <main>
      <h1 class="visually-hidden">Homepage</h1>
      <!-- Hero section -->
      <section class="section-hero" data-section-theme="dark">
        <div class="container">
          <div class="section-body">
            <section class="section-inner">
              <h2 class="section-title">We help you build your brand</h2>
              <a href="#" class="button">Get Started</a>
            </section>
          </div>
        </div>
      </section>
      <!-- Services section -->
      <section id="services" class="section">
        <div class="container">
          <header class="section-header">
            <h2 class="section-title">Services</h2>
            <p class="section-tagline">We work with you</p>
          </header>
          <div class="section-body">
            <ul class="row">
              <li class="col-1-3">
                <div class="card-services">
                  <h3 class="card-title"><a href="#">Design & Concept</a></h3>
                </div>
              </li>
              <li class="col-1-3">
                <div class="card-services">
                  <h3 class="card-title"><a href="#">Digital Strategy</a></h3>
                </div>
              </li>
              <li class="col-1-3">
                <div class="card-services">
                  <h3 class="card-title"><a href="#">Content Strategy</a></h3>
                </div>
              </li>
            </ul>
            <ul class="row">
              <li class="col-1-3">
                <div class="card-services">
                  <h3 class="card-title"><a href="#">UX Design</a></h3>
                </div>
              </li>
              <li class="col-1-3">
                <div class="card-services">
                  <h3 class="card-title"><a href="#">Web Development</a></h3>
                </div>
              </li>
              <li class="col-1-3">
                <div class="card-services">
                  <h3 class="card-title"><a href="#">Social Media</a></h3>
                </div>
              </li>
            </ul>
          </div>
        </div>
      </section>
      <!-- Works section -->
      <section id="works" class="section" data-section-theme="dark">
        <div class="container">
          <header class="section-header">
            <h2 class="section-title">Works</h2>
            <p class="section-tagline">Take a look at our portfolio</p>
          </header>
          <div class="section-body">
            <ul class="row">
              <li class="col-1-3">
                <article class="card-work">
                  <div class="card-outer">
                    <div class="card-image">
                      <img src="images/pic-work-01.jpg" alt="">
                    </div>
                    <div class="card-inner">
                      <h3 class="card-title"><a href="#">Interior Design</a></h3>
                    </div>
                  </div>
                </article>
              </li>
              <li class="col-1-3">
                <article class="card-work">
                  <div class="card-outer">
                    <div class="card-image">
                      <img src="images/pic-work-02.jpg" alt="">
                    </div>
                    <div class="card-inner">
                      <h3 class="card-title"><a href="#">Web Development</a></h3>
                    </div>
                  </div>
                </article>
              </li>
              <li class="col-1-3">
                <article class="card-work">
                  <div class="card-outer">
                    <div class="card-image">
                      <img src="images/pic-work-03.jpg" alt="">
                    </div>
                    <div class="card-inner">
                      <h3 class="card-title"><a href="#">Personal Development</a></h3>
                    </div>
                  </div>
                </article>
              </li>
            </ul>
          </div>
        </div>
      </section>
      <!-- About Us section -->
      <section id="about" class="section">
        <div class="container">
          <header class="section-header">
            <h2 class="section-title">About Us</h2>
            <p class="section-tagline">Everything about us</p>
          </header>
          <div class="section-body">
            <div class="row">
              <div class="col-1-2">
                <img src="images/pic-about-01.jpg" alt="" width="460" height="460">
              </div>
              <div class="col-1-2">
                <h3>Who are we</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!</p>
                <h3>Our culture</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!</p>
                <h3>How we work</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ipsum, omnis expedita! Eum, praesentium cumque accusantium rem, sit quaerat est nisi ratione, deserunt ducimus quidem iste dicta quibusdam atque maxime cum!</p>
              </div>
            </div>
          </div>
          <div class="section-footer">
            <a href="#" class="button">Learn more about us</a>
          </div>
        </div>
      </section>
      <!-- Latest news section -->
      <section id="latest_news" class="section">
        <div class="container">
          <header class="section-header">
            <h2 class="section-title">Latest News</h2>
          </header>
          <div class="section-body">
            <ul class="row">
              <li class="col-1-3">
                <article class="card-blog">
                  <div>
                    <img src="images/pic-article-01.jpg" alt="" width="305" height="305">
                  </div>
                  <p class="card-category">Career</p>
                  <h3><a href="#">Hoc loco tenere se Triarius non potuit.</a></h3>
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane?</p>
                  <small>By Kelly D.</small>
                </article>
              </li>
              <li class="col-1-3">
                <article class="card-blog">
                  <div>
                    <img src="images/pic-article-02.jpg" alt="" width="305" height="305">
                  </div>
                  <p class="card-category">Digital Life</p>
                  <h3><a href="#">Ut alios omittam, hunc appello, quem ille unum secutus est.</a></h3>
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Tum mihi Piso: Quid ergo? Tum ille: Ain tandem? Non autem hoc: igitur ne illud quidem. Sed quod proximum fuit non vidit. Nos commodius agimus. An nisi populari fama?</p>
                  <small>By William A.</small>
                </article>
              </li>
              <li class="col-1-3">
                <article class="card-blog">
                  <div>
                    <img src="images/pic-article-03.jpg" alt="" width="305" height="305">
                  </div>
                  <p class="card-category">Social</p>
                  <h3><a href="#">Bestiarum vero nullum iudicium puto.</a></h3>
                  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Non igitur bene. Quid enim est a Chrysippo praetermissum in Stoicis? Pugnant Stoici cum Peripateticis. Prioris generis est docilitas, memoria; Apparet statim, quae sint officia, quae actiones.</p>
                  <small>By Frances J.</small>
                </article>
              </li>
            </ul>
          </div>
        </div>
      </section>
      <!-- Testimonials section -->
      <section id="testimonials" class="section">
        <div class="container">
          <header class="section-header">
            <h2 class="section-title">Testimonials</h2>
            <p class="section-tagline">We are more than a digital company</p>
          </header>
          <div class="section-body">
            <ul class="row">
              <li class="col-1-3">
                <article class="card-testimonial">
                  <img src="images/pic-person-01.jpg" alt="Yuri Y. avatar" width="100" height="100" class="card-avatar">
                  <blockquote class="card-quote">
                    <p>I am completely blown away. Thanks to Techium, we've just launched our 5th website!
                      <cite>Yuri Y.</cite>
                    </p>
                  </blockquote>
                </article>
              </li>
              <li class="col-1-3">
                <article class="card-testimonial">
                  <img src="images/pic-person-02.jpg" alt="Dorrie S. avatar" width="100" height="100" class="card-avatar">
                  <blockquote class="card-quote">
                    <p>Thank you so much for your help. Techium company is awesome!
                      <cite>Dorrie S.</cite>
                    </p>
                  </blockquote>
                </article>
              </li>
              <li class="col-1-3">
                <article class="card-testimonial">
                  <img src="images/pic-person-03.jpg" alt="Sven H. avatar" width="100" height="100" class="card-avatar">
                  <blockquote class="card-quote">
                    <p>I love your system. Definitely worth the investment. I'd be lost without Techium company.
                      <cite>Sven H.</cite>
                    </p>
                  </blockquote>
                </article>
              </li>
            </ul>
          </div>
        </div>
      </section>
      <!-- Contact section -->
      <section id="contact" class="section">
        <div class="container">
          <header class="section-header">
            <h2 class="section-title">Contact</h2>
            <p class="section-tagline">We'd love to hear from you!</p>
          </header>
          <div class="section-body">
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Id Sextilius factum negabat. Quo tandem modo? At eum nihili facit; Quae contraria sunt his, malane?</p>
          </div>
          <div class="section-footer">
            <a href="#" class="button">Get in touch</a>
          </div>
        </div>
      </section>
            </main>
    <!-- Footer -->
    <footer class="footer" data-section-theme="dark">
      <div  class="container">
        <div class="row">
          <div class="col-1-2">
            <img src="images/logo-white.png" alt="Techium logo" width="160" height="40">
            <address class="footer-address">
              972 Mission St<br>
              San Francisco, CA<br>
              94103
            </address>
          </div>
          <div class="col-1-2">
            <ul class="social nav">
              <li class="social-item nav-item">
                <a href="https://www.facebook.com/HolbertonSchool/" class="social-link">
                  <svg viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" width="25" height="25">
                    <title>
                      Facebook icon
                    </title>
                    <path d="M23.998 12c0-6.628-5.372-12-11.999-12C5.372 0 0 5.372 0 12c0 5.988 4.388 10.952 10.124 11.852v-8.384H7.078v-3.469h3.046V9.356c0-3.008 1.792-4.669 4.532-4.669 1.313 0 2.686.234 2.686.234v2.953H15.83c-1.49 0-1.955.925-1.955 1.874V12h3.328l-.532 3.469h-2.796v8.384c5.736-.9 10.124-5.864 10.124-11.853z"/>
                  </svg>
                </a>
              </li>
              <li class="social-item nav-item">
                <a href="https://twitter.com/holbertonschool" class="social-link">
                  <svg viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" width="25" height="25">
                    <title>
                      Twitter icon
                    </title>
                    <path d="M23.954 4.569a10 10 0 0 1-2.825.775 4.958 4.958 0 0 0 2.163-2.723c-.951.555-2.005.959-3.127 1.184a4.92 4.92 0 0 0-8.384 4.482C7.691 8.094 4.066 6.13 1.64 3.161a4.822 4.822 0 0 0-.666 2.475c0 1.71.87 3.213 2.188 4.096a4.904 4.904 0 0 1-2.228-.616v.061a4.923 4.923 0 0 0 3.946 4.827 4.996 4.996 0 0 1-2.212.085 4.937 4.937 0 0 0 4.604 3.417 9.868 9.868 0 0 1-6.102 2.105c-.39 0-.779-.023-1.17-.067a13.995 13.995 0 0 0 7.557 2.209c9.054 0 13.999-7.496 13.999-13.986 0-.209 0-.42-.015-.63a9.936 9.936 0 0 0 2.46-2.548l-.047-.02z"/>
                  </svg>
                </a>
              </li>
              <li class="social-item nav-item">
                <a href="https://www.instagram.com/holbertonschool/" class="social-link">
                  <svg viewbox="0 0 24 24" xmlns="http://www.w3.org/2000/svg" width="25" height="25">
                    <title>
                      Instagram icon
                    </title>
                    <path d="M12 0C8.74 0 8.333.015 7.053.072 5.775.132 4.905.333 4.14.63c-.789.306-1.459.717-2.126 1.384S.935 3.35.63 4.14C.333 4.905.131 5.775.072 7.053.012 8.333 0 8.74 0 12s.015 3.667.072 4.947c.06 1.277.261 2.148.558 2.913a5.885 5.885 0 0 0 1.384 2.126A5.868 5.868 0 0 0 4.14 23.37c.766.296 1.636.499 2.913.558C8.333 23.988 8.74 24 12 24s3.667-.015 4.947-.072c1.277-.06 2.148-.262 2.913-.558a5.898 5.898 0 0 0 2.126-1.384 5.86 5.86 0 0 0 1.384-2.126c.296-.765.499-1.636.558-2.913.06-1.28.072-1.687.072-4.947s-.015-3.667-.072-4.947c-.06-1.277-.262-2.149-.558-2.913a5.89 5.89 0 0 0-1.384-2.126A5.847 5.847 0 0 0 19.86.63c-.765-.297-1.636-.499-2.913-.558C15.667.012 15.26 0 12 0zm0 2.16c3.203 0 3.585.016 4.85.071 1.17.055 1.805.249 2.227.415.562.217.96.477 1.382.896.419.42.679.819.896 1.381.164.422.36 1.057.413 2.227.057 1.266.07 1.646.07 4.85s-.015 3.585-.074 4.85c-.061 1.17-.256 1.805-.421 2.227a3.81 3.81 0 0 1-.899 1.382 3.744 3.744 0 0 1-1.38.896c-.42.164-1.065.36-2.235.413-1.274.057-1.649.07-4.859.07-3.211 0-3.586-.015-4.859-.074-1.171-.061-1.816-.256-2.236-.421a3.716 3.716 0 0 1-1.379-.899 3.644 3.644 0 0 1-.9-1.38c-.165-.42-.359-1.065-.42-2.235-.045-1.26-.061-1.649-.061-4.844 0-3.196.016-3.586.061-4.861.061-1.17.255-1.814.42-2.234.21-.57.479-.96.9-1.381.419-.419.81-.689 1.379-.898.42-.166 1.051-.361 2.221-.421 1.275-.045 1.65-.06 4.859-.06l.045.03zm0 3.678a6.162 6.162 0 1 0 0 12.324 6.162 6.162 0 1 0 0-12.324zM12 16c-2.21 0-4-1.79-4-4s1.79-4 4-4 4 1.79 4 4-1.79 4-4 4zm7.846-10.405a1.441 1.441 0 0 1-2.88 0 1.44 1.44 0 0 1 2.88 0z"/>
                  </svg>
                </a>
              </li>
            </ul>
          </div>
        </div>
        <hr>
        <div class="row">
          <div class="col-1-2">
            <p class="footer-copyright">© 2020 Techium, made with ♥ by students at Holberton School.</p>
          </div>
          <div class="col-1-2">
            <ul class="footer-nav nav">
              <li class="footer-nav-item nav-item">
                <a href="#" class="footer-nav-link">Terms of use</a>
              </li>
              <li class="footer-nav-item nav-item">
                <a href="#" class="footer-nav-link">Privacy Policy</a>
              </li>
              <li class="footer-nav-item nav-item">
                <a href="#" class="footer-nav-link">Cookie Policy</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </footer>
  </body>
</html>
```



## 📝 Tasks

### 0. 🖼️ Let's get some images!
- Download 10 high-resolution images from Unsplash.
- Include the 3 provided images (`favicon.jpg`, `logo-black.png`, `logo-white.png`).
- Store all images in the `images` directory.



### 1. 🌐 Effortless transitions when scrolling
- Add smooth scrolling behavior to the `html` element using the `scroll-behavior` property.  
  **File:** `styles/1-style.css`



### 2. 🎨 Do you know your color values?
- Set specific color values for:
  - `body` and `a`: `#161616`
  - `.visually-hidden`: `display: none`
  - `.card-category` and `.section-tagline`: `#D73953`  
  **File:** `styles/2-style.css`



### 3. ♻️ Reuse and repeat with variables
- Define custom properties for colors:
  - `--color-primary: #d73953`
  - `--color-black: #090909`
  - `--color-white: #ffffff`
  - `--color-light-grey: #f3f3f3`
  - `--color-dark-grey: #353535`
  - `--text-color: var(--color-black)`
- Update `.section-tagline` and `.card-category` to use `--color-primary`.  
  **File:** `styles/3-style.css`



### 4. ✍️ Variables for font types
- Create custom font-family properties:
  - `--font-family-base: 'Helvetica Neue', Helvetica, Arial, sans-serif`
  - `--font-family-title: 'Helvetica Neue', Helvetica, Arial, sans-serif`
- Apply `--font-family-base` to `body` and `--font-family-title` to all headings (`h1` to `h6`).  
  **File:** `styles/4-style.css`



### 5. 🔠 Variables for font sizes
- Define font size variables:
  - `--font-size-small: 1.2rem`
  - `--font-size-medium: 1.6rem`
  - `--font-size-large: 1.8rem`
  - `--font-size-x-large: 2.3rem`
  - `--font-size-xx-large: 4.8rem`
- Set `html` font size to `62.5%` and `body` font size to `--font-size-medium`.  
  **File:** `styles/5-style.css`



### 6. 💪 Variables for font weight
- Add font weight variables:
  - `--font-weight-regular: 400`
  - `--font-weight-bold: 700`
- Apply `--font-weight-regular` to `body` and `--font-weight-bold` to headings.  
  **File:** `styles/6-style.css`



### 7. 🌐 Integrating Google Fonts
- Add **Open Sans** to `--font-family-base` and **Raleway** to `--font-family-title`.  
  **File:** `styles/7-style.css`



### 8. 📏 Defining line heights
- Create line-height variables:
  - `--line-height-small: 1.2`
  - `--line-height-base: 1.5`
  - `--line-height-big: 1.8`
- Apply `--line-height-base` to `body`.  
  **File:** `styles/8-style.css`


### 9. 🚫 Remove link decorations
- Remove text decorations from all anchor elements (`text-decoration: none`).  
  **File:** `styles/9-style.css`



### 10. 🎯 Centering section titles
- Create a custom property `--section-header-align: center` and apply it to `.section-header`.  
  **File:** `styles/10-style.css`



### 11. 🔤 Add styles to section tagline
- Style `.section-tagline`:
  - Font family: `--font-family-title`
  - Text transform: `uppercase`
  - Font weight: `--font-weight-bold`
- Use a custom property `--section-tagline-transform` for the text transformation.  
  **File:** `styles/11-style.css`



### 12. 🎨 Adding styles to section title
- Style `.section-title`:
  - Font family: `--font-family-title`
  - Font size: `--font-size-xx-large`
  - Font weight: `--font-weight-bold`
  - Margin: `0` (use a custom property `--section-title-margin`)
  - Color: `--color-black` (use a custom property `--section-title-color`)  
  **File:** `styles/12-style.css`



### 13. 🌀 Pseudo Classes
- Style anchor pseudo-classes:
  - `:visited`: Italicize text.
  - `:hover`: Add underline.
  - `:active`: Set background color to `--color-light-grey`.  
  **File:** `styles/13-style.css`



### 14. 🔄 Resetting CSS
- Normalize your CSS using `normalize.css`.  
  **File:** `styles/14-style.css`


### 15. 📦 Add universal box-sizing
- Apply `box-sizing: border-box` to all elements using the universal selector (`*`).  
  **File:** `styles/15-style.css`



### 16. 📐 Styling the container
- Style `.container`:
  - Width: `960px`
  - Centered margins (`margin: 0 auto`).  
  **File:** `styles/16-style.css`



### 17. 📏 Adding padding to sections
- Add padding to `.section`, `.section-header`, `.section-body`, and `.section-footer` using custom properties:
  - `--section-padding: 5rem 0`
  - `--section-header-padding: 0 0 3rem`
  - `--section-body-padding: 0 0 3rem`
  - `--section-footer-padding: 3rem 0 0`
  - `--section-footer-align: center`  
  **File:** `styles/17-style.css`



### 18. 🧭 Customizing the navbar
- Style `.navbar-menu`, `.nav`, `.nav-item`, and `.nav-link`:
  - Float `.navbar-menu` to the right.
  - Remove margins and padding for `.nav`.
  - Style `.nav-item` with:
    - Font family: `--font-family-title`
    - Font weight: `--font-weight-bold`
    - Font size: `--font-size-medium`
    - Letter spacing: `4% of the root element`
    - Display: `inline-block`
    - Margin: `3rem 0 0 0`
  - Style `.nav-link` with:
    - Display: `block`
    - Padding: `0.5rem 1rem`
    - Hover state: Foreground color `--color-primary`.  
  **File:** `styles/18-style.css`



### 19. 🧮 Grid styling and custom variables
- Style grid elements:
  - `.row`: Remove margins and padding, and remove default list styles.
  - `.col-1-3`: Width `33.33%`, float left, padding `0.5rem`.
  - `.col-1-2`: Width `50%`, float left, padding `0.5rem`.
  - `.footer-copyright`: No margins, font size `--font-size-small`, color `--text-color`.
  - Align text to the right for all `<ul>` tags in `.footer`.  
  **File:** `styles/19-style.css`



### 20. 🧹 Clear the grid context
- Add a rule to clear floats after `.row`:
  - Use `content: ""`.
  - Display as `table`.
  - Clear floats on both sides (`clear: both`).  
  **File:** `styles/20-style.css`



### 21. 🧩 Simplify column selectors
- Use a single rule for all `.col-*` classes:
  - Float left.
  - Padding `0.5rem`.  
  **File:** `styles/21-style.css`


### 22. 🌑 Add a dark theme
- Style sections with `data-section-theme="dark"`:
  - Redefine `--text-color` to `--color-white`.
  - Redefine `--section-title-color` to `--color-white`.
  - Set background to `--color-black`.  
  **File:** `styles/22-style.css`



### 23. 🛠️ Fix dark theme issues
- Style `.footer-address`:
  - Set text color to `--text-color`.
- Style `.social-link`:
  - Render as block elements.
  - For `svg` children, set `fill` color to `--text-color`.  
  **File:** `styles/23-style.css`


### 24. 🖌️ Add background and hover states
- Style `.card-services`:
  - Set `a` inside `.card-services` to:
    - Display: `block`
    - Padding: `2rem`
    - Background color: `--color-light-grey`
  - Hover state:
    - Foreground color: `--color-white`
    - Background color: `--color-primary`
    - Remove text decoration.  
  **File:** `styles/24-style.css`



### 25. 🔲 Add button borders
- Style `.button`:
  - Add custom properties:
    - `--button-display: inline-block`
    - `--button-padding: 1.5rem 3rem`
    - `--button-border: 0.2rem solid var(--color-primary)`
    - `--button-color: var(--color-black)`
    - `--button-text-decoration: none`
    - `--button-font-size: var(--font-size-large)`
    - `--button-hover-color: var(--color-white)`
    - `--button-hover-background: var(--color-primary)`
  - Apply these properties to `.button` and its hover state.  
  **File:** `styles/25-style.css`



### 26. 🖼️ Add border radius to images
- Style `.card-avatar`:
  - Border radius: `50%`
  - Width and height: `10rem`
- Style `<cite>` inside `.card-quote`:
  - Display: `block`
  - Padding top: `1rem`
  - Color: `--color-primary`.  
  **File:** `styles/26-style.css`



### 27. 🦸 Styling the hero section
- Style `.section-hero`:
  - Background size: `90rem auto`
- Style `.section-title` inside `.section-hero`:
  - Margin bottom: `5rem`
- Style `.section-inner` inside `.section-hero`:
  - Padding: `10rem 40rem 2rem 0`.  
  **File:** `styles/27-style.css`


### 28. 🧭 Fix header and navigation bar
- Style `.header`:
  - Padding: `4rem 0 0`
- Style `.header-logo`:
  - Position: `relative`
- Style `<a>` inside `.header-logo`:
  - Display: `inline-block`
  - Position: `absolute`
  - Top: `-1rem`
  - Left: `0`.  
  **File:** `styles/28-style.css`



### 29. 🧑‍🎨 Styling navigation items
- Add hover effects and pseudo-elements to `.nav-link`:
  - Use `::before` pseudo-elements:
    - Content: `""`
    - Position: `absolute`
    - Background color: `--color-white`
    - Width: `0`
    - Height: `20%`
  - On hover, set background color to `--color-primary` and width to `100%`.  
  **File:** `styles/29-style.css`



### 30. 🛠️ Fix the works section
- Style `.card-work`:
  - Add hover effects to `.card-image` and `.card-inner`.
  - Use `transform: scale()` for animations.
  - Style `.card-title` with centered text and hover effects.  
  **File:** `styles/30-style.css`



### 31. 💬 Add quotes decoration
- Style `.card-quote`:
  - Add `::before` pseudo-element:
    - Content: `\201C`
    - Position: `absolute`
    - Font size: `10rem`
    - Color: `#efeded`
    - Z-index: `-1`.  
  **File:** `styles/31-style.css`



### 32. 🎥 Add transitions
- Add transitions to:
  - `.card-work:hover .card-image`: Use `transform: scale(1.2)`.
  - `.nav .nav-link::before`: Use `transition` with `cubic-bezier`.
  - `.button:hover`: Animate `background-color` and `color`.  
  **File:** `styles/32-style.css`
