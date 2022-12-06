<template lang="pug">
TopImageVue
#middle
  #left
    LeftMenuVue
    LeftUpdateVue
  #right
    RightMarqueeVue
    //- 根據路由設定決定是否顯示
    #page
      router-view
FooterTextVue
</template>

<script setup>
import TopImageVue from '@/components/TopImage.vue'
import LeftMenuVue from '@/components/LeftMenu.vue'
import LeftUpdateVue from '@/components/LeftUpdate.vue'
import RightMarqueeVue from '@/components/RightMarquee.vue'
import FooterTextVue from '@/components/FooterText.vue'
</script>
