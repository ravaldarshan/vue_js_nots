# vue commends
```
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

## chack vue pakages version
`npm list vue`

## create vue js app build
`npm run build`

## install axios for fetch api using xml
`npm i axios vue-axios or npm install axios`

## add vue-bootsrap in project
`$ npm install bootstrap bootstrap-vue --save`

## install vue routing
`npm install vue-router`

# instolation of laravel + vue.js

## install laravel
`laravel new vue_js_project`

## vue js instollation
### using vue cli
```
npm install -g @vue/cli
vue create my-project
npm install
npm run dev
npm run serve
```
### using php  artition
```
composer require laravel/ui
php artisan ui vue
npm i @vitejs/plugin-vue
```
### using npm 
```
npm install vue@next vue-loader@next
npm i @vitejs/plugin-vue
```


### Connect Vue 3 Component with Laravel blade file
```
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
```

### Update Laravel Routes

Route::get('/', function () {
return view('app');
});


### Update .env file

APP_URL=http://localhost:8000

### reference links

https://techvblogs.com/blog/how-to-install-vue-3-in-laravel-9-with-vite
