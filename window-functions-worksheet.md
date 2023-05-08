```sql
CREATE TABLE `students` (
    `id` int NOT NULL AUTO_INCREMENT,
    `first_name` varchar(255) NOT NULL,
    `last_name` varchar(255) NOT NULL,
    `email` varchar(255) NOT NULL,
    `phone` varchar(255),
    `birth_date` date,
    `address` varchar(255),
    `iq` int,
    `batch_id` int,
    PRIMARY KEY (`id`)
);
```

1. Print the student names along with the number of students in their batch.

```sql
```

2. Print the student names along with the average IQ of their batch.

```sql
```

3. Print the student names along with the maximum IQ of their batch.

```sql
```

4. Print the student names along with their rank based on IQ.

```sql
```

5. Print the student names along with their rank in their batch based on IQ.

```sql
```

6. Print the student names along with their rank in their batch based on IQ. Ties should not increase the rank.

```sql
```

7. Print the student names along with their rank in their batch based on IQ. Ties should not be counted and broken by ID.

```sql
```

8. Find the rank of batches based on the start date of the batch.

```sql
```

9. Sort the instructors by the first and last name and assign them a roll number.

```sql
```