<template>
  <section class="slogan container">
    <div class="text">สโลแกนสโลแกนสโลแกนสโลแกนสโลแกนสโลแกนสโลแกนสโลแกนสโลแกน</div>
    <div class="quoteBorder">
      <div class="quote">ในยุคของโลกดิจิตอล ที่การทำโฆษณาไปสู่รูปแบบของออนไลน์นั้นต้องการความรวดเร็ว น่าสนใจ เเละต้องโดนใจผู้อ่าน การเปลี่ยนเนื้อหาที่น่าเบื่อหลายย่อหน้าให้ น่าสนใจ และ เข้าใจง่ายด้วยภาพเพียงภาพ Infographic (อินโฟกราฟิก) เพียงภาพเดียว จึงเป็นการสื่อสารที่รวดเร็ว ชัดเจน และสมบูรณ์แบบที่สุด เราคือเพจ Infographic Thailand เพจ Infographic อันดับ 1 ของประเทศไทย ที่รับและผลิตคอนเท้นท์เกี่ยวกับอินโฟกราฟิกมากว่า 5 ปี</div>
    </div>
  </section>
</template>

<style lang="scss" scoped>
  section.slogan {
  	.text {
  		color: $primary;
  		font-size: 24px;
  		margin: 80px auto;
  		text-align: center;
  	}

  	.quoteBorder {
  		width: 928px;
  		background: $primary;
  		color: #ffffff;
  		margin: auto;
  		padding: 10px;
  		border-radius: 10px;

  		.quote {
  			border: 1px solid #ffffff;
  			padding: 30px 22px;
  			border-radius: 10px;
  			font-size: 20px;
  			text-align: center;
  		}
  	}
  }

  @media screen and (max-width: 948px) {
  	section.slogan {
  		.text {
  			font-size: 20px;
  			margin: 56px auto;
  			padding: 16px;
  		}

  		.quoteBorder {
  			width: auto;
  			margin: 16px;

  			.quote {
  				font-size: 14px;
  			}
  		}
  	}
  }
</style>
