<script setup lang="ts">
import {
  Menubar,
  MenubarContent,
  MenubarItem,
  MenubarMenu,
  MenubarTrigger,
} from '@/components/ui/menubar'
</script>

<template>
  <Menubar class="border-0 bg-white rounded-0">
    <MenubarMenu class="bg-white">
      <MenubarTrigger as-child
        class="focus:bg-inherit bg-white text-black focus:text-inherit data-[state=open]:bg-inherit data-[state=open]:text-inherit">
        <li class=" capitalize flex items-center flex-nowrap whitespace-nowrap text-black gap-x-2">Overview<svg width="14"
            height="14" viewBox="0 0 512 512" stroke="currentColor" focusable="false"
            xmlns="http://www.w3.org/2000/svg">
            <path d="M256 352 128 160h256z"></path>
          </svg></li>
      </MenubarTrigger>
      <MenubarContent>
        <MenubarItem class="text-black">
          New Tab
        </MenubarItem>
        <MenubarItem class="text-black">
          New Window
        </MenubarItem>
        <MenubarItem class="text-black">
          New Incognito Window
        </MenubarItem>

      </MenubarContent>
    </MenubarMenu>

    <MenubarMenu class="bg-white">
      <MenubarTrigger as-child
        class="focus:bg-inherit bg-white text-black focus:text-inherit data-[state=open]:bg-inherit data-[state=open]:text-inherit">
        <li class=" capitalize flex items-center flex-nowrap whitespace-nowrap text-black gap-x-2">Media<svg width="14" height="14"
            viewBox="0 0 512 512" stroke="currentColor" focusable="false" xmlns="http://www.w3.org/2000/svg">
            <path d="M256 352 128 160h256z"></path>
          </svg></li>
      </MenubarTrigger>
      <MenubarContent>
        <MenubarItem class="text-black">
          New Tab
        </MenubarItem>
        <MenubarItem class="text-black">
          New Window
        </MenubarItem>
        <MenubarItem class="text-black">
          New Incognito Window
        </MenubarItem>

      </MenubarContent>
    </MenubarMenu>
    <MenubarMenu class="bg-white">
      <MenubarTrigger as-child
        class="focus:bg-inherit bg-white text-black focus:text-inherit data-[state=open]:bg-inherit data-[state=open]:text-inherit">
        <li class=" capitalize flex items-center flex-nowrap whitespace-nowrap text-black gap-x-2">fandom<svg width="14"
            height="14" viewBox="0 0 512 512" stroke="currentColor" focusable="false"
            xmlns="http://www.w3.org/2000/svg">
            <path d="M256 352 128 160h256z"></path>
          </svg></li>
      </MenubarTrigger>
      <MenubarContent>
        <MenubarItem class="text-black">
          New Tab
        </MenubarItem>
        <MenubarItem class="text-black">
          New Window
        </MenubarItem>
        <MenubarItem class="text-black">
          New Incognito Window
        </MenubarItem>

      </MenubarContent>
    </MenubarMenu>
    <MenubarMenu class="bg-white">
      <MenubarTrigger as-child
        class="focus:bg-inherit bg-white text-black focus:text-inherit data-[state=open]:bg-inherit data-[state=open]:text-inherit">
         <li class=" capitalize flex items-center flex-nowrap whitespace-nowrap text-black gap-x-2">share <svg width="14"
            height="14" viewBox="0 0 512 512" stroke="currentColor" focusable="false"
            xmlns="http://www.w3.org/2000/svg">
            <path d="M256 352 128 160h256z"></path>
          </svg></li>
      </MenubarTrigger>
      <MenubarContent>
        <MenubarItem class="text-black">
          New Tab
        </MenubarItem>
        <MenubarItem class="text-black">
          New Window
        </MenubarItem>
        <MenubarItem class="text-black">
          New Incognito Window
        </MenubarItem>

      </MenubarContent>
    </MenubarMenu>

  </Menubar>
</template>