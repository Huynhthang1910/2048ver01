<template>
    <div id="app">
        <div class="container">
            <game_board/>
        </div>
    </div>
</template>

<script>
    import game_board from "./game-board";

    export default {
        name: "app",
        components: {
            game_board
        }
    };
</script>

<style>
    * {
        box-sizing: border-box;
        font-family: "Arial";
        font-weight: bold;
    }

    .container {
        margin: 30px auto;
        max-width: 1200px;
    }
</style>



