<template>
    <header>
        <input type="text" placeholder="Cari" class="search">
        <ul class="menu">
            <li><router-link to="/">Home</router-link></li>
            <li><router-link to="/product">Product</router-link></li>
            <li><router-link to="/category">Category</router-link></li>
            <li><router-link to="/profile">Profile</router-link></li>
        </ul>
    </header>
</template>
<style scoped>
    * {
        padding: 0;
        margin: 0;
    }
    header {
        width: 100%;
        height: 4vh;
        background-color: aqua;
        display: flex;
        flex-direction: row;
        justify-content: space-between;
        align-items: center;
    }
    .search {
        width: 10vw;
        height: 20px;
        margin-left: 40px;

    }
    ul {
        display: flex;
        flex-direction: row;
        justify-content: flex-end;
    }
    ul li {
        padding: 5px;
        list-style: none;
    }
    ul li a {
        text-decoration: none;
    }
</style>