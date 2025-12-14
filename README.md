Professional business card:
This repository contains the HTML and CSS code required to create a modern, high-resolution digital business card featuring an elegant gradient background, subtle geometric elements, and interactive hover effects.
    ✨ Features
            1.Minimalist Design: Sophisticated deep navy to soft gray gradient for a premium, low-saturation look.
            2.Print-Ready Aspect Ratio: Designed with a 3.5x2 inch horizontal ratio in mind (scaled up for high-resolution web display).
            3.Circular Headshot Placeholder: Features a central circular cutout for a professional portrait.
            4.Interactive Hover Effects:
                Card Lift: The card lifts slightly and casts a deeper shadow on hover.
                Parallax Background: Blurred shapes shift gently for a 3D depth effect.
                Profile Zoom: The photo subtly zooms in when moused over.
                Text Glow: Contact details brighten and slide when hovered over.
            5.Pure CSS Shapes: The geometric background elements are created entirely with CSS, ensuring crisp details and fast loading.

  🚀 Getting Started
      Follow these steps to set up and view the business card template locally.
        Prerequisites
            A web browser (Chrome, Firefox, Safari, etc.)
            A text editor (VS Code, Sublime Text, etc.)
            Your professional headshot image (e.g., my-portrait.jpg).
            Setup and Usage
            Create a Folder: Create a new directory for your project (e.g., ProfessionalCard).
            Save Files: Place the provided HTML and CSS code into this folder:
            Save the HTML code as index.html.
            Save the CSS code as style.css.
            Add Image: Place your headshot image into the same folder.
            Update HTML (Crucial): Open index.html and change the image source path in the <img /> tag to match your file                 name:
                    <img src="your-photo.jpg" alt="Profile Portrait" class="profile-img">
            View: Double-click index.html. It will open the business card in your default web browser.
 🎨 Customization
            The design is highly flexible. All visual styles are controlled within the style.css file.
            Element to Change	CSS Selector	Key Properties
            Card Background	.card	background: linear-gradient(...)
            Name/Title Font	.name, .title	font-family, font-size, letter-spacing
            Contact Colors	.contact-info p	color (for text), opacity
            Hover Depth	.card:hover	transform: translateY(...), box-shadow
            Blurred Shapes	.shape-1, .shape-2	background, filter: blur(), width, height
        
