<template>
	<div
		font-sans
		text=" gray-700 dark:gray-200"
		class="box-border h-screen w-full flex flex-col"
	>
		<div class="sticky top-0 z-999"><TheHeader /></div>
		<div class="box-border w-full flex flex-col ">
			<!-- <router-view v-if="$route.meta.keepAlive" v-slot="{ Component }">
				<transition name="move" mode="out-in">
					<keep-alive>
						<component :is="Component"></component>
					</keep-alive>
				</transition>
			</router-view> -->

			<!-- <router-view v-if="!$route.meta.keepAlive" v-slot="{ Component }">
				<transition>
					<component :is="Component" />
				</transition>
			</router-view> -->
			123
		</div>
	</div>
</template>

<style>
.fade-enter-active,
.fade-leave-active {
	transition: opacity 0.25s ease;
}

.fade-enter-from,
.fade-leave-to {
	opacity: 0;
}
</style>
