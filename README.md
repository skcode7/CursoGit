# Cabecera H1
## Cabecera h2
### Cabecera h3
#### Cabecera h4
##### Cabecera h5
###### Cabecera h6

Underline 1
-----------
Underline 2
===========

Letra *italica* 1

Letra _italica_ 2

Formato **Negrilla**

Formato __Negrilla__

Formato ~~Tachado~~ 

Formato ~Bajo~

# Listas
1. Item 1
2. Item 2

- Item lista


# Links
<a href="http://www.google.com">Link html</a>
[Link markdown](http://www.google.com)

# Imagenes
![Logo](https://www.udemy.com/staticx/udemy/images/v6/logo-coral.svg)

# Code Snippets
Codigo JSON
```JSON
[
  {
    "title": "apples",
    "count": [12000, 20000],
    "description": {"text": "...", "sensitive": false}
  },
  {
    "title": "oranges",
    "count": [17500, null],
    "description": {"text": "...", "sensitive": false}
  }
]
```

Codigo SQL
```SQL
CREATE TABLE "topic" (
    "id" serial NOT NULL PRIMARY KEY,
    "forum_id" integer NOT NULL,
    "subject" varchar(255) NOT NULL
);
ALTER TABLE "topic"
ADD CONSTRAINT forum_id FOREIGN KEY ("forum_id")
REFERENCES "forum" ("id");

-- Initials
insert into "topic" ("forum_id", "subject")
values (2, 'D''artagnian');
```