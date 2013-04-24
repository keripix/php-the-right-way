---
isChild: true
---

## Windows Setup {#windows_setup_title}

PHP tersedia dengan beragam cara untuk Windows. Anda dapat [mengunduh binarinya][php-downloads].

Untuk proses pembelajaran dan pengembangan lokal, Anda dapat menggunakan server bawaan yang tersedia pada PHP 5.4. Bila Anda menginginkan paket lengkap yang hadir dengan webserver dan MySQL dan tanpa proses pengaturan yang terbilang rumit, Anda dapat mencoba [Web Platform Installer][wpi],
[Zend Server CE][zsce], [XAMPP][xampp] dan [WAMP][wamp]. Namun, hendaklah Anda waspada mengenai perbedaan ketika Anda mengembangkan aplikasi PHP di Windows, dan kemudian melakukan _deployment_ di Linux.

Bila Anda hendak melakukan _deployment_ di Windows, maka IIS7 dapat memberikan performa yang stabil dan baik. Anda dapat menggunakan [phpmanager][phpmanager] (plugin GUI untuk IIS7) untuk melakukan pengaturan dan pengelolaan PHP. IIS7 hadir dengan FastCGI bawaan dan sudah siap untuk dipakai, Anda hanya perlu mengatur PHP sebagai _handler_-nya. Untuk dukungan dan informasi tambahan, terdapat [sumber khusus di iis.net][php-iis] untuk PHP.

[php-downloads]: http://windows.php.net
[phpmanager]: http://phpmanager.codeplex.com/
[wpi]: http://www.microsoft.com/web/downloads/platform.aspx
[zsce]: http://www.zend.com/en/products/server-ce/
[xampp]: http://www.apachefriends.org/en/xampp.html
[wamp]: http://www.wampserver.com/
[php-iis]: http://php.iis.net/
