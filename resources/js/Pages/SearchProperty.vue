<template>
    <section class="bg-black dark:bg-gray-900">
        <div class="p-8 lg:flex lg:items-center lg:justify-center">
            <form class="space-y-4 lg:space-y-0 lg:flex lg:space-x-4 lg:flex-nowrap">
                <div class="">
                    <select
                        class="w-full py-2.5 px-8 bg-white border border-gray-400 rounded outline-none focus:ring-2">
                        <option>Type</option>
                        <option>Apartment</option>
                        <option>Apartment</option>
                        <option>House</option>
                        <option>Villa</option>
                        <option>Hotel</option>
                    </select>

                </div>
                <div>
                    <input type="text"
                           class="w-full p-2 border border-gray-400 rounded outline-none focus:ring-2"
                           Placeholder="Location" />
                </div>
                <div>
                    <input type="number"
                           class="w-full p-2 border border-gray-400 rounded outline-none focus:ring-2"
                           placeholder="min" />
                </div>
                <div>
                    <input type="number"
                           class="w-full p-2 border border-gray-400 rounded outline-none focus:ring-2"
                           placeholder="max" />
                </div>
                <div>
                    <button class="px-8 py-2 text-blue-100 bg-gray-600 rounded">
                        Search</button>
                </div>
            </form>
        </div>
    </section>
</template>

<script>
export default {
    name: "SearchProperty"
}
</script>

<style scoped>

</style>
