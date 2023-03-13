<template>
    <nav class="navbar navbar-expand-lg bg-body-transparent">
        <div class="container-fluid ">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarTogglerDemo01"
                aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
                <ul class="navbar-nav me-auto mb-2 mb-lg-0">
                    <li class="nav-item">
                        <router-link to="/">Home</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/events">Events</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/cart">Cart</router-link>
                    </li>
                </ul>
                <ul class="navbar-nav ms-auto" style="list-style: none;display: flex;">
                    <li class="nav-item">
                        <router-link to="/login">Login</router-link>
                    </li>
                    <li class="nav-item">
                        <router-link to="/register">Register</router-link>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<script>
export default {
    name: 'NavBarC'
}
</script>

<style scoped>
nav {
    background-color: #BFB7B6;
    padding: 30px;
}

a {
    text-decoration: none;
    color: #435058;
    font-size: 25px;
    padding: 5px;
}
</style>