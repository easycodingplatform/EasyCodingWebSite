<template>
    <div class="header-container">
        <!--页面logo-->
        <div class="page-name">
            <p style="color:#02B400;margin:0">Easy</p>
            <p style="color:#126BD1;margin:0">Coding</p>
        </div>

        <!--用户头像跟用户名称-->
        <div class="user-info">
            <el-button class="user-logo" type="success" circle>
                <font-awesome-icon icon="user-secret" style="transform-origin: center|center"/>
            </el-button>
            <p class="user-name">user name</p> 
        </div>

        <!--导航栏中的按键-->
        <div class="function-button">
            <font-awesome-icon icon="plus" style="color:#67C23A;"/>
            <font-awesome-icon icon="ellipsis-v" style="color:#C8C8C8"/>
        </div>
    </div>
</template>

<script>
export default {
}
</script>

<style>
.header-container {
    display:flex;
    flex-direction: row;
    align-items: center;
    width: 100%;
    height: 100%;
}

.page-name{
    display:flex;
    flex-direction: row;
    justify-content: flex-start;
    align-items: center;
    font-family: Source Han Sans CN;
    font-size: 20px;
    height:100%;
}

.user-info{
    display: flex;
    flex-direction: row;
    align-items: center;
    height: 100%;
    margin-left: 900px;
}

.user-logo{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 30px;
    width: 30px;
}

.user-name{
    color: 101010;
    margin-left: 10px;
}

.function-button{
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    margin-left: 200px;
    width: 50px;
}
</style>
