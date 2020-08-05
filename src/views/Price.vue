<template>
     <div class="wrapper">
        <div class="item item-one">
            <h3>Starter</h3>
            <img src="@/img/cycle.png" alt="">
            <div class="info">
                <p>1 Acount</p>
                <p>Limited Access</p>
            </div>
            <div class="price">
                <h3><sup>Ghs</sup>500 <sub>/month</sub> </h3>
            </div>
            <div class="btn">
                <a href="#">View More..</a>
            </div>
        </div>
        <div class="item item-two">
            <h3>Premium</h3>
            <img src="@/img/bike.png" alt="">
            <div class="info">
                <p>5 Acounts</p>
                <p>Unlimited Access</p>
            </div>
            <div class="price">
                <h3><sup>Ghs</sup>500 <sub>/month</sub> </h3>
            </div>
            <div class="btn">
                <a href="#">View More..</a>
            </div>
        </div>
        <div class="item item-three">
            <h3>Unlimited</h3>
            <img src="@/img/sbike.png" alt="">
            <div class="info">
                <p>12 Acount</p>
                <p>unlimited Access</p>
            </div>
            <div class="price">
                <h3><sup>Ghs</sup>500 <sub>/month</sub> </h3>
            </div>
            <div class="btn">
                <a href="#">View More..</a>
            </div>
        </div>
    </div>

</template>



<style scoped>
.wrapper {
    width: auto;
    margin-top: 120px;
    display: flex;
    justify-content: center;
    text-align: center;
    flex-wrap: wrap;
}

.wrapper .item {
    width: 220px;
    height: auto;
    margin: 10px;
    background: gainsboro;
    padding: 30px 20px 65px;
    border-radius: 5px;
    border: 1px solid #e6e6e6;
    position: relative;
}

.wrapper .item h3 {
    letter-spacing: 2px;
}

.wrapper .item.item-one {
    color: #69b0bb
}

.wrapper .item.item-one .btn {
    background: #69b0bb;
}

.wrapper .item.item-two {
    color: #f4581b
}

.wrapper .item.item-two .btn {
    background: #f4581b;
}

.wrapper .item.item-three {
    color: #504b5a;
}

.wrapper .item.item-three .btn {
    background: #504b5a;
}

.wrapper .item img {
    display: block;
    width: 160px;
    margin: 10px auto;
}

.wrapper .item .info p {
    font-size: 10px;
    color: #a3a3a3;
    margin-bottom: 5px;
}

.wrapper .item .price {
    margin-top: 20px;
}

.wrapper .item .price sub,
.wrapper .item .price sub {
    font-size: 10px;
}

.wrapper .item .btn {
    position: absolute;
    bottom: 0;
    left: 50%;
    transform: translateX(-50%);
    width: 170px;
    padding: 8px;
    text-decoration: none;
    border-top-right-radius: 5px;
    border-top-left-radius: 5px;
}

.wrapper .item .btn a {
    display: block;
    color: #fff;
    text-decoration: none;
}
</style>