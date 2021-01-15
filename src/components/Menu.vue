<template>
    <b-navbar toggleable type="primary" variant="primary" id="nav">
        <b-navbar-nav>
            <b-nav>
                <b-navbar-brand href="#">
                    <img src="https://cdn.megajogos.com.br/images/premium/game-logo/trucoespanhol-m_pt_BR.png">
                </b-navbar-brand>
                <b-nav-item href="/">Home</b-nav-item>
                <b-nav-item href="/scoreboard">Scoreboard</b-nav-item>
                <b-nav-item href="/about">About</b-nav-item>
            </b-nav>

        </b-navbar-nav>
    </b-navbar>
</template>
<script>

    export default {
        name: "Menu",
    }
</script>

<style scoped>

    #nav {
        padding: 10px;
        font-size: 20px;
        background-color: green;
    }

    #nav a {
        font-weight: bold;
        color: #2c3e50;
    }

    #nav a.router-link-exact-active {
        color: #42b983;
    }

    img {
        width: 50px;
    }
</style>