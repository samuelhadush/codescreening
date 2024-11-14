<script setup lang="ts">
import { Icon } from '@iconify/vue'
import { ref } from 'vue'
import {
  MenubarContent,
  MenubarItem,
  MenubarMenu,
  MenubarPortal,
  MenubarRoot,
  MenubarSubContent,
  MenubarTrigger,
} from 'radix-vue'

const currentMenu = ref('')
const person = ref('pedro')
function handleClick() {
  // eslint-disable-next-line no-alert
  alert('hello!')
}
</script>

<template>
  <MenubarRoot
    v-model="currentMenu"
    class="flex bg-white p-[3px] rounded-md shadow-[0_2px_10px] shadow-blackA7"
  >


    <MenubarMenu value="Profiles">
      <MenubarTrigger
        class="py-1 px-3  outline-none select-none font-semibold leading-none text-black text-[13px] flex items-center justify-between gap-[2px] data-[highlighted]:bg-gray-200 data-[state=open]:bg-gray-200"
      >
        Profiles
      </MenubarTrigger>
      <MenubarPortal>
        <MenubarContent
          class="min-w-[220px] outline-none bg-white rounded-md p-[5px] shadow-[0px_10px_38px_-10px_rgba(22,_23,_24,_0.35),_0px_10px_20px_-15px_rgba(22,_23,_24,_0.2)] [animation-duration:_400ms] [animation-timing-function:_cubic-bezier(0.16,_1,_0.3,_1)] will-change-[transform,opacity]"
          align="start"
          :side-offset="5"
          :align-offset="-14"
        >
    

          <MenubarItem
            class="text-[13px] leading-none text-black rounded flex items-center h-[25px] px-[10px] relative select-none pl-5 outline-none data-[state=open]:bg-gray-200 data-[state=open]:text-white data-[highlighted]:bg-gradient-to-br data-[highlighted]:from-green9 data-[highlighted]:to-green10 data-[highlighted]:text-green1 data-[highlighted]:data-[state=open]:text-green1 data-[disabled]:text-mauve8 data-[disabled]:pointer-events-none"
          >
            Add Profile…
          </MenubarItem>
          <MenubarItem
            class="text-[13px] leading-none text-black rounded flex items-center h-[25px] px-[10px] relative select-none pl-5 outline-none data-[state=open]:bg-gray-200 data-[state=open]:text-white data-[highlighted]:bg-gradient-to-br data-[highlighted]:from-green9 data-[highlighted]:to-green10 data-[highlighted]:text-green1 data-[highlighted]:data-[state=open]:text-green1 data-[disabled]:text-mauve8 data-[disabled]:pointer-events-none"
          >
            Add Profile…
          </MenubarItem>
          <MenubarItem
            class="text-[13px] leading-none text-black rounded flex items-center h-[25px] px-[10px] relative select-none pl-5 outline-none data-[state=open]:bg-gray-200 data-[state=open]:text-white data-[highlighted]:bg-gradient-to-br data-[highlighted]:from-green9 data-[highlighted]:to-green10 data-[highlighted]:text-green1 data-[highlighted]:data-[state=open]:text-green1 data-[disabled]:text-mauve8 data-[disabled]:pointer-events-none"
          >
            Add Profile…
          </MenubarItem>
          <MenubarItem
            class="text-[13px] leading-none text-black rounded flex items-center h-[25px] px-[10px] relative select-none pl-5 outline-none data-[state=open]:bg-gray-200 data-[state=open]:text-white data-[highlighted]:bg-gradient-to-br data-[highlighted]:from-green9 data-[highlighted]:to-green10 data-[highlighted]:text-green1 data-[highlighted]:data-[state=open]:text-green1 data-[disabled]:text-mauve8 data-[disabled]:pointer-events-none"
          >
            Add Profile…
          </MenubarItem>
          <MenubarItem
            class="text-[13px] leading-none text-black rounded flex items-center h-[25px] px-[10px] relative select-none pl-5 outline-none data-[state=open]:bg-gray-200 data-[state=open]:text-white data-[highlighted]:bg-gradient-to-br data-[highlighted]:from-green9 data-[highlighted]:to-green10 data-[highlighted]:text-green1 data-[highlighted]:data-[state=open]:text-green1 data-[disabled]:text-mauve8 data-[disabled]:pointer-events-none"
          >
            Add Profile…
          </MenubarItem>
        </MenubarContent>
      </MenubarPortal>
    </MenubarMenu>
  </MenubarRoot>
</template>