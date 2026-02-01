# const noBtn = document.getElementById("noBtn");

noBtn.addEventListener("mouseover", () => {
  const x = Math.random() * 200 - 100;
  const y = Math.random() * 200 - 100;

  noBtn.style.transform = `translate(${x}px, ${y}px)`;
});

function yes() {
  document.getElementById("card").innerHTML = `
    <h2>YAY!! 🎉💖</h2>
    <p>You just made my day 😍</p>
    <img src="https://media.giphy.com/media/l0MYt5jPR6QX5pnqM/giphy.gif" width="200">
  `;
}