# patika.dev-SQL-Practice-03

🔸country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız.
``` sql
SELECT COUNTRY FROM COUNTRY 
WHERE COUNTRY LIKE 'A%a';

```

🔸country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' karakteri ile sonlananları sıralayınız..
``` sql
SELECT COUNTRY FROM COUNTRY 
WHERE COUNTRY LIKE '______%n'

```

🔸film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin 'T' karakteri içeren film isimlerini sıralayınız.
``` sql
SELECT TITLE FROM FILM 
WHERE TITLE LIKE '%t%t%t%t'
```

🔸film tablosunda bulunan tüm sütunlardaki verilerden title 'C' karakteri ile başlayan ve uzunluğu (length) 90 dan büyük olan ve rental_rate 2.99 olan verileri sıralayınız.
``` sql
SELECT *
FROM FILM
WHERE TITLE LIKE 'C%'
	AND LENGTH > 90
	AND RENTAL_RATE = 2.99;

```

https://app.patika.dev/emintunahan
