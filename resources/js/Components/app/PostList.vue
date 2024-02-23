<script setup>
import PostItem from './PostItem.vue';

const post1= {
    user: {
        id: 1,
        avatar: 'https://randomuser.me/api/portraits/men/72.jpg',
        name: 'John Smith',
    },
    group: null,
    attachments: [
        {
            id: 1,
            name: 'test.png',
            url: 'https://picsum.photos/1000',
            mime: 'image/png',
        },
        {
            id: 2,
            name: 'test2.png',
            url: 'https://picsum.photos/1000',
            mime: 'image/png',
        },
        {
            id: 3,
            name: 'MyDocument.docx',
            url: '#',
            mime: 'application/msword',
        }
    ],
    body:`<p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis neque ex harum quis explicabo exercitationem, impedit quisquam ab praesentium possimus voluptatem animi. Rem et deserunt excepturi beatae, sint suscipit corporis!</p>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis neque ex harum quis explicabo exercitationem, impedit quisquam ab praesentium possimus voluptatem animi. Rem et deserunt excepturi beatae, sint suscipit corporis!</p>`,
    create_at: '2024-11-19 15:12',
}

const post2= {
    user: {
        id: 1,
        avatar: 'https://randomuser.me/api/portraits/men/36.jpg',
        name: 'Mohammed Younes',
    },
    group: {
        id: 1,
        name: 'Laravel Developers',
    },
    body:`<p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis neque ex harum quis explicabo exercitationem, impedit quisquam ab praesentium possimus voluptatem animi. Rem et deserunt excepturi beatae, sint suscipit corporis!</p>
    <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Veritatis neque ex harum quis explicabo exercitationem, impedit quisquam ab praesentium possimus voluptatem animi. Rem et deserunt excepturi beatae, sint suscipit corporis!</p>`,
    create_at: '2022-07-19 01:15',
}

</script>


<template>
    <div class="overflow-auto">
        <PostItem :post="post1"/>
        <PostItem :post="post2"/>
        <PostItem :post="post1"/>
    </div>
</template>

<style>
    
</style>

