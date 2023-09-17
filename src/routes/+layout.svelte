<style>
	@import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;1,100;1,200;1,300;1,400;1,500;1,600;1,700&display=swap');
	.blinker { 
		animation-name: blinker;
		animation-iteration-count: infinite;
		animation-duration: 1s;
	}

	@keyframes blinker { 
		from { opacity: 1.0; } to { opacity: 0.0; }
	}

	t {
		font-family: 'IBM Plex Mono';
		font-size: 22px;
		font-weight: 200;
	}
</style>

<div>
	<t>WELCOME TO JAEHYUNG'S PORTFOLIO!<span class="blinker">_</span></t>
	<br>
	<br>
	<span style="font-family: 'IBM Plex Mono'; font-size:14px; font-weight: 500;">
		SKILLS | PORTFOLIO | CONTACT | GITHUB
	</span>
</div>

<slot></slot>