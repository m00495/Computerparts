# Computerparts
https://m00495.github.io/Computerparts/cp

/* General Reset */
body {
    margin: 0;
    padding: 0;
    font-family: 'Roboto', Arial, sans-serif;
    line-height: 1.8;
    background-color: #f9f9f9;
    color: #333;
}

/* Header Styling */
header {
    background-color: #3a7c5f;
    color: #fff;
    text-align: center;
    padding: 20px 0;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

header h1 {
    font-size: 2.5rem;
    margin: 0;
}

/* Main Content Styling */
main {
    max-width: 1200px;
    margin: 40px auto;
    padding: 20px;
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
}

/* Section Styling */
section {
    margin-bottom: 40px;
}

section h2 {
    font-size: 1.8rem;
    color: #3a7c5f;
    border-bottom: 3px solid #4caf50;
    display: inline-block;
    margin-bottom: 20px;
    padding-bottom: 5px;
}

p {
    font-size: 1rem;
    margin: 20px 0;
}

/* List Styling */
ul {
    list-style: none;
    padding: 0;
    margin: 20px 0;
}

li {
    margin: 10px 0;
    padding: 10px 15px;
    background-color: #f3f3f3;
    border-left: 5px solid #4caf50;
    border-radius: 4px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    font-size: 1rem;
}

/* Image Styling */
figure {
    margin: 20px 0;
    text-align: center;
}

img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    box-shadow: 0 2px 6px rgba(0, 0, 0, 0.2);
}

figcaption {
    font-size: 0.9rem;
    color: #666;
    margin-top: 10px;
}

/* Link Styling */
a {
    color: #3a7c5f;
    text-decoration: none;
    transition: color 0.3s ease;
}

a:hover {
    color: #4caf50;
    text-decoration: underline;
}

/* Footer Styling */
footer {
    background-color: #222;
    color: #ddd;
    text-align: center;
    padding: 15px 0;
    font-size: 0.9rem;
    border-top: 3px solid #3a7c5f;
}

/* Responsive Design */
@media (max-width: 768px) {
    header h1 {
        font-size: 2rem;
    }

    main {
        margin: 20px;
        padding: 15px;
    }

    section h2 {
        font-size: 1.5rem;
    }
}
