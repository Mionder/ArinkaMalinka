<template>
    <div>
        <Header />
                <section class="tshirt">
		<div class="container">
			<div class="row">
				<div class="col-md-3">
					<div class="tshirt-categories">
						<h6>категорії товарів</h6>
						<hr class="rred">
						<ul class="tshirt-menu">
							<li><a class="tshirt-mainli" href="#">Чоловікам</a>
							<ul class="tshirt-submenu">
								<li><a href="mt-shirt.html">Футболки</a></li>
								<li><a href="#">Худі</a></li>
								<li><a href="#">Штани / Шорти</a></li>
								<li><a href="#">Світшоти</a></li>
								<li><a href="#">Куртки / Дощовики</a></li>
							</ul>
							</li>
							<li><a class="tshirt-mainli" href="#">Жінкам</a>
							<ul class="tshirt-submenu">
								<li><a href="#">Футболки</a></li>
								<li><a href="#">Худі</a></li>
								<li><a href="#">Спорт</a></li>
								<li><a href="#">Світшоти</a></li>
								<li><a href="#">Куртки / Дощовики</a></li>
							</ul>
							</li>
							<li class="tshirt-line"><a class="tshirt-mainli" href="../index2.html">На замовлення</a></li>
						</ul>	
						<div class="tshirt-ne">
							<h6>новинки</h6>
						<hr class="rred">
							<div class="tshirt-new">
									<p><a href="#">Оранж худі <br> HARD Kyivwalls</a> <br><span>1 900.00₴</span></p><img class="season-black" src="../img/man/categories/1.jpg" alt="">
							</div>
							<div class="tshirt-new">
									<p><a href="#">Чорне худі <br>HARD Kyivwalls</a> <br><span>1 900.00₴</span></p><img class="season-black" src="../img/man/categories/2.jpg" alt="">
							</div>
							<div class="tshirt-new">
									<p><a href="#">Худі HARD <br>Pattern (гірчиця)</a><br><span>1 900.00₴</span></p><img class="season-black" src="../img/man/categories/3.jpg" alt="">
							</div>
							<div class="tshirt-new">
									<p><a href="#">Чорне худі <br>HARD Pattern</a> <br><span>1 900.00₴</span></p><img class="season-black" src="../img/man/categories/4.jpg" alt="">
							</div>
						</div>
							<div class="tshirt-ne">
							<h6>SALE!</h6>
						<hr class="rred">
							<div class="tshirt-new">
									<p><a href="#">HARD lampas світшот</a><br><span><del>1500.00₴</del>1300.00₴</span></p><img class="season-black" src="../img/man/categories/5.jpg" alt="">
							</div>
							<div class="tshirt-new">
									<p><a href="#">Футболка HARD <br>Kyivwalls пісок </a><br><span><del>800.00₴</del> 700.00₴</span></p><img class="season-black" src="../img/man/categories/6.jpg" alt="">
							</div>
							<div class="tshirt-new">
									<p><a href="#">Шорти HARD хакі</a><br><span><del>680.00₴</del> 480.00₴</span></p><img class="season-black" src="../img/man/categories/7.jpg" alt="">
							</div>
						</div>
					</div>
				</div>
				<div class="col-md-9">
					<div class="tshirt-goods">
						<h2>Футболки</h2>
						<hr>
						</div>
							<div class="col-md-3 offset-md-7">
								<div class="tshirt-mm">
										<div class="dropdown">
								  <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
									Сортування за замовчуванням
								  </button>
								  <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
									<a class="dropdown-item" href="#">Сортувати за замовчування</a>
									<a class="dropdown-item" href="#">Сортувати за популярністю</a>
									<a class="dropdown-item" href="#">Сортувати за новизною</a>
									<a class="dropdown-item" href="#">Сортувати за ціною: від нижчої до вищої</a>
								  </div>
							   </div>
							   <select v-model="isSort" @change="sortProducts()">
								   <option value="newestProducts">New</option>
								   <option value="upPrice">UpPrice</option>
								   <option value="downPrice">Down</option>
							   </select>
							   <div class="dropdown">
								  <button class="btn btn-secondary dropdown-toggle bb" type="button" id="dropdownMenuButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
									будь-який розмір
								  </button>
								  <div class="dropdown-menu" aria-labelledby="dropdownMenuButton">
									<a class="dropdown-item" href="#">xs</a>
									<a class="dropdown-item" href="#">s</a>
									<a class="dropdown-item" href="#">m</a>
									<a class="dropdown-item" href="#">l</a>
									<a class="dropdown-item" href="#">xl</a>
								  </div>
							   </div>
								</div>
							</div>
						<div class="col-md-12">
								<div class="im sec-goods" id="nahod">
									<div class="slide myslideone"><div class="hoverslide"><img src="../img/man/t-shirt/1-1.jpg" alt=""></div><p>Футболка HARD Kyivwalls пісок</p><span><del>800.00₴</del></span><h6 class="sale">700.00₴</h6><div class="sales"><span class="red">Sale! -13.3%</span><span class="blue">&NEW!</span></div></div>
									<div class="slide myslidetwo"><div class="hoverslide"><img src="../img/man/t-shirt/1-2.jpg" alt=""></div><p>Футболка HARD Kyivwalls чорна</p><span><del>800.00₴ </del></span><h6 class="sale">700.00₴</h6><div class="saless"><span class="red">Sale! -13.3%</span><span class="blue">&NEW!</span></div></div>
									<div class="slide myslidethree"><div class="hoverslide"><img src="../img/man/t-shirt/1-3.jpg" alt=""></div><p>Футболка HARD CHURCH біла</p><span></span><h6 class="sale">600.00₴</h6><div class="salesss"><span class="blue bluesh">&NEW!</span></div></div>
								</div>
						</div>
						<div class="col-md-12">
								<div class="im sec-goods im-goods" id="nahod">
									<div class="slide myslidefour"><div class="hoverslide"><img src="../img/man/t-shirt/1-4.jpg" alt=""></div><p>Футболка HARD Kyivwalls пісок</p><h6 class="sale">600.00₴</h6><div class="sales"><span class="blue bluesh">&NEW!</span></div></div>
									<div class="slide myslidefive"><div class="hoverslide"><img src="../img/man/t-shirt/1-5.jpg" alt=""></div><p>Футболка HARD Kyivwalls чорна</p><span><del>600.00₴ </del></span><h6 class="sale">400.00₴</h6><div class="saless"><span class="red redsh">Sale! -33.3%</span></div></div>
									<div class="slide myslidesix"><div class="hoverslide"><img src="../img/man/t-shirt/1-6.jpg" alt=""></div><p>Футболка HARD CHURCH біла</p><span><del>600.00₴ </del></span><h6 class="sale">200.00₴</h6><div class="salesss"><span class="red redsh">Sale! -66.7%</span></div></div>
								</div>
						</div>
						<div class="col-md-12">
								<div class="im sec-goods im-goods" id="nahod">
									<div class="slide myslideseven"><div class="hoverslide"><img src="../img/man/t-shirt/1-7.jpg" alt=""></div><p>Футболка HARD Kyivwalls пісок</p><span><del>700.00₴</del></span><h6 class="sale">500.00₴</h6><div class="sales"><span class="red redsh">Sale! -28.6%</span></div></div>
									<div class="slide myslidenine"><div class="hoverslide"><img src="../img/man/t-shirt/1-8.jpg" alt=""></div><p>Футболка HARD Kyivwalls чорна</p><span><del>700.00₴ </del></span><h6 class="sale">500.00₴</h6><div class="saless"><span class="red redsh">Sale! -28.6%</span></div></div>
									<div class="slide myslideeight"><div class="hoverslide"><img src="../img/man/t-shirt/1-9.jpg" alt=""></div><p>Футболка HARD CHURCH біла</p><span><del>600.00₴ </del></span><h6 class="sale">400.00₴</h6><div class="salesss"><span class="red redsh">Sale! -33.3%</span></div></div>
								</div>
						</div>	
						<div class="col-md-5 offset-md-3">
							<div class="pages">
								<span><a href="#">1</a></span>
								<span><a href="#">2</a></span>
								<span><a href="#">3</a></span>
								<span><a href="#">&gt;</a></span>
							</div>
						</div>
					</div>
				</div>
			</div>
	</section>
	
									
<div v-for="item in productsList">
										<img :src="item.img" alt="">
										<p>{{item.name}}</p>
										<p>{{item.price}}</p>
										<p>{{item.size}}</p>
										<p v-if="item.saleprice != 0 ">{{item.saleprice}}</p>
									</div>
        <Footer />
    </div>
</template>

<script>
import Vue from 'vue' 
import Vuex from 'vuex'
import axios from 'axios'
import VueAxios from 'vue-axios'
Vue.use(VueAxios, axios)
import Header from './Header.vue'
import Footer from './Footer.vue'
export default {
    components:{
        Header,
        Footer
	},
	data(){
		return{
			productsList : [],
			item: '',
			isSort: 'downPrice'
		}
	},
		mounted: function(){
		Vue.axios.get("http://localhost:3000/tasks").then((popa)=>{
		 this.productsList = popa.data;
		//  this.sortProducts();
		 console.log(this.productsList);
	 })
	},
	function:{
		sortProducts(){
                switch(this.isSort) {
                    // case 'newestProducts' : {this.productsList.sort((a, b) => +a.name < +b.name ? 1 : -1); break;}
                    case 'upPrice' : {this.productsList.sort((a, b) => +a.price > +b.price ? 1 : -1); break;}
                    case 'downPrice' : {this.productsList.sort((a, b) => +a.price < +b.price ? 1 : -1); break;}
                    default : break;
                }
			}
	},

}
</script>