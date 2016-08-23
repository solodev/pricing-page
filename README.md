# pricing-page
Selling products and services online requires an intuitive and informative pricing page that gets across the benefits, pricing, and value that each of your plans provide in a clear and concise design. 

## Tutorial

For detailed instructions, view Solodev's [Creating a Pricing Page That Sells](https://www.solodev.com/blog/web-design/designing-a-pricing-page-that-sells.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/0z8Lwhpu/).

## HTML

The pricing page contains the following basic HTML markup.

```
<section class="company-heading intro-type" id="parallax-one">
                    <div class="container">
                        <div class="row product-title-info">
                            <div class="col-md-12">
                                <h1>
                                    WEBCORPCO<br>
                                    DECIDE WITH DATA
                                </h1>
                            </div>
                        </div>
                    </div>
                    <div class="parallax" id="parallax-cta" style="background-image:url(images/company-hero-1.jpg);">
                        &nbsp;
                    </div>
                </section>
<div class="container">
<div class="pricing-table row">
		<div class="col-sm-4 pricing-container">
			<div class="pricing-table-item">
				<h2 class="item-header">Personal</h2>
				<div class="item-cta-block" style="height: 213px;">
					<div id="js__block-price" class="block-price currency-container" style="display: inline-block;" data-country="usd">$1,000</div>
					<div class="block-sub-text"><div id="js__block-price" class="currency-container" style="display: none;" data-country="cad">USD</div> Per Month</div>

					<div class="pricing-toggle-holder">
						<button class="pricing-toggle">
							<span class="pricing-toggle-open">See Standard Features <span class="glyphicon glyphicon-plus"></span></span>
							<span class="pricing-toggle-close">Hide Standard Features <span class="glyphicon glyphicon-minus"></span></span>
						</button>
					</div> <!-- /.pricing-toggle-holder -->

					<a class="button orange-button outbound" href="" target="_blank">View Demo<span class="glyphicon glyphicon-menu-right"></span></a>
				</div>
				<div class="item-details-block" style="height: 525px;">
					<div class="plus-header">Includes the following features:</div>
					<div class="separator"></div>
					<ul>
						<li><i class="fa fa-check" aria-hidden="true"></i> Proin placerat justo vitae</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Sed vehicula dolor vitae felis</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Curabitur at arcu ullamcorper</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Nulla ut mauris malesuada</li>
						<li>Nam pharetra ante et dictum</li>
						<li>Vivamus at elit et purus</li>
                        <li>Proin scelerisque risus</li>
                        <li>Mauris et justo ac quam feugiat</li>
						<li>Donec at eros vitae orci pulvinar</li>
					</ul>
				</div>
			</div>
		</div>
		<div class="col-sm-4 pricing-container">
			<div class="pricing-table-item">
				<h2 class="item-header">Pro</h2>
				<div class="item-cta-block" style="height: 213px;">
					<div id="js__block-price" class="block-price currency-container" style="display: inline-block;" data-country="usd">$2,000</div>
					<div class="block-sub-text"><div id="js__block-price" class="currency-container" style="display: none;" data-country="cad">USD</div> Per Month</div>

					<div class="pricing-toggle-holder">
						<button class="pricing-toggle">
							<span class="pricing-toggle-open">See Pro Features <span class="glyphicon glyphicon-plus"></span></span>
							<span class="pricing-toggle-close">Hide Pro Features <span class="glyphicon glyphicon-minus"></span></span>
						</button>
					</div> <!-- /.pricing-toggle-holder -->

					<a class="button orange-button outbound" href="" target="_blank">View Demo<span class="glyphicon glyphicon-menu-right"></span></a>
				</div>
				<div class="item-details-block" style="height: 525px;">
					<div class="plus-header">Includes the following features:</div>
					<div class="separator"></div>
					<ul>
						<li><i class="fa fa-check" aria-hidden="true"></i> Proin placerat justo vitae</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Sed vehicula dolor vitae felis</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Curabitur at arcu ullamcorper</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Nulla ut mauris malesuada</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Nam pharetra ante et dictum</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Vivamus at elit et purus</li>
                        <li>Proin scelerisque risus</li>
                        <li>Mauris et justo ac quam feugiat</li>
						<li>Donec at eros vitae orci pulvinar</li>
					</ul>
				</div>
			</div>
		</div>
		<div class="col-sm-4 pricing-container">
			<div class="pricing-table-item">
				<h2 class="item-header">Enterprise</h2>
				<div class="item-cta-block" style="height: 213px;">
					<div id="js__block-price" class="block-price currency-container" style="display: inline-block;" data-country="usd">$3,000</div>
					<div class="block-sub-text"><div id="js__block-price" class="currency-container" style="display: none;" data-country="cad">USD</div> Per Month</div>

					<div class="pricing-toggle-holder">
						<button class="pricing-toggle">
							<span class="pricing-toggle-open">See Ultimate Features <span class="glyphicon glyphicon-plus"></span></span>
							<span class="pricing-toggle-close">Hide Ultimate Features <span class="glyphicon glyphicon-minus"></span></span>
						</button>
					</div> <!-- /.pricing-toggle-holder -->

					<a class="button orange-button outbound" href="" target="_blank">View Demo<span class="glyphicon glyphicon-menu-right"></span></a>
				</div>
				<div class="item-details-block" style="height: 525px;">
					<div class="plus-header">Includes the following features:</div>
					<div class="separator"></div>
					<ul>
						<li><i class="fa fa-check" aria-hidden="true"></i> Proin placerat justo vitae</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Sed vehicula dolor vitae felis</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Curabitur at arcu ullamcorper</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Nulla ut mauris malesuada</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Nam pharetra ante et dictum</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Vivamus at elit et purus</li>
                        <li><i class="fa fa-check" aria-hidden="true"></i> Proin scelerisque risus</li>
                        <li><i class="fa fa-check" aria-hidden="true"></i> Mauris et justo ac quam feugiat</li>
						<li><i class="fa fa-check" aria-hidden="true"></i> Donec at eros vitae orci pulvinar</li>
					</ul>
				</div>
			</div>
		</div>
	</div>
</div>

```
## CSS

All necessary CSS is in pricing.css

## External Includes

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.6.3/css/font-awesome.min.css" rel="stylesheet">
<link href="pricing.css" rel="stylesheet">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
```
