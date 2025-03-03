<script setup lang="ts"></script>

<template>
  <q-layout view="lHh Lpr lFf">
    <q-header class="flex row bg-white text-black justify-between q-px-md" style="height: 4em">
      <div class="flex justify-center items-center q-py-md">
        <q-avatar  class="text-h5 q-mr-sm">
          <img src="https://developers.google.com/static/blockly/images/logos/logo_only.svg" />
        </q-avatar>

        <span class="text-h6">Blockly Javascript</span>
      </div>
      <span class="flex items-center">
        <span class="">boo</span>
      </span>
    </q-header>
    <q-page-container>
      <router-view />
    </q-page-container>
  </q-layout>
</template>
