<template>
    <UContainer class="h-screen flex flex-col items-center justify-center text-center px-6">
        <UPageHero title="Nordstream Resource Management Limited"
            description=" Providing Innovative & Sustainable Energy Solutions."
            :links="links" headline="Coming Soon"/>
        <footer class="absolute bottom-6 text-gray-500 text-sm">
            © {{ new Date().getFullYear() }} Nordstream Resource Management Ltd. All rights reserved.
        </footer>
    </UContainer>
</template>

<script setup lang="ts">
const links = ref([
    {
        label: 'Chat with Us',
        to: 'https://wa.me/2347062415688',
        icon: 'i-lucide-message-circle', 
        color: 'primary'
    },
    {
        label: 'Send us Email',
        to: 'mailto:info@nordstreamresources.com',
        icon: 'i-lucide-mail', 
        color: 'neutral',
        variant: 'subtle',
    },
])
</script>
