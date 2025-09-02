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


# Layout
<!-- toc -->
## Dusk
- On my keyboard Piantor, `R` is slightly to the right of what's shown here.
- This variant with `,.` and `r<spc>` swaps is what I personally use.
- To read my 6 weeks experience, read [here](../journeys/2024_Jun_5.md).

![](../assets/dusk.svg)


### ACSII
```
x f d p q  j ' o u .
n s t c y  m h a e i
b v k g w  z l _ / ,
        r   
```

## Dusk-vq
It's made to address concern over `V`.

This variant has similar stats but with even lower scissor at the expense of having left index do more work and higher 2u SFS from `g_v`.

- The higher 2u SFS can further be addressed by swapping `PG`, but `NG` and `G_T` become slightly worse.

- Or you can swap `WV`, but make sure you are okay with typing `know`.

![](../assets/dusk-alt.svg)

### ACSII
```
x f d p v  j ' o u .
n s t c y  m h a e i
b q k g w  z l _ / ,
        r                  
```

## Variants in Cmini bots
For the curious: In `Cmini` discord bots, you can find dusk variants created by me and other people with `!cmini filter --name dusk`.
