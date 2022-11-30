<template>
    <div :class="'color' + number" class="cell">{{ number || '' }}</div>
</template>
<script>
    export default {
        name: 'game-cell',
        methods: {},
        props: {
            number: String
        }
    }
</script>
<style>
    .color0 {
        background-color: #dfe6e9;
        color: #fff;
    }

    @keyframes color_change2 {
        from {
            background-color: #dfe6e9;
        }
        to {
            background-color: #74b9ff;
        }
    }

    .color2 {
        background-color: #74b9ff;
        color: #fff;
        animation-name: color_change2;
        animation-duration: 0.20s;
        animation-direction: alternate;
    }

    @keyframes color_change4 {
        from {
            background-color: #74b9ff;
        }
        to {
            background-color: #0984e3;
        }
    }

    .color4 {
        animation-name: color_change4;
        background-color: #0984e3;
        color: #fff;
        animation-duration: 1s;
        animation-direction: alternate;

    }

    @keyframes color_change8 {
        from {
            background-color: #0984e3;
        }
        to {
            background-color: #ff7675;
        }
    }

    .color8 {
        animation-name: color_change8;
        background-color: #ff7675;
        color: #fff;
        animation-duration: 1s;
        animation-direction: alternate;

    }

    @keyframes color_change16 {
        from {
            background-color: #ff7675;
        }
        to {
            background-color: #d63031;
        }
    }

    .color16 {
        animation-name: color_change16;
        background-color: #d63031;
        color: #fff;
        font-size: 60px;
        animation-duration: 1s;
        animation-direction: alternate;

    }

    @keyframes color_change32 {
        from {
            background-color: #d63031;
        }
        to {
            background-color: #a29bfe;
        }
    }

    .color32 {
        animation-name: color_change32;
        background-color: #a29bfe;
        color: #fff;
        font-size: 60px;
        animation-duration: 1s;
        animation-direction: alternate;

    }

    @keyframes color_change64 {
        from {
            background-color: #a29bfe;
        }
        to {
            background-color: #fd79a8;
        }
    }

    .color64 {
        animation-name: color_change64;
        background-color: #fd79a8;
        color: #fff;
        font-size: 60px;
        animation-duration: 1s;
        animation-direction: alternate;

    }

    @keyframes color_change128 {
        from {
            background-color: #fd79a8;
        }
        to {
            background-color: #55efc4;
        }
    }

    .color128 {
        animation-name: color_change128;
        background-color: #55efc4;
        color: #fff;
        font-size: 56px;
        animation-duration: 1s;
        animation-direction: alternate;

    }

    @keyframes color_change256 {
        from {
            background-color: #55efc4;
        }
        to {
            background-color: #ffeaa7;
        }
    }

    .color256 {
        animation-name: color_change256;
        background-color: #ffeaa7;
        color: #fff;
        font-size: 56px;
        animation-duration: 1s;
        animation-direction: alternate;

    }

    @keyframes color_change512 {
        from {
            background-color: #ffeaa7;
        }
        to {
            background-color: #e17055;
        }
    }

    .color512 {
        animation-name: color_change512;
        background-color: #e17055;
        color: #fff;
        font-size: 56px;
        animation-duration: 1s;
        animation-direction: alternate;

    }

    @keyframes color_change1024 {
        from {
            background-color: #e17055;
        }
        to {
            background-color: #c0392b;
        }
    }

    .color1024 {
        animation-name: color_change1024;
        background-color: #c0392b;
        color: #fff;
        font-size: 46px;
        animation-duration: 1s;
        animation-direction: alternate;

    }

    @keyframes color_change2048 {
        from {
            background-color: #c0392b;
        }
        to {
            background-color: #f1c40f;
        }
    }

    .color2048 {
        animation-name: color_change2048;
        background-color: #f1c40f;
        color: #fff;
        font-size: 46px;
    }

    .color4096 {
        background-color: #1abc9c;
        color: #fff;
        font-size: 46px;
    }

    .color8192 {
        background-color: #34495e;
        color: #000000;
        font-size: 46px;
    }

    .cell {
        width: 23%;
        height: 23%;
        border-radius: 8px;
        border: 1px solid #ccc;
        margin: 1%;
        font-size: 64px;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    

</style>
