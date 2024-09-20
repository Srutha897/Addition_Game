# Addition_Game
Created addition game using HTML CSS and JS
<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>

<body>
    <div class="text-center">
        <img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-dynamic-webapps/sum-of-two-numbers-img.png" class="image" />
        <div class="bg-container pt-5 pb-5">
            <span class="number m-2" id="firstNumber"></span>
            <span class="operator m-1">+</span>
            <span class="number m-2" id="secondNumber"></span>
            <span class="operator m-1">=</span>
            <input class="user-input" type="text" id="userInput" />
            <div class="mt-4 mb-4">
                <button id="checkButton" class="btn btn-primary mr-3" onclick="checkResult()">
                    Check
                </button>
                <button id="restartButton" class="btn btn-primary" onclick="restart()">
                    Restart
                </button>
            </div>
            <p class="game-result" id="gameResult"></p>
        </div>
    </div>
</body>

</html>
