<!--
 * @Date: 19/04/2021 20.31.32 +0800
 * @Author: KnowsCount
 * @LastEditTime: 25/04/2021 21.45.18 +0800
 * @FilePath: /vue-lib/dev/serve.vue
-->
<script>
import Vue from 'vue';
// Uncomment import and local "components" registration if library is not registered globally.
// import { inputBox } from '@/entry.esm';
import InputBox from '../src/lib-components/input-box.vue';
import SmashToSubmit from '../src/lib-components/smash-to-submit.vue';
import Check from '../src/lib-components/check.vue';
import FeedbackReactions from '../src/lib-components/feedback-reactions.vue';
import FavouriteButton from '../src/lib-components/favourite-button.vue';
import PaperplaneButton from '../src/lib-components/paperplane-button.vue';
import LinkHover from '../src/lib-components/link-hover.vue';
import SlidingTabs from '../src/lib-components/sliding-tabs.vue';

export default Vue.extend({
	name: 'ServeDev',
	components: {
		InputBox,
		SmashToSubmit,
		Check,
		FeedbackReactions,
		FavouriteButton,
		PaperplaneButton,
		LinkHover,
		SlidingTabs
	}
});
</script>

<template>
	<div id="app">
		<input-box />
		<br />
		<smash-to-submit />
		<br />
		<check />
		<br />
		<feedback-reactions />
		<br />
		<favourite-button/>
		<br />
		<paperplane-button />
		<br />
		<link-hover />
		<br />
		<sliding-tabs />
	</div>
</template>
