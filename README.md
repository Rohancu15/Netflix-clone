📺 Netflix Clone

A Netflix landing page clone built using HTML, CSS, and JavaScript.
This project recreates the UI of Netflix including the hero section, trending movie slider, feature cards, FAQ section, and footer.

The goal of this project is to practice frontend development, layout design, and UI cloning.

🚀 Live Demo

(Add your GitHub Pages link here after deploying)

https://rohancu15.github.io/Netflix-clone
🖼️ Project Preview

Add a screenshot of your project here.

Example:

assets/images/preview.png
✨ Features

🎬 Netflix-style Trending Movies Slider

🔢 Ranking numbers for trending movies

🖱️ Hover animations on movie posters

🎯 Smooth slider navigation (5 movies at a time)

📱 Responsive layout

🎨 Feature cards section

❓ FAQ section

📩 Email signup section

🧾 Netflix-style footer

🎨 Gradient UI design

🛠️ Technologies Used

HTML5

CSS3

JavaScript

Google Fonts

📂 Project Structure
Netflix-clone
│
├── index.html
├── style.css
├── README.md
│
└── assets
    ├── images
    │   ├── bg.jpg
    │   ├── logo.svg
    │
    └── icons
        ├── tv.svg
        ├── download.svg
        ├── watch.svg
        └── kids.svg
🎮 Slider Functionality

The trending movies section uses JavaScript horizontal scrolling.

Each arrow button scrolls 5 movie cards at a time.

function scrollMovies(direction){

const slider = document.getElementById("movieSlider")

const cardWidth = document.querySelector(".card").offsetWidth + 20

slider.scrollBy({
left: direction * cardWidth * 5,
behavior: "smooth"
})

}
📦 Installation

Clone the repository:

git clone https://github.com/Rohancu15/Netflix-clone.git

Open the project folder:

cd Netflix-clone

Run the project by opening:

index.html

in your browser.

📱 Responsive Design

The layout is built using Flexbox and Grid, making it adaptable for:

Desktop

Tablet

Mobile

📚 What I Learned

Through this project I practiced:

Creating modern UI layouts with Flexbox

Building interactive components using JavaScript

Implementing movie sliders

Structuring frontend projects properly

Improving CSS styling and layout skills

🔮 Future Improvements

FAQ dropdown animation

Mobile responsive slider

Poster expansion animation like Netflix

Deploy using GitHub Pages

👨‍💻 Author

Rohan

GitHub:
https://github.com/Rohancu15