---
tags:
  - barovia_era_de_ouro
img: "[[char_img.png]]"
conexao: "[[Barovia │ Era de Ouro]]"
descricao: Heróis, traidores, santos e monstros disfarçados de gente.
---

<div class="campaign-title">
  <h2>PERSONAGENS</h2>
</div>

```datacards
TABLE img, status, Afiliação, Localização
FROM #npc_era_de_ouro
SORT Localização ASC 

// Settings
preset: cover
imageSize: xlarge
imageProperty: img
imagePosition: center
columns: 7
lazyLoad: true

```
