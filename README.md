# NGO-Bhuvi

# Basti Ki Pathshala Foundation - Website

A single-page, responsive, and interactive website for the **Basti Ki Pathshala Foundation**. This project aims to create a compelling online presence for the non-profit, guiding users through a journey of learning about the mission, building trust through impact data and testimonials, and finally encouraging them to act through volunteering or donations.



### 🔗 **Live Demo**

[**View the live project here**](https://bhuaneswar-24.github.io/NGO-Bhuvi/) &lt;-- 

---

## 📋 Table of Contents

* [About The Project](#about-the-project)
* [Built With](#built-with)
* [Key Features](#key-features)
* [Design & UX Philosophy](#design--ux-philosophy)
* [Getting Started](#getting-started)
* [File Structure](#file-structure)
* [Code Explanation](#code-explanation)
    * [JavaScript Interactivity](#javascript-interactivity)
* [Contributing](#contributing)
* [License](#license)
* [Author](#author)

---

## ✨ About The Project

This project is a self-contained, single-page application (SPA) designed to serve as the primary informational and engagement hub for the **Basti Ki Pathshala Foundation**. The foundation is dedicated to breaking the cycle of poverty by providing quality education to children in slum areas.

The website is strategically structured to:
1.  **Inform & Educate**: Clearly state the organization's mission, vision, and origins.
2.  **Build Credibility & Trust**: Showcase tangible impact through animated statistics and heartfelt testimonials.
3.  **Drive Action**: Provide a seamless and user-friendly way for visitors to volunteer or donate.

The entire website is built within a single `index.html` file, leveraging modern web technologies and a thoughtful user experience design to create a professional and effective online presence.

---

## 🛠️ Built With

This project relies entirely on front-end technologies with no backend dependencies, making it lightweight and easy to deploy.

* **[HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)**: For the core structure and content.
* **[Tailwind CSS](https://tailwindcss.com/)**: A utility-first CSS framework for rapid and responsive UI development (via CDN).
* **[Vanilla JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)**: For all dynamic features and interactivity, with no external libraries.
* **[Google Fonts](https://fonts.google.com/)**: For the 'Poppins' typeface to ensure clean and readable typography.

---

## 🚀 Key Features

* **Single-Page Application (SPA) Structure**: A modern, fluid user experience with smooth scrolling and no page reloads.
* **Responsive Design**: Fully functional and visually appealing on all devices, from mobile phones to desktops.
* **Sticky Navigation Bar**: Provides easy access to all sections and key actions (like "Donate Now") from anywhere on the page.
* **Dynamic Impact Counters**: Numbers in the "Our Impact" section animate (count up) when they scroll into the user's view, drawing attention to key metrics. This is powered by the `IntersectionObserver` API.
* **Automatic Testimonial Slider**: A carousel that cycles through intern and volunteer testimonials automatically, with manual next/previous controls for user interaction.
* **Interactive Volunteer Form**:
    * Features client-side validation using HTML5 attributes.
    * Includes a conditional input field that appears only when the "Other" skill is checked.
    * Upon successful submission, the form is replaced by a "Thank You" message without a page refresh, providing instant feedback.
* **Mobile-First Navigation**: A clean, accessible hamburger menu for smaller screens.

---

## 🎨 Design & UX Philosophy

The design choices were guided by a specific strategy to maximize user engagement and trust.

* **Color Palette: "Hopeful Horizon"**
    * A warm and inviting palette centered around **amber** and complemented by neutral **slate** tones. This choice evokes feelings of hope, optimism, and professionalism, aligning perfectly with the foundation's mission.

* **User Journey: "Learn -> Trust -> Act"**
    * The website's structure follows a logical flow designed to guide the visitor.
    1.  **Learn**: The **Home** and **About Us** sections introduce the foundation's purpose and story.
    2.  **Trust**: The **Impact Counters** and **Testimonials** provide social proof and data-backed evidence of the foundation's effectiveness, building emotional connection and credibility.
    3.  **Act**: The **Volunteer Form** and prominent **Donate** buttons provide clear, low-friction pathways for users to get involved.

---

## 🏁 Getting Started

To get a local copy up and running, follow these simple steps.

### Prerequisites

You only need a modern web browser (like Chrome, Firefox, or Edge). No other software or dependencies are required.

### Installation

1.  **Clone the repository:**
    ```sh
    git clone [https://github.com/Bhuaneswar-24/NGO-Bhuvi]
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd NGO-Bhuvi
    ```
3.  **Open the file:**
    * Simply open the `index.html` file in your web browser.

---

## 📂 File Structure

The entire project is self-contained within a single file, demonstrating an efficient and portable implementation.
