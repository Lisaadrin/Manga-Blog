Beyond Magic - Manga & Anime Blog
A responsive multi-page blog project focused on manga and anime reviews, such as Hunter x Hunter and Goodnight Punpun. The primary goal of this project was to master Responsive Web Design using modern CSS techniques.

🚀 Learning Objectives: Responsive CSS
The core of this project was implementing a "mobile-first" or adaptive approach to ensure the layout works across different screen sizes.

Key Features Implemented:
Media Queries: Used to transition from a single-column mobile layout to a complex grid system on larger screens (e.g., @media (min-width: 1024px)).

CSS Grid & Flexbox:

Flexbox is used for the navigation bar to keep links aligned and for the cookie popup buttons.

CSS Grid is utilized on the "About Me" and "Blog" pages to create sophisticated layouts where images and text reposition based on screen width.

Fluid Typography & Spacing: Use of rem and em units instead of fixed pixels to ensure the design scales naturally with the browser's root font size.

Responsive Images: Images are styled to adapt to their containers without breaking the layout.

📂 Project Structure
index.html: The landing page featuring a "Hero" section with a featured post.

about-me.html: A profile page demonstrating grid-based layout shifts.

blog.html & blog-1.html to blog-6.html: Individual review pages with consistent responsive styling.

main-page-styles.css: The central stylesheet containing all layout logic, custom font faces (Cormorant Unicase), and responsive breakpoints.

index.js: Handles interactive elements like the cookie consent popup.

🛠️ Technologies Used
HTML5: Semantic structure (using <header>, <main>, <section>, and <article>).

CSS3: Custom properties, Flexbox, CSS Grid, and Media Queries.

JavaScript: Basic DOM manipulation for UI components.

🎨 Design Notes
The project uses a dark, atmospheric color palette (#370617 background) with high-contrast text to match the "Beyond Magic" theme. The typography relies on the Cormorant Unicase font family to provide a unique, stylized look for a manga-themed blog.
