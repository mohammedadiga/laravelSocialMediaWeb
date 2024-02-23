<script setup>
    import TextInput from '@/Components/TextInput.vue';
    import {ref} from 'vue';

    import FollowingItem from './FollowingItem.vue';   
</script>

<template>
    <TextInput :model-value="searchKeyword" placeholder="Type to search" class="w-full mt-4"/>

    <div class="mt-3 h-[200px] lg:flex-1 overflow-auto">

        <div v-if="false" class="text-gray-400 text-center p-3" >
            You don't have friends yet.
        </div>

        <div v-else>
            <FollowingItem image="https://picsum.photos/100" title="joun Doe" />
            <FollowingItem image="https://picsum.photos/200" title="Elon Musk" />
            <FollowingItem image="https://picsum.photos/100" title="joun Doe" />
            <FollowingItem image="https://picsum.photos/200" title="Elon Musk" />
            <FollowingItem image="https://picsum.photos/100" title="joun Doe" />
            <FollowingItem image="https://picsum.photos/200" title="Elon Musk" />
            <FollowingItem image="https://picsum.photos/100" title="joun Doe" />
            <FollowingItem image="https://picsum.photos/200" title="Elon Musk" />
            <FollowingItem image="https://picsum.photos/100" title="joun Doe" />
            <FollowingItem image="https://picsum.photos/200" title="Elon Musk" />
            <FollowingItem image="https://picsum.photos/100" title="joun Doe" />
            <FollowingItem image="https://picsum.photos/200" title="Elon Musk" />
            <FollowingItem image="https://picsum.photos/100" title="joun Doe" />
            <FollowingItem image="https://picsum.photos/200" title="Elon Musk" />
            <FollowingItem image="https://picsum.photos/100" title="joun Doe" />
            <FollowingItem image="https://picsum.photos/200" title="Elon Musk" />
            <FollowingItem image="https://picsum.photos/100" title="joun Doe" />
            <FollowingItem image="https://picsum.photos/200" title="Elon Musk" />
        </div>
    </div>
</template>


<style>
    
</style>