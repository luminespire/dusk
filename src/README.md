<div class="collapsible" style="display: inline-flex; align-items: center; justify-content: left; border-radius: 5px; padding: 0px 15px; margin-bottom: 10px; background-color: #ffffffff; color: black;">

  <div style="margin-right: 15px;">
    <b>This is an archived site </b> of <a href="https://luminespire.github.io/dusk/">Dusk</a> by <a href="https://github.com/Aorta3698">Zoe Winters</a> and is no longer maintained. <a href="https://github.com/luminespire/dusk/blob/main/README.md">Learn more here</a>.
  </div>

  <span class="close" style="cursor: pointer; font-size: 24px; font-weight: bold; position: relative;">&times;</span>

</div>

<script>
  const banner = document.querySelector('.collapsible');
  const closeButton = banner.querySelector('.close');

  if (localStorage.getItem('bannerClosed') === 'true') {
    banner.style.display = 'none';
  }

  closeButton.addEventListener('click', (event) => {
    banner.style.display = 'none';
    localStorage.setItem('bannerClosed', 'true');
  });
</script>

# Introduction

- Site last updated on 06/05/2024

`Dusk`, created on 04/14/2024, is a well-balanced keyboard layout for columnar keyboard with thumb keys.

The most impressive feat that `Dusk` achieves is that it is remarkably low in (per oxeylyzer, keysolve, cyanophage)
- SFS ` ~4.90%`
- SFB ` ~0.50%`
- 2u SFS `~0.10%`
- Finger speed `~17.33`
- Both full and half scissors and skipgram scissors `0.02%/0.11%/2.09%/4.68%`

while maintaining a reasonable redirection and LSB. As such, `Dusk` is consistent and a good general-purpose thumb layout.

### My Review
- [Six Weeks In](journeys/2024_Jun_5.md)

### Github
You can star this repo by clicking on the Github icon located on the top right corner <3

### Side Note
No idea what LSB, SFS, or SFB means? Check out [terminology](chapters/term.md)!

### Site Navigation
- Click on the hamburger menu located on the top left to access Table of Contents.

- Click on the brush icon located on the top left to change sitewide theme.

- On Desktop, there is a table of contents on the right side for each chapter that has more than 1 section.

- Go to the next/previous chapter by clicking on the `>` and `<` icon located on each side of the screen, respectively.

