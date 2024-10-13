<script setup lang="ts">
import { Search } from 'lucide-vue-next'
</script>

<template>
  <header class="px-4 sm:px-6 py-7">

    <div class="flex justify-between items-center">
<!--      <Sheet v-model:open="open">-->
<!--        <SheetTrigger as-child>-->
<!--          <Button variant="ghost" size="icon" class="shrink-0 lg:hidden -ml-2">-->
<!--            <Menu class="size-6" />-->
<!--            <span class="sr-only">Toggle navigation menu</span>-->
<!--          </Button>-->
<!--        </SheetTrigger>-->
<!--        <SheetContent side="left" class="flex flex-col">-->
<!--          <Navigation />-->
<!--        </SheetContent>-->
<!--      </Sheet>-->

      <div class="flex justify-between items-center">
        <img src="../../assets/images/logo.webp" alt="Logo SV Salvo">
        <nav>
          <ul>
            <li>
              <a href="#">Home</a>
            </li>
            <li>
              <a href="#">About</a>
            </li>
            <li>
              <a href="#">Services</a>
            </li>
            <li>
              <a href="#">Contact</a>
            </li>
          </ul>
        </nav>
      </div>
    </div>

  </header>
</template>