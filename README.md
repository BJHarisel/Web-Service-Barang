# Web-Service-Barang

Boby Jamis Hari sel-1154040

Analisis :
***********************************************
Dalam kode tersebut ada tag <?xml version="1.0" encoding="UTF-8"?> itu merupakan tag penting atau 
jantungnya dari xml, merupakan sebuah Instruksi Proses / direktif khusus untuk mengelola  xml, Jadi 
jika kita ingin membuat sebuah xml  maka Perintah tersebut harus ada, jika tidak maka srcpt tersebut 
tidak bisa di compile menjadi xml. Diawali <?....?>

***********************************************
Deklarasi DOCTYPE memiliki tanda seru (!) Pada awal nama elemen. DOCTYPE menginformasikan parser yang DTD dikaitkan dengan dokumen XML ini.
***********************************************
xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="barang.xsd"
adalah sebuah schema XSD, Dimana xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" sebagai pendeklarasi standar namespace, dan 
xsi:noNamespaceSchemaLocation="barang.xsd" adalah lokasi skema XML yaitu daro Kursus.xsd
***********************************************
Dalam kode PesertaBimbel.xml  tersebut memiliki 1  element. Element sendiri merupakan nama teknis untuk 
tag yang berpasangan dimulai dari tag pembuka dan tag penutup pada dokumen XML. 
1 element/class  yaitu logbarang dalam element tersebut mempunyai  Sub element yaitu barang yang terdiri dari kode, satuan, harga, asal, tujuan. Didalam kode tersebut disematkan data-data atau entitaas yang akan dimunculkan. Jadi semua kode tersebut akan di compile.
