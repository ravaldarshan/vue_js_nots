### vue_js_comands 

requerd node js

1. instollation
## install vue cli
npm install -g @vue/cli
vue create my-project
	

## install vue.js using cli
npm init vue@latest or npm i vue-router@latest
cd <your-project-name>
npm install
npm run dev
npm run serve

## chack vue pakages version 
npm list vue

## use vue.js using cdn
<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>

2.build vue.js project
npm run build

## install axios for fetch api using xml
npm i axios vue-axios or npm install axios

## add vue-bootsrap in project 
vue add bootsrap-vue

## vue routing 
..for vue 2
npm install vue-router
..for vue 3

##install vue js inlaravel
npm install --save-dev vue vue-template-compiler

## install bootsrap 
npm i vue-router@next
npm install @popperjs/core

#watch in vue 
npm run watch
npm run watch-poll

### install laravel + vue.js 

# install laravel
laravel new vue_js_project

# install vue js 
npm install vue@next vue-loader@next
//inatall vue js using artisan 
composer require laravel/ui
php artisan ui vue

# Install vitejs/plugin-vue plugin 
npm i @vitejs/plugin-vue

# Update vite.config.js
// vite.config.js
import { defineConfig } from 'vite';
import laravel from 'laravel-vite-plugin';
import vue from '@vitejs/plugin-vue'


export default defineConfig({
    plugins: [
        vue(),//add vue project
        laravel([
            'resources/css/app.css',
            'resources/js/app.js',
        ]),
    ],
});

# Vite Dev Server Start
npm run dev

# Create Vue 3 App
// app.js
require('./bootstrap');

import {createApp} from 'vue'

import App from './App.vue'

createApp(App).mount("#app")

# Create Vue 3 Component
<template>
    How To Install Vue 3 in Laravel 9 with Vite - TechvBlogs
</template>

# Connect Vue 3 Component with Laravel blade file

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>How To Install Vue 3 in Laravel 9 with Vite</title>

	@vite('resources/css/app.css')
</head>
<body>
	<div id="app"></div>

	@vite('resources/js/app.js')
</body>
</html>

# Update Laravel Routes
Route::get('/', function () {
    return view('app');
});

# Update .env file
APP_URL=http://localhost:8000

# build vue.js project
npm run build

# Start the laravel server
php artisan serve

### refers
https://techvblogs.com/blog/how-to-install-vue-3-in-laravel-9-with-vite
