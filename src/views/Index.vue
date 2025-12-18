<template>
    <div>main</div>

</template>

<script>
    export default {
        name:"Index"
    }
</script>

<style scoped>
    .el-container {
        padding: 0;
        margin: 0;
        display: flex;
        min-height: 100vh;
    }

    .el-header {
        background-color: #17B3A3;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 0 20px;
        height: 60px;
    }


    .header-avatar {
        display: flex;
        align-items: center;
        gap: 10px;
    }


    .el-dropdown-link {
        display: flex;
        align-items: center;
        cursor: pointer;
    }


    .el-aside {
        background-color: #D3DCE6;
        color: #333;
        text-align: left;
        line-height: 200px;
    }

    .el-main {
        color: #333;
        text-align: center;
        line-height: 160px;
        padding: 0;
    }


    .el-menu-vertical-demo {
        height: 100%;
    }

    a{
        text-decoration: none;
    }



</style>