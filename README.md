1. SELECT country FROM country WHERE country LIKE 'A%a';

2. SELECT country FROM country 	WHERE length(country) >= 6 AND country LIKE '%n';

3. SELECT title FROM film WHERE length(title) >= 4 AND ILIKE '%T%' OR ILIKE 'T%' OR ILIKE '%T';

4. SELECT * FROM film WHERE title LIKE 'C%' AND length > 90 AND rental_rate IN 2.99;
