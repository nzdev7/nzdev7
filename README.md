<div>
  <h1>EatNow - Restaurant Website</h1>

  <p>
    <strong>About Project:</strong> 
    A modern restaurant website featuring auto-rotating hero sliders, interactive menu showcase, and table reservation system built with React and Vite. Utilizes component-based architecture for maintainable code, Lucide React icons for clean UI elements, and CSS animations for engaging user interactions including preloader effects, sticky navigation, and mobile slide-out menu all organized in a scalable folder structure perfect for restaurant and dining businesses, and much more.
  </p>

  <p> 
    <strong>What I learned:</strong>
    Built reusable React components with hooks (useState, useEffect) for state management, implemented auto-advancing image sliders with interval cleanup, created responsive navigation with mobile overlay and body scroll lock, and structured component props for efficient data rendering, and much more.
  </p>

  <p> 
    <strong>Personal Note:</strong>
    I began my web development journey in 2022, focusing on learning fundamentals before sharing my work on GitHub. Currently I'm building <strong>Full Stack applications</strong> and seeking opportunities as a <strong>Frontend Developer</strong> or <strong>Full Stack Developer</strong>. Thank You!
  </p>
</div>

<details open> 
  <summary><h2>Project More Details</h2></summary>

  <details> 
    <summary><h4>What's Inside</h4></summary>
    <ul>
      <li><strong>Preloader Component</strong> - Animated circle with brand text that fades out when page loads</li>
      <li><strong>Top Bar</strong> - Contact information strip displaying location, hours, phone number, and email</li>
      <li><strong>Header Component</strong> - Sticky navigation with logo, menu links, active state tracking, and reservation button</li>
      <li><strong>Hero Slider</strong> - Auto-rotating three-slide carousel with subtitle, title, description, and navigation arrows</li>
      <li><strong>Service Section</strong> - Three category cards for Morning Meals, Starters, and Beverages with hover effects</li>
      <li><strong>About Section</strong> - Restaurant story with parallax images, decorative badge, and contact details</li>
      <li><strong>Special Dish Section</strong> - Featured menu item showcase with pricing, description, and promotional badge</li>
      <li><strong>Menu Section</strong> - Six menu cards with images, titles, prices, badges, and descriptions</li>
      <li><strong>Testimonials Section</strong> - Customer review with decorative quote, message, and profile image</li>
      <li><strong>Reservation Form</strong> - Table booking system with guest count, date picker, time selector, and contact panel</li>
      <li><strong>Features Section</strong> - Four benefit cards highlighting cleanliness, comfort, team experience, and private events</li>
      <li><strong>Event Section</strong> - Latest news cards with dates, categories, images, and event descriptions</li>
      <li><strong>Footer Component</strong> - Brand info, navigation links, social media, newsletter subscription, and copyright</li>
      <li><strong>Back to Top Button</strong> - Scroll-triggered floating button for quick page navigation</li>
      <li><strong>Mobile Navigation</strong> - Full-screen overlay menu with close button and location details</li>
    </ul>
  </details>

  <details> 
    <summary><h4>Technologies Used</h4></summary>
    <ul>
      <li><strong>React 18</strong> - Component-based UI library with hooks for state and side effects</li>
      <li><strong>Vite</strong> - Fast build tool with hot module replacement for development</li>
      <li><strong>Lucide React</strong> - Icon library providing clean SVG icons (MapPin, Clock, Phone, Mail, ChevronLeft, etc.)</li>
      <li><strong>CSS3</strong> - Modern styling with custom properties, Grid, Flexbox, transforms, and keyframe animations</li>
      <li><strong>JavaScript ES6+</strong> - Arrow functions, destructuring, template literals, and array methods</li>
      <li><strong>React Hooks</strong> - useState for component state, useEffect for lifecycle management and cleanup</li>
      <li><strong>Google Fonts</strong> - Lobster Two and Pacifico font families for elegant restaurant typography</li>
      <li><strong>Component Props</strong> - Data-driven rendering through props and array mapping</li>
      <li><strong>CSS Modules Pattern</strong> - Scoped styling with BEM-like class naming conventions</li>
      <li><strong>Responsive Design</strong> - Mobile-first approach with breakpoints for tablets and desktops</li>
    </ul>
  </details>

  <details> 
    <summary><h4>Project Structure</h4></summary>
    <pre>
    eat-now/
    │
    ├── public/                       # Static assets served directly
    │   ├── logo.png                 # Brand logo used in header and footer
    │   ├── hero-slider-1.jpg        # First hero slide background
    │   ├── hero-slider-2.jpg        # Second hero slide background
    │   ├── hero-slider-3.jpg        # Third hero slide background
    │   ├── service-1.jpg            # Morning Meals category image
    │   ├── menu-1.png               # Garden Fresh Bowl menu item
    │   ├── about-banner.jpg         # About section main image
    │   ├── special-dish-banner.jpg  # Featured dish image
    │   ├── testimonial-bg.jpg       # Review section background
    │   ├── footer-bg.jpg            # Footer background image
    │   └── (other images)           # Event cards, badges, shapes, icons
    │
    ├── src/
    │   ├── components/
    │   │   ├── Preloader.jsx        # Loading animation component
    │   │   ├── Header.jsx           # Top bar and navigation
    │   │   ├── Hero.jsx             # Auto-rotating slider
    │   │   ├── Service.jsx          # Category showcase
    │   │   ├── About.jsx            # Restaurant story section
    │   │   ├── Special.jsx          # Featured dish highlight
    │   │   ├── Menu.jsx             # Menu items grid
    │   │   ├── Testimonial.jsx      # Customer review
    │   │   ├── Reservation.jsx      # Booking form and contact
    │   │   ├── Features.jsx         # Benefit cards
    │   │   ├── Event.jsx            # Latest news section
    │   │   └── Footer.jsx           # Site footer with newsletter
    │   │
    │   ├── App.jsx                  # Main component importing all sections
    │   ├── main.jsx                 # React DOM render entry point
    │   └── index.css                # Global styles and CSS variables
    │
    ├── index.html                   # HTML template with meta tags and fonts
    ├── package.json                 # Dependencies and scripts
    ├── vite.config.js               # Vite configuration
    └── README.md                    # Project documentation
    </pre>
  </details>

  <details> 
    <summary><h4>Key Features</h4></summary>
    <ul>
      <li><strong>Component-Based Architecture</strong> - Modular React components for easy maintenance and reusability</li>
      <li><strong>Auto-Rotating Hero Slider</strong> - Three slides that change every 7 seconds with manual navigation controls</li>
      <li><strong>Sticky Header Navigation</strong> - Becomes fixed with background color after scrolling 50px</li>
      <li><strong>Active Link Tracking</strong> - Navigation highlights current section with custom styling</li>
      <li><strong>Mobile Slide-Out Menu</strong> - Full-screen overlay navigation with body scroll lock when active</li>
      <li><strong>Interactive Reservation Form</strong> - Date picker, time selector, guest count dropdown, and text area for notes</li>
      <li><strong>Hover and Shine Effects</strong> - Cards feature smooth transforms and overlay animations on mouse interaction</li>
      <li><strong>Parallax Image Elements</strong> - About section images with data attributes for depth effect</li>
      <li><strong>Scroll-Triggered Elements</strong> - Back-to-top button appears after 200px scroll distance</li>
      <li><strong>Data-Driven Content</strong> - Menu items, services, events, and features rendered from JavaScript arrays</li>
      <li><strong>Newsletter Subscription</strong> - Email input form in footer with promotional messaging</li>
      <li><strong>Badge System</strong> - "Popular" and "New" labels on menu items for highlighting</li>
      <li><strong>Cleanup Functions</strong> - Proper event listener removal in useEffect for memory optimization</li>
      <li><strong>Cross-Browser Support</strong> - Compatible with modern browsers including Chrome, Firefox, Safari, and Edge</li>
      <li><strong>Fast Performance</strong> - Vite's optimized build process and lazy loading of images</li>
      <li><strong>Fully Responsive Layout</strong> - Adapts seamlessly from 320px mobile screens to 1920px+ desktops</li>
    </ul>
  </details>

  <details> 
    <summary><h4>Quick Start</h4></summary>
    <ol>
      <li>
        <strong>Clone the repository:</strong>
        <pre><code>git clone https://github.com/nawazdevx/eat-now.git</code></pre>
      </li>

      <li>
        <strong>Navigate to project folder:</strong>
        <pre><code>cd eat-now</code></pre>
      </li>

      <li>
        <strong>Install dependencies:</strong>
        <pre><code>npm install</code></pre>
      </li>

      <li>
        <strong>Start development server:</strong>
        <pre><code>npm run dev</code></pre>
        Then visit the local URL shown in terminal (usually <code>http://localhost:5173</code>)
      </li>

      <li>
        <strong>Build for production:</strong>
        <pre><code>npm run build</code></pre>
        Production files will be generated in <code>dist/</code> folder
      </li>
    </ol>

  </details>

  <details> 
    <summary><h4>Customization</h4></summary>
    <ul>
      <li><strong>Restaurant Information:</strong> Update business name, address, phone, and email in <code>src/components/Header.jsx</code> and <code>Footer.jsx</code> topBarItems and contact sections</li>
      <li><strong>Hero Slides:</strong> Modify slide content in <code>src/components/Hero.jsx</code> slides array - change images, subtitles, titles, and descriptions</li>
      <li><strong>Menu Items:</strong> Edit <code>src/components/Menu.jsx</code> menuItems array to add, remove, or update dishes with new images, prices, and descriptions</li>
      <li><strong>Service Categories:</strong> Update <code>src/components/Service.jsx</code> services array with your restaurant's meal categories</li>
      <li><strong>Colors and Theme:</strong> Modify CSS custom properties in <code>src/index.css</code> :root selector for primary colors, backgrounds, and text
        <pre><code>:root {
  --gold-crayola: hsl(38, 61%, 73%);      /* Primary accent color */
  --quick-silver: hsla(0, 0%, 65%, 1);    /* Secondary text color */
  --davys-grey: hsla(30, 3%, 34%, 1);     /* Dark backgrounds */
}</code></pre>
      </li>
      <li><strong>Images:</strong> Replace files in <code>public/</code> folder with your restaurant photos - keep filenames the same or update references in component files</li>
      <li><strong>Typography:</strong> Change Google Fonts in <code>index.html</code> and update font-family in CSS file</li>
      <li><strong>Events/News:</strong> Modify <code>src/components/Event.jsx</code> events array to showcase your latest restaurant updates</li>
      <li><strong>Features Section:</strong> Update <code>src/components/Features.jsx</code> features array to highlight what makes your restaurant unique</li>
      <li><strong>About Content:</strong> Edit story text, phone number, and call-to-action in <code>src/components/About.jsx</code></li>
      <li><strong>Special Dish:</strong> Change featured item details, pricing, and image in <code>src/components/Special.jsx</code></li>
      <li><strong>Testimonial:</strong> Replace customer review, name, and avatar in <code>src/components/Testimonial.jsx</code></li>
      <li><strong>Navigation Links:</strong> Add or remove menu items in <code>src/components/Header.jsx</code> navLinks array</li>
      <li><strong>Reservation Times:</strong> Adjust available booking times in <code>src/components/Reservation.jsx</code> timeOptions array</li>
      <li><strong>Animation Speed:</strong> Change slider interval (currently 7000ms) and transition durations in component files and CSS</li>
    </ul>
  </details>

</details>

<p> 
  <strong>License:</strong>
  This project is licensed under the <a href="https://choosealicense.com/licenses/mit/">MIT License</a>.
</p>

<p> 
  <strong>Contact:</strong> 
  Connect with me on <a href="https://www.linkedin.com/in/nawazdevx">LinkedIn</a> or visit my <a href="https://nawazdevx.vercel.app/">Portfolio</a>.
</p>

<p> 
  <strong>Support:</strong> 
  Found this helpful? Give it a ⭐ on GitHub! Thank you.
</p>

<br />

<div>
  <h2>Project Preview</h2>

  <p>
    <strong>You can view the live project here ➜</strong>
    <a href="https://nawazdevx.github.io/eat-now/" target="_blank">
      <strong>Live Demo</strong>
    </a>
  </p>

  <img src="readme-image.png" alt="Desktop Demo" />
</div>
