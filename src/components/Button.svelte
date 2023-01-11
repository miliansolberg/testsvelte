<script>
    let count = 0;

    function handleClick() {
        count += 1;
    }
</script>

<main>
    <button on:click={handleClick}>
    Clicked {count} {count === 1 ? 'time' : 'times'}
    </button>
</main>

<style>
    button {
        margin: 30px auto;
        display: flex;
        padding: 20px;
        border-radius: 20px;
        background-color: #F46036;
        color: #fff;
        font-size: 1rem;
        font-weight: bold;
}
</style>