---
tags:
  - barovia_era_de_ouro
img: "[[artifacts_img.png]]"
conexao: "[[Barovia │ Era de Ouro]]"
descricao: Relíquias perdidas, objetos amaldiçoados ou tesouros lendários que moldam o destino de quem os possui.
---

<div class="campaign-title">
  <h2>ARTEFATOS</h2>
</div>

```datacards
TABLE img, posse as "Posse", tipo_artefato as "Tipo"
FROM #artefatos_era_de_ouro
SORT tipo_artefato

// Settings
preset: portrait
imageSize: small
imageProperty: img
imagePosition: center
columns: 9
lazyLoad: true

```