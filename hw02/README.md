## Решение

- All 12 tasks are solved in hw02: base, standard and challenge
- No pandas or numpy, only csv module, functions, dicts and sets
- to_num() removes spaces from amounts like "1 230" and converts them to float
- clean_city() uses strip(), lower(), capitalize() and CITY_MAP dict to turn latin names into cyrillic
- Counts and sums by category, month, city and customer were done with dict accumulator d.get(key, 0)
- Unique customers per city were counted with dict of sets using setdefault()
- Duplicates were found with tuple(r.values()) and a set, there are 180 of them and all are in September
- Customer TEST has 3 orders of 9999990 each, it is test data and was removed in task 10
- After removing duplicates and TEST the revenue drop from September to October is 2.3% instead of 22.7%
