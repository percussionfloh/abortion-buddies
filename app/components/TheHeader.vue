<script setup>
const localePath = useLocalePath();


</script>

<template>
    <header class="h-19 w-auto bg-primary-700 text-white">
        <div class="flex justify-between items-center py-2 px-4 gap-4">
            <div class="grow flex items-center gap-4">
                <div class="font-extrabold text-2xl md:text-6xl">
                    <NuxtLink :to="localePath('/')">
                        Abortion Buddies
                    </NuxtLink>
                </div>
            </div>
            <div class="flex gap-2 justify-end items-center">
                <UButton
                    icon="i-simple-icons-github"
                    to="https://github.com/percussionfloh"
                    target="_blank"
                    variant="ghost"
                    color="neutral"
                    square
                    :ui="{ label: 'hidden', base: 'text-white hover:text-black' }"
                />
                <UButton
                    icon="i-simple-icons-instagram"
                    to="https://www.instagram.com/abortionbuddy.freiburg"
                    target="_blank"
                    variant="ghost"
                    color="neutral"
                    square
                    :ui="{ label: 'hidden', base: 'text-white hover:text-black' }"
                />
            </div>
        </div>
    </header>
</template>

