<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Comprehensive CSS Guide</title>
   <style>

/* Basic Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  /* General Body Styling */
  body {
    font-family: Arial, sans-serif; /* Default font family */
    line-height: 1.6; /* Default line height */
    padding: 60px; /* Ensure content is below the fixed header */
  }
  
  /* Header Section */
  header {
    background: #645a5a; /* Dark background color */
    color: #fff; /* White text color */
    padding: 1rem 0; /* Vertical padding */
    position:fixed; /* Fix the header at the top */
    width: 100%; /* Full width */
    top: 0; /* Align to top */
  }
  
  nav ul {
    display: flex; /* Flexbox for horizontal layout */
    justify-content: center; /* Center the items */
    list-style: none; /* Remove default list styling */
  }
  
  nav a {
    color: #fff; /* White text color */
    padding: 0.5rem 1rem; /* Padding for links */
    text-decoration:dotted; /* Remove underline */
  }
  
  nav a:hover {
      background: #e80606; /* Darker background on hover */
    font-family: Verdana, Geneva, Tahoma, sans-serif;
  }
  
  /* Hero Section */
  #hero {
    background: #f4f4f4; /* Light grey background */
    padding: 5rem 1rem; /* Padding */
    text-align: center; /* Center text */
  }
  
  #hero h1 {
    font-size: 2.5rem; /* Large font size */
  }
  
  /* Basic Styling Section */
  #basic-styling {
    padding: 2rem; /* Padding */
    background: #db1a1a; /* White background */
  }
  
  .basic-styling-examples .text-color {
    color: #3498db; /* Blue text color */
  }
  
  .basic-styling-examples .text-alignment {
    justify-content: end;
    justify-items: flex-start;
    text-align:right; /* Center text alignment */
  }
  
  .basic-styling-examples .text-font {
    font-family: "Courier New", Courier, monospace; /* Different font family */
  }
  
  /* Layouts Section */
  #layouts {
    padding: 2rem; /* Padding */
    background: #f4f4f4; /* Light grey background */
  }
  
  .flexbox-container {
    display: flex; /* Flexbox layout */
    justify-content: space-around; /* Space between items */
    margin-bottom: 2rem; /* Bottom margin */
   }
  
  .flexbox-item {
    background: #3498db; /* Blue background */
    color: #fff; /* White text */
    padding: 1rem; /* Padding */
    width: 50%; /* Width */
    text-align: center; /* Center text */
  }
  
  .grid-container {
    display: grid; /* Grid layout */
    grid-template-columns: repeat(2, 1fr); /* Two columns */
    gap: 1rem; /* Gap between items */
  }
  
  .grid-item {
    background: #2ecc71; /* Green background */
    color: #fff; /* White text */
    padding: 1rem; /* Padding */
    text-align: center; /* Center text */
  }
  
  /* Positioning Section */
  #positioning {
    padding: 2rem; /* Padding */
    background: #fff; /* White background */
  }
  
  .positioning-container {
    position: relative; /* Relative positioning */
    height: 300px; /* Fixed height */
    border: 1px solid #ddd; /* Border */
    margin-bottom: 2rem; /* Bottom margin */
  }
  
  .relative-box {
    position: relative; /* Relative positioning */
    top: 20px; /* Top offset */
    left: 20px; /* Left offset */
    background: #3498db; /* Blue background */
    color: #fff; /* White text */
    padding: 1rem; /* Padding */
  }
  
  .absolute-box {
    position: absolute; /* Absolute positioning */
    top: 20px; /* Top offset */
    right: 20px; /* Right offset */
    background: #e74c3c; /* Red background */
    color: #fff; /* White text */
    padding: 1rem; /* Padding */
  }
  
  .fixed-box {
    position: fixed; /* Fixed positioning */
    bottom: 20px; /* Bottom offset */
    left: 20px; /* Left offset */
    background: #f1c40f; /* Yellow background */
    color: #fff; /* White text */
    padding: 1rem; /* Padding */
  }
  
  .sticky-box {
     position:-webkit-sticky; /* Sticky positioning */
    top: 0; /* Top offset */
    background: #9b59b6; /* Purple background */
    color: #fff; /* White text */
    padding: 1rem; /* Padding */
  }
  
  /* Backgrounds Section */
  #backgrounds {
    padding: 2rem; /* Padding */
    background: #f4f4f4; /* Light grey background */
  }
  
  .background-image {
    background: url("https://assets.ccbp.in/frontend/intermediate-rwd/tajmahal-img.png")
      no-repeat center center/cover; /* Background image with cover */
    height: 200px; /* Fixed height */
    margin-bottom: 2rem; /* Bottom margin */
    background-size: cover;
  }
  
  .background-gradient {
    background: linear-gradient(
      to right,
      #3498db,
      #2ecc71
    ); /* Linear gradient background */
    height: 200px; /* Fixed height */
  }
  .radial-gradient-component {
    width: 300px;
    height: 300px;
    display: flex;
    align-items: center;
    justify-content: center;
    color: white;
    font-size: 20px;
    text-align: center;
    background: radial-gradient(circle, #ff7e5f, #2318ed);
    border-radius: 10px;
  }
  
  /* Borders Section */
  #borders {
    padding: 2rem; /* Padding */
    background: #fff; /* White background */
  }
  
  .borders-container div {
    margin-bottom: 1rem; /* Bottom margin */
    padding: 1rem; /* Padding */
    text-align: center; /* Center text */
  }
  
  .border-solid {
    border: 2px solid #3498db; /* Solid border */
  }
  
  .border-dashed {
    border: 2px dashed #e74c3c; /* Dashed border */
  }
  
  .border-dotted {
    border: 2px dotted #f1c40f; /* Dotted border */
  }
  
  .border-radius {
    border: 2px solid #9b59b6; /* Solid border */
    border-radius: 10px; /* Rounded corners */
  }
  
  /* Box Model Section */
  #box-model {
    padding: 2rem; /* Padding */
    background: #f4f4f4; /* Light grey background */
  }
  
  .box-model-container div {
    margin-bottom: 1rem; /* Bottom margin */
    padding: 1rem; /* Padding */
    text-align: center; /* Center text */
  }
  
  .box-padding {
    background: #3498db; /* Blue background */
    color: #fff; /* White text */
    padding: 20px; /* Padding */
  }
  
  .box-margin {
    background: #e74c3c; /* Red background */
    color: #fff; /* White text */
    margin: 20px; /* Margin */
  }
  
  .box-border {
    background: #f1c40f; /* Yellow background */
    color: #fff; /* White text */
    border: 5px solid #fff; /* Border */
  }
  
  .box-content {
    background: #2ecc71; /* Green background */
    color: #fff; /* White text */
    content: "Box with content"; /* Content */
  }
  
  /* Transitions and Animations Section */
  #transitions {
    padding: 2rem; /* Padding */
    background: #fff; /* White background */
  }
  
  .transition-box {
    background: #3498db; /* Blue background */
    color: #fff; /* White text */
    padding: 1rem; /* Padding */
    text-align: center; /* Center text */
    transition: background 0.3s ease; /* Background transition */
  }
  
  .transition-box:hover {
    background: #2ecc71; /* Green background on hover */
  }
  
  @keyframes example-animation {
    0% {
      background: #e74c3c; /* Red background */
      transform: translateX(0); /* No translation */
    }
    50% {
      background: #f1c40f; /* Yellow background */
      transform: translateX(50px); /* Translate 50px to the right */
    }
    100% {
      background: #3498db; /* Blue background */
      transform: translateX(0); /* No translation */
    }
  }
  
  .animation-box {
    background: #e74c3c; /* Red background */
    color: #fff; /* White text */
    padding: 1rem; /* Padding */
    text-align: center; /* Center text */
    animation: example-animation 3s infinite; /* Animation */
  }
  
  /* Typography Section */
  #typography {
    padding: 2rem; /* Padding */
    background: #f4f4f4; /* Light grey background */
  }
  
  .typography-container p {
    margin-bottom: 1rem; /* Bottom margin */
    padding: 1rem; /* Padding */
    text-align: center; /* Center text */
  }
  
  .font-family {
    font-family: "Courier New", Courier, monospace; /* Different font family */
  }
  
  .font-size {
    font-size: 1.5rem; /* Different font size */
  }
  
  .font-weight {
    font-weight: bold; /* Bold font weight */
  }
  
  .line-height {
    line-height: 2; /* Different line height */
  }
  
  .letter-spacing {
    letter-spacing: 2px; /* Different letter spacing */
  }
  
  /* Display Section */
  #display {
    padding: 2rem; /* Padding */
    background: #fff; /* White background */
  }
  
  .display-container div {
    margin-bottom: 1rem; /* Bottom margin */
    padding: 1rem; /* Padding */
    text-align: center; /* Center text */
  }
  
  .display-block {
    display: block; /* Block display */
    background: #3498db; /* Blue background */
    color: #fff; /* White text */
  }
  
  .display-inline {
    display: inline; /* Inline display */
    background: #e74c3c; /* Red background */
    color: #fff; /* White text */
  }
  
  .display-flex {
    display: flex; /* Flex display */
    justify-content: center; /* Center items */
    background: #2ecc71; /* Green background */
    color: #fff; /* White text */
  }
  
  .display-grid {
    display: grid; /* Grid display */
    place-items: center; /* Center items */
    background: #f1c40f; /* Yellow background */
    color: #fff; /* White text */
  }
  
  .display-none {
    display: none; /* None display */
  }
  
  /* Footer */
  footer {
    background: #333; /* Dark background */
    color: #fff; /* White text */
    text-align: center; /* Center text */
    padding: 1rem 0; /* Vertical padding */
  }
   </style>
  </head>
  <body>
    <header>
      <nav>
        <ul>
          <li><a href="#hero">Home</a></li>
          <li><a href="#basic-styling">Basic Styling</a></li>
          <li><a href="#layouts">Layouts</a></li>
          <li><a href="#positioning">Positioning</a></li>
          <li><a href="#backgrounds">Backgrounds</a></li>
          <li><a href="#borders">Borders</a></li>
          <li><a href="#box-model">Box Model</a></li>
          <li><a href="#transitions">Transitions</a></li>
          <li><a href="#typography">Typography</a></li>
          <li><a href="#display">Display</a></li>
        </ul>
      </nav>
    </header>

    <section id="hero">
      <h1>Welcome to the Comprehensive CSS Guide</h1>
      <p>Explore various CSS properties and their values</p>
    </section>

    <section id="basic-styling">
      <h2>Basic Styling</h2>
      <div class="basic-styling-examples">
        <p class="text-color">This text has a different color.</p>
        <p class="text-alignment">This text is centered.</p>
        <p class="text-font">This text uses a different font family.</p>
      </div>
    </section>

    <section id="layouts">
      <h2>Layouts</h2>
      <div class="flexbox-container">
        <div class="flexbox-item">Flexbox Item 1</div>
        <div class="flexbox-item">Flexbox Item 2</div>
        <div class="flexbox-item">Flexbox Item 3</div>
      </div>
      <div class="grid-container">
        <div class="grid-item">Grid Item 1</div>
        <div class="grid-item">Grid Item 2</div>
        <div class="grid-item">Grid Item 3</div>
        <div class="grid-item">Grid Item 4</div>
      </div>
    </section>

    <section id="positioning">
      <h2>Positioning</h2>
      <div class="positioning-container">
        <div class="relative-box">Relative Box</div>
        <div class="absolute-box">Absolute Box</div>
        <div class="fixed-box">Fixed Box</div>
        <div class="sticky-box">Sticky Box</div>
      </div>
    </section>

    <section id="backgrounds">
      <h2>Backgrounds</h2>
      <div class="backgrounds-container">
        <div class="background-image">Background Image</div>
        <div class="background-gradient">Background Gradient</div>
        <div class="radial-gradient-component">Radial Gradient Example</div>
      </div>
    </section>

    <section id="borders">
      <h2>Borders</h2>
      <div class="borders-container">
        <div class="border-solid">Solid Border</div>
        <div class="border-dashed">Dashed Border</div>
        <div class="border-dotted">Dotted Border</div>
        <div class="border-radius">Rounded Border</div>
      </div>
    </section>

    <section id="box-model">
      <h2>Box Model</h2>
      <div class="box-model-container">
        <div class="box-padding">Box with Padding</div>
        <div class="box-margin">Box with Margin</div>
        <div class="box-border">Box with Border</div>
        <div class="box-content">Box with Content</div>
      </div>
    </section>

    <section id="transitions">
      <h2>Transitions and Animations</h2>
      <div class="transitions-container">
        <div class="transition-box">Hover me for transition</div>
        <div class="animation-box">Animation Example</div>
      </div>
    </section>

    <section id="typography">
      <h2>Typography</h2>
      <div class="typography-container">
        <p class="font-family">This text uses a different font family.</p>
        <p class="font-size">This text has a different font size.</p>
        <p class="font-weight">This text has a different font weight.</p>
        <p class="line-height">This text has a different line height.</p>
        <p class="letter-spacing">This text has different letter spacing.</p>
      </div>
    </section>

    <section id="display">
      <h2>Display</h2>
      <div class="display-container">
        <div class="display-block">Display Block</div>
        <div class="display-inline">Display Inline</div>
        <div class="display-flex">Display Flex</div>
        <div class="display-grid">Display Grid</div>
        <div class="display-none">Display None</div>
      </div>
    </section>

    <footer>
      <p>&copy; 2024 CSS Guide. All rights reserved.</p>
    </footer>
  </body>
</html>