# Portfolio

## Overview
This is a portfolio website to display some services of the company. We will keep updating our website.

## Components

### Header
Header is the component a the top of the website. It contains logo, name, and navigation bar.
```html
<header>
        
        <div class="logo-name">
            <a href="./index.html">
                <img src="./images/CA_logo.png" alt="CA_logo">
            </a>
            <p class="name">
                <span class="coder-text">Coder</span>
                <span class="academy-text">Academy</span>
            </p>
        </div>

        <!-- the navigation bar need to be inside the header but outside the logo name -->
        <nav id="nav-items">
            <a href="./index.html">Home</a>
            <a href="./pages/about.html">About</a>
            <a href="./pages/contact.html">Contact</a>
        </nav>

    </header>
```