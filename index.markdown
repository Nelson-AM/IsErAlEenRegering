---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Nee

<div id="ontslagCounter"></div>
<div id=verkiezingenCounter></div>

<script type="text/javascript">
const today = new Date();
const ontslagdatum = new Date("January 15, 2021");
const tijdSindsOntslag = Math.abs(ontslagdatum - today);
const dagenSindsOntslag = Math.ceil(tijdSindsOntslag / (1000*60*60*24));
document.getElementById("ontslagCounter").innerHTML = "<p>Het is " + dagenSindsOntslag.toString() + " dagen geleden dat Rutte III zijn ontslag heeft aangeboden.</p>";
</script>

<script type="text/javascript">
const verkiezingen = new Date("March 17, 2021");
const tijdSindsVerkiezingen = Math.abs(verkiezingen - today);
const dagenSindsVerkiezingen = Math.ceil(tijdSindsVerkiezingen / (1000*60*60*24));
document.getElementById("verkiezingenCounter").innerHTML = "<p>Het is " + dagenSindsVerkiezingen.toString() + " dagen geleden dat de tweede kamerverkiezingen hebben plaatsgevonden.</p>";
</script>

<p align="center">
  <img src="/assets/images/chapeau-buma.gif">
</p>
🎉 Dit is nu officiëel de langste formatie in de Nederlandse geschiedenis. 🎉

![IK GEEF EEN NIER VOOR GEEN MARK RUTTE IV](/assets/images/nierposter.jpg)

<!-- ## Tijdlijn -->
