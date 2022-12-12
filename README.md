# skyline.almav.com.br
Quick Start Mapa Interativo

A API JavaScript do almav Mapas permite que você personalize mapas com seu próprio conteúdo e imagens para exibição em páginas da web e dispositivos móveis que você pode modificar usando camadas e estilos, controles e eventos.

EXEMPLO ELEMENTO DESTINO

```
<div id=”map”></div>
```

EXEMPLO FUNÇÃO RETORNO
```
let map;
function initMap() {
  map = new almav.maps.Map(document.getElementById(“map”), {
      “settings-id”: 1,
  });
}
```

URL: Javascript
```
<script src=”https://h3-skyline.maps.almav.com/maps/api/js?key=<chave>&callback=<retorno>” async></script>
```
IMPORTANTE
1. Ao incluir o Mapa Interativo via iFrame, funções como o botão de GPS e tela cheia não irão funcionar. Utilize sempre a implementação por meio do código javascript.
2. No console (Painel) de administração do Mapa Interativo, será necessário incluir todos os domínios permitidos para integração. 

Visite https://almav.com
