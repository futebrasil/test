<body  style="padding: 0px; margin:0px;">
<script src='https://content.jwplatform.com/libraries/KB5zFt7A.js'></script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/crypto-js/4.0.0/crypto-js.min.js"></script>
<script> jwplayer.key='XSuP4qMl+9tK17QNb+4+th2Pm9AWgMO/cYH8CI0HGGr7bdjo';</script>
<div id="player"></div>
<script>
var playerInstance = jwplayer("player");

    playerInstance.setup({

        playlist: [{
    
         "image": "https://www.prolongadordeeixos.com.br/images/play.gif",
"sources": [
                {
                    "default": false,
                    "type": "dash",
                    "file": 'https://cdn.live.vidgo.com/Content/DASH_WV/Live/channel(72189-FXDEPHD)/manifest.mpd',
                    "drm": {
                        "clearkey": { "keyId": "411a4423a6da462988884c13be14c336", "key": "2188c18bdeb20d713619da0dec98d5c9" }
                    },
                    "label": "0"
                }
            ]
        }],
         width: "100%",
        height: "100%",
        aspectratio: "16:9",
        autostart: false,
        cast: {},
        sharing: {}
    });
</script>

