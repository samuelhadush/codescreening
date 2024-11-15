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
  <Menubar class="border-0">
    <MenubarMenu>
      <MenubarTrigger as-child class="focus:bg-inherit focus:text-inherit data-[state=open]:bg-inherit data-[state=open]:text-inherit"><li class="font-semibold cursor-pointer ">Movies</li></MenubarTrigger>
      <MenubarContent>
        <MenubarItem class="text-black">
          New Tab 
        </MenubarItem>
        <MenubarItem class="text-black">
          New Window 
        </MenubarItem>
        <MenubarItem class="text-black" >
          New Incognito Window
        </MenubarItem>

      </MenubarContent>
    </MenubarMenu>

    <MenubarMenu>
      <MenubarTrigger as-child class="focus:bg-inherit focus:text-inherit data-[state=open]:bg-inherit data-[state=open]:text-inherit"><li class="font-semibold cursor-pointer ">TV Shop</li></MenubarTrigger>
      <MenubarContent>
        <MenubarItem class="text-black">
          New Tab 
        </MenubarItem>
        <MenubarItem class="text-black">
          New Window 
        </MenubarItem>
        <MenubarItem class="text-black" >
          New Incognito Window
        </MenubarItem>

      </MenubarContent>
    </MenubarMenu>
    <MenubarMenu>
      <MenubarTrigger as-child class="focus:bg-inherit focus:text-inherit data-[state=open]:bg-inherit data-[state=open]:text-inherit"><li class="font-semibold cursor-pointer ">People</li></MenubarTrigger>
      <MenubarContent>
        <MenubarItem class="text-black">
          New Tab 
        </MenubarItem>
        <MenubarItem class="text-black">
          New Window 
        </MenubarItem>
        <MenubarItem class="text-black" >
          New Incognito Window
        </MenubarItem>

      </MenubarContent>
    </MenubarMenu>
    <MenubarMenu>
      <MenubarTrigger as-child class="focus:bg-inherit focus:text-inherit data-[state=open]:bg-inherit data-[state=open]:text-inherit"><li class="font-semibold cursor-pointer  ">More</li></MenubarTrigger>
      <MenubarContent>
        <MenubarItem class="text-black">
          New Tab 
        </MenubarItem>
        <MenubarItem class="text-black">
          New Window 
        </MenubarItem>
        <MenubarItem class="text-black" >
          New Incognito Window
        </MenubarItem>

      </MenubarContent>
    </MenubarMenu>

  </Menubar>
</template>