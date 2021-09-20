# Mongodb RelationShips

## Three types of mongodb relationships

- One to One
- One to Many
- Many to Many

---

## benifits of refrencing vs embeding

referencing prevents data from growing larger than the 16mb file size amount and it allows you to easily locate where that data is at as well as preventing mongo from having to index the data every time that large document is changed over time

---

## What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?

keeping into consideration the connections between data and how much information each connection holds will determine what type of embeding method or refrencing method to take

---

**afternoon challenge: https://github.com/DariusDeah/gregslist-auth.git**
