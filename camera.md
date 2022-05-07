<script src="https://cdn.bootcss.com/flv.js/1.5.0/flv.min.js"></script>
<video autoplay muted id="videoElement"></video>
<script>
    if (flvjs.isSupported()) {
        var videoElement = document.getElementById('videoElement');
        var flvPlayer = flvjs.createPlayer({
            type: 'flv',
            url: 'http://pogpega.duckdns.org:2727/live/test.flv'
        });
        flvPlayer.attachMediaElement(videoElement);
        flvPlayer.load();
        flvPlayer.play();
    }
</script>