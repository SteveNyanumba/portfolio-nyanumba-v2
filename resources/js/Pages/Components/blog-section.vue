<template>
<section class="blog section" data-simplebar>
    <div class="container">
        <div class="header-page mt-70">
            <i class="fas fa-receipt icon-page"></i>
              <i class="far fa-times-circle close-page" data-tooltip="close page" data-position="left"></i>
            <h2>Blog</h2>
        </div>

        <!-- Blog Row Start -->
        <div class="row mt-100 mb-50 mob-mt">

            <nos-blog-item/>
            <nos-blog-item/>
            <nos-blog-item/>
            <nos-blog-item/>
            <nos-blog-item/>


        </div>
        <!--Blog Row End-->
    </div>
</section>
</template>

<script>
import NosBlogItem from './sub/BlogItem.vue'
export default {
    components:{
        NosBlogItem
    }
}
</script>
