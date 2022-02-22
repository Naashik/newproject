<template>
    
    
    <div role="main" class="main">
    <section class="page-header page-header-modern bg-color-light-scale-1 page-header-md ">
					<div class="container-fluid">
						<div class="row align-items-center">

							

						</div>
					</div>
				</section>

<div id="examples" class="container py-2">

					<div class="row pb-4 mb-2">
						<div class="col-md-6 mb-4 mb-md-0 appear-animation" data-appear-animation="fadeInLeftShorter" data-appear-animation-delay="300">
						<div class="row">
								
								
				
							<div class="col-lg-3">
										
											<a class="img-thumbnail d-block lightbox" href="../img/products/product56.jpg" data-plugin-options="{'type':'image'}">
												<img class="img-fluid" src="../../static/img/products/product56.jpg" alt="Project Image">
											</a>
										</div>
                                        <div class="col-lg-3">
										
											<a class="img-thumbnail d-block lightbox" href="../img/products/product57.jpg" data-plugin-options="{'type':'image'}">
												<img class="img-fluid" src="../../static/img/products/product57.jpg" alt="Project Image">
											</a>
										</div>
                 
									
						</div>
                        
						
							


						</div>


						<div class="col-md-6">
							<div class="overflow-hidden">
								


								
							<div class="size">	<h2 class="text-color-dark font-weight-normal text-4 mb-0 appear-animation" data-appear-animation="maskUp" data-appear-animation-delay="600"><strong class="font-weight-extra-bold">Laboratory Autoclave </strong></h2></div><br/>
								<h4 class="text-color-dark font-weight-normal text-4 mb-0 appear-animation" data-appear-animation="maskUp" data-appear-animation-delay="600"><strong class="font-weight-extra-bold">Brand - </strong>ALP - Japan</h4>
								<h4 class="text-color-dark font-weight-normal text-4 mb-0 appear-animation" data-appear-animation="maskUp" data-appear-animation-delay="600"><strong class="font-weight-extra-bold">Model - </strong>MC series</h4><br/>
							</div> 

							<h4 class="text-color-dark font-weight-normal text-4 mb-0 appear-animation" data-appear-animation="maskUp" data-appear-animation-delay="600"><strong class="font-weight-extra-bold">Description</strong></h4><b>Robust as a simple structure hard to break</b><br/>
<p>Designed to be "Robust due to a simple structure hard to break"
having with manual lid handles and an operation panel intuitively
easy to operate.</p>

<b>Optimal for sterilizing wastes</b>
<p>The durable and hard-to-brake structure is ideal for sterilizing
wastes.</p>

<b>A wide range of chamber volume 20-120L with space saving</b>

<p>Selectable chamber volume from a wide range depending on an amount of the
load per cycle. Not take up much space due to a vertical structure, even a large
chamber volume.</p>
							<a href="http://alpco.co.jp/en/wp-content/uploads/catalog-mc.pdf" class="btn btn-dark btn-with-arrow mb-2" >more details<span><i class="fas fa-chevron-right"></i></span></a>


							
							
						</div>
					</div>

				</div>
    </div>

</template>
<style scoped>
.size{
	font-size: 20px;

}
</style>
<script>
export default {
mounted(){

if ($.isFunction($.fn['themePluginAnimate']) && $('[data-appear-animation]').length) {
        theme.fn.dynIntObsInit('[data-appear-animation], [data-appear-animation-svg]', 'themePluginAnimate', theme.PluginAnimate.defaults);
    }
if ($.isFunction($.fn['themePluginCarousel']) && $('[data-plugin-carousel]:not(.manual), .owl-carousel:not(.manual)').length) {
        theme.fn.intObsInit('[data-plugin-carousel]:not(.manual), .owl-carousel:not(.manual)', 'themePluginCarousel');
    }
 if ($.isFunction($.fn['themePluginLightbox']) && ($('[data-plugin-lightbox]').length || $('.lightbox').length)) {
        theme.fn.execOnceTroughEvent('[data-plugin-lightbox]:not(.manual), .lightbox:not(.manual)', 'mouseover.trigger.lightbox', function() {
            var $this = $(this),
                opts;
            var pluginOptions = theme.fn.getOptions($this.data('plugin-options'));
            if (pluginOptions)
                opts = pluginOptions;
            $this.themePluginLightbox(opts);
        });
    }
}
}
</script>


