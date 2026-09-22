# Front-End Web Development Portfolio

This project is my ongoing portfolio for the Front-End Web Development course.

I first created the portfolio using semantic HTML5 and then added CSS to improve the layout, colours, typography, and overall presentation. For this assignment, I developed the portfolio further by making it responsive across mobile, tablet, and desktop screen sizes.

## Responsive Design Approach

I used a mobile-first approach for the responsive design.

The base CSS is designed for smaller screens first. I then used media queries to adjust the layout as the available screen size increases.

The main breakpoints used are:

- Mobile: base styles below 768px
- Tablet: 768px and above
- Desktop: 1024px and above

I tested the website at:

- 375px for mobile
- 768px for tablet
- 1024px for desktop

This helped me check that the content remained readable and that there was no horizontal scrolling or content overflowing outside its containers.

## Layout

I used both CSS Grid and Flexbox in the project.

### CSS Grid

CSS Grid is used for the main page layout on tablet and desktop screens.

At smaller screen sizes, the sections appear in a single column.

From 768px and above, the Learning and Projects sections are displayed next to each other in two columns, while the About and Contact sections span the full width.

I also used a two-column Grid for the mobile navigation so that the four navigation links appear as a compact 2 × 2 layout.

### Flexbox

Flexbox is used for the navigation on tablet and desktop screens.

At 768px and above, the navigation changes from the mobile Grid layout into a horizontal row.

Flexbox also helps centre the text inside each navigation link.

## Navigation

The navigation was designed to change depending on the screen size.

On mobile screens, the links are displayed in a 2 × 2 layout so that the buttons remain easy to read and use without taking up too much vertical space.

On tablet and desktop screens, the navigation changes to one horizontal row.

The links also include a transition that changes the background and text colour when the user hovers over or focuses on them.

## Custom List Styling

The skills list in the What I Am Learning section uses custom check marks instead of the browser's normal list markers.

I removed the default list style and used the `::before` pseudo-element to add a blue check mark before each item.

This gave me practice using pseudo-elements and customising lists with CSS.

## Transitions and Interaction

I added several small transitions to make the website feel more interactive.

These include:

- Navigation link hover and focus transitions
- A colour transition on the contact email link
- A background colour transition on the Send Message button
- A hover effect on my portfolio image that slightly increases its size

The transitions are kept simple so that they provide feedback without distracting from the page content.

## Accessibility

I used semantic HTML5 elements such as:

- `header`
- `nav`
- `main`
- `section`
- `article`
- `figure`
- `footer`

The navigation includes an accessible label, form fields are connected to their labels, and the image contains alternative text.

Focus states are also visible for links and form controls to help users navigating with a keyboard.

## Challenges and Experiments

One of the main challenges was deciding how the navigation should behave on smaller screens.

My first mobile version displayed all four navigation buttons underneath each other. Although it worked, the buttons took up too much vertical space.

I changed the mobile navigation to a 2 × 2 Grid instead. This kept the buttons evenly spaced and easier to use while still allowing them to change into a horizontal Flexbox layout on larger screens.

I also tested the two-column Learning and Projects layout at the 768px breakpoint to make sure the content remained readable even though the two sections contain different amounts of text.

Working through the different screen sizes helped me understand how mobile-first CSS, media queries, Grid, and Flexbox can work together.

## Styling

The portfolio uses a simple blue, navy, white, and light grey colour scheme.

Main colours include:

- Navy: `#0f172a`
- Blue: `#1d4ed8`
- Light background: `#f8fafc`
- Border grey: `#e2e8f0`
- White: `#ffffff`

The main fonts are:

- Poppins for headings
- Roboto for body text

Fallback fonts are also included in the CSS.

## Validation

The HTML was checked using the Nu HTML Checker.

Result:

**No errors or warnings.**

The CSS was checked using the W3C CSS Validation Service.

Result:

**No errors found.**

## Project Files

The project contains:

- `index.html` – page structure and content
- `styles.css` – styling and responsive layout
- `images/` – portfolio images
- `README.md` – project documentation

## What I Learned

This project has helped me understand how a webpage can develop from a basic HTML structure into a responsive website.

I have practised:

- Semantic HTML5
- External CSS
- The CSS Box Model
- Typography and colour
- Responsive design
- Mobile-first development
- Media queries
- Flexbox
- CSS Grid
- Custom list styling
- CSS transitions
- Accessible focus states
- HTML and CSS validation
- Git and GitHub

I will continue updating the portfolio as I learn more throughout the course.