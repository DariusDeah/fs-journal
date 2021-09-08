# Proxy Objects

## What are the two common operations that we will set in the handler?

get and set are the two comman operations that are set in event handlers

---

## What do we need to do on our get to not get undefined

The get operator takes two parameters the object itself and the property being accessed.
to prevent us from getting undefined we need to set a trap that tells or get to return the value of the object that is being accessed

---

## Benifits of proxys

proxys act as a bodyguard between data we want to acces so if we have data we dont want easily accesed we can put a proxy over tahat wich requires you to request accases to that info through the proxy

---

**afternoon chalange link:**https://dariusdeah.github.io/fall21-gregslist/
