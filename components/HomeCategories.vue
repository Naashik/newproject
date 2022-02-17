<template>
    <section class="section-secondary custom-section-padding-2">
        <div class="container">
            <div class="row">
                <div class="col">
                    <h2 class="font-weight-bold text-color-dark mb-3">- Product Categories</h2>
                </div>
            </div>
        </div>
        <div class="owl-carousel categories-carousel show-nav-title custom-both-sides-shadow custom-dots-position-2 custom-dots-style-1 custom-xs-arrows-style-2 mb-0"
            data-plugin-options="{'items': 5, 'loop': false, 'dots': true, 'nav': false}">
            <div>
                <router-link to="/products-and-services#Blood_Bank"  class="text-decoration-none">
                    <span class="thumb-info custom-thumb-info-style-1 thumb-info-hide-wrapper-bg">
                        <span class="thumb-info-wrapper m-0">
                            <img src="/img/demos/business-consulting/cases/category-blood-bank-equipment.jpg" class="img-fluid" alt="">
                        </span>
                        <span class="thumb-info-caption bg-color-secondary p-4 pt-5 pb-5">
                            <span class="custom-thumb-info-title">
                                <span
                                    class="custom-thumb-info-name font-weight-semibold text-color-dark text-4">Blood Bank <br> Equipment</span>
                                <!-- <span class="custom-thumb-info-desc font-weight-light">&nbsp;</span> -->
                            </span>
                            <span class="custom-arrow"></span>
                        </span>
                    </span>
                </router-link>
            </div>
            <div>
                <router-link to="/products-and-services#Laboratory"  class="text-decoration-none">
                    <span class="thumb-info custom-thumb-info-style-1 thumb-info-hide-wrapper-bg">
                        <span class="thumb-info-wrapper m-0">
                            <img src="/img/demos/business-consulting/cases/category-laboratory-equipment.jpg" class="img-fluid" alt="">
                        </span>
                        <span class="thumb-info-caption bg-color-secondary p-4 pt-5 pb-5">
                            <span class="custom-thumb-info-title">
                                <span
                                    class="custom-thumb-info-name font-weight-semibold text-color-dark text-4">Laboratory  <br> Equipment</span>
                                <!-- <span class="custom-thumb-info-desc font-weight-light">&nbsp;</span> -->
                            </span>
                            <span class="custom-arrow"></span>
                        </span>
                    </span>
                </router-link>
            </div>
            <div>
                <router-link to="/products-and-services#Medical" onclick="return false" class="text-decoration-none">
                    <span class="thumb-info custom-thumb-info-style-1 thumb-info-hide-wrapper-bg">
                        <span class="thumb-info-wrapper m-0">
                            <img src="/img/demos/business-consulting/cases/category-medical-equipment.jpg" class="img-fluid" alt="">
                        </span>
                        <span class="thumb-info-caption bg-color-secondary p-4 pt-5 pb-5">
                            <span class="custom-thumb-info-title">
                                <span
                                    class="custom-thumb-info-name font-weight-semibold text-color-dark text-4">Medical  <br> Equipment</span>
                                <!-- <span class="custom-thumb-info-desc font-weight-light">&nbsp;</span> -->
                            </span>
                            <span class="custom-arrow"></span>
                        </span>
                    </span>
                </router-link>
            </div>
            <div>
                <router-link to="/products-and-services#Bio_Technology" onclick="return false" class="text-decoration-none">
                    <span class="thumb-info custom-thumb-info-style-1 thumb-info-hide-wrapper-bg">
                        <span class="thumb-info-wrapper m-0">
                            <img src="/img/demos/business-consulting/cases/category-bio-technology-equipment.jpg" class="img-fluid" alt="">
                        </span>
                        <span class="thumb-info-caption bg-color-secondary p-4 pt-5 pb-5">
                            <span class="custom-thumb-info-title">
                                <span
                                    class="custom-thumb-info-name font-weight-semibold text-color-dark text-4">Bio Technology  <br> Equipment</span>
                                <!-- <span class="custom-thumb-info-desc font-weight-light">&nbsp;</span> -->
                            </span>
                            <span class="custom-arrow"></span>
                        </span>
                    </span>
                </router-link>
            </div>
            <div>
                <router-link to="/products-and-services#Hospital_Furniture" onclick="return false" class="text-decoration-none">
                    <span class="thumb-info custom-thumb-info-style-1 thumb-info-hide-wrapper-bg">
                        <span class="thumb-info-wrapper m-0">
                            <img src="/img/demos/business-consulting/cases/category-hospital-furniture.jpg" class="img-fluid" alt="">
                        </span>
                        <span class="thumb-info-caption bg-color-secondary p-4 pt-5 pb-5">
                            <span class="custom-thumb-info-title">
                                <span
                                    class="custom-thumb-info-name font-weight-semibold text-color-dark text-4">Hospital <br> Furniture</span>
                                <!-- <span class="custom-thumb-info-desc font-weight-light">&nbsp;</span> -->
                            </span>
                            <span class="custom-arrow"></span>
                        </span>
                    </span>
                </router-link>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    mounted() {
        if ($.isFunction($.fn['themePluginCarousel']) && $('[data-plugin-carousel]:not(.manual), .categories-carousel:not(.manual)').length) {
            theme.fn.intObsInit('[data-plugin-carousel]:not(.manual), .categories-carousel:not(.manual)', 'themePluginCarousel');
        }
        
        
        
    }
}
</script>