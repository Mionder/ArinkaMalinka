<template>
    <section class="header">
			<div class="container">
				<div class="row">
					<div class="col-md-2">
						<div class="header-logo">
							<a href="index.html"><img class="header-hard" src="img/header/logo.png" alt="Hard Kyiv" title="Головний по жесті - @hardukr - Kyiv streetwear"></a>
						</div>
					</div>
					<div class="col-md-10">
						<div class="header-list">
									<ul class="header-menu topmenu">
							<li><a class="header-menu-nav down" href="#">Чоловікам</a>
								<ul class="submenu">
									<li><router-link v-bind:to="'/productlist'">Футболки</router-link></li>
									<li><a href="#">Худі</a></li>
									<li><a href="#">Штани/Шорти</a></li>
									<li><a href="#">Світшоти</a></li>
									<li><a href="#">Куртки/Дощовики</a></li>
						  		</ul>
						  </li>
							<li><a class="header-menu-nav down" href="#">Жінкам</a>
								<ul class="submenu">
									<li><a href="#">Футболки</a></li>
									<li><a href="#">Худі</a></li>
									<li><a href="#">Спорт</a></li>
									<li><a href="#">Світшоти</a></li>
									<li><a href="#">Куртки/Дощовики</a></li>
						  		</ul>
							</li>
							<li><router-link v-bind:to="'/contacts'">	Контакти</router-link></li>
							<li><a class="header-menu-nav down" href="#">Про нас</a>
							<ul class="submenu">
									<li><router-link v-bind:to="'/production'">Виробництво одягу</router-link></li>
							</ul>
							</li>
							<li><a href="#">+38(096)9688662</a></li>
							<li><a href="#"><img class="header-menu-icon" src="img/header/cardicon.png" alt="card"></a></li>
							<li><form class="header-menu-search"><input type="search" placeholder=""></form></li>
						</ul>		
					</div>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {
    
}
</script>