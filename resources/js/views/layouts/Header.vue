<template>
	<header class="header shop">
		<!-- Topbar -->
		<div class="topbar">
			<div class="container">
				<div class="row">
					<div class="col-lg-5 col-md-12 col-12">
						<!-- Top Left -->
						<div class="top-left">
							<ul class="list-main">
								<li><i class="ti-headphone-alt"></i> +060 (800) 801-582</li>
								<li><i class="ti-email"></i> support@shophub.com</li>
							</ul>
						</div>
						<!--/ End Top Left -->
					</div>
					<div class="col-lg-7 col-md-12 col-12">
						<!-- Top Right -->
						<div class="right-content">
							<ul class="list-main">
								<li><i class="ti-location-pin"></i> Store location</li>
								<li><i class="ti-alarm-clock"></i> <a href="#">Daily deal</a></li>
								<li><i class="ti-user"></i><router-link to="/account">My account</router-link></li>
								<li><i class="ti-power-off"></i><router-link to="/login">Login</router-link></li>
							</ul>
						</div>
						<!-- End Top Right -->
					</div>
				</div>
			</div>
		</div>
		<!-- End Topbar -->
		<div class="middle-inner">
			<div class="container">
				<div class="row">
					<div class="col-lg-2 col-md-2 col-12">
						<!-- Logo -->
						<div class="logo">
							<router-link to="/">
								<img src="images/logo/1.jpg" alt="logo">
							</router-link>
							<!-- <a href="index.html"><img src="images/logo.png" alt="logo"></a> -->
						</div>
						<!--/ End Logo -->
						<!-- Search Form -->
						<div class="search-top">
							<div class="top-search"><a href="#0"><i class="ti-search"></i></a></div>
							<!-- Search Form -->
							<div class="search-top">
								<form class="search-form">
									<input type="text" placeholder="Search here..." name="search">
									<button value="search" type="submit"><i class="ti-search"></i></button>
								</form>
							</div>
							<!--/ End Search Form -->
						</div>
						<!--/ End Search Form -->
						<div class="mobile-nav"></div>
					</div>
					<div class="col-lg-8 col-md-7 col-12">
						<div class="search-bar-top">
							<div class="search-bar">
								<select>
									<option selected="selected">All Category</option>
									<option>watch</option>
									<option>mobile</option>
									<option>kid’s item</option>
								</select>
								<form>
									<input name="search" placeholder="Search Products Here....." type="search">
									<button class="btnn"><i class="ti-search"></i></button>
								</form>
							</div>
						</div>
					</div>
					<div class="col-lg-2 col-md-3 col-12">
						<div class="right-bar">
							<!-- Search Form -->
							<div class="sinlge-bar">
								<a href="#" class="single-icon"><i class="fa fa-heart-o" aria-hidden="true"></i></a>
							</div>
							<div class="sinlge-bar">
								<a href="#" class="single-icon"><i class="fa fa-user-circle-o" aria-hidden="true"></i></a>
							</div>
							<div class="sinlge-bar shopping">
								<a href="#" class="single-icon"><i class="ti-bag"></i> <span class="total-count">2</span></a>
								<!-- Shopping Item -->
								<div class="shopping-item">
									<div class="dropdown-cart-header">
										<span>2 Items</span>
										<router-link to="/cart">View Cart</router-link>
									</div>
									<ul class="shopping-list">
										<li>
											<a href="#" class="remove" title="Remove this item"><i class="fa fa-remove"></i></a>
											<router-link to="/product-detail" class="cart-img">
												<img src="images/100x100/1.jpg" alt="product cart 1">
											</router-link>
											<h4><a href="#">Woman Ring</a></h4>
											<p class="quantity">1x - <span class="amount">$99.00</span></p>
										</li>
										<li>
											<a href="#" class="remove" title="Remove this item"><i class="fa fa-remove"></i></a>
											<router-link to="/product-detail" class="cart-img">
												<img src="images/100x100/2.jpg" alt="product cart 2">
											</router-link>
											<h4><a href="#">Woman Necklace</a></h4>
											<p class="quantity">1x - <span class="amount">$35.00</span></p>
										</li>
									</ul>
									<div class="bottom">
										<div class="total">
											<span>Total</span>
											<span class="total-amount">$134.00</span>
										</div>
										<router-link to="/checkout" class="btn animate">Checkout</router-link>
										<!-- <a href="checkout.html" class="btn animate">Checkout</a> -->
									</div>
								</div>
								<!--/ End Shopping Item -->
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- Header Inner -->
		<div class="header-inner">
			<div class="container">
				<div class="cat-nav-head">
					<div class="row">
						<div class="col-12">
							<div class="menu-area">
								<!-- Main Menu -->
								<nav class="navbar navbar-expand-lg">
									<div class="navbar-collapse">	
										<div class="nav-inner">	
											<ul class="nav main-menu menu navbar-nav">
												<li class="active"><router-link to="/">Home</router-link></li>
												<li><router-link to="/product">Product</router-link></li>
												<li><a href="#">Service<i class="ti-angle-down"></i></a>
													<ul class="dropdown">
														<li><router-link to="/contact">Contact Us</router-link></li>
													</ul>
												</li>
												<li><a href="#">Shop<i class="ti-angle-down"></i><span class="new">New</span></a>
													<ul class="dropdown">
														<li><router-link class="d-flex justify-content-between" to="/cart">Cart <span class="badge badge-primary d-flex align-items-center">24</span></router-link></li>
														<li><router-link to="/checkout">Checkout</router-link></li>
													</ul>
												</li>
												<!-- <li><a href="#">Pages</a></li> -->
												<li><a href="#">Blog<i class="ti-angle-down"></i></a>
													<ul class="dropdown">
														<li><router-link to="/blog">Blog Single Sidebar</router-link></li>
														<!-- <li><a href="blog-single-sidebar.html">Blog Single Sidebar</a></li> -->
													</ul>
												</li>
												<!-- <li><router-link to="/contact">Contact Us</router-link></li> -->
												<!-- <li><a href="contact.html">Contact Us</a></li> -->
											</ul>
										</div>
									</div>
								</nav>
								<!--/ End Main Menu -->	
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!--/ End Header Inner -->
	</header>
</template>

<script>
export default {

}
</script>

<style scoped>
	.menu-area ul.navbar-nav li a{
		color: black;
		/* color:red */
	}
</style>