<template>
<main>
				<scroll-view @scrolltoupper="scrolltoupperFlex1" @scrolltolower="scrolltolowerFlex1" scroll-x scroll-with-animation class="flex scroll-view flex-wrap diygw-col-24">
					<div class="flex flex-nowrap">
						<div class="flex flex-wrap diygw-col-0 flex-direction-column items-center flex5-clz">
							<img src="./static/kt.png" class="image4-size diygw-image diygw-col-0 image4-clz" mode="widthFix" />
							<div class="diygw-text-line1 diygw-col-0 red text8-clz">สด</div>
							<div class="diygw-col-24 text9-clz diygw-ellipsis">บราซิล</div>
						</div>
						<div class="flex flex-wrap diygw-col-0 flex-direction-column items-center flex-clz">
							<img src="./static/kt.png" class="image-size diygw-image diygw-col-0 image-clz" mode="widthFix" />
							<div class="diygw-text-line1 diygw-col-0 red text12-clz">สด</div>
							<div class="diygw-col-24 text1-clz diygw-ellipsis">แมนยู</div>
						</div>
						<div class="flex flex-wrap diygw-col-0 flex-direction-column items-center flex4-clz">
							<img src="./static/kt.png" class="image3-size diygw-image diygw-col-0 image3-clz" mode="widthFix" />
							<div class="diygw-text-line1 diygw-col-0 red text-clz">สด</div>
							<div class="diygw-col-24 text18-clz diygw-ellipsis">แมนยู</div>
						</div>
						<div class="flex flex-wrap diygw-col-0 flex-direction-column items-center flex3-clz">
							<img src="./static/3.png" class="image2-size diygw-image diygw-col-0 image2-clz" mode="widthFix" />
							<div class="diygw-col-0 blue text4-clz diygw-ellipsis">เร็วๆนี้</div>
							<div class="diygw-col-24 text5-clz diygw-ellipsis">ไทย</div>
						</div>
						<div class="flex flex-wrap diygw-col-0 flex-direction-column items-center flex2-clz">
							<img src="./static/kt.png" class="image1-size diygw-image diygw-col-0 image1-clz" mode="widthFix" />
							<div class="diygw-col-0 blue text2-clz diygw-ellipsis">เร็วๆนี้</div>
							<div class="diygw-col-24 text3-clz diygw-ellipsis">บรูไน</div>
						</div>
						<div class="flex flex-wrap diygw-col-0 flex-direction-column items-center flex6-clz">
							<img src="./static/kt.png" class="image5-size diygw-image diygw-col-0 image5-clz" mode="widthFix" />
							<div class="diygw-col-0 red text10-clz">เร็วๆนี้</div>
							<div class="diygw-col-24 text11-clz diygw-ellipsis">อังกฤษ</div>
						</div>
					</div>
				</scroll-view>
</main>
<router-view>

</router-view>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'App',
});
</script>
