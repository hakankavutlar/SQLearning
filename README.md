# SQLearning
## SORU 1
SELECT title,description FROM film 
## SORU 2
SELECT title,description From film 
WHERE (length<75 AND 60<length)
## SORU 3
SELECT title,description FROM film 
WHERE rental_rate=0.99 AND (replacement_cost=12.99 OR replacement_cost=28.99); 
## SORU 4
SELECT last_name FROM customer 
WHERE first_name='Mary';
## SORU 5
SELECT * FROM film
WHERE NOT (50<length) 
AND NOT rental_rate = 2.99 OR NOT rental_rate = 4.99;




