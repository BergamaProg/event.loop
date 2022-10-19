# Event Loop : microtask ve macrotask
NodeJS 'de olduğu gibi tarayıcıdaki JavaScript kodlarının çalışması Event Loop (olay döngüsü) a dayanır.

Olay döngüsünün nasıl çalıştığını anlamak, optimizasyonlar ve bazen de kodlamalarımızı yaparken kurduğumuz
algoritma mimarisi için önemlidir.

Burada teorik olarak bu işlemlerin nasıl gerçekleştiğini ve pratik uygulamalarını inceleyeceğiz.

## Event Loop (Olay Döngüsü)
Event Loop konsepti gayet basittir. JavaScript motorumuzdaki kodlarımızı
çalıştıran döngümüz aşağıdaki gibi sonsuz bir döngüdür.
```
    	while(true){
            kodlarımız...
            ............
        }
```
