<div class="container">
	<div class="top">
		<h1 class="heading">Join our community</h1>
		<h2 class="sub-heading">30-day, hassle-free money back guarantee</h2>
		<p class="text">
			Gain access to our full library of tutorials along with expert code reviews. Perfect for any
			developers who are serious about honing their skills.
		</p>
	</div>
	<div class="bottom">
		<div class="left">
			<div class="l-heading">Monthly Subscription</div>
			<div class="l-price">
				<div class="price">$29</div>
				<div class="price-text">per month</div>
			</div>
			<div class="l-text">Full access for less than $1 a day</div>
			<div class="btn">Sign Up</div>
		</div>
		<div class="right">
			<div class="r-heading">Why Us</div>
			<div class="r-text">
				Tutorials by industry experts Peer & expert code review Coding exercises Access to our
				GitHub repos Community forum Flashcard decks New videos every week
			</div>
		</div>
	</div>
</div>

<style>
	.container {
		width: 635px;
		height: 475px;
		background-color: white;
		border-radius: 8px;
		display: flex;
		flex-direction: column;
	}
	.top {
		padding: 40px;
		width: 100%;
		height: 216px;
	}
	.heading {
		color: #2ab3b1;
		font-size: 24px;
		font-weight: bold;
		letter-spacing: -0.3px;
		margin-bottom: 24px;
	}
	.sub-heading {
		color: #c0df33;
		font-size: 18px;
		font-weight: bold;
		letter-spacing: -0.22px;
		margin-bottom: 11px;
	}
	.text {
		color: #9aa7be;
		font-size: 16px;
		line-height: 26px;
		letter-spacing: -0.2px;
	}
	.bottom {
		display: flex;
		flex-direction: row;
		height: 259px;
	}
	.left {
		width: 317px;
		height: 100%;
		background-color: #2ab3b1;
		border-radius: 0 0 0 8px;
		padding: 40px;
	}
	.l-heading {
		font-size: 18px;
		font-weight: bold;
		letter-spacing: -0.22px;
		color: white;
		margin-bottom: 18px;
	}
	.l-price {
		display: flex;
		flex-direction: row;
		align-items: center;
		margin-bottom: 4px;
	}
	.price {
		color: white;
		font-size: 32px;
		font-weight: bold;
		letter-spacing: -0.4px;
		margin-right: 11px;
		opacity: 1;
	}
	.price-text {
		font-size: 16px;
		line-height: 26px;
		letter-spacing: -0.2px;
		color: white;
		opacity: 0.5;
	}
	.l-text {
		font-size: 16px;
		line-height: 26px;
		color: white;
		letter-spacing: -0.2px;
		margin-bottom: 25px;
	}
	.btn {
		width: 237px;
		height: 48px;
		display: flex;
		justify-content: center;
		align-items: center;
		background-color: #c0df33;
		color: white;
		font-size: 16px;
		font-weight: bold;
		letter-spacing: -0.2px;
		border-radius: 5px;
		cursor: pointer;
	}
	.right {
		padding: 40px;
		width: 318px;
		height: 100%;
		background-color: #4abfbd;
		border-radius: 0 0 8px 0;
	}
	.r-heading {
		font-size: 18px;
		font-weight: bold;
		letter-spacing: -0.22px;
		margin-bottom: 18px;
		color: white;
	}
	.r-text {
		font-size: 14px;
		line-height: 20px;
		letter-spacing: -0.17px;
		color: white;
	}

	@media only screen and (max-width: 375px) {
		.container {
			width: 311px;
			height: 722px;
			border-radius: 5px;
		}
		.top {
			padding: 28px 24px 32px 24px;
			height: 267px;
		}
		.bottom {
			display: flex;
			flex-direction: column;
			width: 100%;
			height: 455px;
		}
		.heading {
			font-size: 20px;
			letter-spacing: -0.25px;
		}
		.sub-heading {
			font-size: 15px;
			letter-spacing: -0.19px;
			margin-bottom: 16px;
		}
		.text {
			font-size: 14px;
			letter-spacing: -0.17px;
		}
		.left {
			width: 100%;
			border-radius: 0;
			height: 228px;
			padding: 24px;
		}
		.right {
			width: 100%;
			height: 227px;
			border-radius: 0 0 5px 5px;
			padding: 24px;
		}
		.btn {
			width: 263px;
			cursor: pointer;
		}
	}
</style>
