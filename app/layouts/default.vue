<script setup lang="ts"></script>

<template>
    <Head>
        <Title> Create Quizbe </Title>
    </Head>

    <nav class="border-b border-muted flex gap-4 p-2">
        <NuxtLink to="/" class="font-serif text-primary-500 text-2xl">
            Quizbe
        </NuxtLink>

        <span class="grow"></span>

        <UButton to="/account" label="Account" variant="soft" />
    </nav>

    <div
        class="h-[calc(100vh-var(--spacing)*12-1px)] overflow-y-auto space-y-4"
    >
        <slot />
    </div>
</template>
