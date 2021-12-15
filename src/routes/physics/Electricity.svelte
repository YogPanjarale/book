<script>
import Title from "$lib/title.svelte";
</script>
<svelte:head>
    <title>Electricity</title>
    <meta name="description" content="Electricity book ">
</svelte:head>


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
                <li>
                    <p class="text-xl"><span class="font-medium">ELECTRON</span> = e = - 1.6 x 10<sup>-19</sup>C</p>
                </li>
            </ul>
        </li>
        <li>
            <p>As charge of one electron  = 1.6 x 10<sup>-19</sup>C</p>
            <p>∴ charge on n electron = n x 1.6 x 10<sup>-19</sup>C</p>
        </li>
        <li>
            i.e. <b>q = n x e</b><sub >(where n is number of electron)</sub>
        </li>
    </ul>
</Title>
 <!-- footer -->
 <footer class="fixed left-0 bottom-0 w-screen  flex flex-reverse-row items-center pb-8 text-center justify-center">

    <div class=" text-black  text-sm font-bak">
        <p>
            <a href="https://www.yogpanjarale.com" class=" text-black">
                Made with ❤️&🕐 by Yog Panjarale
            </a>
        </p>
    </div>
</footer>

<style>
* {
    font-family: cursive;
    @apply text-lg;
}

sup,sub {
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
    @apply bg-yellow-100 px-2 rounded-sm;
}
</style>
