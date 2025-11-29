<template>
    <nav class="flex justify-between items-center py-4 px-8 bg-white shadow">
      <h1 class="font-bold text-xl">MyWeb</h1>
      <ul class="flex gap-6 text-gray-600">
        <li><router-link to="/" class="hover:text-blue-500">Home</router-link></li>
        <li><router-link to="/about" class="hover:text-blue-500">About Us</router-link></li>
        <li><router-link to="/contact" class="hover:text-blue-500">Contact</router-link></li>
      </ul>
    </nav>
  </template>
  