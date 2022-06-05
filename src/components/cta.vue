<template>
	<div
		class="flex flex-col container mx-auto mt-32 justify-between relative min-h-[400px]"
	>
    	<img
			src="../assets/sm-hero.png"
			alt="hero image"
			class="absolute right-3 -top-24 md:hidden block"
		/>
		<div class="flex flex-col w-full px-6 md:px-0 md:w-fit">
			<p
				class="md:text-6xl text-[40px] max-w-[250px] md:max-w-max font-bold capitalize leading-tight"
			>
				Let’s get you where <br />
				<span class="text-red-500">you need to be</span>
			</p>
			<p class="md:w-[718px] w-[320px] text-base   mt-5 text-[#2D2D2D] md:text-lg leading-tight">
				Buy train tickets easily without needing to leave your home. You can
				either book a single one way ticket or get a return ticket with your
				order.
			</p>

			<div class="flex items-center gap-5 mt-10">
				<label class="flex items-center cursor-pointer select-none">
					<div
						class="box flex items-center justify-center w-5 h-5 rounded border mr-2"
					>
						<span class="bg-[#3B89FF] w-[10px] h-[10px] rounded-sm"></span>
					</div>
					single
				</label>
				<label class="flex items-center cursor-pointer select-none">
					<div
						class="box flex items-center justify-center w-5 h-5 rounded border mr-2"
					>
						<span class="bg-[#fff] w-[10px] h-[10px] rounded-sm"></span>
					</div>
					Return
				</label>
			</div>
            
			<div class="flex flex-wrap items-stretch sha py-8 px-5 mt-5 gap-5 md:w-[860px]">
				<div
					class="bg-[#F1F1F1] px-4 flex items-center py-1.5 w-full cursor-pointer"
				>
					<div>
						<span class="text-xs mt-3 font-light">From ?</span>
						<p>Oyo</p>
					</div>
					<img src="../assets/down.svg" alt="icon" class="ml-auto" />
				</div>
				<div
					class="bg-[#F1F1F1] px-4 flex items-center py-1.5 w-full cursor-pointer"
				>
					<div>
						<span class="text-xs mt-3 font-light">To ?</span>
						<p>Lagos</p>
					</div>
					<img src="../assets/down.svg" alt="icon" class="ml-auto" />
				</div>
				<div
					class="bg-[#F1F1F1] px-4 flex items-center py-1.5 w-full cursor-pointer"
				>
					<div class="flex">
						<img src="../assets/date.svg" alt="icon" class="mr-2" />
						<p>Today</p>
					</div>
					<img src="../assets/down.svg" alt="icon" class="ml-auto" />
				</div>
				<div
					class="bg-[#F1F1F1] px-4 flex items-center py-1.5 w-full cursor-pointer"
				>
					<div class="flex">
						<img src="../assets/user.svg" alt="icon" class="mr-2" />
						<p>1 Adult</p>
					</div>
					<img src="../assets/down.svg" alt="icon" class="ml-auto" />
				</div>
			</div>

			<div class="w-full flex flex-col-reverse md:flex-row gap-3 justify-center md:justify-end mt-8 ">
				<button
					class="text-[#3B89FF] md:border-[#3B89FF] md:border md:text-xl   bg-white text-lg font-medium rounded capitalize px-12 py-4 md:mr-8 mx-auto underline md:no-underline"
				>
					View train schedule
				</button>
				<button
					class="bg-[#3B89FF] md:text-xl text-white font-medium text-lg rounded capitalize md:px-8 px-6 py-4 md:mr-8 mx-auto"
				>
					Find your train
				</button>
			</div>
		</div>

		<img
			src="../assets/hero.png"
			alt="hero image"
			class="absolute -right-20 top-0 hidden md:block"
		/>
	</div>
</template>

<script setup lang="ts"></script>

<style scoped>
.sha {
	background: #fcfcfc;
	box-shadow: 0px 1px 17px rgba(0, 22, 40, 0.15);
}
</style>
