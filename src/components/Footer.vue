<template>
    <footer class="text-center text-sm">
        <span class="text-white font-bold">Author: ngosangns</span>
        <span class="text-white font-bold">Clone ké by l3mnt2010 :v</span>
         <button class="text-white font-bold bg-green-600 rounded-md" onclick="window.print()">Lưu về PDF</button>
    </footer>
</template>

<style>
	footer {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		padding: 12px;
		width: 100%;
		min-width: 60rem;
	}

	@media (min-width: 480px) {
		footer {
			padding: 12px 0;
		}
	}
</style>
