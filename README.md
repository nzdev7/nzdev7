<div>
  <h1>EatNow - Restaurant Website</h1>
  <p>
    <strong>About Project:</strong> 
    A modern restaurant landing page featuring an immersive dining experience with smooth slider animations, interactive menu displays, and a complete table reservation system. Crafted with React components and custom CSS properties for elegant theming, delivering a polished presentation that restaurants can adapt to showcase their culinary offerings, and much more.
  </p>
  <p> 
    <strong>What I learned:</strong>
    Built a complete React application using Vite for fast development, implemented complex CSS animations with keyframes and transitions, managed component state for interactive elements like sliders and navigation, and structured scalable component architecture for maintainable code, and much more.
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
      <li><strong>Preloader</strong> - Animated loading screen with rotating circle and gradient text effect</li>
      <li><strong>Header</strong> - Fixed navigation with contact info bar, logo, and mobile hamburger menu</li>
      <li><strong>Hero Slider</strong> - Auto-rotating image carousel with smooth scale animations and navigation arrows</li>
      <li><strong>Service Section</strong> - Three category cards with hover shine effects and decorative background shapes</li>
      <li><strong>About Section</strong> - Restaurant story with parallax imagery, phone reservation, and animated badges</li>
      <li><strong>Special Dish</strong> - Featured menu item showcase with original and discounted pricing display</li>
      <li><strong>Menu Section</strong> - Grid of food items with images, descriptions, prices, and category badges</li>
      <li><strong>Testimonials</strong> - Customer review section with background image and quote styling</li>
      <li><strong>Reservation Form</strong> - Complete booking system with guest count, date picker, and time selection</li>
      <li><strong>Features Grid</strong> - Four quality highlights with icon cards and hover rotation effects</li>
      <li><strong>Events Section</strong> - Upcoming happenings with date overlays and category labels</li>
      <li><strong>Footer</strong> - Newsletter signup, contact details, social links, and back-to-top button</li>
    </ul>
  </details>
  <details> 
    <summary><h4>Technologies Used</h4></summary>
    <ul>
      <li><strong>React 18</strong> - Component-based architecture with hooks for state management</li>
      <li><strong>Vite</strong> - Fast build tool and development server with hot module replacement</li>
      <li><strong>CSS3</strong> - Custom properties, Grid, Flexbox, keyframe animations, and transforms</li>
      <li><strong>Lucide React</strong> - Modern SVG icon library for UI elements</li>
      <li><strong>Google Fonts</strong> - Pacifico and Lobster Two font families for elegant typography</li>
      <li><strong>CSS Custom Properties</strong> - Variables for gold, powder blue, and dark theme colors</li>
      <li><strong>CSS Animations</strong> - Smooth reveals, rotating elements, floating shapes, and hover transitions</li>
      <li><strong>Media Queries</strong> - Responsive breakpoints at 575px, 768px, 992px, 1200px, and 1400px</li>
      <li><strong>ESLint</strong> - Code quality and consistency checking</li>
    </ul>
  </details>
  <details> 
    <summary><h4>Project Structure</h4></summary>
    <pre>
eat-now/
│
├── public/                   # Hero banners, menu photos, event images, icons
│
├── src/
│   ├── components/
│   │   ├── Preloader.jsx     # Loading animation component
│   │   ├── Header.jsx        # Navigation with mobile menu
│   │   ├── Hero.jsx          # Image slider with auto-play
│   │   ├── Service.jsx       # Food category cards
│   │   ├── About.jsx         # Restaurant story section
│   │   ├── Special.jsx       # Featured dish showcase
│   │   ├── Menu.jsx          # Food menu grid
│   │   ├── Testimonial.jsx   # Customer review section
│   │   ├── Reservation.jsx   # Booking form component
│   │   ├── Features.jsx      # Quality highlights grid
│   │   ├── Event.jsx         # Upcoming events cards
│   │   └── Footer.jsx        # Footer with newsletter
│   │
│   ├── App.jsx               # Main application layout
│   ├── main.jsx              # React entry point
│   └── index.css             # Global styles and CSS variables
│
├── index.html                # HTML template with font links
├── package.json              # Dependencies and scripts
├── vite.config.js            # Vite configuration
├── eslint.config.js          # ESLint rules
└── README.md                 # Project documentation
    </pre>
  </details>
  <details> 
    <summary><h4>Key Features</h4></summary>
    <ul>
      <li><strong>Fully Responsive Design</strong> - Optimized for mobile, tablet, and desktop screens</li>
      <li><strong>Auto-Playing Hero Slider</strong> - Three slides with 7-second intervals and smooth scale animations</li>
      <li><strong>Mobile Navigation</strong> - Slide-out menu with overlay and contact information</li>
      <li><strong>Sticky Header</strong> - Navigation becomes fixed with background color change on scroll</li>
      <li><strong>Interactive Menu Cards</strong> - Hover effects with image scaling and shine animations</li>
      <li><strong>Table Reservation System</strong> - Complete form with dropdowns for guests, date picker, and time slots</li>
      <li><strong>Decorative Animations</strong> - Floating shapes, rotating badges, and moving elements throughout</li>
      <li><strong>Price Display</strong> - Original and discounted pricing with strikethrough styling</li>
      <li><strong>Category Badges</strong> - "Popular" and "New" labels for menu items</li>
      <li><strong>Newsletter Subscription</strong> - Email input with icon in footer section</li>
      <li><strong>Back to Top Button</strong> - Appears after scrolling with smooth scroll behavior</li>
      <li><strong>Custom Typography</strong> - Elegant font pairing for headings and body text</li>
      <li><strong>Dark Theme Design</strong> - Sophisticated black and gold color scheme</li>
    </ul>
  </details>
  <details> 
    <summary><h4>Quick Start</h4></summary>
    <ol>
      <li>
        <strong>Clone the repository:</strong>
        <pre><code>git clone https://github.com/nawazdevx/eat-now.git</code></pre>
      </li>
Copy
  <li>
    <strong>Install dependencies:</strong>
    <pre><code>cd eat-now
npm install
Copy
  <li>
    <strong>Start development server:</strong>
    <pre><code>npm run dev</code></pre>
    Then visit <code>http://localhost:5173</code>
  </li>

  <li>
    <strong>Build for production:</strong>
    <pre><code>npm run build</code></pre>
  </li>
</ol>
  </details>
  <details> 
    <summary><h4>Start Customizing</h4></summary>
    <ul>
      <li>Update restaurant name and content in <code>src/components/</code> files</li>
      <li>Change theme colors in <code>src/index.css</code> using CSS variables</li>
      <li>Replace images in <code>public/images/</code> folder</li>
      <li>Modify menu items in <code>src/components/Menu.jsx</code></li>
      <li>Update contact details and hours in <code>src/components/Footer.jsx</code></li>
    </ul>
  </details>
  <details> 
    <summary><h4>Customization</h4></summary>
    <ul>
      <li><strong>Text Content:</strong> Edit component files in <code>src/components/</code> - update restaurant name, menu descriptions, event details, and contact information</li>
      <li><strong>Colors:</strong> Update CSS variables in <code>:root</code> selector in <code>src/index.css</code>
        <pre><code>:root {
  --gold-crayola: hsl(38, 61%, 73%);      /* Primary gold accent */
  --powder-blue: hsl(195, 51%, 82%);      /* Secondary blue accent */
  --eerie-black-1: hsla(210, 4%, 9%, 1);  /* Main background */
}</code></pre>
      </li>
      <li><strong>Images:</strong> Replace files inside <code>public/images/</code> with your own photos (keep same filenames or update component references)</li>
      <li><strong>Fonts:</strong> Change the Google Fonts link in <code>index.html</code> and update <code>--fontFamily-Pacifico</code> and <code>--fontFamily-Lobster</code> variables</li>
      <li><strong>Menu Items:</strong> Modify the <code>menuItems</code> array in <code>src/components/Menu.jsx</code> to add or remove dishes</li>
      <li><strong>Hero Slides:</strong> Update the <code>slides</code> array in <code>src/components/Hero.jsx</code> with new images and text</li>
      <li><strong>Business Hours:</strong> Adjust operating times in <code>src/components/Reservation.jsx</code> and <code>src/components/Footer.jsx</code></li>
      <li><strong>Animations:</strong> Adjust timing in <code>@keyframes</code> sections and transition properties in CSS</li>
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
