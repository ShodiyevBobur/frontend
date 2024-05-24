<script>
export default {
	data() {
		return {
			message: 'Hello Vuejs dadad',
			name: '',
			count: 0,
			img: 'https://cdn.sanity.io/images/8edntncj/production/7cb22a8a9885468d96662f6ece61ceb2bc95666d-500x300.png',
			users: ['Sardor', 'Vali', 'Jumavoy'],
			user: {
				name: 'Bekzod',
				age: 20,
				counrse: ['vue', 'react', 'angular'],
			},
			groups: [
				{
					number: '1',
					amount: 10,
					pupils: [
						{
							name: 'sardor',
							age: 20,
							job: 'programmer',
						},
						{
							name: 'hojiakbar',
							age: 37,
							job: 'programmer',
						},
						{
							name: 'jumavoy',
							age: 30,
							job: 'programmer',
						},
						{
							name: 'tursunqul',
							age: 24,
							job: 'programmer',
						},
					],
				},
				{
					number: '2',
					amount: 10,
					pupils: [
						{
							name: 'sardor',
							age: 20,
							job: 'programmer',
						},
						{
							name: 'hojiakbar',
							age: 37,
							job: 'programmer',
						},
						{
							name: 'jumavoy',
							age: 30,
							job: 'programmer',
						},
						{
							name: 'tursunqul',
							age: 24,
							job: 'programmer',
						},
					],
					pupils: [
						{
							name: 'sardor',
							age: 20,
							job: 'programmer',
						},
						{
							name: 'hojiakbar',
							age: 37,
							job: 'programmer',
						},
						{
							name: 'jumavoy',
							age: 30,
							job: 'programmer',
						},
						{
							name: 'tursunqul',
							age: 24,
							job: 'programmer',
						},
					],
				},
			],
			img: './assets/first-watch.jpg',
			title: 'Discover Most Suitable Watches',
			array: [1, 2, 3, 4],
			html: `<p>bu html tag</p><button>button</button>`,
			arr: [],
			input: '',
			navItems: [
				{ name: 'Home', href: '#' },
				{ name: 'Brands', href: '#' },
				{ name: 'Recent Products', href: '#' },
				{ name: 'Contact', href: '#' },
				{ name: 'About', href: '#' },
			],
		}
	},
	methods: {
		counter() {
			this.count++
		},
		addName() {
			this.array.push(this.name)
		},
	},
}
</script>
<template>
	<div>
		<header class="bg-[black] mb-[73px]">
			<div
				class="container pt-[23px w-[1100px] bg-[black] m-auto border border-red-500"
			>
				<div class="justify-between flex w-full items-center">
					<div class="flex gap-x-2 bg-[black] items-center">
						<img src="./assets/Apple Watch.png" />
						<p class="text-[white]">Mohid</p>
					</div>
					<div>
						<ul class="flex justify-between gap-x-10 items-center">
							<li><a class="text-[white] text-[16px]">Home</a></li>
							<li>
								<a class="text-[white] text-[16px]">Brands</a>
							</li>
							<li><a class="text-[white] text-[16px]">Recent Products</a></li>
							<li><a class="text-[white] text-[16px]">Contact</a></li>
							<li><a class="text-[white] text-[16px]">About</a></li>
						</ul>
					</div>
					<div
						class="flex justify-center gap-x-4 border border-red-500 bg-[black]"
					>
						<img src="./assets/Search.png" />
						<img src="./assets/Person.png" />
						<img src="./assets/Shopping Cart.png" />
					</div>
				</div>

				<div
					class="flex justify-between gap-x-[183px] items-center mt-[154px] mb-[142px]"
				>
					<div>
						<h1 class="text-[64px] max-w-[460px] text-[white]">
							Discover Most Suitable Watches
						</h1>
						<p class="max-w-[464px] mb-[47px] text-[white]">
							Find the best, reliable, and cheap smart watches here. We focus on
							product quality. Here you can find smart watches of almost all
							brands. So why you are waiting? Just order now!
						</p>

						<div class="rounded-[20px] relative flex items-center">
							<input
								class="bg-[white] w-[443px] py-[10px] outline rounded-lg pl-[40px]"
								placeholder="Find the best brands"
							/>
							<img src="./assets/qidiruv.svg" class="absolute top-3 left-2" />
							<button
								class="bg-[#3858D6] rounded-xl mr-[10px] my-[2px] text-[white] py-[4px] px-[10px] text-[22px] z-20 font-normal absolute right-4"
							>
								Search
							</button>
						</div>
					</div>
					<div>
						<img src="./assets/soat.svg" />
					</div>
				</div>
			</div>
		</header>

		<!-- 3ta soat sectioni -->
		<section>
			<div class="container w-[1100px] m-auto border border-red-500 mb-[135px]">
				<div class="flex gap-x-[20px] items-center ]">
					<div
						class="bg-[#F6F6F6] flex items-center justify-between border pt-[46px] pb-[44px] pl-[41px] pr-[29px] gap-x-[26px] border-red-500 rounded-3xl "
					>
						<img src="./assets/watch.svg" />

						<div class="">
							<h2 class="text-[32px] font-bold">Apple</h2>
							<p class="max-w-44">
								Apple is one of the most famous smart watches providing company.
							</p>
						</div>
					</div>
					<div
						class="bg-[#F6F6F6] flex items-center justify-between border pt-[46px] pb-[44px] pl-[41px] pr-[29px] gap-x-[26px] border-red-500 rounded-3xl"
					>
						<img src="./assets/watch2.svg" />

						<div class="">
							<h2 class="text-[32px] font-bold">Xiaomi</h2>
							<p class="max-w-44">
								Xiaomi smart watches are produced by MI company.
							</p>
						</div>
					</div>
					<div
						class="flex bg-[#F6F6F6] items-center justify-between border pt-[46px] pb-[44px] pl-[41px] pr-[29px] gap-x-[26px] border-red-500 rounded-3xl"
					>
						<img src="./assets/watch.svg" />

						<div class="">
							<h2 class="text-[32px] font-bold">FitBit</h2>
							<p class="max-w-44">
								Apple is one of the most famous smart watches providing company.
							</p>
						</div>
					</div>
				</div>
			</div>
		</section>

		<!-- Prosta ikkita qator teks -->
		<section>
			<div class="container w-[1100px] m-auto border border-red-500 mb-[65px]">
				<p class="text-[16px] font-normal text-[blue] text-center mb-[1px]">
					Find your favourite smart watch.
				</p>
				<h2 class="text-[36px] font-bold text-center mt-[0px]">
					Our Latest Products
				</h2>
			</div>
		</section>

		<!-- 6talik soat hisoblanadi bu yerda -->
		<section>
			<div
				class="container w-[1100px] mx-auto border border-red-500 p-4 mb-[135px]"
			>
				<div class="flex flex-wrap justify-between gap-x-[50px] mb-[69px]">
					<!-- Item 1 -->
					<div
						class="w-[30%] border border-red-500 px-[43px] py-[28px] mb-4 bg-[#F6F6F6]"
					>
						<img src="./assets/image.png" />
						<p class="text-[24px] font-bold text-center mb-[4px]">
							Apple Smart I
						</p>
						<div class="flex gap-x-[4px] items-center justify-center mb-[4px]">
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
						</div>
						<div class="flex gap-x-[4px] items-center justify-center">
							<p><del>450.000</del></p>
							<p>$399.00</p>
						</div>
					</div>
					<!-- Item 2 -->
					<div
						class="w-[30%] border border-red-500 px-[43px] py-[28px] mb-4 bg-[#F6F6F6]"
					>
						<img src="./assets/image.png" />
						<p class="text-[24px] font-bold text-center mb-[4px]">
							Apple Smart I
						</p>
						<div class="flex gap-x-[4px] items-center justify-center mb-[4px]">
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
						</div>
						<div class="flex gap-x-[4px] items-center justify-center">
							<p><del>450.000</del></p>
							<p>$399.00</p>
						</div>
					</div>
					<!-- Item 3 -->
					<div
						class="w-[30%] border border-red-500 px-[43px] py-[28px] mb-4 bg-[#F6F6F6]"
					>
						<img src="./assets/image.png" />
						<p class="text-[24px] font-bold text-center mb-[4px]">
							Apple Smart I
						</p>
						<div class="flex gap-x-[4px] items-center justify-center mb-[4px]">
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
						</div>
						<div class="flex gap-x-[4px] items-center justify-center">
							<p><del>450.000</del></p>
							<p>$399.00</p>
						</div>
					</div>
					<!-- Item 4 -->
					<div
						class="w-[30%] border border-red-500 px-[43px] py-[28px] mb-4 bg-[#F6F6F6]"
					>
						<img src="./assets/image.png" />
						<p class="text-[24px] font-bold text-center mb-[4px]">
							Apple Smart I
						</p>
						<div class="flex gap-x-[4px] items-center justify-center mb-[4px]">
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
						</div>
						<div class="flex gap-x-[4px] items-center justify-center">
							<p><del>450.000</del></p>
							<p>$399.00</p>
						</div>
					</div>
					<!-- Item 5 -->
					<div
						class="w-[30%] border border-red-500 px-[43px] py-[28px] mb-4 bg-[#F6F6F6]"
					>
						<img src="./assets/image.png" />
						<p class="text-[24px] font-bold text-center mb-[4px]">
							Apple Smart I
						</p>
						<div class="flex gap-x-[4px] items-center justify-center mb-[4px]">
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
						</div>
						<div class="flex gap-x-[4px] items-center justify-center">
							<p><del>450.000</del></p>
							<p>$399.00</p>
						</div>
					</div>
					<!-- Item 6 -->
					<div
						class="w-[30%] border border-red-500 px-[43px] py-[28px] mb-4 bg-[#F6F6F6]"
					>
						<img src="./assets/image.png" />
						<p class="text-[24px] font-bold text-center mb-[4px]">
							Apple Smart I
						</p>
						<div class="flex gap-x-[4px] items-center justify-center mb-[4px]">
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
							<img src="./assets/start.svg" />
						</div>
						<div class="flex gap-x-[4px] items-center justify-center">
							<p><del>450.000</del></p>
							<p>$399.00</p>
						</div>
					</div>
				</div>

				<div>
					<button
						class="text-[18px] ml-[450px] rounded-2xl font-semibold text-center py-[10px] px-[55px] bg-[#3858D6] text-[white]"
					>
						View More
					</button>
				</div>
			</div>
		</section>

		<section>
			<div class="container w-[1100px] m-auto mb-[135px]">
				<div class="mb-[55px]">
					<p class="text-[16px] font-medium text-center text-[blue]">
						Here are our some of the best clients.
					</p>
					<h2 class="text-[32px] font-bold text-center">
						What People Say About Us
					</h2>
				</div>

				<div class="flex items-center gap-x-[50px] px-[5px] bg-[#F6F6F6]">
					<div class="part-one py-[30px] px-[50px] flex gap-x-[30px]">
						<div>
							<img src="./assets/child.jpg" />
						</div>
						<div class="">
							<h2 class="text-[24px] font-bold mb-[2px]">Hamza Faizi</h2>
							<p class="max-w-[255px] text-[16px] font-medium mb-[10px]">
								Don’t waste time, just order! This is the best website to
								puschase smart watches.
							</p>
							<div class="flex gap-x-4">
								<img src="./assets/start.svg" />
								<img src="./assets/start.svg" />
								<img src="./assets/start.svg" />
								<img src="./assets/start.svg" />
								<img src="./assets/start.svg" />
							</div>
						</div>
					</div>
					<!-- part-two -->
					<div
						class="part-two py-[30px] pl-[34px] flex gap-x-[30px] bg-[#F6F6F6]"
					>
						<div>
							<img src="./assets/child2.jpg" />
						</div>
						<div>
							<h2 class="text-[24px] font-bold mb-[2px]">Hafiz Huzaifa</h2>
							<p class="max-w-[255px] text-[16px] font-medium mb-[10px]">
								I’ve been purchasing smart watches of Mohid for a long time. All
								the products are good quality.
							</p>
							<div class="flex gap-x-4">
								<img src="./assets/start.svg" />
								<img src="./assets/start.svg" />
								<img src="./assets/start.svg" />
								<img src="./assets/start.svg" />
								<img src="./assets/start.svg" />
							</div>
						</div>
					</div>
				</div>
			</div>
		</section>

		<section>
			<div class="container w-[1100px] m-auto bg-[#F6F6F6] mb-[91px]">
				<div class="flex gap-x-[180px] border">
					<div class="pt-[107px] pl-[107px] relative">
						<h2 class="text-[36px] font-bold mb-[5px]">Subscribe To Newsletter</h2>
						<p class="mb-[13px] text-[16px] text-#8B8E99">Get free guide about smart watches daily. </p>

						<input    class=" w-[443px] rounded-2xl py-[10px]   border border-red-5000  " placeholder="   Enter Email Address">
					   </input>
					   	<button class="py-[8px] px-[30px] text-[16px] bg-[#3858D6]  rounded-2xl  absolute right-2 my-[2px] text-[#fff]" >Subscribe</button>
					</div>
					<div class="pt-[33px] pr-[110px] pb-[44px]">
						<img src="./assets/oxirgi_soat.svg">

					
					</div>
				</div>
			</div>
		</section>


		<section>
			  <div class="container w-[1100px] m-auto bg-[black] mb-[50px]">

				    <p class="text-[16px] text-[white] font-medium text-center py-[10px]">Copyright @ 2022 | Mohid</p>
				  
			  </div>
		</section>

		<!-- <div>
			<input type="text" v-model="name" class="my-class" />
			<button @click="addName" class="my-button">add name</button>
		</div>

		<h1>bek{{ title }}</h1>

		<div></div> -->

		<!-- <h1>{{ message }}</h1>
		<input type="text" v-model="name" />
		<h2>{{ name }}</h2>
		<h2 v-if="name.length > 10">v-if{{ name }}</h2>
		<h2 v-else-if="name.length > 5">v-else-if {{ name }}</h2>
		<h2 v-else>v-else {{ name }}</h2>
		<h3 v-show="name.length">10>v-show {{ name }}</h3>
		<h1 v-once>{{ count }}</h1>
		<button @click="counter">count:{{ count }}</button>
		<ul>
			<template v-for="(item, index) in users" :key="index">
				<li v-if="item != 'Sardor'">{{ item }}{{ index }}</li>
			</template>
		</ul>
		<img v-bind:src="img" alt="" />
		<h1 :class="{ active: name.length > 10 }">Binding class</h1>
		<div v-for="item in users">
			{{ item }}
		</div>
		<a href="" srtyle=""></a> -->
		<!-- <div class="groups">
			<div class="group" v-for="(item, index) in groups" :key="index">
				<h4>Gruh raqami :{{ item.number }}</h4>
				<h4>Oquvchilar soni: {{ item.pupils_count }}</h4>
				<h4>Oquvchilar</h4>
				<ul>
					<li v-for="pupil in item.pupils">
						<p>Ismi:{{ pupil.name }}</p>
						<p>yoshi:{{ pupil.age }}</p>
					</li>
				</ul>
			</div>
		</div> -->
		<!-- <div>
				<input @input="handleInput"enter   type="text" v-model="name"/>
			</div>
			<button @click="addName" class="btn">Button</button>
			<ul>
				<li v-for="x in array">
					<p>Ismi:{{ x }}</p>
				</li>
			</ul>
			<h2>{{ array }}</h2> -->
		<!-- 
		<ul class="text-[red]">
			<li v-for="x in array">
				<p>Ismi:{{ x }}</p>
			</li>
		</ul>
		<h2>{{ array }}</h2> -->
	</div>

	<HelloWorld msg="Vite + Vue" />
</template>
<style scoped>
.my-class {
	margin-top: 50px;
	margin-left: 100px;
	border-radius: 100px;
	border: 1px solid black;
	width: 250px;
}
.my-button {
	margin-left: 15px;
	padding: 15px 10px;
	border-radius: 10px;
	background-color: green;
	border-top-left-radius: 10px;
	color: white;
}

.btn {
	padding: 10px;
	color: blue;
	outline: none;
	background-color: antiquewhite;
}
btn:hover {
	background-color: blue;
	color: white;
}
.groups {
	display: gird;
	gap: 20px;
	grid-template-columns: repeat(3, 400px);
}
.group {
	background-color: white;
	padding: 5px;
	border-radius: 10px;
	border-radius: 10px;
	margin-bottom: 20px;
	color: black;
}
.active {
	font-size: 30px;
	color: red;
}
.logo {
	height: 6em;
	padding: 1.5em;
	will-change: filter;
	transition: filter 300ms;
}
.logo:hover {
	filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
	filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
