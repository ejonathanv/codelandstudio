<template>
    <Loader :loading="loading" />
    <div class="min-h-screen bg-light max-w-full overflow-x-hidden">
        <Header />
        <Follow-Links />
        <slot />
        <Footer />
    </div>
</template>
<script>
import { Link } from '@inertiajs/inertia-vue3';
import Loader from '@/Components/Website/Loader';
import Header from '@/Components/Website/Header';
import Footer from '@/Components/Website/Footer';
import FollowLinks from '@/Components/Website/FollowLinks';
import {WOW} from 'wowjs';
export default {
    components: {
        Loader,
        Header,
        Footer,
        Link,
        FollowLinks
    },
    data(){
        return {
            loading: true
        }
    },
    mounted(){
        setTimeout(() => {
            this.loading = false;
        }, 500);
        this.initAnimate();
    },
    methods: {
        initAnimate(){
            var wow = new WOW(
                {
                    boxClass:     'wow',      // animated element css class (default is wow)
                    animateClass: 'animate__animated', // animation css class (default is animated)
                    offset:       0,          // distance to the element when triggering the animation (default is 0)
                    mobile:       false,       // trigger animations on mobile devices (default is true)
                    live:         false,       // act on asynchronously loaded content (default is true)
                }
            );
            wow.init();
            console.log(wow);
        }
    }
}
</script>