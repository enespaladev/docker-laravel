# Docker Laravel 11 Geliştirme Ortamı 

Docker üzerinde Laravel 11 geliştirme ortamının hazırlanması

* Windows kullanıyorsanız Docker Desktop bilgisayarınızda kurulu olmalı.
* Proje klasörüne gittikten sonra `docker compose up -d` komutu çalıştırılarak docker ayağa kaldırılır.
* Ayağa kaldırmış olduğumuz docker'da containera bağlanılır.
    * `docker ps` komutu ile container'ları görebilirsiniz.
    * `docker exec -it containerID bash` komutu ile container'a bağlanabilirsiniz.
* composer ile proje oluşturabilirsiniz.