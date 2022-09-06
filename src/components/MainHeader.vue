
<template>
    <header>
        <div class="container">

            <div class="nav-wrapper">

                <div class="logo">
                    <img :src="logo" alt="logo dc">
                </div>
                <nav class="nav">
                    <ul>
                        <li v-for="(link, i) in links" :key="i" :class="[link.current ? 'active' : '', 'nav-link']">
                            <a :href="link.href">
                                {{ link.text }}
                            </a>
                        </li>

                    </ul>
                </nav>
            </div>
        </div>
    </header>
</template>



<script>

import logo from '../assets/dc-logo.png'
export default {
    data() {
        return {
            logo:logo,
            links: [
                {
                    text: 'Characters',
                    href: '#',
                    current: false,
                }, {
                    text: 'Comics',
                    href: '#',
                    current: true,
                },
                {
                    text: 'Movies',
                    href: '#',
                    current: false,
                },
                {
                    text: 'Tv',
                    href: '#',
                    current: false,
                },
                {
                    text: 'Games',
                    href: '#',
                    current: false,
                },
                {
                    text: 'Collectibles',
                    href: '#',
                    current: false,
                },
                {
                    text: 'Videos',
                    href: '#',
                    current: false,
                },
                {
                    text: 'Fans',
                    href: '#',
                    current: false,
                },
                {
                    text: 'News',
                    href: '#',
                    current: false,
                },
                {
                    text: 'Shop',
                    href: '#',
                    current: false,
                },
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
header {
    padding: 60px 0;
}

.nav-wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;


    .nav {
        ul {
            display: flex;
            gap: 1rem;


            .nav-link {
                text-transform: uppercase;
                font-size: 18px;



                &.active,
                &:hover {
                    color: #0282F9;
                    border-bottom: 1px solid #0282F9;

                }


            }
        }
    }
}
</style>