<template>
    	<!--================ Start Header Area =================-->
	<header class="header_area">
		<div class="main_menu">
			<nav class="navbar navbar-expand-lg">
				<div class="container">
					<!-- Brand and toggle get grouped for better mobile display -->
					<a class="navbar-brand navbar-light logo_h" href="index.html">
                        <img src="../assets/img/mazeko.png" class="thumbnail" style="width: 160px;" alt="">
                    </a>

					<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
					 aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
						<span class="icon-bar"></span>
					</button>
					<!-- Collect the nav links, forms, and other content for toggling -->
					<div class="collapse navbar-collapse offset" id="navbarSupportedContent">
						<ul class="nav navbar-nav menu_nav justify-content-end">
							<li class="nav-item"><router-link to="/" class="nav-link">Home</router-link></li>
							<li class="nav-item"><router-link to="/artikel" class="nav-link">Artikel</router-link></li>
							<li class="nav-item"><router-link to="/tutorial" class="nav-link">Tutorial</router-link></li>
							<li class="nav-item"><a class="nav-link" href="">Service</a></li>
							<li class="nav-item"><a class="nav-link" href="">Contact</a></li>
							<li class="nav-item submenu dropdown">
								<a href="#" class="nav-link dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true"
								 aria-expanded="false">Community</a>
								<ul class="dropdown-menu">
                                    <li class="nav-item">
										<a class="nav-link partial-link" href="">Youtube</a>
									</li>
                                    <li class="nav-item">
										<a class="nav-link partial-link" href="">Github</a>
									</li>
                                  
                                    <li class="nav-item">
										<a class="nav-link partial-link" href="">Instagram</a>
									</li>
									<li class="nav-item">
										<a class="nav-link partial-link" href="">Linkedin</a>
									</li>
								</ul>
							</li>
						</ul>
					</div>
				</div>
			</nav>
		</div>
	</header>
	<!--================ End Header Area =================-->

</template>

<script>
export default {
    name: 'Navbar'
}
</script>