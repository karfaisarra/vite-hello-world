<script></script>

<template>
    <section>
        <div class="container">
            <h2 class="title">Ecco il mio Jumbotron</h2>
            <p class="text">
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Adipisci laborum itaque atque
                doloribus odio quasi commodi at, voluptatem ipsam incidunt. Inventore ea ad beatae perferendis laborum,
                totam cupiditate quia provident!
            </p>
        </div>

    </section>
</template>

<style scoped>
section {
    background-image: url(../assets/scale.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    width: 100%;
    height: 700px;
}

.container {
    padding-top: 2rem;
    width: 80%;
    margin: auto;
}

.title {
    color: white;
}

.container .text {
    width: 30%;
    margin-top: 1rem;
    color: white;
}
</style>