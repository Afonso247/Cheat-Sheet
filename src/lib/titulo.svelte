<script>
    export let titulo = "Cheat Sheet!"
</script>


<div class="titulo">
    <img src="/controller.svg" alt="Logo do Site">
    <h1>{titulo}</h1>
</div>


<style>
    .titulo {
        display: flex;
    }
    .titulo img {
        display: inline-block;
        filter: invert(88%) sepia(18%) saturate(886%) hue-rotate(199deg)
        brightness(100%) contrast(90%);
        max-height: 80px;
        max-width: 100px;
    }
    .titulo h1 {
        margin-left: 10px;
    }
</style>