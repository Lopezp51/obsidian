---
node_size: "10"
---

<div class="campaign-title">
  <h2>LOREHOLDER'S</h2>
</div>

<div class="campaign-title">
  <h1>CAMPANHAS</h1>
</div>


```datacards
TABLE img, status, inicio as "Inicio", fim as "Fim"
FROM #campanha
SORT inicio ASC

// Settings
preset: square
imageSize: small
imageProperty: img
imagePosition: center
columns: 5
lazyLoad: true

```



<div class="campaign-title">
  <h1>LIVROS</h1>
</div>

<div class="campaign-title">
  <h1>JOGADORES</h1>
</div>