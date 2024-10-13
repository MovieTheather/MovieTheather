<div id="fullscreen-container" style="position: relative; padding: 70% 0;">
  <iframe id="my-iframe" style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;" src="https://ww16.0123movie.net/movie/godzilla-x-kong-the-new-empire-1630856838.html" frameborder="0" allowfullscreen="true"></iframe>
</div>

<script>
  const fullscreenContainer = document.getElementById("fullscreen-container");
  const iframe = document.getElementById("my-iframe");

  // Function to trigger fullscreen mode
  function makeFullScreen() {
    if (fullscreenContainer.requestFullscreen) {
      fullscreenContainer.requestFullscreen();
    } else if (fullscreenContainer.webkitRequestFullscreen) {
      fullscreenContainer.webkitRequestFullscreen();
    } else if (fullscreenContainer.msRequestFullscreen) {
      fullscreenContainer.msRequestFullscreen();
    }
  }

  // Call the function when the iframe is clicked
  iframe.addEventListener("click", makeFullScreen);
</script>

<!--
**MovieTheather/MovieTheather** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
