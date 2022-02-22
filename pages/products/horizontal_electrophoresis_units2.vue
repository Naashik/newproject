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
										
											<a class="img-thumbnail d-block lightbox" href="../img/products/product65.jpg" data-plugin-options="{'type':'image'}">
												<img class="img-fluid" src="../../static/img/products/product65.jpg" alt="Project Image">
											</a>
										</div>
                                       
									
						</div>
						
							


						</div>


						<div class="col-md-6">
							<div class="overflow-hidden">
								


								
							<div class="size">	<h2 class="text-color-dark font-weight-normal text-4 mb-0 appear-animation" data-appear-animation="maskUp" data-appear-animation-delay="600"><strong class="font-weight-extra-bold">Horizontal Electrophoresis Units</strong></h2></div><br/>
								<h4 class="text-color-dark font-weight-normal text-4 mb-0 appear-animation" data-appear-animation="maskUp" data-appear-animation-delay="600"><strong class="font-weight-extra-bold">Brand - </strong>CONSORT </h4>
								<h4 class="text-color-dark font-weight-normal text-4 mb-0 appear-animation" data-appear-animation="maskUp" data-appear-animation-delay="600"><strong class="font-weight-extra-bold">Model - </strong>EHS1000 series</h4><br/>
							</div> 

							<h4 class="text-color-dark font-weight-normal text-4 mb-0 appear-animation" data-appear-animation="maskUp" data-appear-animation-delay="600"><strong class="font-weight-extra-bold">Description</strong></h4><p class="appear-animation" data-appear-animation="fadeInUpShorter" data-appear-animation-delay="800">Low cost : Injection moulded construction, Durable, leak-proof environment for complete safety and long life. Cassette type electrodes. Inexpensive, easy to replace. Made of 99.99% corrosion resistant, pure platinum. Multiple gel trays :  Gel size and sample number requirements can be exactly matched in each unit, with the option of additional gel tray sizes. This eliminates the need for multiple gel tanks for changes in gel size or application. With no indentations or casting gate grooves in the tray to interfere with sample progression, traditional tape casting can be used, should this be preferred. Easy to use : Leak proof “Plug and Go” casting dams allow gels to be rapidly cast externally while the tank remains in use for electrophoresis.
</p>
							<a href="https://consort.be/product-range/electrophoresis/elektrophoresis-tanks/horizontal/ehs1000-series/" class="btn btn-dark btn-with-arrow mb-2" >more details<span><i class="fas fa-chevron-right"></i></span></a>
							
							
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


