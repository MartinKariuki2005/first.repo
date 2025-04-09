<!DOCTYPE html>
<html>
  <head>
<title>Rock Paper Scissors</title>
<link rel="stylesheet" href="styles/10-rock-paper-scissors.css">
   
  </head>
  <body>

    <p class="title"><h1>Rock Paper Scissors</h1> </p>


    <button onclick="
     playGame('rock');
     " class="move-button"
     ><img src="images/rock-emoji.png" class="move-icon"></button>
    
    
    <button onclick="
     playGame('paper');
    " class="move-button"><img src="images/paper-emoji.png" class="move-icon"></button>

    
    <button onclick="
      playGame('scissors');
     " class="move-button"><img src="images/scissors-emoji.png" class="move-icon"></button>

     <p class="js-result"></p>
     <p class="js-moves"></p>
    <p class="js-score"></p>
    

     <button onclick="
     score.wins = 0;
     score.losses = 0;
     score.ties = 0;
     localStorage.removeItem('score')
    updateScoreElement();
     " class="reset-score-button">
      Reset Score</button>
      <button class="auto-play-button" onclick="
      autoplay();
      ">Autoplay</button>

      <p>&#169;</p>
      

      <script></script>
