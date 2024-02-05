<script lang="ts">
    import { photos } from "$lib/photos";
</script>

{#each photos as photo }
    <img src={photo.url} />
    <p>{photo.explanation}</p>
{/each}