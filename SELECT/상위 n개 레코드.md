### 상위 n개 레코드

🔒 [문제 보기](https://school.programmers.co.kr/learn/courses/30/lessons/59405)

```SQL
SELECT NAME FROM ANIMAL_INS 
WHERE DATETIME IN (SELECT MIN(DATETIME)FROM ANIMAL_INS);
```

------
