# Exercise 1

```sql
CREATE TABLE courses(
    course_id INT IDENTITY PRIMARY KEY,
    course_name VARCHAR(60),
    course_author VARCHAR(40),
    course_status VARCHAR(6) CHECK (course_status in ('published','draft','inactive')),
    course_published_dt DATE
);
```

# Exercise 2


