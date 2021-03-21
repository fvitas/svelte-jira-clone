<script>

</script>

<nav class="navigation">
    <aside class="navbar">
        <div class="navbar--top">
            <svg width="32" height="32" viewBox="0 0 32 32">
                <defs>
                    <linearGradient x1="108.695%" x2="12.439%" y1="-14.936%" y2="45.215%" id="uid11-1">
                        <stop stop-color="#DEEBFF" stop-opacity="0.4" offset="0%"></stop>
                        <stop stop-color="#DEEBFF" offset="100%"></stop>
                    </linearGradient>
                    <linearGradient x1="0%" x2="91.029%" y1="118.55%" y2="63.971%" id="uid11-2">
                        <stop stop-color="#DEEBFF" stop-opacity="0.4" offset="0%"></stop>
                        <stop stop-color="#DEEBFF" offset="100%"></stop>
                    </linearGradient>
                </defs>
                <g>
                    <path d="M15.967 29.362a6.675 6.675 0 0 0 0-9.442l-8.699-8.671-3.957 3.957a1.062 1.062 0 0 0 0 1.5l12.656 12.656zm12.656-14.156L15.967 2.55l-.039.039a6.675 6.675 0 0 0 .028 9.41l8.706 8.667 3.96-3.96a1.062 1.062 0 0 0 0-1.5z" fill="white"></path>
                    <path d="M15.967 11.992a6.675 6.675 0 0 1-.028-9.41L6.91 11.606l4.72 4.721 4.336-4.335z" fill="url(#uid11-1)"></path>
                    <path d="M20.295 15.591l-4.328 4.329a6.675 6.675 0 0 1 0 9.442l9.05-9.05-4.722-4.72z" fill="url(#uid11-2)"></path>
                </g>
            </svg>

            <svg class="icon" width="24" height="24" viewBox="0 0 24 24">
                <path d="M16.436 15.085l3.94 4.01a1 1 0 0 1-1.425 1.402l-3.938-4.006a7.5 7.5 0 1 1 1.423-1.406zM10.5 16a5.5 5.5 0 1 0 0-11 5.5 5.5 0 0 0 0 11z" fill="white"></path>
            </svg>

            <svg class="icon" width="24" height="24" viewBox="0 0 24 24">
                <path d="M13 11V3.993A.997.997 0 0 0 12 3c-.556 0-1 .445-1 .993V11H3.993A.997.997 0 0 0 3 12c0 .557.445 1 .993 1H11v7.007c0 .548.448.993 1 .993.556 0 1-.445 1-.993V13h7.007A.997.997 0 0 0 21 12c0-.556-.445-1-.993-1H13z" fill="white"></path>
            </svg>
        </div>

        <div class="navbar--bottom">
            <img class="profile" src="/images/githuboctocat.png">

            <svg class="icon" width="24" height="24" viewBox="64 64 896 896">
                <path d="M512 64C264.6 64 64 264.6 64 512s200.6 448 448 448 448-200.6 448-448S759.4 64 512 64zm0 708c-22.1 0-40-17.9-40-40s17.9-40 40-40 40 17.9 40 40-17.9 40-40 40zm62.9-219.5a48.3 48.3 0 00-30.9 44.8V620c0 4.4-3.6 8-8 8h-48c-4.4 0-8-3.6-8-8v-21.5c0-23.1 6.7-45.9 19.9-64.9 12.9-18.6 30.9-32.8 52.1-40.9 34-13.1 56-41.6 56-72.7 0-44.1-43.1-80-96-80s-96 35.9-96 80v7.6c0 4.4-3.6 8-8 8h-48c-4.4 0-8-3.6-8-8V420c0-39.3 17.2-76 48.4-103.3C430.4 290.4 470 276 512 276s81.6 14.5 111.6 40.7C654.8 344 672 380.7 672 420c0 57.8-38.1 109.8-97.1 132.5z" fill="white"></path>
            </svg>
        </div>
    </aside>
    <div class="sidebar"></div>
</nav>

<style lang="sass">
    .navigation
        display: flex

    .navbar
        display: flex
        flex-direction: column
        justify-content: space-between
        width: 64px
        height: 100vh
        padding: 24px 0
        background-color: #0747a6

    .profile
        width: 24px
        height: 24px
        border-radius: 50%

    .navbar--top
        display: flex
        flex-direction: column
        justify-content: space-between
        align-items: center
        width: 100%
        padding-bottom: 16px

    .navbar--bottom
        align-items: center
        display: flex
        flex-direction: column
        justify-content: space-between
        width: 100%
        padding-top: 8px

    .icon
        margin-top: 15px
        color: white
</style>