# DATA STRUCTURES AND ALGORITHMS
## Array
## Linked List

## Stack
    LIFO(Last In First Out) mantığıyla çalışır.
        #push: Yığının üzerine eleman eklemek
        #pop:  Yığından eleman çıkarmak
## Queue
    FIFO(First In First Out) mantığıyla çalışır.
        #eunqueue: Yeni elemanın eklenmesi(yeni elemanın sıraya girmesi)
        #dequeue:  Elemanın sıradan çıkarılması(sırası gelenin sıradan çıkması)
## Hash Function
    Her seferinde aynı girdiye aynı sonucu vermelidir. Farklı girdilere farklı sonuçlar vermelidir.
## Hash Table
    Hash Table, key-value prensibine dayanan bir array kümesidir. Key olarak çağırdığımız elemanın değerini(value) yansıtır.
    Hash table yerine dizileri kullanabilirdik fakat her keyi ve değerini tek tek aramak istemediğimiz için hash table kullanılır.

* Hash Collision: Farklı iki değerden aynı sayı üretilirse buna collision(çarpışma) denir.

# ALGORİTMA ANALİZİ
- **Programcının Harcadığı Süre**
- **Kullanılan Hafıza**
- **Programın Çalışma Hızı**

## Analizi Nasıl Yapabilirim?
### Büyüme hızı(***rate of growth***):
    Programa verdiğimiz input(girdi) boyutu ile çalışma zamanını fonksiyonel olarak birbirine bağlarsak bilgisayara ve programlama
    dillerine bağlı olmayan bir yapı oluşturmuş oluruz. Bununla analiz edebiliriz.
