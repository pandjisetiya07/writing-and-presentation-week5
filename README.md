__PANDJI SETIYA BUDHI ARTHA__ -- _Tugas writing minggu ke-Empat_

-----------------------------------------------------------------------
## React JS
### Apa itu React JS?
- React JS yaitu Framwoerk view library Javascript untuk membuat tampilan (user interface) pada website.
- React JS dibuat oleh Tim Engineer Facebook. Facebook menggunakan React JS pada sisi front-end. dan React JS masih unggul diantara Framwork javascript lainnya seperti Vue dan Angular menurut Google Trends.
### Mengapa menggunakan React JS?
- Karena React Js Is Fast, ketika membuat aplikasi front-end menjadi lebih cepat walaupun harus menghandle berbagai data.
- React JS is Modular. kita dapat menerapkan konsep modular javascript pada react js. disini react js membagi 1 tampilan pada website menjadi komponen" kecil. seperti Navbar , Form dan Title With Descripion
- React JS is Scalabe. digunakan pada aplikasi berskala kecil hingga besar dan kompleks.
- React is popular. dan kebanyakan perusahaan teknologi menggunakan React JS.
### Vanilla JS is a anonymous.
- Vanilla JS adalah kita menggunakan native javascript (default).
### Mengapa terdapat tag element HTML di dalam javascript.
- mengapa karena itu merupakan JSX.
JSX adalah syntax extension for javascript. JSX dikembangkan untuk digunakan untuk pada React JS. namun JSX perlu dicompile untuk menjadi Javascript. dengan JSX kita dapat menggunakan HTML didalam file extension Javascript (.js)
### JSX Rules
- setiap JSX hanya bisa memiliki 1 parent element. dan jika parent element lebih dari satu maka terjadi ERROR.
dan gunakan tag element ``` <div> ``` / fragment <> sebagai parent dari element.
- contoh 2 parent element:
![](/Screenshot/Screenshot%20(16).png)
- contoh ketika error
![](/Screenshot/Screenshot%20(17).png) 
### The Virtual Dom
- Dengan DOM kita dapat berinteraksi seperti mengupdate data di web page.
- virtual DOM adalah duplikasi dari real DOM yang sebenarnya.
![](/Screenshot/Screenshot%20(18).png)
### Class dan ClassName
- Pada JSX attribut class di tag element HTML harus menggunakan className.
- contoh:
![](/Screenshot/Screenshot%20(20).png)
### Curly Braces in JSX
- Kita bisa menggunakan syntax Javascript di dalam element HTML dengan curly braces.
![](/Screenshot/Screenshot%20(21).png)
- *element dalam tag ``` <h1> ``` akan dianggap sebagai Javascript jika menggunakan curly braces. Dan tampilan yang akan di tampilkan angka 5*
- *dan jika tidak menggunakan curly braces akan dianggap sebagai content HTML. maka tampilan yg ditampilkan 2+3*
### Variable pada JSX
- Gunakan curly braces untuk akses variable pada JSX.
- Seperti gambar di bawah ini:
![](/Screenshot/Screenshot%20(24).png)
### Attribute pada JSX
- Menggunakan curly brance untuk data attribute
![](/Screenshot/Screenshot%20(25).png) <br>
### Event in JSX
- Deklarasi event dengan curly brance pada JSX
![](/Screenshot/Screenshot%20(28).png)
### Conditional in JSX
- Salah satu contoh penggunaan conditional pada JSX.
![](/Screenshot/Screenshot%20(26).png)
### .Map()
- Untuk menampilkan data React juga memiliki beberapa cara:
![](/Screenshot/Screenshot%20(27).png)
- Hasil dari gambar diatas:
```
 1 
 2
 3
 4
 5
```

## React JS Component
### Apa itu Component?
- yaitu salah satu core dari React JS.
- Component dibuat jika component tersebut bersifat reusable code. pada skala project maka kita harus membuat componet jika component tersebut akan dibutuhkan pada section atau page lain.
### Membuat Component
- Ada 2 cara membuat component:
1. Gunakan function
2. Gunakan class
### State & Props
- merupakan hal yang berhubungan dengan Stateless & Stateful Component. stateles yang berarti tidak memiliki state. dia hanya memiliki props. sedangkan stateful berarti memiliki state dan bisa mengirim state tersebut ke component. 
![](Screenshot%20(29).png)

![](Screenshot%20(30).png)
- Jadi state adalah data Local. Props digunakan agar component memiliki data yang dinamis yang dikirim dari component lain.