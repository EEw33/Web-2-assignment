# Advanced CSS Layouts: Flexbox & Grid

**Name:** Arlan Narushev  
**Group:** IT-2513 

## Summary of Work Process
This project demonstrates modern layout techniques without the use of floats or external frameworks. The overarching structure of the page (Header, Sidebar, Main Content, Footer) was built using **CSS Grid areas** to define clear 2-dimensional zones. Inside these zones, **Flexbox** was utilized for 1-dimensional layouts where alignment and equal spacing were critical (such as the navigation bar and the row of equal-height project cards). The image gallery combines Grid's `auto-fit` capability with relative/absolute positioning to create responsive image tiles with seamless hover overlays. 

## Completed Tasks & Screenshots

### Task 0: Navigation Bar
Used Flexbox (`justify-content: space-between`, `align-items: center`) to align the logo to the left and links to the right, keeping them vertically centered.
*(Insert Screenshot Here)*
`![Task 0 Screenshot](./screenshots/task0.png)`

### Task 1: Card Row
Created a flex container for the cards. Used `flex-direction: column` on individual cards and applied `margin-top: auto` to the buttons to ensure all cards have equal heights and buttons are uniformly pushed to the bottom. Added a `translateY` hover effect.
*(Insert Screenshot Here)*
`![Task 1 Screenshot](./screenshots/task1.png)`

### Task 2 & Task 4: Page Layout & Portfolio Structure
Turned the `<body>` into a Grid container using `grid-template-areas`. Mapped out `"header header"`, `"sidebar main"`, and `"footer footer"`, assigning each HTML semantic tag to its respective area. 
*(Insert Screenshot Here)*
`![Task 2 Screenshot](./screenshots/task2.png)`

### Task 3: Image Gallery
Used a CSS Grid container with 9 images. Applied `grid-template-columns: repeat(auto-fit, minmax(250px, 1fr))` for responsiveness. Implemented an absolute-positioned overlay caption that transitions from `opacity: 0` to `opacity: 1` on hover.
*(Insert Screenshot Here)*
`![Task 3 Screenshot](./screenshots/task3.png)`# Web-2-assignment
