<template>
  <section class="contact">
    <div class="container">
      <!-- <div id="map"></div> -->
      <div class="wrapper">
        <img src="/map.png" alt="map">
        <location />
        <div class="borderWrapper">
          <div class="border">
            <h4 class="roboto">Contact</h4>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
  import Location from '~/components/Location.vue'

  export default {
  	components: {
  		Location
  	}
  }
</script>

<style lang="scss" scoped>
  section.contact {
  	background: #f7f7f8;
  	margin-top: -48px;

  	.container {
  		padding-top: 146px;
  		padding-bottom: 100px;

  		.wrapper {
  			max-width: 928px;
  			position: relative;
  			display: flex;
  			flex-flow: row wrap;
  			justify-content: space-between;
  			margin: auto;
  			img {
  				margin-top: 62px;
  				z-index: 2;
  			}

  			.borderWrapper {
  				width: 100%;
  				position: absolute;
  				padding: 0 24px;

  				.border {
  					height: 404px;
  					border: 1px solid rgba(0, 0, 0, 0.1);
  					top: 0;

  					h4 {
  						width: 193px;
  						font-size: 32px;
  						font-weight: 700;
  						margin: -24px auto 0;
  						text-align: center;
  						background: #f7f7f8;
  					}
  				}
  			}
  		}
  	}
  }

  @media screen and (max-width: 768px) {
  	section.contact {
  	}
  }

  @media screen and (max-width: 948px) {
  	section.contact {
  		padding: 16px;

  		.container {
  			.wrapper {
  				img {
  					width: 100%;
  				}
  			}
  		}
  	}
  }
</style>
