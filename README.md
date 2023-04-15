SELECT SUM(salary), Dept FROM register GROUP BY(Dept) HAVING SUM(salary) >50000
