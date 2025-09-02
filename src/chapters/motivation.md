<div class="collapsible" style="display: inline-flex; align-items: center; justify-content: left; border-radius: 5px; padding: 0px 15px; margin-bottom: 10px; background-color: #ffffffff; color: black;">

  <div style="margin-right: 15px;">
    <b>This is an archived site </b> of <a href="https://luminespire.github.io/dusk/">Dusk</a> by <a href="https://github.com/Aorta3698">Zoe Winters</a> and is no longer maintained. <a href="https://github.com/luminespire/dusk/blob/main/README.md">Learn more here</a>.
  </div>

  <span class="close" style="cursor: pointer; font-size: 24px; font-weight: bold; position: relative;">&times;</span>

</div>

<script>
  const closeButtons = document.querySelectorAll('.close');
  closeButtons.forEach(button => {
    button.addEventListener('click', (event) => {
      let collapsible = event.target.closest('.collapsible');
      if (collapsible) {
        collapsible.style.display = 'none';
      }
    });
  });
</script>


# Motivation

As a [Canary-ortho](https://github.com/Apsu/Canary) user for 14 months and reached about 140 wpm on MonkeyType, its flaws - high SFS and high index workload - start to bother me. 

```
--- Canary Ortho ---

w l y p b  z f o u '
c r s t g  m n e i a
q j v d k  x h / , .  
```


In particular, I don't vibe with:
- `B_D` and all the `K` interaction with `B__K` (`back`) leading to 2u SFS.

- That feeling that left index is flying all over the place at high speed.

- High SFS (compared to modern layouts).

- `LV`, `SYS`, `RL`, `WR`, `CL`.

Don't get me wrong - `Canary-ortho` is a decent layout - but I just hope for something better. I decided to try other modern layouts such as `Graphite`, `Gallium`, `Kuntum`, `Stronk`, and several others, but none of it speaks to me the way that `Canary` does.

Additionally, my keyboard `Piantor Pro` (shown below) is a split columnar keyboard with an aggressive pinky stagger and 3 thumb keys on each side, and most popular keyboard layouts were designed for conventional rowstag keyboards.

Eventually, after making several different layouts and not finding the one, I realized what I am looking for may not be possible without having a letter on the thumb key. I started to expriment with thumb `Y`, `I`, `S`, and finally landing on thumb `R`: `Dusk`.

![](../assets/piantor.png)

