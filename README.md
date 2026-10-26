# CDNPEER SDK

P2P para vídeo en vivo HLS. Añade el P2P de CDNPEER al reproductor de tu web.

## Clappr

```html
<script src="https://cdn.jsdelivr.net/npm/@clappr/player@0.8.0/dist/clappr.min.js"></script>
<script src="https://cdn.jsdelivr.net/gh/cdnpeer/sdk@1.2.1/cdnpeer.min.js"></script>
<div id="player"></div>
<script>
  var player = cdnpeer.clappr(Clappr, {
    id: "TU_IDENTIFICADOR",
    src: "https://tu-servidor/canal/index.m3u8",
    parentId: "#player"
  });
</script>
```

Tu identificador y el código completo están en tu panel: https://cdnpeer.com (pestaña Integración).
El dominio de tu web debe estar dado de alta en el panel.

## Licencias

Incluye p2p-media-loader (Apache License 2.0, © Novage), con cambios de CDNPEER. Ver NOTICE.
