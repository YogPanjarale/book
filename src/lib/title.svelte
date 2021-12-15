<script lang="ts">
    export let text; 
</script>
<div class="m-2">

    <div class="back">{text}</div>
    <div class="main">{text}</div>
    <slot></slot>
</div>

<style>
   .main{
        @apply bg-yellow-300 px-3 py-2 h-12;
    /* max-width: min-content; */
    max-width: max-content;
    border: 2px solid black;
    font-family: cursive;
    font-size: larger;
    font-weight: 500;
    }
   .back{
       z-index: -1;
    @apply absolute h-12 px-4 py-2 bg-pink-300 border-2 border-black;
    font-size: larger;
    transform: translate(1rem, 0.5rem);
    /* background-color: red; */
   }
   
</style>