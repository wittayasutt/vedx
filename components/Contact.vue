<template>
  <section class="contact">
    <div class="container">
      <div class="wrapper">
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3875.9688129347846!2d100.49952631540644!3d13.720337990367785!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x30e298cddf96d609%3A0x8b83d4e785447223!2sLike+Me+Co.%2C+Ltd.!5e0!3m2!1sth!2sth!4v1519121888011" width="544" height="286" frameborder="0" style="border:0" allowfullscreen></iframe>
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

  			iframe {
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

  @media screen and (max-width: 948px) {
  	section.contact {
  		padding: 16px;

  		.container {
        padding-top: 52px;
      
  			.wrapper {
  				iframe {
  					width: 100%;
  					margin-top: 27px;
  				}

  				.borderWrapper {
  					padding: 0 8px;

  					.border {
  						height: 597px;

  						h4 {
  							width: 103px;
  							font-size: 18px;
  							margin: -14px auto 0;
  						}
  					}
  				}
  			}
  		}
  	}
  }
</style>
