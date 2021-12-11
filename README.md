<!DOCTYPE html>
<html lang="en">

<head>
    <title>Test personalitate</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Rubik:wght@300&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>

<body>
    <div class="quiz-container">
        <img src="student-gfd4e668d8_1280.png" width="150" height="200">
        <div class="title">Test de personalitate</div>
        <div id="question" class="question"></div>
        <label class="option">
            <input type="radio" name="option" value="1" />
            <span class="option1"></span>
        </label>
        <label class="option">
            <input type="radio" name="option" value="2" />
            <span class="option2"></span>
        </label>
        <label class="option">
            <input type="radio" name="option" value="3" />
            <span class="option3"></span>
        </label>
        <!-- Butoane-->
        <div class="controls">
            <button class="previous">Întrebarea anterioară</button>
            <button class="next">Întrebarea următoare</button>
        </div>
    </div>

    <div class="result">

    </div>

    <script src=questions.js></script>
    <script src="quizpersonalitate.js"></script>
</body>

</html>
