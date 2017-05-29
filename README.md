# vipbafrahaber
bafrahaber.com vip uyelik ve odeme modulu

## Özellikler

- REST API gibi ama graphql (mutlak versiyonlama gerekli. Ör Endpoint: http://api.bafrahaber.com.tr/v1/user )

- Üyelik ancak omniauth

- Authorization header ve token mantığıyla

- Ürün veya Üyelik paketi mantığında. (Temelde ürünler)

- SMS doğrulaması

- Üye olunca 1 gün demo kullanım.

- Telefon numarası ve e-posta adresi unique olmalı. (e-posta hiç olmayabilir de)

-


Örnek İstek
```bash
$ curl http://api.bafrahaber.com.tr/v1/user/12 -H 'Authorization: Token token="afbadb4ff8485c0adcba486b4ca90cc4"'
```


## Back-End Araçlar

- https://github.com/rails/rails

- https://github.com/rmosolgo/graphql-ruby

- http://ionicframework.com/docs/intro/installation/

- https://github.com/iyzico/iyzipay-ruby

-

## Admin Paneli

  Örnek temalar

  - http://tattek.sk/minimal/index.html

  - http://flatable.phoenixcoded.net/default/

  - http://keenthemes.com/preview/metronic/theme/admin_1/dashboard_2.html

## Front-End Araçlar

  uyelik.bafrahaber.com adresinden üye kaydı, üye girişi ve giriş yapılmış mı kontrolleri için

- https://vuejs.org/

- http://getbootstrap.com/


## Sunucu

Makine debian (wheezy) olmalı.

- https://www.digitalocean.com/

- https://nginx.org/en/

- https://www.phusionpassenger.com/
