<script setup lang="ts">
import type { HTMLAttributes } from 'vue'
import { type ButtonVariants, buttonVariants } from './index'
import cn from "~/utils/cn";

interface Props {
  variant?: ButtonVariants['variant']
  size?: ButtonVariants['size']
  class?: HTMLAttributes['class']
}

const props = defineProps<Props>()
</script>

<template>
  <button
    :class="cn(buttonVariants({ variant, size }), props.class)"
  >
    <slot />
  </button>
</template>
