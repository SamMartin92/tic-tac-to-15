
https://www.youtube.com/watch?v=B3pmT7Cpi24&ab_channel=JavaScriptAcademy

https://www.color-hex.com/color-palette/1007780


need to implement the game logic


bug:
 for (let i = 0; i < tiles.length; i++) {
    if (tiles[i].textContent == '') {
      availableMoves.push(tiles[i]);
    }/*https://codepen.io/lando464/pen/BPGEKO*/

    let randomMove= Math.floor(Math.random()*availableMoves.length);
    let computerMove=availableMoves[randomMove];
    computerMove.innerText=tileValue;

  }

  this is putting the tileValue in a random number of tiles rather than a random tile
  <img href='assets/images/testing_and_bugs/multiple-tiles-1.png'>
   <img src ='assets/images/testing_and_bugs/multiple-tiles-2.png'>generateRandomInteger(min, max)


   a bug:
   userAction can be called twice before computerAction timeout is over:
   could maybe put a faceade over board


   acknowledge Ed in tutor support


   modal https://www.youtube.com/watch?v=XH5OW46yO8I


   bunnys https://pixabay.com/illustrations/rabbit-easter-pastel-bunny-hare-4120085/