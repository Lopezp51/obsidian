---
tags:
  - barovia_era_de_ouro
img: "[[char_img.png]]"
conexao: "[[Barovia │ Era de Ouro]]"
---

<div class="campaign-title">
  <h2>PERSONAGENS</h2>
</div>

```datacards
TABLE img, status, Afiliação, Localização
FROM #npc
SORT name ASC, Afiliação ASC

// Settings
preset: cover
imageSize: xlarge
imageProperty: img
imagePosition: center
columns: 7
lazyLoad: true

```
