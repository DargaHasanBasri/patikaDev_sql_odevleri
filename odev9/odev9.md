# ODEV9
1. city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
2. customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
3. customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

# CEVAPLAR
1. ```SELECT city.city, country.country from country INNER JOIN city ON country.country_id = city.country_id;``` 
2. ```SELECT payment.payment_id, customer.first_name, customer.last_name from customer INNER JOIN payment ON customer.customer_id = payment.customer_id;```
3. ```SELECT rental.rental_id, customer.first_name, customer.last_name from customer INNER JOIN rental ON customer.customer_id = rental.customer_id;```