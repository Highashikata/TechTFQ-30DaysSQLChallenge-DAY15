# TechTFQ-30DaysSQLChallenge-DAY15

Finding the number of mututal friends

going through the challenge of SQL interview questions featured in the TechTFQ channel



In this repository we will be going through the SQL interview questions featured in the following YouTube video [SQL Interview Query 15 | SQL Problem Level "HARD"](https://www.youtube.com/watch?v=ka9kDqkITX4&list=PLavw5C92dz9Hxz0YhttDniNgKejQlPoAn&index=15).

### Day 15: The problem statement: Finding the number of mututal friends


**PROBLEM STATEMENT :** 
For the given friends, find the NO of mutual friends.

![image](https://github.com/user-attachments/assets/24ac56ba-0853-4744-825c-95f472488c0d)


**DDL&DML**

```
-- Drop the table if it exists
DROP TABLE IF EXISTS FriendsTable;

-- Create the table
CREATE TABLE FriendsTable (
    FRIEND1 VARCHAR(50),
    FRIEND2 VARCHAR(50)
);

-- Insert data into the table
INSERT INTO FriendsTable (FRIEND1, FRIEND2) VALUES
('Jason', 'Mary'),
('Mike', 'Mary'),
('Mike', 'Jason'),
('Susan', 'Jason'),
('John', 'Mary'),
('Susan', 'Mary');

```

**DQL**

```


```
