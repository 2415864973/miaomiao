<template>
    <div id="main">
        <Header title="我的"/>
        <Login/>
        <tabBar/>
    </div>
</template>
<script>
import Header from '@/components/Header';
import tabBar from '@/components/TabBar';
import Login from '@/components/Login';
export default {
    name : 'Mine',
    components : {
        Header,
        tabBar,
        Login
    }
}
</script>
<style scoped>
    
</style>