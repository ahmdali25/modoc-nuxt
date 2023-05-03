<template>
    <div class="bg-white items-center container-mobile-nav w-full flex justify-between items-center">
        <div class="grid h-full max-w-lg grid-cols-4 mx-auto font-medium">
            <button type="button" class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-50 dark:hover:bg-gray-800 group">
                <img src="../assets/images/home.svg" alt="Home Icon">
                <span class="text-sm text-gray-500 dark:text-gray-400 group-hover:text-blue-600 dark:group-hover:text-blue-500">Beranda</span>
            </button>
            <button type="button" class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-50 dark:hover:bg-gray-800 group">
                <img src="../assets/images/garage.svg" alt="Garage Icon">
                <span class="text-sm text-gray-500 dark:text-gray-400 group-hover:text-blue-600 dark:group-hover:text-blue-500">My Garage</span>
            </button>
            <button type="button" class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-50 dark:hover:bg-gray-800 group">
                <img src="../assets/images/chat.svg" alt="Chat Icon">
                <span class="text-sm text-gray-500 dark:text-gray-400 group-hover:text-blue-600 dark:group-hover:text-blue-500">Chat</span>
            </button>
            <button type="button" class="inline-flex flex-col items-center justify-center px-5 hover:bg-gray-50 dark:hover:bg-gray-800">
                <div class="active px-2 rounded-2xl">
                    <img src="../assets/images/profile.svg" alt="Profile Icon">
                </div>
                <span class="text-sm text-gray-500 dark:text-gray-400 group-hover:text-blue-600 dark:group-hover:text-blue-500">Profile</span>
            </button>
        </div>
    </div>
</template>

<style>
.container-mobile-nav {
    position: fixed;
    z-index: 2000;
    bottom: 0;
    padding: 0.5rem;
    max-width: 600px;
    margin: auto;
    box-shadow: 0px -4px 14px rgb(0 0 0 / 10%);
}

.active {
    background: #00AEFF;
}
</style>