<script>
    let { hide } = $props()
</script>

<dialog open>
    <article>
        <header>
            <button aria-label="Close" rel="prev" onclick={hide}></button>
            <h2>Cast Vote</h2>
            <form id="cast-vote-form">
                <div></div>
                <button name="submit">Cast Vote</button>
                <p id="cast-vote-form-error" class="danger"></p>
            </form>
        </header>
    </article>
</dialog>