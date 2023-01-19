<script>
    export let title = 'PingPong';
    export let description = 'This is a sport game for cool persons how realy loves to enjoy playing something ...';
    export let color = '#FBFFCE';
</script>

<div class="card" style="--color:{color}">
    <div class="heading">

    </div>
    <div class="content">
        <h3 class="title">
            {title}
        </h3>
        <h5 class="description">
            {description}
        </h5>
    </div>
</div>

<style>
    div.card {
        overflow: hidden;

        width: 15vw;
        height: 35vh;

        border-radius: 15px;
        background-color: #262626;

        transition: all 0.5s ease-in-out;
    }

    div.card:hover,
    div.card:active {
        transform: scale(1.1);
        box-shadow: 0px 10px 20px 2px var(--color);
    }

    div.heading {
        width: 400px;
        height: 190px;

        margin-top: -45px;
        margin-left: -40px;

        background-color: var(--color);

        transform: rotate(10deg);
    }

    div.content {
        padding: 00px 20px 20px 20px;
    }

    .title {
        color: #F1F1F1;
    }

    .description {
        color: #676767;
    }
</style>