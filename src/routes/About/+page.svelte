<script>
    import { Card, Button } from 'flowbite-svelte';
    import { ArrowRightOutline } from 'flowbite-svelte-icons';
</script>

<!-- Parent container to center the Card -->
<div class="flex justify-center items-center min-h-screen">
    <Card class="w-96"> <!-- You can adjust the width as needed -->
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">I'm 20 Years Old</h5>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Height: 5'10</h5>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Male</h5>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Virgo</h5>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Green Flag</h5>
        <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">Lover Boy</h5>
        <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 leading-tight">
            At 20 years old, I stand 5'10", embodying the traits of a Virgo. I embrace positivity, represented by my green flag status, and I'm known as a lover boy, which reflects my affectionate nature. My personality traits and age shape my perspective on life, making me a young adult eager to explore the world.
        </p>
        <Button class="w-fit">
            Read more <ArrowRightOutline class="w-6 h-6 ms-2 text-white" />
        </Button>
    </Card>
</div>
