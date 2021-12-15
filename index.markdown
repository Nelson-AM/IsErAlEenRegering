---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

# Nee

... maar er is wel een [coalitieakkoord](https://www.kabinetsformatie2021.nl/documenten/publicaties/2021/12/15/coalitieakkoord-omzien-naar-elkaar-vooruitkijken-naar-de-toekomst)!

<div id="ontslagCounter"></div>
<div id=verkiezingenCounter></div>

<script type="text/javascript">
const today = new Date();
const ontslagdatum = new Date("January 15, 2021");
const tijdSindsOntslag = Math.abs(ontslagdatum - today);
const dagenSindsOntslag = Math.ceil(tijdSindsOntslag / (1000*60*60*24));
document.getElementById("ontslagCounter").innerHTML = "<p>" + dagenSindsOntslag.toString() + " dagen geleden heeft Rutte III zijn ontslag aangeboden.</p>";
</script>

<script type="text/javascript">
const verkiezingen = new Date("March 17, 2021");
const tijdSindsVerkiezingen = Math.abs(verkiezingen - today);
const dagenSindsVerkiezingen = Math.ceil(tijdSindsVerkiezingen / (1000*60*60*24));
document.getElementById("verkiezingenCounter").innerHTML = "<p>" + dagenSindsVerkiezingen.toString() + " dagen geleden hebben de tweede kamerverkiezingen plaatsgevonden.</p>";
</script>

<p align="center">
  <img src="/assets/images/chapeau-buma.gif">
</p>
<p style="text-align: center;">
  🎉 Dit is nu officiëel de langste formatie in de Nederlandse geschiedenis. 🎉
</p>

![IK GEEF EEN NIER VOOR GEEN MARK RUTTE IV](/assets/images/nierposter.jpg)

<!-- ## Tijdlijn -->
