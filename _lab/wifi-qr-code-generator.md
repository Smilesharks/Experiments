---
layout: qr
title: Wifi QR code generator
date: 2022-05-09 19:12 +1200
status: OK
---

<style>
	#qrcode img {
		mix-blend-mode: multiply;
	}
</style>

<div class="relative flex flex-col justify-center min-h-screen py-6 overflow-hidden bg-gray-50 sm:py-12">
	<img src="https://play.tailwindcss.com/img/beams.jpg" alt="" class="absolute -translate-x-1/2 -translate-y-1/2 top-1/2 left-1/2 max-w-none" width="1308" />
<div class="absolute inset-0 bg-[url(https://play.tailwindcss.com/img/grid.svg)] bg-center [mask-image:linear-gradient(180deg,white,rgba(255,255,255,0))]"></div>
<div class="relative px-6 pt-10 pb-8 bg-white shadow-xl ring-1 ring-gray-900/5 sm:mx-auto sm:max-w-lg sm:rounded-lg sm:px-10">
<div class="max-w-md mx-auto space-y-4">
	<h1 class="text-4xl font-bold">Wifi Password QR Code</h1>
	<form class="flex flex-col space-y-4" id="form">
		<div class="grid grid-cols-1 gap-6">
			<div class="grid grid-cols-1 gap-6 print:hidden">
				<label class="block">
					<span class="text-gray-700">SSID:</span>
					<input class="block w-full mt-1" type="text" id="ssid" placeholder="WiFi Name (SSID)">
				</label>
				<label class="block">
					<span class="text-gray-700">Password:</span>
					<input class="block w-full mt-1" id="password" type="password" placeholder="Password">
				</label>
				<label class="block">
					<span class="text-gray-700">Encryption:</span>
					<select class="block w-full mt-1" id="enc">
						<option>WPA</option>
						<option>WEP</option>
					</select>
				</label>
				<label class="block">
					<span class="text-gray-700">Is Hidden?</span>
					<input class="block mt-1" type="checkbox" id="hidden">
				</label>
			</div>
			<span id="qrcode" class="p-2 mx-auto rounded-xl bg-gradient-to-r from-pink-500 via-teal-500 to-purple-500 ">
			</span>
			<div class="print:hidden">
				<div class="flex flex-row space-x-2 ">
				<button id="print" class="inline-flex items-center justify-center px-4 py-2 text-base font-bold text-white transition-all bg-gray-900 border border-gray-600 max-w-fit rounded-xl hover:text-white hover:bg-sitehost-milford hover:border-sitehost-milford group text-md focus:outline-none focus-visible:ring-2 focus-visible:ring-white focus-visible:ring-offset-2" onclick="window.print()">Print</button>
			</div>
			</div>
		</div>
	</form>
</div>
</div>
</div>