<script>
  import tofuLogo from './assets/tofu.svg';

  const githubLink = 'https://github.com/TofuBeans';
  const youtubeLink = 'https://www.youtube.com/channel/UCNpiujwbIPCeUxI9TYEzUaw';
  const tiktokLink = 'https://www.tiktok.com/@tofu_beans';
  const twitterLink = 'https://twitter.com/TofuTheNPC';

</script>

<main>
  <div class="noselect">
    <a href={githubLink} target="_blank" rel="noreferrer"> 
      <img src={tofuLogo} class="logo tofu" alt="Tofu_Beans Logo" />
    </a>
    <h1>Tofu_Beans</h1>
    <h2>Programmer, developer, unlovable goofball</h2>
  
    <p class="read-the-docs">
      Click on the logo to visit <a href={githubLink}>my GitHub</a>
    </p>
  </div>

  <div class="noselect">
    <a href={youtubeLink}>
      <button class="card">
        <img src="src/assets/youtube.svg" />
      </button>
    </a>
    <a href={tiktokLink}>
      <button class="card">
        <img src="src/assets/tiktok.svg" />
      </button>
    </a>
    <a href={twitterLink}>
      <button class="card">
        <img src="src/assets/twitter.svg" />
      </button>
    </a>
    
  </div>
    
</main>

<style>
  .logo {
    height: 6em;
    padding: 1.5em;
    will-change: filter;
    transition: filter .4s ease-in;
    transition: filter .25s ease-out;
  }
  .logo:hover {
    filter: drop-shadow(0 0 2em #646cffaa);
  }
  .logo.tofu:hover {
    filter: drop-shadow(0 0 2em #ff3e00aa);
  }
  .read-the-docs {
    color: #888;
  }
</style>
