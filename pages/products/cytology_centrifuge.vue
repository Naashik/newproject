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
										
											<a class="img-thumbnail d-block lightbox" href="../img/products/product18.jpg" data-plugin-options="{'type':'image'}">
												<img class="img-fluid" src="../../static/img/products/product18.jpg" alt="Project Image">
											</a>
										</div>
									<div class="col-lg-3">
										
											<a class="img-thumbnail d-block lightbox" href="../img/products/product19.jpg" data-plugin-options="{'type':'image'}">
												<img class="img-fluid" src="../../static/img/products/product19.jpg" alt="Project Image">
											</a>
										</div>
											

						</div>
						<div class="row">
							<div class="col-lg-3">
										
											<a class="img-thumbnail d-block lightbox" href="../img/products/product20.jpg" data-plugin-options="{'type':'image'}">
												<img class="img-fluid" src="../../static/img/products/product20.jpg" alt="Project Image">
											</a>
										</div>
							<div class="col-lg-3">
										
											<a class="img-thumbnail d-block lightbox" href="../img/products/product21.jpg" data-plugin-options="{'type':'image'}">
												<img class="img-fluid" src="../../static/img/products/product21.jpg" alt="Project Image">
											</a>
										</div>
											
						</div>
						
							


						</div>


						<div class="col-md-6">
							<div class="overflow-hidden">
								


								
							<div class="size">	<h2 class="text-color-dark font-weight-normal text-4 mb-0 appear-animation" data-appear-animation="maskUp" data-appear-animation-delay="600"><strong class="font-weight-extra-bold">Cytology Centrifuge</strong></h2></div><br/>
								<h4 class="text-color-dark font-weight-normal text-4 mb-0 appear-animation" data-appear-animation="maskUp" data-appear-animation-delay="600"><strong class="font-weight-extra-bold">Brand - </strong>Centurion - UK</h4>
								<h4 class="text-color-dark font-weight-normal text-4 mb-0 appear-animation" data-appear-animation="maskUp" data-appear-animation-delay="600"><strong class="font-weight-extra-bold">Model - </strong>PrO-Cyt.LED4, PrO-Cyt.LED8 , PrO-Cyt.LED12</h4><br/>
							</div> 

							<h4 class="text-color-dark font-weight-normal text-4 mb-0 appear-animation" data-appear-animation="maskUp" data-appear-animation-delay="600"><strong class="font-weight-extra-bold">Description</strong></h4><p class="appear-animation" data-appear-animation="fadeInUpShorter" data-appear-animation-delay="800">Our PrO-Cyt range are compact and practical centrifuges for small , medium and large sample volumes. Unlike others we offer you a choice of two Centrifuges and each can use one of three rotors, from 4, 8 and 12 places, thus meeting your needs exactly.</p>
							<a href="https://pro-cytologycentrifuge.com/?_ga=2.134442161.1587819406.1640861437-1413944015.1640861437" class="btn btn-dark btn-with-arrow mb-2" >more details<span><i class="fas fa-chevron-right"></i></span></a>
							
							
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


