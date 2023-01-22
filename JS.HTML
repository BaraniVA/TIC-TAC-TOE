const squares = document.querySelectorAll('.square');
let currentPlayer = 'X';
let winner = null;
let roundCount = 0;
const resetButton = document.querySelector("#reset-button");

// Winning combinations
const winningCombinations = [
  [0, 1, 2],
  [3, 4, 5],
  [6, 7, 8],
  [0, 3, 6],
  [1, 4, 7],
  [2, 5, 8],
  [0, 4, 8],
  [2, 4, 6],
];

for (const square of squares) {
  square.addEventListener('click', function(event) {
    event.target.textContent = currentPlayer;
    roundCount++;

    if (checkForWinner() === true) {
        alert(`Player ${winner} wins!`);
        reset();
    } else if (roundCount === 9) {
        alert("It's a tie!");
        reset();
    } else {
        if (currentPlayer === 'X') {
            currentPlayer = 'O';
        } else {
            currentPlayer = 'X';
        }
    }
  });
}

resetButton.addEventListener("click", function() {
    reset();
});

function checkForWinner() {
    for (const combination of winningCombinations) {
        const [a, b, c] = combination;
        if (squares[a].textContent === currentPlayer && squares[b].textContent === currentPlayer && squares[c].textContent === currentPlayer) {
            winner = currentPlayer;
            return true;
        }
    }
    return false;
}

function reset() {
    for (const square of squares) {
        square.textContent = "";
    }
    winner = null;
    roundCount = 0;
    currentPlayer = 'X';
}
