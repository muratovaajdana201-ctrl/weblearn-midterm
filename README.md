# WebLearn: Online Courses Website

## Project title and topic
**WebLearn** is an online courses website for the Web Technologies-1 course at Astana IT University. Students read the lectures, take a quiz and do live coding tasks after each lecture.

## Group members
- Aidana Muratova
- Zhasmira Mamyrbayeva
- Khanzada Nyshanbek

## Short description
A responsive website with the lectures of Week 1 (HTML Basics), Week 2 (CSS), Week 3 (Flexbox and Grid) and Week 4 (Bootstrap and Media Queries). After each lecture the student takes the quiz for that lecture and then does three live coding tasks for that lecture.

Pages: Home, Lectures, Quiz (hub + one quiz page per lecture: Week 1, Week 2, Week 3, Week 4), Live Coding (hub + one page per lecture), Contact (+ thank-you page).

## Features implemented
- Header with logo and Flexbox navigation, footer with contacts, copyright and social links on every page
- Hamburger menu on small screens
- Semantic HTML5, a table (lecture schedule) and forms (quizzes, live coding, contact)
- External CSS with variables, Flexbox, Grid, positioning, `:hover`, `:focus`, `:nth-child()`
- Responsive design: Bootstrap grid and utility classes, media queries for tablet and mobile
- "Take the quiz" and "Live coding" buttons after every lecture that open the quiz and the coding tasks for that lecture
- Quizzes with theory and code questions; **Check Answers** shows the correct answers (green), wrong choices (red) and an explanation, made with CSS only (`:checked` + sibling selectors `~` and `+`), **Try again** is a `reset` button
- Live Coding: three coding tasks per lecture, each with requirements, an expected result, a box for your code and a **Show Solution** button (CSS-only, same `:checked` trick as the quiz)
- Contact form with `required` fields; Send message submits the form (`action="thank-you.html" method="get"`) and opens a confirmation page
- Google Font (Sora), lazy loading for images below the fold

## Technologies used
HTML5, CSS3, Bootstrap 5.3, Google Fonts, GitHub Pages

## Individual contributions
- **Aidana Muratova:** Lectures page (lecture content and schedule table), Contact page, media queries and hamburger menu
- **Zhasmira Mamyrbayeva:** Quiz and Live Coding pages, forms, Bootstrap classes
- **Khanzada Nyshanbek:** project structure, Home page, header and footer, main `css/style.css` (variables, Flexbox, Grid), publishing the website

## Published website
(add the GitHub Pages / Netlify link here)
