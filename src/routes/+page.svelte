<!-- Card component -->
<script>
    import Card from "../components/Card.svelte";
</script>

<section>
    <div class="group-card">
        <Card />
        <Card />
        <Card />
        <Card />
        <Card />
        <Card />
    </div>
</section>

<style>
    section {
        display: flex;
        align-items: center;
        justify-content: center;
    }

    div.group-card {
        width: 70vw;

        display: flex;
        flex-flow: wrap;
        gap: 4vw;
    }
</style>