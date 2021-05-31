# Vue JS sandbox

Halo semuanya, Vue JS sandbox ini bisa menjadi salah satu alat kalian untuk belajar basic-basic vue.js

## Instalasi

1. git checkout -b "1.installation"
2. Tambahkan script yang dibutuhkan untuk menggunakan vue js
3. https://vuejs.org/v2/guide/installation.html

## Declarative Rendering

1. git checkout -b "2.declarative-rendering"
2. Buatlah instance Vue dan render pada id app
3. Buatlah "state" dengan nama message dengan isi "Hello Vue!"
4. Tampilkan isi state tersebut dalam div dengan id app dengan memanfaatkan interpolasi / declarative rendering
5. referensi : https://vuejs.org/v2/guide/index.html

## Binding Element Attributes

1. git checkout -b "3.binding-attributes"
2. Lakukan Binding state imgUrl pada attribute src tag img
3. Tambahkan class active / disabled pada tag button sesuai dengan state isActive (jika true maka "active" jika false maka "disabled")
4. referensi: https://vuejs.org/v2/api/#v-bind

## Conditional

1. git checkout -b "4.conditional"
2. Tampilkan div dengan id login page jika state currentPage berisi login
3. Tampilkan div dengan id register page jika state currentPage berisi register
4. Tampilkan div dengan id dashboard page jika state currentPage berisi dashboard
5. Selain itu tampilkan div dengan id 404
6. referensi: https://vuejs.org/v2/api/#v-if

## Handling User Input - click

1. git checkout -b "5.handling-click"
2. Buatlah method dengan nama "changePage" di vue instance yang tersedia, method menerima 1 parameter berfungsi untuk mengubah state "currentPage" menjadi isi dari parameter yang dikirim
3. Manfaatkan v-on click pada button dengan id "login" yang tersedia dan panggil method changePage dengan parameter "loginPage"
4. referensi : https://vuejs.org/v2/api/#v-on

## Loops

1. git checkout -b "6.loops"
2. Lakukan perulangan pada state todos menggunakan tag li (di dalam tag ul yang tersedia) dengan format `title: status`
3. jangan lupa tambahkan attribute key untuk setiap tag li yang diiterasi
4. referensi: https://vuejs.org/v2/api/#v-for

## Handling User Input - submit

1. git checkout -b "7.handling-submit"
2. Buatlah state dengan nama title , kaitkan state ini dengan input tag dengan id title menggunakan v-model. referensi : https://vuejs.org/v2/guide/forms.html
3. Buatlah state dengan nama status, kaitkan state ini dengan tag select dengan id status menggunakan v-model. referensi : https://vuejs.org/v2/guide/forms.html#Select
4. Buatlah method dengan nama "addTodo" di vue instance yang tersedia, method akan menambahkan object baru dengan format  ```{ status: "...", title: "..."}``` pada state "todos" 
5. Manfaatkan v-on submit pada form yang tersedia dan panggil method addTodo, jangan lupa tambahkan modifier prevent agar page tidak reload.
6. referensi : https://vuejs.org/v2/api/#v-on

## Computed Method

1. git checkout -b "8.computed"
2. Buatlah function totalPrice yang akan menambahkan semua price * quantity di dalam state cart, pada property computed
3. Tampilkan totalPrice yang ada menggunakan interpolasi
4. referensi: https://vuejs.org/v2/api/#computed

## Lifecycle Created

1. git checkout -b "9.created"
2. Masukkan script axios pada index.html https://github.com/axios/axios
3. Buatlah property created pada instance Vue yang tersedia
4. Lakukan request ke https://jsonplaceholder.typicode.com/users
5. Simpan data hasil request ke state users
6. Lakukan looping menggunakan v-for di dalam tag ul yang tersedia menggunakan tag li, tampilkan dengan format "<name>:<city>"

## Watchers

1. Untuk watchers tidak ada branchnya silahkan coba baca artikel berikut https://vuejs.org/v2/guide/computed.html#Watchers dan ambil kesimpulan apa kegunaan watchers ini dan kapan kita membutuhkannya
