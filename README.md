# Optimal Query Performance

## SQL Joins in Laravel: Enhancing Query Performance

| Section                               | Link                                                                                                                                                                         |
|---------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Introduction**                      | [Introduction](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#introduction)                                                                        |
| **Understanding Joins in Laravel**    | [Understanding Joins in Laravel](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#understanding-joins-in-laravel)                                      |
| &nbsp;&nbsp;&nbsp;Eloquent Relationship Types | [Eloquent Relationship Types](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#eloquent-relationship-types)                                       |
| **Types of Joins**                    | [Types of Joins](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#types-of-joins)                                                                      |
| &nbsp;&nbsp;&nbsp;1. Cross Join       | [1. Cross Join](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#1-cross-join)                                                                        |
| &nbsp;&nbsp;&nbsp;2. Inner Join       | [2. Inner Join](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#2-inner-join)                                                                        |
| &nbsp;&nbsp;&nbsp;3. Left Outer Join  | [3. Left Outer Join](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#3-left-outer-join)                                                              |
| &nbsp;&nbsp;&nbsp;4. Right Outer Join | [4. Right Outer Join](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#4-right-outer-join)                                                            |
| &nbsp;&nbsp;&nbsp;5. Full Outer Join  | [5. Full Outer Join](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#5-full-outer-join)                                                              |
| &nbsp;&nbsp;&nbsp;6. Self Join         | [6. Self Join](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#6-self-join)                                                                            |
| &nbsp;&nbsp;&nbsp;7. Subquery Joins    | [7. Subquery Joins](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#7-subquery-joins)                                                                  |
| **Join Performance in Laravel**       | [Join Performance in Laravel](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#join-performance-in-laravel)                                            |
| &nbsp;&nbsp;&nbsp;Optimizing Join Queries    | [Optimizing Join Queries](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#optimizing-join-queries)                                                   |
| &nbsp;&nbsp;&nbsp;Using Eager Loading          | [Using Eager Loading](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#using-eager-loading)                                                           |
| &nbsp;&nbsp;&nbsp;Indexing Strategies           | [Indexing Strategies](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#indexing-strategies)                                                         |
| &nbsp;&nbsp;&nbsp;Query Performance Analysis    | [Query Performance Analysis](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#query-performance-analysis)                                           |
| **Best Practices**                     | [Best Practices](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#best-practices)                                                                      |
| &nbsp;&nbsp;&nbsp;Common Pitfalls             | [Common Pitfalls](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#common-pitfalls)                                                                  |
| **Laravel-specific Join Methods**      | [Laravel-specific Join Methods](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#laravel-specific-join-methods)                                        |
| **Comparison with Raw SQL**            | [Comparison with Raw SQL](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#comparison-with-raw-sql)                                                      |
| **Joins in Laravel Migrations**        | [Joins in Laravel Migrations](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#joins-in-laravel-migrations)                                            |
| **Testing Join Queries**               | [Testing Join Queries](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#testing-join-queries)                                                          |
| **Version-specific Features**          | [Version-specific Features](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#version-specific-features)                                                |
| **Real-world Examples**                | [Real-world Examples](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#real-world-examples)                                                            |
| **Additional Resources**               | [Additional Resources](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#additional-resources)                                                          |
| **License**                            | [License](https://github.com/zhorton34/optimal-query-performance/blob/main/joins.md#license)                                                                                    |


[Clean Code Studio](https://cleancode.studio)
