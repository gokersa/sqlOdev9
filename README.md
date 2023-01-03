# sqlOdev9

1.city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

2.customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

3.customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

**CEVAPLAR**
1. select city, country from city
   Inner Join country
   on city.country_id = country.country_id;

2. select payment_id, first_name from customer
   Inner Join payment
   On customer.customer_id = payment.customer_id;

3. select rental_id,first_name,last_name from rental
   Inner Join customer
   On rental.customer_id = customer.customer_id;
