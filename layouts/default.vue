<template>
    <div class="contrainer">
        <div class="side-nav">
    
        </div>
        <div class="center-content">
            <NuxtPage />
        </div>
        <div class="cert">
    
        </div>
    </div>
</template>

<script>
export default {
    setup () {
        

        return {}
    }
}
</script>

<style>

body {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
    background-color: lightcyan;
}
.contrainer {
    width: 100%;
    display: flex;
}
.side-nav {
    border: 1px solid;
    width: 500px;
    height: 500px;
    background-color: white;
}
.center-content {
    border: 1px solid;
    width: 100%;
    height: 500px;
    margin: 0px 10px 0px 10px;
}
.cert {
    border: 1px solid;
    width: 600px;
    height: 500px;
    background-color: white;
}


</style>