<template>
	<div class="background">
		<div class="cloud1" id="movement1">
			<div class="cloud-middle"></div>
			<div class="cloud-spire1"></div>
			<div class="cloud-spire2"></div>
			<div class="cloud-spire3"></div>
			<div class="cloud-spire4"></div>
			<div class="cloud-spire5"></div>
			<div class="cloud-spire6"></div>
			<div class="cloud-spire7"></div>
			<div class="cloud-spire8"></div>
			<div class="cloud-spire9"></div>
			<div class="cloud-spire10"></div>
		</div>

		<div class="cloud2" id="movement2">
			<div class="cloud-middle"></div>
			<div class="cloud-spire1"></div>
			<div class="cloud-spire2"></div>
			<div class="cloud-spire3"></div>
			<div class="cloud-spire4"></div>
			<div class="cloud-spire5"></div>
			<div class="cloud-spire6"></div>
			<div class="cloud-spire7"></div>
			<div class="cloud-spire8"></div>
			<div class="cloud-spire9"></div>
			<div class="cloud-spire10"></div>
		</div>

		<div class="cloud3" id="movement3">
			<div class="cloud-middle"></div>
			<div class="cloud-spire1"></div>
			<div class="cloud-spire2"></div>
			<div class="cloud-spire3"></div>
			<div class="cloud-spire4"></div>
			<div class="cloud-spire5"></div>
			<div class="cloud-spire6"></div>
			<div class="cloud-spire7"></div>
			<div class="cloud-spire8"></div>
			<div class="cloud-spire9"></div>
			<div class="cloud-spire10"></div>
		</div>

		<div class="cloud4" id="movement4">
			<div class="cloud-middle"></div>
			<div class="cloud-spire1"></div>
			<div class="cloud-spire2"></div>
			<div class="cloud-spire3"></div>
			<div class="cloud-spire4"></div>
			<div class="cloud-spire5"></div>
			<div class="cloud-spire6"></div>
			<div class="cloud-spire7"></div>
			<div class="cloud-spire8"></div>
			<div class="cloud-spire9"></div>
			<div class="cloud-spire10"></div>
		</div>

		<div class="cloud5" id="movement5">
			<div class="cloud-middle"></div>
			<div class="cloud-spire1"></div>
			<div class="cloud-spire2"></div>
			<div class="cloud-spire3"></div>
			<div class="cloud-spire4"></div>
			<div class="cloud-spire5"></div>
			<div class="cloud-spire6"></div>
			<div class="cloud-spire7"></div>
			<div class="cloud-spire8"></div>
			<div class="cloud-spire9"></div>
			<div class="cloud-spire10"></div>
		</div>

		<div class="balloon">
			<div class="balloon-top"></div>
			<div class="balloon-bottom"></div>
			<div class="balloon-left"></div>
			<div class="balloon-right"></div>
			<div class="balloon-tie"></div>
			<div class="balloon-string"></div>
			<div class="balloon-highlight">
				<div class="highlight-circle"></div>
				<div class="highlight-cover"></div>
			</div>
		</div>

		<div class="quote">
			<p class="line-1">"... always</p>
			<p class="line-2">remember:</p>
			<p class="line-3">you are</p>
			<p class="line-4">braver</p>
			<p class="line-5">than you believe,</p>
			<p class="line-6">stronger</p>
			<p class="line-7">than you seem,</p>
			<p class="line-8">& smarter</p>
			<p class="line-9">than you</p>
			<p class="line-10">think."</p>
			<p class="line-11">Christopher Robin</p>
		</div>
	</div>
</template>

<script>
	export default {

	}
</script>

<style scoped>
	.background {
		position: relative;
		margin: auto;
		display: block;
		width: 800px;
		height: 950px;
		background: #b1ecff;
	}

	.cloud1 {
		position: absolute;
		top: 6%;
		left: 8%;
		width: 38%;
		height: 33%;
	}

	#movement1 {
		animation-name: firstCloud;
		animation-duration: 120s;
		animation-iteration-count: infinite;
		animation-timing-function: ease-in;
		animation-delay: 2s;
	}

	@keyframes firstCloud {
		0% {
			left: 8%;
		}
		25% {
			left: 100%;
		}
		50% {
			left: -25%;
		}
		100% {
			left: 8%;
		}
	}

	.cloud2 {
		position: absolute;
		top: 18%;
		left: 80%;
		width: 12%;
		height: 10%;
	}

	#movement2 {
		animation-name: secondCloud;
		animation-duration: 60s;
		animation-iteration-count: infinite;
		animation-timing-function: ease-in;
	}

	@keyframes secondCloud {
		0% {
			left: 80%;
		}
		25% {
			left: 100%;
		}
		50% {
			left: -15%;
		}
		100% {
			left: 80%;
		}
	}

	.cloud3 {
		position: absolute;
		top: 65%;
		left: 10%;
		width: 25%;
		height: 23%;
	}

	#movement3 {
		animation-name: thirdCloud;
		animation-duration: 105s;
		animation-iteration-count: infinite;
		animation-timing-function: ease-in;
		animation-delay: 3s;
	}

	@keyframes thirdCloud {
		0% {
			left: 10%;
		}
		25% {
			left: 100%;
		}
		50% {
			left: -25%;
		}
		100% {
			left: 10%;
		}
	}

	.cloud4 {
		position: absolute;
		top: 81%;
		left: 20%;
		width: 29%;
		height: 27%;
	}

	#movement4 {
		animation-name: fourthCloud;
		animation-duration: 120s;
		animation-iteration-count: infinite;
		animation-timing-function: ease-in;
		animation-delay: 4s;
	}

	@keyframes fourthCloud {
		0% {
			left: 20%;
		}
		25% {
			left: 100%;
		}
		50% {
			left: -25%;
		}
		100% {
			left: 20%;
		}
	}

	.cloud5 {
		position: absolute;
		top: 74%;
		left: 53%;
		width: 46%;
		height: 35%;
	}

	#movement5 {
		animation-name: fifthCloud;
		animation-duration: 90s;
		animation-iteration-count: infinite;
		animation-timing-function: linear;
	}

	@keyframes fifthCloud {
		0% {
			left: 53%;
		}
		25% {
			left: 100%;
		}
		50% {
			left: -50%;
		}
		100% {
			left: 53%;
		}
	}

	.cloud-middle {
		position: absolute;
		top: 8%;
		left: 8%;
		width: 65%;
		height: 45%;
		background: white;
		border-radius: 50%;
	}

	.cloud-spire1 {
		position: absolute;
		top: 1%;
		left: 9%;
		width: 27%;
		height: 18%;
		background: white;
		border-radius: 50%;
	}

	.cloud-spire2 {
		position: absolute;
		top: -2%;
		left: 33%;
		width: 25%;
		height: 20%;
		background: white;
		border-radius: 50%;
	}

	.cloud-spire3 {
		position: absolute;
		top: 5%;
		left: 54%;
		width: 23%;
		height: 20%;
		background: white;
		border-radius: 50%;
	}

	.cloud-spire4 {
		position: absolute;
		top: 19%;
		left: 61%;
		width: 23%;
		height: 17%;
		background: white;
		border-radius: 50%;
	}	

	.cloud-spire5 {
		position: absolute;
		top: 34%;
		left: 57%;
		width: 23%;
		height: 15%;
		background: white;
		border-radius: 50%;
	}	

	.cloud-spire6 {
		position: absolute;
		top: 40%;
		left: 46%;
		width: 22%;
		height: 18%;
		background: white;
		border-radius: 50%;
	}

	.cloud-spire7 {
		position: absolute;
		top: 41%;
		left: 31%;
		width: 17%;
		height: 18%;
		background: white;
		border-radius: 50%;
	}

	.cloud-spire8 {
		position: absolute;
		top: 39%;
		left: 12%;
		width: 23%;
		height: 18%;
		background: white;
		border-radius: 50%;
	}

	.cloud-spire9 {
		position: absolute;
		top: 29%;
		left: 1%;
		width: 23%;
		height: 18%;
		background: white;
		border-radius: 50%;
	}

	.cloud-spire10 {
		position: absolute;
		top: 14%;
		left: -2%;
		width: 23%;
		height: 18%;
		background: white;
		border-radius: 50%;
	}

	.balloon {
		position: absolute;
		top: 5%;
		left: 9%;
		width: 80%;
		height: 71%;
		transform: rotate(5deg);
	}

	.balloon-top {
		position: absolute;
		width: 98%;
		height: 83%;
		background: #ff5656;
		border-radius: 50%;
		transform: rotate(-5deg);
	}

	.balloon-bottom {
		position: absolute;
		top: 43%;
		left: 2%;
		width: 100%;
		height: 75%;
		background: #ff5656;
		-webkit-clip-path: polygon(90% 0, 0 15%, 66% 83%);
		clip-path: polygon(90% 0, 0 15%, 66% 83%);
	}

	.balloon-left {
		position: absolute;
		top: 50%;
		left: 32%;
		width: 10%;
		height: 70%;
		background: #ff5656;
		border-radius: 50%;
		transform: rotate(-52deg);
	}

	.balloon-right {
		position: absolute;
		top: 42%;
		right: 14%;
		width: 10%;
		height: 68%;
		background: #ff5656;
		border-radius: 50%;
		transform: rotate(26deg);
	}

	.balloon-tie {
		position: absolute;
		top: 101%;
		left: 63%;
		width: 5%;
		height: 8%;
		background: #ff5656;
		-webkit-clip-path: polygon(51% 9%, 0% 100%, 100% 100%);
		clip-path: polygon(51% 9%, 0% 100%, 100% 100%);
		transform: rotate(-16deg);
	}

	.balloon-highlight {
		position: absolute;
		width: 100%;
		height: 100%;
	}

	.highlight-circle {
		position: absolute;
		left: 4%;
		top: 3%;
		width: 85%;
		height: 75%;
		background: #fe7b7b;
		border-radius: 50%;
	}

	.highlight-cover {
		position: absolute;
		left: 6%;
		top: 4%;
		width: 90%;
		height: 83%;
		background: #ff5656;
		border-radius: 50%;
	}

	.balloon-string {
		position: absolute;
		top: 109%;
		left: 66%;
		width: 5px;
		height: 157px;
		border-radius: 50%;
		border-right: 2px solid gray;
	}

	p {
		margin: 0;
	}

	.quote {
		position: relative;
		top: 12%;
		margin: auto;
		width: 520px;
		text-align: center;
		font-family: 'Josefin Slab', serif;
		font-size: 54px;
		line-height: 60px;
		color: white;
	}

	.line-4, .line-6, .line-8 {
		text-transform: uppercase;
	}

	.line-9 {
		margin-left: 60px;
	}

	.line-10 {
		margin-left: 90px;
	}

	.line-11 {
		color: black;
		font-size: 26px;
		margin-top: 67px;
		margin-left: 327px;
	}
</style>
