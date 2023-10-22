<!--
  This source file is part of the Swift.org open source project

  Copyright (c) 2023 Apple Inc. and the Swift project authors
  Licensed under Apache License v2.0 with Runtime Library Exception

  See https://swift.org/LICENSE.txt for license information
  See https://swift.org/CONTRIBUTORS.txt for Swift project authors
-->

<template>
  <SVGIcon
    class="kotlin-file-icon"
    viewBox="0 0 16 16"
    themeId="kotlin-file"
  >
    <polygon points="15,15 1,15 1,1 15,1 8,8 "/>
  </SVGIcon>
</template>

<script>
import SVGIcon from 'docc-render/components/SVGIcon.vue';

export default {
  name: 'KotlinFileIcon',
  components: { SVGIcon },
};
</script>
<style scoped lang="scss">
@import 'docc-render/styles/_core.scss';

.kotlin-file-icon {
  &.file-icon {
    height: 1rem;
  }
}
</style>
