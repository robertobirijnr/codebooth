<template>
    <main>
        <div class="presentation">
            <div class="introduction">
                <div class="intro-text">
                    <h1>Learn anything, anywhere</h1>
                    <p>Choose from 100,000 online video courses with new additions published every month</p>
                </div>
                <div class="cta">
                    <button class="cta-select"><router-link  to="/login" >Login</router-link></button> 
                    <button class="cta-add">Register</button>
                </div>
            </div>
            <div class="cover">
                <img src="@/img/matebook.png" alt="matebook">
            </div>
        </div>

        <img class="big-circle" src="@/img/big-eclipse.svg" alt="">
        <img class="medium-circle" src="@/img/mid-eclipse.svg" alt="">
        <img class="small-circle" src="@/img/small-eclipse.svg" alt="">
    </main>
</template>



<style  scoped>

.presentation {
    display: flex;
    width: 80%;
    margin: auto;
    min-height: 80vh;
    align-items: center;
}

.introduction {
    flex: 1;
}

.intro-text h1 {
    font-size: 44px;
    font-weight: 500;
    background: linear-gradient(to right, #494964, #6f6f89);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

.cta {
    padding: 50px 0px 0px 0px;
}

.cta-select {
    border: 2px solid #c36cbb;
    background: transparent;
    color: violet;
    width: 150px;
    height: 50px;
    cursor: pointer;
    font-size: 16px;
}

.cta-add {
    background: violet;
    color: white;
    width: 150px;
    height: 50px;
    cursor: pointer;
    text-decoration:none;
    font-size: 16px;
    border: none;
    margin: 30px 0px 0px 30px
}

.cover {
    flex: 1;
}

.cover img {
    height: 60vh;
    filter: drop-shadow(0px 5px 3px black);
    animation: drop 1.5s ease;
}

.big-circle {
    position: absolute;
    top: 0px;
    right: 0px;
    z-index: -1;
    opacity: 0.5;
    height: 80%;
}

.medium-circle {
    position: absolute;
    top: 30%;
    height: 60%;
    z-index: -1;
    right: 30%;
    opacity: 0.4;
}

.small-circle {
    position: absolute;
    bottom: 0%;
    left: 25%;
    z-index: -1;
}

@keyframes drop {
    0% {
        opacity: 0;
        transform: translateY(-800px);
    }

    100% {
        opacity: 1;
        transform: translateY(0px);
    }
}

@media screen and (max-width:1024px) {
    .presentation {
        flex-direction: column;
    }

    .introduction {
        margin-top: 5vh;
        text-align: center;
    }

    .intro-text h1 {
        font-size: 30px;
    }

    .intro-text p {
        font-size: 18px;
    }

    .cta {
        padding: 10px 0px 0px 0px;
    }
}

</style>