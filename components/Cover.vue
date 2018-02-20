<template>
  <section class="cover">
    <img src="/logo.png" alt="vedx">
  </section>
</template>

<style lang="scss" scoped>
  section.cover {
    background: url('/cover.png');
    background-size: cover;
  	background-repeat: repeat-x;
  	height: 280px;
  	display: flex;
  	justify-content: center;
  	align-items: center;

  	img {
  		background: #ffffff;
      height: 75px + (20px * 2);
      width: 295.26px + (40px * 2);
  		padding: 20px 40px;
  	}
  }

  @media screen and (max-width: 768px) {
  	section.cover {
  		height: 150px;

  		img {
  			height: 40px + (16px * 2);
  			width: 156px + (32px * 2);
  			padding: 16px 32px;
  		}
  	}
  }
</style>
