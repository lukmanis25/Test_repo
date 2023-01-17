0. Czyścić niepotrzebne obrazy i volumes !!!
1. Utowrzyć network taki jak w docker-compose się ustawi
2. Utworzyć volumen taki jak w docker-compose się ustawi (tego chyba jednak nie trzeba bo doker sam tworzy swoje)
3. Tworzymy obraz z Dockerfile o nazwie my_presta:
docker build -t my_presta .


Baza danych:
Adres serwera bazy danych: mariadb:3306
Nazwa bazy danych: prestashop
Użytkownik bazy danych: root
Hasło bazy danych: haslo



