# Code Style Guide  {#code_style_guide_title}

Komunitas PHP adalah suatu komunitas yang besar dan beragam, terdiri atas library, framework dan komponen yang tak terhitung jumlahnya. Adalah hal yang lumrah bagi pengembang PHP untuk memilih beberapa dari opsi tersebut dan menggabungkannya kedalam satu proyek. Penting sifatnya dimana kode PHP mengikuti panduan umum dalam menuliskan kode. Hal tersebut akan memudahkan para pengembang untuk menggabungkan dan menggunakan beragam libray dalam proyek mereka.

[Framework Interop Group][fig] telah menawarkan dan mensahkan beberapa rekomendasri, yang dikenal dengan [PSR-0][psr0],
[PSR-1][psr1] dan [PSR-2][psr2]. Jangan sampai tertipu dengan namanya yang aneh, rekomendasi ini adalah beberapa acuan yang sudah mulai diadopsi oleh beberapa proyek, seperti Drupal, Zend, Symfony, CakePHP, phpBB, AWS SDK, FuelPHP, Lithium, dsb. Anda dapat menggunakan acuan tersebut dalam proyek Anda, atau menggunakan "gaya" Anda sendiri.

Secara ideal, Anda sebaiknya menulis kode PHP yang mengikuti standar yang direkomendasikan. Ini dapat berarti Anda menggunakan standar yang direkomendasikan oleh PSR, ataupun yang direkomendasrikan oleh PEAR dan Zend. Ini memudahkan pengembang lain untuk membaca dan menggunakan kode yang Anda tulis. Aplikasi yang menggunakan komponen-komponen lain juga akan memiliki konsistensi meskipun menggunakan kode dari pihak ketiga.

* [Read about PSR-0][psr0]
* [Read about PSR-1][psr1]
* [Read about PSR-2][psr2]
* [Read about PEAR Coding Standards][pear-cs]
* [Read about Zend Coding Standards][zend-cs]

Anda dapat menggunakan [PHP_CodeSniffer][phpcs] untuk memeriksa kualitas dari kode anda terhadap standar yang direkomendasikan. Anda dapat juga menggunakan plugin semisal [Sublime Text 2][st-cs] untuk memperoleh masukan secara langsung.

Untuk mengubah kode Anda secara otomatis dan disesuaikan dengan standar, Anda dapat menggunakan [PHP Coding Standards Fixer][phpcsfixer] yang telah dibuat oleh Fabien Potencier.

Menggunakan bahasa Inggris untuk nama dan infrastruktur kode lebih dianjurkan. Namun, komentar dapat ditulis menggunakan bahasa apapun, selama hal tersebut memudahkan pihak yang menggunakan kode Anda saat ini, dan berikutnya.

[fig]: http://www.php-fig.org/
[psr0]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-0.md
[psr1]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-1-basic-coding-standard.md
[psr2]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-2-coding-style-guide.md
[psr3]: https://github.com/php-fig/fig-standards/blob/master/accepted/PSR-3-logger-interface.md
[pear-cs]: http://pear.php.net/manual/en/standards.php
[zend-cs]: http://framework.zend.com/wiki/display/ZFDEV2/Coding+Standards
[phpcs]: http://pear.php.net/package/PHP_CodeSniffer/
[st-cs]: https://github.com/benmatselby/sublime-phpcs
[phpcsfixer]: http://cs.sensiolabs.org/
