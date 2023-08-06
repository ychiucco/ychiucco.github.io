---
layout: default
title: Chess ♜♞♝
---

# {{ page.title }}

Let's talk about chess!

<div id="board1" style="width: 400px"></div>
<script>
var config = {
    draggable: true,
    dropOffBoard: 'snapback', // 'trash'
    moveSpeed: 'slow',
    snapbackSpeed: 500,
    snapSpeed: 100,
    position: 'rnbqkb1r/pppp1ppp/5n2/4p3/4PP2/2N5/PPPP2PP/R1BQKBNR',
    showNotation: false
}
var board1 = Chessboard('board1', config)
</script>
