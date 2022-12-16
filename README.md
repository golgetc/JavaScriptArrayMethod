# Javascript Array Metodları
## Array metotları Javascript'te oluşturduğunuz/kullandığınız dizilere ekleme, silme, güncelleme gibi temel becerileri sağlayan dizi metotlarıdır. 

JavaScript dilinde, diziler (array) veri türü birçok değeri bir arada tutmak için kullanılır. Dizilerde değerler bir sırayla depolanır ve her bir değere bir index numarası verilir. JavaScript dizileri, dizi elemanlarına erişmek için özel metotlar içerir. Aşağıda, JavaScript dizileriyle ilgili bazı yaygın metotlar ve örnekleri verilmiştir:

## push()
Bu metodu kullanarak bir dizinin sonuna yeni bir değer ekleyebilirsiniz. Örnek olarak, aşağıdaki kod bloğunda, push() metodu kullanılarak bir dizinin sonuna yeni bir sayı eklenmiştir:
```
let numbers = [1, 2, 3];
numbers.push(4); // numbers dizisi şimdi [1, 2, 3, 4] olur
```

## pop()
Bu metot bir dizinin son elemanını siler ve silinen elemanı döndürür. Örnek olarak, aşağıdaki kod bloğunda, pop() metodu kullanılarak dizinin son elemanı silinmiş ve silinen eleman ekrana yazdırılmıştır:
```
let numbers = [1, 2, 3];
let last = numbers.pop(); // numbers dizisi şimdi [1, 2] olur ve last değişkenine 3 değeri atanır
console.log(last); // 3
```

## shift()
Bu metodu kullanarak bir dizinin ilk elemanını siler ve silinen elemanı döndürür. Örnek olarak, aşağıdaki kod bloğunda, shift() metodu kullanılarak dizinin ilk elemanı silinmiş ve silinen eleman ekrana yazdırılmıştır:
```
let numbers = [1, 2, 3];
let first = numbers.shift(); // numbers dizisi şimdi [2, 3] olur ve first değişkenine 1 değeri atanır
console.log(first); // 1
```

## unshift()
Bu metodu kullanarak bir dizinin başına yeni bir değer ekleyebilirsiniz. Örnek olarak, aşağıdaki kod bloğunda, unshift() metodu kullanılarak bir dizinin başına yeni bir sayı eklenmiştir:
```
let numbers = [1, 2, 3];
numbers.unshift('0'); // numbers dizisi şimdi [0, 1, 2, 3] olur.
```

## indexOf()
Bu metodu kullanarak bir dizide belirli bir değerin bulunduğu ilk indeksi bulabilirsiniz. Örnek olarak, aşağıdaki kod bloğunda, indexOf() metodu kullanılarak bir dizide 2 değerinin indeksi bulunmuş ve ekrana yazdırılmıştır:
```
let numbers = [1, 2, 3, 4, 2];
let index = numbers.indexOf(2); // index değişkenine 1 değeri atanır
console.log(index); // 1
```

## slice()
Bu metodu kullanarak bir diziden belirli bir aralıkta elemanları alabilirsiniz. Örnek olarak, aşağıdaki kod bloğunda, slice() metodu kullanılarak dizinin 2. ve 4. elemanları arasındaki elemanlar alınmış ve yeni bir dizi olarak atanmıştır:
```
let numbers = [1, 2, 3, 4, 5];
let newNumbers = numbers.slice(1, 4); // newNumbers dizisi şimdi [2, 3, 4] olur
```

## sort()
Bu metodu kullanarak bir dizinin elemanlarını sıralayabilirsiniz. Örnek olarak, aşağıdaki kod bloğunda, sort() metodu kullanılarak dizinin elemanları sayısal olarak sıralanmıştır:
```
let numbers = [3, 1, 4, 2];
numbers.sort(); // numbers dizisi şimdi [1, 2, 3, 4] olur
```

## reverse()
Bu metodu kullanarak bir dizinin elemanlarını tersine çevirebilirsiniz. Örnek olarak, aşağıdaki kod bloğunda, reverse() metodu kullanılarak dizinin elemanları tersine çevrilmiştir:
```
let numbers = [1, 2, 3, 4];
numbers.reverse(); // numbers dizisi şimdi [4, 3, 2, 1] olur
```
