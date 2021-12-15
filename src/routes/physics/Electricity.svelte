<script>
import Title from "$lib/title.svelte";
</script>

<Title text="Electric charge">
    <p class="description">
        The electric charge is a physical entity which is defined by exess or deficiency of electron on a body.
    </p>
    <ul class="list-disc">
        <li>
            <p>It is a <b>Scalar Quantity</b></p>
        </li>
        <li>
            <p>SI Unit of charge is <b> Coulomb (C)</b></p>
        </li>
        <li >
            <b class="text-xl">Magnitute of Charge on one</b>
            <ul>
                <li>
                    <p class="text-xl"><span class="font-medium">PROTON</span> = e = + 1.6 x 10<sup>-19</sup>C</p>
                </li>
            </ul>
        </li>

    </ul>
</Title>

<style>
* {
    font-family: cursive;
    @apply text-lg;
}

sup {
    @apply text-sm
}

.description {
    @apply mt-4 ml-4;
    font-family: cursive;
}

ul {
    @apply m-2 ml-8;

    /* list-style-image: url('/assets/blob.svg'); */
}

b {
    @apply bg-yellow-200 px-2 rounded-sm;
}
</style>
