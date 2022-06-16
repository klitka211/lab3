PROGRAMOWANIE FULL-STACK W CHMURACH OBLICZENIOWYCH
Zadanie 2
CZĘŚĆ OBOWIĄZKOWA
1. (max. 100%)
Proszę uruchomić przygotowaną aplikację na platformie AWS, usługa EBS. W tym celu należy
wykorzystać przykład przedstawiony na laboratorium nr 3 (pliki: Lab3_AWS.pdf oraz
Lab3_AWS_sources.zip).
Wdrożenie aplikacji ma byż zrealizowane w oparciu o GitHub Action i załączony przykład pliku
konfiguracyjnego, który jest dostępny na moodle w katalogu Zadanie 2 (plik: zad2_GHActions.zip)
W sprawozdaniu proszę podać link do repozytorium GitHub oraz link do uruchomionej aplikacji w
chmurze AWS.

Działąnie GitHub Actions:
![image](https://user-images.githubusercontent.com/78439685/174057212-c6e4ae98-125d-4d68-a28c-ba2f65c14183.png)

Poprawnie przesłany obraz na AWS:
![image](https://user-images.githubusercontent.com/78439685/174057287-6a1f425a-b656-4d47-a513-e95307457272.png)

Link do aplikacji na AWS: http://zadanie2-env-1.eba-sawqrua2.us-east-1.elasticbeanstalk.com/


Działanie aplikacji:

![image](https://user-images.githubusercontent.com/78439685/174057339-1a3c880d-472c-4d54-b933-c6eebf325cef.png)


CZĘŚĆ DODATKOWA
-------------------------------------------------------------------------------------------
Do pliku .yml w workflows należało dodac kod widniejący poniżej:
![image](https://user-images.githubusercontent.com/78439685/174059084-eede6715-aaf2-40d1-964f-eface041886d.png)

Dzięki niemu po wdrożeniu aplikacji na AWS został wysłany obraz na DockerHub za pomocą GitHub Actions:
![image](https://user-images.githubusercontent.com/78439685/174060161-5e9ade8d-ebb8-44c1-858a-885ae9ac30bf.png)
![image](https://user-images.githubusercontent.com/78439685/174060236-2213a123-a408-428d-8ecc-317a86fbdc18.png)

Link do repozytorium DockerHub: https://hub.docker.com/r/krzysztoflitka/zadanie2
