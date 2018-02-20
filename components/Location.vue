<template>
  <section class="location">
    <p>126/5 2nd Flr. Thai Sri Tower Krungthonburi Rd., Banglampoolang, Klongsan, Bangkok 10600</p>
    <p class="light">Monday to Friday 10 AM - 6PM</p>
    <div class="line"></div>
    <p>info@edx.com</p>
    <p>02-408-5410</p>
  </section>
</template>

<style lang="scss" scoped>
  section.location {
  	flex: 1;
  	height: 286px;
  	display: flex;
  	flex-direction: column;
  	justify-content: space-between;
  	background: #ffffff;
  	margin-top: 62px;
  	margin-left: 32px;
  	padding: 32px 24px;
  	border-radius: 10px;
  	box-shadow: 0px 18px 13px -5px rgba(0, 0, 0, 0.09);
  	z-index: 2;

  	p.light {
  		font-weight: 200;
  	}

  	.line {
  		height: 2px;
  		width: 24px;
  		background: $primary;
  	}
  }

  @media screen and (max-width: 768px) {
  	section.location {
  		margin-left: auto;
  	}
  }

  @media screen and (max-width: 948px) {
  	section.location {
  		margin-top: 16px;
  		margin-left: auto;
  	}
  }
</style>
