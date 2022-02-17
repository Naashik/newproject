<template>

    <header id="header" class="header-transparent header-transparent-dark-bottom-border header-effect-shrink"
			data-plugin-options="{'stickyEnabled': true, 'stickyEffect': 'shrink', 'stickyEnableOnBoxed': true, 'stickyEnableOnMobile': true, 'stickyChangeLogo': true, 'stickyStartAt': 30, 'stickyHeaderContainerHeight': 70}">
     <div class="header-body border-top-0 bg-dark box-shadow-none">
            <div class="header-container container">
                <div class="header-row">
                    <div class="header-column">
                        <div class="header-row">
                            <div class="header-logo">
                                <router-link to="/">
                                    <img alt="Porto" width="82" height="auto"
                                        src="/img/logo-default-slim-dark-small.png">
                                </router-link>
                            </div>
                        </div>
                    </div>
                    <div class="header-column justify-content-end">
                        <div class="header-row">
                            <div
                                class="header-nav header-nav-links header-nav-dropdowns-dark header-nav-light-text order-2 order-lg-1">
                                <div 
                                    class="header-nav-main header-nav-main-mobile-dark header-nav-main-square header-nav-main-dropdown-no-borders header-nav-main-effect-2 header-nav-main-sub-effect-1">
                                    <nav class="collapse">
                                    
                                        <ul class="nav nav-pills" id="mainNav">
                                            <li class="nav-item">
                                                <router-link to="/" exact  class="nav-link" >Home</router-link>
                                            </li>
                                            <li class="nav-item">
                                                  <router-link to="/products-and-services"  class="nav-link" > Products & Services</router-link>
                                            </li>
                                            <li class="nav-item">
                                                <router-link to="/our-projects" exact class="nav-link"> Our Projects</router-link>
                                            </li>
                                            <li class="nav-item"> 
                                                 <router-link to="#" exact class="nav-link"> News</router-link>
                                            </li>
                                            <li class="nav-item">                                             
                                                <router-link to="/about-us"  class="nav-link">About Us</router-link>
                                            </li>
                                        </ul>
                                      
                                    </nav>
                                </div>
                                <button class="btn header-btn-collapse-nav" data-toggle="collapse"
                                    data-target=".header-nav-main nav">
                                    <i class="fas fa-bars"></i>
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>

</template>


<script>
import FixedHeader from './FixedHeader.vue';
export default {
  components: { FixedHeader },
    mounted() {
        if (typeof theme.StickyHeader !== 'undefined') {
            theme.StickyHeader.initialize();
        }
        if (typeof theme.Nav !== 'undefined') {
            theme.Nav.initialize();
        }
        if (typeof theme.Search !== 'undefined' && ($('#searchForm').length || $('.header-nav-features-search-reveal').length)) {
            theme.Search.initialize();
        }
        if (typeof theme.Newsletter !== 'undefined' && $('#newsletterForm').length) {
            theme.fn.intObs('#newsletterForm', 'theme.Newsletter.initialize();', {});
        }
        if (typeof theme.Account !== 'undefined' && ($('#headerAccount').length || $('#headerSignUp').length || $('#headerSignIn').length || $('#headerRecover').length || $('#headerRecoverCancel').length)) {
            theme.Account.initialize();
        }

        if ($.isFunction($.fn['themePluginSticky']) && $('[data-plugin-sticky]').length) {
            theme.fn.execOnceTroughWindowEvent(window, 'scroll.trigger.sticky', function() {
                $('[data-plugin-sticky]:not(.manual)').each(function() {
                    var $this = $(this),
                        opts;
                    var pluginOptions = theme.fn.getOptions($this.data('plugin-options'));
                    if (pluginOptions)
                        opts = pluginOptions;
                    $this.themePluginSticky(opts);
                });
            });
        }
        
    }
}
</script>
<style scoped>
a.active{
    color: #000;

}
</style>