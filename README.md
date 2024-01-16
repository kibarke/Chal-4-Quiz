# Chal-4-Quiz
I am building a quiz that is timed and has multiple choices.

<!DOCTYPE html>
<html lang="en"> 

    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Challenge Four - Quiz</title>
        <link rel="stylesheet" href="assets/css/style.css">
    </head>

    <body>

        <main class="main">
            <header class="header">
                <a href="#" class="logo">Quiz.</a>

                <nav class="navbar">
                    <a href="#" class="active">Home</a>
                    <a href="#">About</a>
                    <a href="#">Services</a>
                    <a href="#">Contact</a>
                </nav>
            </header>

            <div class="container">
                <section class="quiz-section">
                    <div class="quiz-box">
                        <h1>Kirsten's Quiz</h1>
                        <div class="quiz-header">
                            <span>Quiz Website Challenge 4</span>
                            <span class="header-score">Score: 0/5</span>
                        </div>

                        <h2 class="question-test">Quiz Question One: How plays Iron-Man?</h2>

                        <div class="option-list">
                            <div class="option">
                                <span>A. Tom Hiddlestone</span>
                            </div>
                            <div class="option">
                                <span>Chris Hemsworth</span>
                            </div>
                            <div class="option">
                                <span>Robert Downey Junior</span>
                            </div>
                            <div class="option">
                                <span>Chris Evans</span>
                            </div>
                        </div>
                        <div class="quiz-footer">
                            <span class="question-total">1 of 5 Questions</span>
                            <button class="next-btn">Next</button>
                        </div>
                    </div>
                </section>

                <section class="home">
                    <div class="home-content">
                        <h1>Quiz Website</h1>
                        <p>Are you excited?</p>
                        <button class="start-btn">Start Quiz</button>
                    </div>
                </section>
            </div>
        </main>

        <div class="popup-info">
            <h2>Quiz Guide</h2>
            <span class="info">1. This is a practice of me learning JavaScript.</span>
            <span class="info">2. Random questions are thrown in the mix.</span>
            <span class="info">3. It's okay if you get them wrong.</span>
            <span class="info">4. It's not real.</span>
            <span class="info">5. Have fun.</span>

            <div class="btn-group">
                <button class="info-btn exit-btn">Exit Quiz</button>
                <a href="#" class="info-btn continue-btn">Continue</a>
            </div>
        </div>  
        
        
        <script src="assets/js/questions.js"></script>
        <script src="assets/js/script.js"></script>
    </body>

</html>