# Makina Öğrenmesi ile Ev Fiyat Tahmini Uygulaması

## Kurulum

Virtual Environment Kurulumu

```sh
$ virtualenv2 --no-site-packages env
$ source env/bin/activate
```

Kütüphanelerin Kurulumu

```sh
$ pip install -r requirements.txt
```

## Çalıştırma

```sh
(env)$ cd fiyatTahmin
(env)$ python manage.py runserver
```

## Makina Öğrenmesini Konsol Ortamında Çalıştırma

```sh
(env)$ cd fiyatTahmin
(env)$ cd ev_fiyat_tahmin
(env)$ python test_veri_okuma.py
```

## NOT
Arayüzde seçilen bilgileri kesinlikle doğru kodlayın örneğin İstanbulun Beşiktaş ilçesi için yapıyorsanız mahalleyi kesinlikle beşiktaşın mahallelerinden seçiniz iyileştirmelerle beraber bunları da düzeltip arayüzü zenginleştireceğim.
