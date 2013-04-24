---
isChild: true
---

## Vagrant {#vagrant_title}

Menjalankan aplikasi dengan lingkungan yang berbeda antara proses pengembangan dan proses produksi dapat berujung pada _bugs_ yang aneh. Hal yang tidak mudah juga untuk menjaga agar library yang digunakan adalah sama dan sudah terbaru ketika bekerja secara bersama-sama dalam sebuah tim.

Bila Anda bekerja di Windows dan melakukan _deployment_ ke Linux (atau platform lainnya selain Windows), atau Anda mengembangkan dalam sebuah tim, Anda perlu mencoba menggunakan _virtual machine_. Ini terdengar rumit, tetapi dengan menggunakan [Vagrant][vagrant], Anda dapat menyiapkan sebuah _virtual machine_ dengan beberapa langkah saja. _Virtual Machine_ ini kemudian dapat dipasang secara manual atau Anda dapat melakukannya dengan menggunakan aplikasi semacam [Puppet][puppet] atau [Chef][chef].

Provisioning the base box is a great way to
ensure that multiple boxes are set up in an identical fashion and removes the need for you to maintain complicated
"set up" command lists. You can also "destroy" your base box and recreate it without many manual steps, making it
easy to create a "fresh" installation.

Vagrant menciptakan sebuah direktori yang digunakan untuk berbagi kode antara host Anda dan _virtual machine_ Anda. Sehingga Anda dapat melakukan pengkodean di mesin host Anda, namun menjalankannya di dalam _virtual machine_.

[vagrant]: http://vagrantup.com/
[puppet]: http://www.puppetlabs.com/
[chef]: http://www.opscode.com/
