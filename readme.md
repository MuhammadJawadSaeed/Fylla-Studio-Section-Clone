#  Fylla Studio Section Clone

A responsive clone of the **Studio** section from the [Fylla Framer Template](https://fylla-template.framer.website/studio), crafted using **HTML5** and **SCSS** to practice modern layout design and responsive development.

##  Overview

This project focuses on recreating the Studio section layout of the Fylla website using **semantic HTML** and **modular SCSS** with responsive design in mind. It includes two primary views (`view-1` and `view-2`), styled using flexbox and enhanced with breakpoints for large screens.

##  Key Features

-  Fully responsive layout using SCSS media queries
-  Modular SCSS with mixins (`@mixin light-weight-text`)
-  Flexbox-based structure with column/row reflow
-  Typography control using custom weights and spacing
-  Mobile-first design approach

##  Technologies Used

- **HTML5**
- **SCSS (Sass)**
- **CSS Flexbox**
- **Responsive Media Queries**
- **Google Fonts/System Fonts**

## SCSS Highlights

```scss
@mixin light-weight-text {
  font-weight: 300;
  opacity: 0.8;
}

.view-1 h1 {
  font-size: 3.6rem;
  font-weight: 400;
  width: 70%;
}

.view-2 .top h1 {
  font-size: 3rem;
  font-weight: 500;
}
```

> Responsive breakpoints kick in at `min-width: 1020px`, where the layout switches from vertical stacking to horizontal rows, adjusts font sizes, and realigns elements.


## How to Run

1. Clone the repo:

```bash
git clone https://github.com/MuhammadJawadSaeed/Fylla-Studio-Section-Clone.git
```

2. Open the HTML file in your browser:
 
 Use **Live Server** extension in VS Code.

##  Learning Outcomes

- Learned how to structure layouts using **Flexbox**
- Practiced creating **responsive UIs** with **SCSS media queries**
- Used **SCSS mixins** for reusable styles and cleaner code

## Credits

- UI inspiration: [Fylla Studio on Framer](https://fylla-template.framer.website/studio)
- Icons and fonts used are open-source

> This is a self-practice project and not intended for commercial use. All rights belong to the original template designers.

## Connect With Me

- LinkedIn: <a href="https://www.linkedin.com/in/muhammad-jawad-saeed-967b87368" target="_blank" rel="noopener noreferrer">Muhammad Jawad Saeed</a>
