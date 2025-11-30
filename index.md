<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>English Scroll</title>

<!-- Calligraphy Font -->
<link href="https://fonts.googleapis.com/css2?family=Great+Vibes&display=swap" rel="stylesheet">

<style>
    /* Body background: subtle parchment */
    body {
        margin: 0;
        padding: 0;
        background: #f2e6c9 url('https://i.imgur.com/5rK9tUu.jpg') repeat; /* subtle parchment texture */
        font-family: Georgia, serif;
        display: flex;
        justify-content: center;
        padding: 50px 0;
    }

    /* The main scroll */
    .scroll {
        background: #fff8e7;
        border: 5px solid #b58b4c;
        border-radius: 20px;
        width: 80%;
        max-width: 1200px;
        padding: 40px 60px;
        box-shadow: 0px 8px 20px rgba(0,0,0,0.3);
        position: relative;
    }

    /* Top scroll decoration */
    .scroll::before {
        content: "";
        position: absolute;
        top: -40px;
        left: 50%;
        transform: translateX(-50%);
        width: 120px;
        height: 40px;
        background: url('https://i.imgur.com/LrFZbCo.png') no-repeat center;
        background-size: contain;
    }

    /* Bottom scroll decoration */
    .scroll::after {
        content: "";
        position: absolute;
        bottom: -40px;
        left: 50%;
        transform: translateX(-50%);
        width: 120px;
        height: 40px;
        background: url('https://i.imgur.com/LrFZbCo.png') no-repeat center;
        background-size: contain;
        transform: translateX(-50%) rotate(180deg);
    }

    /* Scroll banner */
    .scroll-banner {
        text-align: center;
        padding: 30px 0;
        margin-bottom: 30px;
        background: url('https://www.pngall.com/wp-content/uploads/2016/07/Scroll-PNG-Clipart.png') no-repeat center;
        background-size: contain;
    }

    .scroll-banner h1 {
        font-family: 'Great Vibes', cursive;
        font-size: 90px;
        color: #4b2e0f;
        margin: 0;
        letter-spacing: 3px;
        text-shadow: 3px 3px 6px #e8d7b4;
        animation: shimmer 3s infinite alternate;
    }

    @keyframes shimmer {
        0% { color: #4b2e0f; text-shadow: 3px 3px 6px #e8d7b4; }
        50% { color: #5a3a12; text-shadow: 3px 3px 10px #f5e0b7; }
        100% { color: #4b2e0f; text-shadow: 3px 3px 6px #e8d7b4; }
    }

    h2 {
        text-align: center;
        color: #4b2e0f;
        font-size: 32px;
        margin-top: 0;
    }

    p {
        font-size: 18px;
        line-height: 1.7;
    }

    ul {
        font-size: 18px;
        line-height: 1.7;
        padding-left: 20px;
    }

    a {
        color: #7a4a1f;
        text-decoration: none;
        font-weight: bold;
    }

    a:hover {
        text-decoration: underline;
    }

    @media (max-width: 768px) {
        .scroll {
            width: 90%;
            padding: 20px 30px;
        }

        .scroll-banner h1 {
            font-size: 60px;
        }
    }
</style>
</head>
<body>

<div class="scroll">
    <div class="scroll-banner">
        <h1>English Scroll</h1>
    </div>

    <h2>English Grammar for College Students</h2>

    <p>Welcome! This site provides clear explanations and helpful links to master English grammar at the college level.</p>

    <p>Use the links below to navigate the main topics:</p>

    <ul>
        <li><a href="parts-of-speech.md">Parts of Speech</a></li>
        <li><a href="sentence-structure.md">Sentence Structure</a></li>
        <li><a href="punctuation.md">Punctuation</a></li>
        <li><a href="academic-grammar.md">Academic Grammar</a></li>
        <li><a href="common-errors.md">Common Errors</a></li>
        <li><a href="practice.md">Practice Exercises</a></li>
        <li><a href="readings.md">Readings</a></li>
    </ul>
</div>

</body>
</html>
