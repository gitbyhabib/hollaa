<template>
    <footer class="fixed bottom-0 left-0 right-0 w-full bg-gray-800 text-gray-200 py-6 overflow-x-hidden">
        <div class="w-full max-w-full mx-auto px-4 flex flex-col md:flex-row items-center justify-between">
            <div class="mb-4 md:mb-0">
                <span class="font-semibold text-lg">Hollaa &copy; {{ new Date().getFullYear() }}</span>
            </div>
            <div class="flex space-x-4">
                <a href="#" class="hover:text-white transition">Home</a>
                <a href="#" class="hover:text-white transition">About</a>
                <a href="#" class="hover:text-white transition">Contact</a>
            </div>
        </div>
    </footer>
</template>

<script setup>
// No script logic needed for this simple footer
</script>