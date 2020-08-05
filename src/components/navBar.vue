<template>
    <header>
        <div class="logo-container">
            <img src="@/img/logo.svg" alt="">
            <h4 class="logo">CodeBooth</h4>
        </div>

        <nav>
            <ul class="nav-links">
                <li><a class="nav-link" href="/index.html">Home</a></li>
                <li><a class="nav-link" href="#">Our Courses</a></li>
                <li><a class="nav-link" href="./pricing.html">Pricing</a></li>
                <li><a class="nav-link" href="#">Contact</a></li>
            </ul>
        </nav>
        <div class="cart">
            <img src="@/img/cart.svg" alt="cart">

        </div>

    </header>
</template>



<style  scoped>
header {
    display: flex;
    width: 90%;
    height: 10vh;
    margin: auto;
    align-items: center;
    justify-content: space-between;
}

.logo-container,
.nav-links,
.cart {
    display: flex;
}

.logo-container {
    flex: 1;
}

.logo {
    font-weight: 400;
    margin: 5px;
}

nav {
    flex: 2;
}

.nav-links {
    justify-content: space-evenly;
    list-style: none;
}

.nav-link {
    text-decoration: none;
    color: #5f5f78;
    font-size: 18px;

}

.cart {
    flex: 1;
    justify-content: end;
}

</style>