## 1. Logging in to the Database

`psql <databaseName> <username>`

<details>
<summary>Terminal Output</summary>

```
psql <databaseName> <username>
psql postgres postgres
password: ~enter password~
```

```
psql (15.2)
WARNING: Console code page (850) differs from Windows code page (1252)
         8-bit characters might not work correctly. See psql reference
         page "Notes for Windows users" for details.
Type "help" for help.

postgres=#
```

</details><br>

---

## 2. Postgres Help

`help`

<details>
<summary>Terminal Output</summary>

```
postgres=# help
You are using psql, the command-line interface to PostgreSQL.
Type:  \copyright for distribution terms
       \h for help with SQL commands
       \? for help with psql commands
       \g or terminate with semicolon to execute query
       \q to quit
postgres=#
```

</details><br>

---

## 3. Add the Contents of an External File

`\include </path/file.sql>`

<details>
<summary>Terminal Output</summary>

```
postgres=# \include desktop/build-hotel.sql
psql:desktop/build-hotel.sql:4: ERROR:  table "invoices" does not exist
psql:desktop/build-hotel.sql:5: ERROR:  table "reservations" does not exist
psql:desktop/build-hotel.sql:6: ERROR:  table "customers" does not exist
psql:desktop/build-hotel.sql:7: ERROR:  table "rooms" does not exist
psql:desktop/build-hotel.sql:8: ERROR:  table "room_types" does not exist
CREATE TABLE
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
CREATE TABLE
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
CREATE TABLE
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
CREATE TABLE
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
INSERT 0 1
psql:desktop/build-hotel.sql:344: NOTICE:  function fixup_dates() does not exist, skipping
DROP FUNCTION
CREATE FUNCTION
 fixup_dates
-------------

(1 row)


UPDATE 41
CREATE TABLE
INSERT 0 63
postgres=#
```

</details><br>

---

## 4. List All Tables In The Current Database

`\dt`

<details>
<summary>Terminal Output</summary>

```
postgres=# \dt
            List of relations
 Schema |     Name     | Type  |  Owner
--------+--------------+-------+----------
 public | customers    | table | postgres
 public | invoices     | table | postgres
 public | reservations | table | postgres
 public | room_types   | table | postgres
 public | rooms        | table | postgres
(5 rows)


postgres=#
```

</details><br>

---

## 5. The SELECT Statement

`SELECT ... FROM ...;`

`SELECT name, phone, country FROM customers;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT name, phone, country FROM customers;
          name           |       phone        |   country
-------------------------+--------------------+--------------
 John Smith              | 0151 123 4567      | UK
 Sue Jones               | 0201 234 5678      | UK
 Alice Evans             | 0161 345 6789      | UK
 Mohammed Trungpa        | 0161 456 7890      | UK
 Steven King             | 01245 134 4678     | UK
 Nadia Sethuraman        |                    | UK
 Melinda Marsh           | 070 1513 5671      | UK
 Mart├¡n Sommer          | (91) 555 22 82     | Spain
 Laurence Lebihan        | 91.24.4555         | France
 Keith Stewart           | 078 4679 1282      | UK
 Carlos Porter           | 070 2679 6812      | UK
 Carine Schmitt          | 40.32.2555         | France
 Jean King               | 07025 551 838      | USA
 Peter Ferguson          | 03 9520 4555       | Australia
 Janine Labrune          | 40.67.8555         | France
 Jonas Bergulfsen        | 07-98 9555         | Norway
 Susan Nelson            | 0415 555 1450      | USA
 Zbyszek Piestrzeniewicz | (26) 642-7555      | Poland
 Roland Keitel           | +49 69 66 90 2555  | Germany
 Julie Murphy            | 0650 555 5787      | USA
 Kwai Lee                | 0212 555 7818      | USA
 Diego Freyre            | (91) 555 94 44     | Spain
 Christina Berglund      | 0921-12 3555       | Sweden
 Jytte Petersen          | 31 12 3555         | Denmark
 Mary Saveley            | 78.32.5555         | France
 Eric Natividad          | +65 221 7555       | Singapore
 Jeff Young              | 0212 555 7413      | USA
 Kelvin Leong            | 0215 555 1555      | USA
 Juri Hashimoto          | 0650 555 6809      | USA
 Wendy Victorino         | +65 224 1555       | Singapore
 Veysel Oeztan           | +47 2267 3215      | Norway
 Keith Franco            | 2035557845         | USA
 Isabel de Castro        | (1) 356-5555       | Portugal
 Martine Ranc├®          | 20.16.1555         | France
 Marie Bertrand          | (1) 42.34.2555     | France
 Jerry Tseng             | 6175555555         | USA
 Julie King              | 2035552570         | USA
 Mory Kentary            | +81 06 6342 5555   | Japan
 Michael Frick           | 2125551500         | USA
 Matti Karttunen         | 90-224 8555        | Finland
 Rachel Ashworth         | (171) 555-1555     | UK
 Dean Cassidy            | +353 1862 1555     | Ireland
 Leslie Taylor           | 6175558428         | USA
 Elizabeth Devon         | (171) 555-2282     | UK
 Yoshi Tamuri            | (604) 555-3392     | Canada
 Miguel Barajas          | 6175557555         | USA
 Julie Young             | 6265557265         | USA
 Brydey Walker           | +612 9411 1555     | Singapore
 Fr├®d├®rique Citeaux    | 88.60.1555         | France
 Mike Gao                | +852 2251 1555     | Hong Kong
 Eduardo Saavedra        | (93) 203 4555      | Spain
 Mary Young              | 3105552373         | USA
 Horst Kloss             | 0372-555188        | Germany
 Palle Ibsen             | 86 21 3555         | Denmark
 Jean Fresni├¿re         | (514) 555-8054     | Canada
 Alejandra Camino        | (91) 745 6555      | Spain
 Valarie Thompson        | 7605558146         | USA
 Helen Bennett           | (198) 555-8888     | UK
 Annette Roulet          | 61.77.6555         | France
 Renate Messner          | 069-0555984        | Germany
 Paolo Accorti           | 011-4988555        | Italy
 Daniel Da Silva         | +33 1 46 62 7555   | France
 Daniel Tonini           | 30.59.8555         | France
 Henriette Pfalzheim     | 0221-5554327       | Germany
 Elizabeth Lincoln       | (604) 555-4555     | Canada
 Peter Franken           | 089-0877555        | Germany
 Anna O'Hara             | 02 9936 8555       | Australia
 Giovanni Rovelli        | 035-640555         | Italy
 Adrian Huxley           | +61 2 9495 8555    | Australia
 Marta Hernandez         | 6175558555         | USA
 Ed Harrison             | +41 26 425 50 01   | Switzerland
 Mihael Holz             | 0897-034555        | Switzerland
 Jan Klaeboe             | +47 2212 1555      | Norway
 Bradley Schuyler        | +31 20 491 9555    | Netherlands
 Mel Andersen            | 030-0074555        | Germany
 Pirkko Koskitalo        | 981-443655         | Finland
 Catherine Dewey         | (02) 5554 67       | Belgium
 Steve Frick             | 9145554562         | USA
 Wing Huang              | 5085559555         | USA
 Julie Brown             | 6505551386         | USA
 Mike Graham             | +64 9 312 5555     | New Zealand
 Ann Brown               | (171) 555-0297     | UK
 William Brown           | 2015559350         | USA
 Ben Calaghan            | 61-7-3844-6555     | Australia
 Kalle Suominen          | +358 9 8045 555    | Finland
 Philip Cramer           | 0555-09555         | Germany
 Francisca Cervantes     | 2155554695         | USA
 Jesus Fernandez         | +34 913 728 555    | Spain
 Brian Chandler          | 2155554369         | USA
 Patricia McKenna        | 2967 555           | Ireland
 Laurence Lebihan        | 91.24.4555         | France
 Paul Henriot            | 26.47.1555         | France
 Armand Kuger            | +27 21 550 3555    | South Africa
 Wales MacKinlay         | 64-9-3763555       | New Zealand
 Karin Josephs           | 0251-555259        | Germany
 Juri Yoshido            | 6175559555         | USA
 Dorothy Young           | 6035558647         | USA
 Lino Rodriguez          | (1) 354-2555       | Portugal
 Braun Urs               | 0452-076555        | Switzerland
 Allen Nelson            | 6175558555         | USA
 Pascale Cartrain        | (071) 23 67 2555   | Belgium
 Georg Pipps             | 6562-9555          | Austria
 Arnold Cruz             | +63 2 555 3587     | Philippines
 Maurizio Moroni         | 0522-556555        | Italy
 Akiko Shimamura         | +81 3 3584 0555    | Japan
 Dominique Perrier       | (1) 47.55.6555     | France
 Rita M├╝ller            | 0711-555361        | Germany
 Sarah McRoy             | 04 499 9555        | New Zealand
 Michael Donnermeyer     |  +49 89 61 08 9555 | Germany
 Maria Hernandez         | 2125558493         | USA
 Alexander Feuer         | 0342-555176        | Germany
 Dan Lewis               | 2035554407         | USA
 Martha Larsson          | 0695-34 6555       | Sweden
 Sue Frick               | 4085553659         | USA
 Roland Mendel           | 7675-3555          | Austria
 Leslie Murphy           | 2035559545         | USA
 Yu Choi                 | 2125551957         | USA
 Mart├¡n Sommer          | (91) 555 22 82     | Spain
 Sven Ottlieb            | 0241-039123        | Germany
 Violeta Benitez         | 5085552555         | USA
 Carmen Anton            | +34 913 728555     | Spain
 Sean Clenahan           | 61-9-3844-6555     | Australia
 Franco Ricotti          | +39 022515555      | Italy
 Steve Thompson          | 3105553722         | USA
 Hanna Moos              | 0621-08555         | Germany
 Alexander Semenov       | +7 812 293 0521    | Russia
 Raanan Altagar,G M      | + 972 9 959 8555   | Israel
 Jos├® Pedro Roel        | (95) 555 82 82     | Spain
 Rosa Salazar            | 2155559857         | USA
 Sue Taylor              | 4155554312         | USA
 Thomas Smith            | (171) 555-7555     | UK
 Valarie Franco          | 6175552555         | USA
 Tony Snowden            | +64 9 5555500      | New Zealand
(133 rows)


postgres=#
```

</details><br>

---

## 6. Multiline SQL Commands

The SQL command can extend across several lines, but each keyword, name or value cannot be split over more than one line.

```
SELECT name,
     phone,
     country
FROM
     customers;
```

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT name,
postgres-#      phone,
postgres-#      country
postgres-# FROM
postgres-#      customers;
          name           |       phone        |   country
-------------------------+--------------------+--------------
 John Smith              | 0151 123 4567      | UK
 Sue Jones               | 0201 234 5678      | UK
 Alice Evans             | 0161 345 6789      | UK
 Mohammed Trungpa        | 0161 456 7890      | UK
 Steven King             | 01245 134 4678     | UK
 Nadia Sethuraman        |                    | UK
 Melinda Marsh           | 070 1513 5671      | UK
 Mart├¡n Sommer          | (91) 555 22 82     | Spain
 Laurence Lebihan        | 91.24.4555         | France
 Keith Stewart           | 078 4679 1282      | UK
 Carlos Porter           | 070 2679 6812      | UK
 Carine Schmitt          | 40.32.2555         | France
 Jean King               | 07025 551 838      | USA
 Peter Ferguson          | 03 9520 4555       | Australia
 Janine Labrune          | 40.67.8555         | France
 Jonas Bergulfsen        | 07-98 9555         | Norway
 Susan Nelson            | 0415 555 1450      | USA
 Zbyszek Piestrzeniewicz | (26) 642-7555      | Poland
 Roland Keitel           | +49 69 66 90 2555  | Germany
 Julie Murphy            | 0650 555 5787      | USA
 Kwai Lee                | 0212 555 7818      | USA
 Diego Freyre            | (91) 555 94 44     | Spain
 Christina Berglund      | 0921-12 3555       | Sweden
 Jytte Petersen          | 31 12 3555         | Denmark
 Mary Saveley            | 78.32.5555         | France
 Eric Natividad          | +65 221 7555       | Singapore
 Jeff Young              | 0212 555 7413      | USA
 Kelvin Leong            | 0215 555 1555      | USA
 Juri Hashimoto          | 0650 555 6809      | USA
 Wendy Victorino         | +65 224 1555       | Singapore
 Veysel Oeztan           | +47 2267 3215      | Norway
 Keith Franco            | 2035557845         | USA
 Isabel de Castro        | (1) 356-5555       | Portugal
 Martine Ranc├®          | 20.16.1555         | France
 Marie Bertrand          | (1) 42.34.2555     | France
 Jerry Tseng             | 6175555555         | USA
 Julie King              | 2035552570         | USA
 Mory Kentary            | +81 06 6342 5555   | Japan
 Michael Frick           | 2125551500         | USA
 Matti Karttunen         | 90-224 8555        | Finland
 Rachel Ashworth         | (171) 555-1555     | UK
 Dean Cassidy            | +353 1862 1555     | Ireland
 Leslie Taylor           | 6175558428         | USA
 Elizabeth Devon         | (171) 555-2282     | UK
 Yoshi Tamuri            | (604) 555-3392     | Canada
 Miguel Barajas          | 6175557555         | USA
 Julie Young             | 6265557265         | USA
 Brydey Walker           | +612 9411 1555     | Singapore
 Fr├®d├®rique Citeaux    | 88.60.1555         | France
 Mike Gao                | +852 2251 1555     | Hong Kong
 Eduardo Saavedra        | (93) 203 4555      | Spain
 Mary Young              | 3105552373         | USA
 Horst Kloss             | 0372-555188        | Germany
 Palle Ibsen             | 86 21 3555         | Denmark
 Jean Fresni├¿re         | (514) 555-8054     | Canada
 Alejandra Camino        | (91) 745 6555      | Spain
 Valarie Thompson        | 7605558146         | USA
 Helen Bennett           | (198) 555-8888     | UK
 Annette Roulet          | 61.77.6555         | France
 Renate Messner          | 069-0555984        | Germany
 Paolo Accorti           | 011-4988555        | Italy
 Daniel Da Silva         | +33 1 46 62 7555   | France
 Daniel Tonini           | 30.59.8555         | France
 Henriette Pfalzheim     | 0221-5554327       | Germany
 Elizabeth Lincoln       | (604) 555-4555     | Canada
 Peter Franken           | 089-0877555        | Germany
 Anna O'Hara             | 02 9936 8555       | Australia
 Giovanni Rovelli        | 035-640555         | Italy
 Adrian Huxley           | +61 2 9495 8555    | Australia
 Marta Hernandez         | 6175558555         | USA
 Ed Harrison             | +41 26 425 50 01   | Switzerland
 Mihael Holz             | 0897-034555        | Switzerland
 Jan Klaeboe             | +47 2212 1555      | Norway
 Bradley Schuyler        | +31 20 491 9555    | Netherlands
 Mel Andersen            | 030-0074555        | Germany
 Pirkko Koskitalo        | 981-443655         | Finland
 Catherine Dewey         | (02) 5554 67       | Belgium
 Steve Frick             | 9145554562         | USA
 Wing Huang              | 5085559555         | USA
 Julie Brown             | 6505551386         | USA
 Mike Graham             | +64 9 312 5555     | New Zealand
 Ann Brown               | (171) 555-0297     | UK
 William Brown           | 2015559350         | USA
 Ben Calaghan            | 61-7-3844-6555     | Australia
 Kalle Suominen          | +358 9 8045 555    | Finland
 Philip Cramer           | 0555-09555         | Germany
 Francisca Cervantes     | 2155554695         | USA
 Jesus Fernandez         | +34 913 728 555    | Spain
 Brian Chandler          | 2155554369         | USA
 Patricia McKenna        | 2967 555           | Ireland
 Laurence Lebihan        | 91.24.4555         | France
 Paul Henriot            | 26.47.1555         | France
 Armand Kuger            | +27 21 550 3555    | South Africa
 Wales MacKinlay         | 64-9-3763555       | New Zealand
 Karin Josephs           | 0251-555259        | Germany
 Juri Yoshido            | 6175559555         | USA
 Dorothy Young           | 6035558647         | USA
 Lino Rodriguez          | (1) 354-2555       | Portugal
 Braun Urs               | 0452-076555        | Switzerland
 Allen Nelson            | 6175558555         | USA
 Pascale Cartrain        | (071) 23 67 2555   | Belgium
 Georg Pipps             | 6562-9555          | Austria
 Arnold Cruz             | +63 2 555 3587     | Philippines
 Maurizio Moroni         | 0522-556555        | Italy
 Akiko Shimamura         | +81 3 3584 0555    | Japan
 Dominique Perrier       | (1) 47.55.6555     | France
 Rita M├╝ller            | 0711-555361        | Germany
 Sarah McRoy             | 04 499 9555        | New Zealand
 Michael Donnermeyer     |  +49 89 61 08 9555 | Germany
 Maria Hernandez         | 2125558493         | USA
 Alexander Feuer         | 0342-555176        | Germany
 Dan Lewis               | 2035554407         | USA
 Martha Larsson          | 0695-34 6555       | Sweden
 Sue Frick               | 4085553659         | USA
 Roland Mendel           | 7675-3555          | Austria
 Leslie Murphy           | 2035559545         | USA
 Yu Choi                 | 2125551957         | USA
 Mart├¡n Sommer          | (91) 555 22 82     | Spain
 Sven Ottlieb            | 0241-039123        | Germany
 Violeta Benitez         | 5085552555         | USA
 Carmen Anton            | +34 913 728555     | Spain
 Sean Clenahan           | 61-9-3844-6555     | Australia
 Franco Ricotti          | +39 022515555      | Italy
 Steve Thompson          | 3105553722         | USA
 Hanna Moos              | 0621-08555         | Germany
 Alexander Semenov       | +7 812 293 0521    | Russia
 Raanan Altagar,G M      | + 972 9 959 8555   | Israel
 Jos├® Pedro Roel        | (95) 555 82 82     | Spain
 Rosa Salazar            | 2155559857         | USA
 Sue Taylor              | 4155554312         | USA
 Thomas Smith            | (171) 555-7555     | UK
 Valarie Franco          | 6175552555         | USA
 Tony Snowden            | +64 9 5555500      | New Zealand
(133 rows)


postgres=#
```

</details><br>

---

## 7. Return ALL Columns

`SELECT * FROM rooms;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM rooms;
 room_no |  rate  |  room_type   | no_guests
---------+--------+--------------+-----------
     101 |  85.00 | PREMIUM      |         2
     102 |  85.00 | PREMIUM      |         2
     103 |  85.00 | PREMIUM      |         2
     104 |  85.00 | PREMIUM      |         2
     105 |  85.00 | PREMIUM      |         2
     106 |  85.00 | PREMIUM      |         2
     107 |  85.00 | PREMIUM      |         2
     108 |  98.00 | PREMIUM PLUS |         2
     109 |  98.00 | PREMIUM PLUS |         2
     110 |  98.00 | PREMIUM PLUS |         2
     111 |  98.00 | PREMIUM PLUS |         2
     112 |  98.00 | PREMIUM PLUS |         2
     201 |  85.00 | PREMIUM      |         2
     202 |  85.00 | PREMIUM      |         2
     203 |  85.00 | PREMIUM      |         2
     204 |  85.00 | PREMIUM      |         2
     205 |  85.00 | PREMIUM      |         3
     206 |  85.00 | PREMIUM      |         3
     207 |  85.00 | PREMIUM      |         3
     208 |  98.00 | PREMIUM PLUS |         2
     209 |  98.00 | PREMIUM PLUS |         2
     210 |  98.00 | PREMIUM PLUS |         2
     211 |  98.00 | PREMIUM PLUS |         3
     212 |  98.00 | PREMIUM PLUS |         3
     301 | 110.00 | PREMIER      |         2
     302 | 110.00 | PREMIER      |         2
     303 | 110.00 | PREMIER      |         2
     304 | 110.00 | PREMIER      |         2
     305 | 110.00 | PREMIER      |         2
     306 | 110.00 | PREMIER      |         2
     307 | 110.00 | PREMIER      |         2
     308 | 123.00 | PREMIER PLUS |         2
     309 | 123.00 | PREMIER PLUS |         2
     310 | 123.00 | PREMIER PLUS |         2
     311 | 123.00 | PREMIER PLUS |         2
     312 | 123.00 | PREMIER PLUS |         2
     401 | 110.00 | PREMIER      |         2
     402 | 110.00 | PREMIER      |         2
     403 | 110.00 | PREMIER      |         2
     404 | 110.00 | PREMIER      |         2
     405 | 110.00 | PREMIER      |         2
     406 | 110.00 | PREMIER      |         2
     407 | 110.00 | PREMIER      |         2
     408 | 123.00 | PREMIER PLUS |         2
     409 | 123.00 | PREMIER PLUS |         2
     410 | 123.00 | PREMIER PLUS |         2
     411 | 123.00 | FAMILY       |         4
     412 | 123.00 | FAMILY       |         4
(48 rows)


postgres=#
```

</details><br>

---

## 8. See What Columns Exist in a Table

`\d <table_name>`

`\d customers`

<details>
<summary>Terminal Output</summary>

```
postgres=# \d customers
                                     Table "public.customers"
  Column  |          Type          | Collation | Nullable |                Default
----------+------------------------+-----------+----------+---------------------------------------
 id       | integer                |           | not null | nextval('customers_id_seq'::regclass)
 name     | character varying(30)  |           | not null |
 email    | character varying(120) |           | not null |
 phone    | character varying(20)  |           |          |
 address  | character varying(120) |           |          |
 city     | character varying(30)  |           |          |
 postcode | character varying(12)  |           |          |
 country  | character varying(20)  |           |          |
Indexes:
    "customers_pkey" PRIMARY KEY, btree (id)
Referenced by:
    TABLE "reservations" CONSTRAINT "res_guest_fk" FOREIGN KEY (cust_id) REFERENCES customers(id)


postgres=#
```

</details><br>

---

## 9. UPPER/lower case

The use of UPPER/lower case is only to emphasise and differentiate the SQL keywords (upper case) from the other names (lower case) e.g. column and table names.  
**SQL keywords are not case-sensitive.**

---

## 10. Scrolling the Results

`Space - Next screenful`

`B - Previous screenful`

`Down Arrow - Next line`

`Up Arrow - Previous line`

`Q  - Quit back to prompt`

---

## 11. Exercise 1

### 11.1

- List the name, phone and email of all customers
- `SELECT name, phone, email FROM customers;`
<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT name, phone, email FROM customers;
          name           |       phone        |              email
-------------------------+--------------------+----------------------------------
 John Smith              | 0151 123 4567      | j.smith@johnsmith.org
 Sue Jones               | 0201 234 5678      | s.jones1234@gmail.com
 Alice Evans             | 0161 345 6789      | alice.evans001@hotmail.com
 Mohammed Trungpa        | 0161 456 7890      | mo.trungpa@hotmail.com
 Steven King             | 01245 134 4678     | steve.king123@hotmail.com
 Nadia Sethuraman        |                    | nadia.sethuraman@mail.com
 Melinda Marsh           | 070 1513 5671      | mel.marsh-123@gmail.com
 Mart├¡n Sommer          | (91) 555 22 82     | martin.sommer@dfgg.net
 Laurence Lebihan        | 91.24.4555         | laurence.lebihan@xmzx.net
 Keith Stewart           | 078 4679 1282      | keith.stewart@gmail.com
 Carlos Porter           | 070 2679 6812      | carlos.porter@ortynuf.com
 Carine Schmitt          | 40.32.2555         | carine.schmitt@dftu.net
 Jean King               | 07025 551 838      | jean.king@hjgp.net
 Peter Ferguson          | 03 9520 4555       | peter.ferguson@mxnx.net
 Janine Labrune          | 40.67.8555         | janine.labrune@dlsh.net
 Jonas Bergulfsen        | 07-98 9555         | jonas.bergulfsen@dxbn.net
 Susan Nelson            | 0415 555 1450      | susan.nelson@fsve.net
 Zbyszek Piestrzeniewicz | (26) 642-7555      | zbyszek.piestrzeniewicz@askt.net
 Roland Keitel           | +49 69 66 90 2555  | roland.keitel@riys.net
 Julie Murphy            | 0650 555 5787      | julie.murphy@lrtc.net
 Kwai Lee                | 0212 555 7818      | kwai.lee@imic.net
 Diego Freyre            | (91) 555 94 44     | diego.freyre@amyr.net
 Christina Berglund      | 0921-12 3555       | christina.berglund@cggp.net
 Jytte Petersen          | 31 12 3555         | jytte.petersen@cpbn.net
 Mary Saveley            | 78.32.5555         | mary.saveley@yppl.net
 Eric Natividad          | +65 221 7555       | eric.natividad@swll.net
 Jeff Young              | 0212 555 7413      | jeff.young@hahh.net
 Kelvin Leong            | 0215 555 1555      | kelvin.leong@mqzy.net
 Juri Hashimoto          | 0650 555 6809      | juri.hashimoto@fttv.net
 Wendy Victorino         | +65 224 1555       | wendy.victorino@ueai.net
 Veysel Oeztan           | +47 2267 3215      | veysel.oeztan@vqkn.net
 Keith Franco            | 2035557845         | keith.franco@dlha.net
 Isabel de Castro        | (1) 356-5555       | isabel.de.castro@fpro.net
 Martine Ranc├®          | 20.16.1555         | martine.ranc├®@xeqs.net
 Marie Bertrand          | (1) 42.34.2555     | marie.bertrand@glut.net
 Jerry Tseng             | 6175555555         | jerry.tseng@etea.net
 Julie King              | 2035552570         | julie.king@yhfj.net
 Mory Kentary            | +81 06 6342 5555   | mory.kentary@nqfg.net
 Michael Frick           | 2125551500         | michael.frick@jdep.net
 Matti Karttunen         | 90-224 8555        | matti.karttunen@xkig.net
 Rachel Ashworth         | (171) 555-1555     | rachel.ashworth@rzyb.net
 Dean Cassidy            | +353 1862 1555     | dean.cassidy@sntj.net
 Leslie Taylor           | 6175558428         | leslie.taylor@tunp.net
 Elizabeth Devon         | (171) 555-2282     | elizabeth.devon@bpcb.net
 Yoshi Tamuri            | (604) 555-3392     | yoshi.tamuri@juuq.net
 Miguel Barajas          | 6175557555         | miguel.barajas@rsyq.net
 Julie Young             | 6265557265         | julie.young@rmhl.net
 Brydey Walker           | +612 9411 1555     | brydey.walker@kwtj.net
 Fr├®d├®rique Citeaux    | 88.60.1555         | fr├®d├®rique.citeaux@vekn.net
 Mike Gao                | +852 2251 1555     | mike.gao@pdrv.net
 Eduardo Saavedra        | (93) 203 4555      | eduardo.saavedra@tiqa.net
 Mary Young              | 3105552373         | mary.young@ratm.net
 Horst Kloss             | 0372-555188        | horst.kloss@bpzv.net
 Palle Ibsen             | 86 21 3555         | palle.ibsen@bjqn.net
 Jean Fresni├¿re         | (514) 555-8054     | jean.fresni├¿re@uxsm.net
 Alejandra Camino        | (91) 745 6555      | alejandra.camino@omet.net
 Valarie Thompson        | 7605558146         | valarie.thompson@brll.net
 Helen Bennett           | (198) 555-8888     | helen.bennett@quet.net
 Annette Roulet          | 61.77.6555         | annette.roulet@lgha.net
 Renate Messner          | 069-0555984        | renate.messner@ebse.net
 Paolo Accorti           | 011-4988555        | paolo.accorti@xcuw.net
 Daniel Da Silva         | +33 1 46 62 7555   | daniel.da.silva@hijy.net
 Daniel Tonini           | 30.59.8555         | daniel.tonini@mxvw.net
 Henriette Pfalzheim     | 0221-5554327       | henriette.pfalzheim@hmib.net
 Elizabeth Lincoln       | (604) 555-4555     | elizabeth.lincoln@elct.net
 Peter Franken           | 089-0877555        | peter.franken@fszx.net
 Anna O'Hara             | 02 9936 8555       | anna.o"hara@hzjw.net
 Giovanni Rovelli        | 035-640555         | giovanni.rovelli@xrbz.net
 Adrian Huxley           | +61 2 9495 8555    | adrian.huxley@hmep.net
 Marta Hernandez         | 6175558555         | marta.hernandez@xqti.net
 Ed Harrison             | +41 26 425 50 01   | ed.harrison@svjb.net
 Mihael Holz             | 0897-034555        | mihael.holz@dnji.net
 Jan Klaeboe             | +47 2212 1555      | jan.klaeboe@mpnl.net
 Bradley Schuyler        | +31 20 491 9555    | bradley.schuyler@stie.net
 Mel Andersen            | 030-0074555        | mel.andersen@nggg.net
 Pirkko Koskitalo        | 981-443655         | pirkko.koskitalo@rcva.net
 Catherine Dewey         | (02) 5554 67       | catherine.dewey@ndft.net
 Steve Frick             | 9145554562         | steve.frick@unam.net
 Wing Huang              | 5085559555         | wing.huang@romc.net
 Julie Brown             | 6505551386         | julie.brown@zbfm.net
 Mike Graham             | +64 9 312 5555     | mike.graham@nlpt.net
 Ann Brown               | (171) 555-0297     | ann.brown@xwkb.net
 William Brown           | 2015559350         | william.brown@wrbo.net
 Ben Calaghan            | 61-7-3844-6555     | ben.calaghan@bprq.net
 Kalle Suominen          | +358 9 8045 555    | kalle.suominen@acif.net
 Philip Cramer           | 0555-09555         | philip.cramer@gmlf.net
 Francisca Cervantes     | 2155554695         | francisca.cervantes@sxxp.net
 Jesus Fernandez         | +34 913 728 555    | jesus.fernandez@cgxs.net
 Brian Chandler          | 2155554369         | brian.chandler@wdgi.net
 Patricia McKenna        | 2967 555           | patricia.mckenna@eert.net
 Laurence Lebihan        | 91.24.4555         | laurence.lebihan@xmzx.net
 Paul Henriot            | 26.47.1555         | paul.henriot@uwua.net
 Armand Kuger            | +27 21 550 3555    | armand.kuger@axkq.net
 Wales MacKinlay         | 64-9-3763555       | wales.mackinlay@omis.net
 Karin Josephs           | 0251-555259        | karin.josephs@gyfv.net
 Juri Yoshido            | 6175559555         | juri.yoshido@klqb.net
 Dorothy Young           | 6035558647         | dorothy.young@cwtg.net
 Lino Rodriguez          | (1) 354-2555       | lino.rodriguez@xscn.net
 Braun Urs               | 0452-076555        | braun.urs@aols.net
 Allen Nelson            | 6175558555         | allen.nelson@eruo.net
 Pascale Cartrain        | (071) 23 67 2555   | pascale.cartrain@oggv.net
 Georg Pipps             | 6562-9555          | georg.pipps@uyvb.net
 Arnold Cruz             | +63 2 555 3587     | arnold.cruz@awqa.net
 Maurizio Moroni         | 0522-556555        | maurizio.moroni@nqnk.net
 Akiko Shimamura         | +81 3 3584 0555    | akiko.shimamura@pipl.net
 Dominique Perrier       | (1) 47.55.6555     | dominique.perrier@bdim.net
 Rita M├╝ller            | 0711-555361        | rita.m├╝ller@gfsn.net
 Sarah McRoy             | 04 499 9555        | sarah.mcroy@fjnn.net
 Michael Donnermeyer     |  +49 89 61 08 9555 | michael.donnermeyer@lvpk.net
 Maria Hernandez         | 2125558493         | maria.hernandez@uzkx.net
 Alexander Feuer         | 0342-555176        | alexander.feuer@hzrr.net
 Dan Lewis               | 2035554407         | dan.lewis@bqfi.net
 Martha Larsson          | 0695-34 6555       | martha.larsson@abhf.net
 Sue Frick               | 4085553659         | sue.frick@npgp.net
 Roland Mendel           | 7675-3555          | roland.mendel@wclf.net
 Leslie Murphy           | 2035559545         | leslie.murphy@lbgq.net
 Yu Choi                 | 2125551957         | yu.choi@vmpd.net
 Mart├¡n Sommer          | (91) 555 22 82     | mart├¡n.sommer@wcoa.net
 Sven Ottlieb            | 0241-039123        | sven.ottlieb@dqyj.net
 Violeta Benitez         | 5085552555         | violeta.benitez@yqsd.net
 Carmen Anton            | +34 913 728555     | carmen.anton@bhmy.net
 Sean Clenahan           | 61-9-3844-6555     | sean.clenahan@gzyw.net
 Franco Ricotti          | +39 022515555      | franco.ricotti@ycbk.net
 Steve Thompson          | 3105553722         | steve.thompson@nirj.net
 Hanna Moos              | 0621-08555         | hanna.moos@fmga.net
 Alexander Semenov       | +7 812 293 0521    | alexander.semenov@xgru.net
 Raanan Altagar,G M      | + 972 9 959 8555   | raanan.altagar,g.m@mlap.net
 Jos├® Pedro Roel        | (95) 555 82 82     | jos├®.pedro.roel@qjmk.net
 Rosa Salazar            | 2155559857         | rosa.salazar@fzik.net
 Sue Taylor              | 4155554312         | sue.taylor@wllx.net
 Thomas Smith            | (171) 555-7555     | thomas.smith@nvze.net
 Valarie Franco          | 6175552555         | valarie.franco@qait.net
 Tony Snowden            | +64 9 5555500      | tony.snowden@rzcz.net
(133 rows)


postgres=#
```

</details><br>

### 11.2

- List all the details of rooms
- `SELECT * from rooms`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * from rooms;
 room_no |  rate  |  room_type   | no_guests
---------+--------+--------------+-----------
     101 |  85.00 | PREMIUM      |         2
     102 |  85.00 | PREMIUM      |         2
     103 |  85.00 | PREMIUM      |         2
     104 |  85.00 | PREMIUM      |         2
     105 |  85.00 | PREMIUM      |         2
     106 |  85.00 | PREMIUM      |         2
     107 |  85.00 | PREMIUM      |         2
     108 |  98.00 | PREMIUM PLUS |         2
     109 |  98.00 | PREMIUM PLUS |         2
     110 |  98.00 | PREMIUM PLUS |         2
     111 |  98.00 | PREMIUM PLUS |         2
     112 |  98.00 | PREMIUM PLUS |         2
     201 |  85.00 | PREMIUM      |         2
     202 |  85.00 | PREMIUM      |         2
     203 |  85.00 | PREMIUM      |         2
     204 |  85.00 | PREMIUM      |         2
     205 |  85.00 | PREMIUM      |         3
     206 |  85.00 | PREMIUM      |         3
     207 |  85.00 | PREMIUM      |         3
     208 |  98.00 | PREMIUM PLUS |         2
     209 |  98.00 | PREMIUM PLUS |         2
     210 |  98.00 | PREMIUM PLUS |         2
     211 |  98.00 | PREMIUM PLUS |         3
     212 |  98.00 | PREMIUM PLUS |         3
     301 | 110.00 | PREMIER      |         2
     302 | 110.00 | PREMIER      |         2
     303 | 110.00 | PREMIER      |         2
     304 | 110.00 | PREMIER      |         2
     305 | 110.00 | PREMIER      |         2
     306 | 110.00 | PREMIER      |         2
     307 | 110.00 | PREMIER      |         2
     308 | 123.00 | PREMIER PLUS |         2
     309 | 123.00 | PREMIER PLUS |         2
     310 | 123.00 | PREMIER PLUS |         2
     311 | 123.00 | PREMIER PLUS |         2
     312 | 123.00 | PREMIER PLUS |         2
     401 | 110.00 | PREMIER      |         2
     402 | 110.00 | PREMIER      |         2
     403 | 110.00 | PREMIER      |         2
     404 | 110.00 | PREMIER      |         2
     405 | 110.00 | PREMIER      |         2
     406 | 110.00 | PREMIER      |         2
     407 | 110.00 | PREMIER      |         2
     408 | 123.00 | PREMIER PLUS |         2
     409 | 123.00 | PREMIER PLUS |         2
     410 | 123.00 | PREMIER PLUS |         2
     411 | 123.00 | FAMILY       |         4
     412 | 123.00 | FAMILY       |         4
(48 rows)
```

</details><br>

### 11.3

- List the customer id, checkin date and number of guests from reservations
- `SELECT cust_id, checkin_date, no_guests FROM reservations;`
<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT cust_id, checkin_date, no_guests FROM reservations;
 cust_id | checkin_date | no_guests
---------+--------------+-----------
       3 | 2023-03-21   |         1
       4 | 2023-04-10   |         2
       4 | 2023-04-17   |         2
       5 | 2023-03-23   |         2
       6 | 2023-03-27   |         2
     102 | 2023-03-25   |         2
     115 | 2023-03-03   |         1
       2 | 2023-03-16   |         2
      86 | 2023-03-22   |         1
      25 | 2023-03-27   |         2
      30 | 2023-04-11   |         1
      25 | 2023-04-01   |         1
      15 | 2023-03-15   |         2
     131 | 2023-04-22   |         2
     117 | 2023-04-23   |         2
      25 | 2023-03-21   |         1
      38 | 2023-04-21   |         2
      97 | 2023-03-24   |         2
      51 | 2023-03-11   |         2
     119 | 2023-05-24   |         2
      64 | 2023-05-21   |         2
      31 | 2023-06-02   |         1
      32 | 2023-05-12   |         1
      83 | 2023-05-04   |         1
      51 | 2023-05-09   |         1
      46 | 2023-05-06   |         2
      19 | 2023-05-06   |         2
      76 | 2023-05-24   |         2
     108 | 2023-05-29   |         1
      82 | 2023-05-30   |         1
      77 | 2023-03-16   |         1
      52 | 2023-04-25   |         1
      23 | 2023-04-15   |         1
     114 | 2023-03-14   |         1
      58 | 2023-03-22   |         2
      30 | 2023-03-07   |         1
     129 | 2023-04-05   |         2
     129 | 2023-04-04   |         2
      20 | 2023-04-04   |         2
     104 | 2023-03-03   |         2
       5 | 2023-03-19   |         2
       9 | 2023-04-16   |         1
     104 | 2023-03-17   |         1
      54 | 2023-03-23   |         2
      37 | 2023-03-25   |         2
     115 | 2023-03-10   |         1
     109 | 2023-03-21   |         1
      91 | 2023-04-22   |         2
      97 | 2023-04-13   |         1
      88 | 2023-04-17   |         1
      30 | 2023-03-01   |         1
      77 | 2023-03-23   |         2
     121 | 2023-03-06   |         1
      80 | 2023-03-04   |         2
      64 | 2023-03-14   |         1
      43 | 2023-03-01   |         2
      41 | 2023-04-27   |         2
      75 | 2023-03-19   |         2
      65 | 2023-03-14   |         2
      14 | 2023-03-31   |         1
     115 | 2023-03-13   |         1
     106 | 2023-04-25   |         1
     130 | 2023-03-22   |         1
      84 | 2023-03-16   |         2
     108 | 2023-03-31   |         2
      67 | 2023-04-19   |         1
       2 | 2023-03-11   |         2
       9 | 2023-03-21   |         1
      29 | 2023-03-26   |         1
      13 | 2023-03-31   |         2
      70 | 2023-03-22   |         1
      49 | 2023-04-01   |         1
      18 | 2023-04-19   |         2
      95 | 2023-03-04   |         1
      13 | 2023-03-21   |         1
      84 | 2023-04-04   |         1
      14 | 2023-06-02   |         1
     123 | 2023-06-02   |         1
     110 | 2023-05-12   |         2
      31 | 2023-05-05   |         1
      16 | 2023-05-03   |         1
     117 | 2023-05-22   |         1
     126 | 2023-06-04   |         1
      97 | 2023-05-17   |         1
      20 | 2023-05-29   |         1
      15 | 2023-05-06   |         1
      79 | 2023-05-09   |         2
      40 | 2023-06-04   |         1
       9 | 2023-05-24   |         1
      26 | 2023-05-11   |         1
      96 | 2023-05-27   |         1
      35 | 2023-05-11   |         2
     119 | 2023-05-28   |         2
      38 | 2023-05-09   |         2
      96 | 2023-05-24   |         1
      24 | 2023-05-09   |         1
      12 | 2023-05-28   |         1
      63 | 2023-05-14   |         1
      66 | 2023-05-02   |         1
      44 | 2023-04-30   |         2
     129 | 2023-05-04   |         1
      55 | 2023-06-04   |         2
     116 | 2023-05-20   |         1
      93 | 2023-05-13   |         1
      98 | 2023-06-01   |         2
     108 | 2023-05-26   |         1
(106 rows)
```

</details><br>

---

## 12. PSQL Commands

The psql commands are not SQL and are specific to PostgreSQL (although most other RDBMS's have commands to perform similar jobs).

These commands let you display information, execute system commands, etc.

`\dt`
Display a list of available tables in the database

`\d <table name>`
Display the definition of a table

`\h [command]`
Display help for SQL commands

`\?`
Display a summary of the psql (backslash) commands

`\q`
Exit (quit) from psql:

Note that psql commands ARE case sensitive, unlike SQL commands.

---

## 13. Exercise 2

### 13.1

- Display the definition of the customers table
- `\d customers`
<details>
<summary>Terminal Output</summary>

```
postgres=# \d customers
                                     Table "public.customers"
  Column  |          Type          | Collation | Nullable |                Default
----------+------------------------+-----------+----------+---------------------------------------
 id       | integer                |           | not null | nextval('customers_id_seq'::regclass)
 name     | character varying(30)  |           | not null |
 email    | character varying(120) |           | not null |
 phone    | character varying(20)  |           |          |
 address  | character varying(120) |           |          |
 city     | character varying(30)  |           |          |
 postcode | character varying(12)  |           |          |
 country  | character varying(20)  |           |          |
Indexes:
    "customers_pkey" PRIMARY KEY, btree (id)
Referenced by:
    TABLE "reservations" CONSTRAINT "res_guest_fk" FOREIGN KEY (cust_id) REFERENCES customers(id)


postgres=#
```

</details><br>

### 13.2

- Display the help for the SELECT command (Note: we will not be covering ALL of this syntax!)
- `\h SELECT`

<details>
<summary>Terminal Output</summary>

```
postgres=# \h SELECT
Command:     SELECT
Description: retrieve rows from a table or view
Syntax:
[ WITH [ RECURSIVE ] with_query [, ...] ]
SELECT [ ALL | DISTINCT [ ON ( expression [, ...] ) ] ]
    [ * | expression [ [ AS ] output_name ] [, ...] ]
    [ FROM from_item [, ...] ]
    [ WHERE condition ]
    [ GROUP BY [ ALL | DISTINCT ] grouping_element [, ...] ]
    [ HAVING condition ]
    [ WINDOW window_name AS ( window_definition ) [, ...] ]
    [ { UNION | INTERSECT | EXCEPT } [ ALL | DISTINCT ] select ]
    [ ORDER BY expression [ ASC | DESC | USING operator ] [ NULLS { FIRST | LAST } ] [, ...] ]
    [ LIMIT { count | ALL } ]
    [ OFFSET start [ ROW | ROWS ] ]
    [ FETCH { FIRST | NEXT } [ count ] { ROW | ROWS } { ONLY | WITH TIES } ]
    [ FOR { UPDATE | NO KEY UPDATE | SHARE | KEY SHARE } [ OF table_name [, ...] ] [ NOWAIT | SKIP LOCKED ] [...] ]

where from_item can be one of:

    [ ONLY ] table_name [ * ] [ [ AS ] alias [ ( column_alias [, ...] ) ] ]
                [ TABLESAMPLE sampling_method ( argument [, ...] ) [ REPEATABLE ( seed ) ] ]
    [ LATERAL ] ( select ) [ AS ] alias [ ( column_alias [, ...] ) ]
    with_query_name [ [ AS ] alias [ ( column_alias [, ...] ) ] ]
    [ LATERAL ] function_name ( [ argument [, ...] ] )
                [ WITH ORDINALITY ] [ [ AS ] alias [ ( column_alias [, ...] ) ] ]
    [ LATERAL ] function_name ( [ argument [, ...] ] ) [ AS ] alias ( column_definition [, ...] )
    [ LATERAL ] function_name ( [ argument [, ...] ] ) AS ( column_definition [, ...] )
    [ LATERAL ] ROWS FROM( function_name ( [ argument [, ...] ] ) [ AS ( column_definition [, ...] ) ] [, ...] )                [ WITH ORDINALITY ] [ [ AS ] alias [ ( column_alias [, ...] ) ] ]
    from_item join_type from_item { ON join_condition | USING ( join_column [, ...] ) [ AS join_using_alias ] }
    from_item NATURAL join_type from_item
    from_item CROSS JOIN from_item

and grouping_element can be one of:

    ( )
    expression
    ( expression [, ...] )
    ROLLUP ( { expression | ( expression [, ...] ) } [, ...] )
    CUBE ( { expression | ( expression [, ...] ) } [, ...] )
    GROUPING SETS ( grouping_element [, ...] )

and with_query is:

    with_query_name [ ( column_name [, ...] ) ] AS [ [ NOT ] MATERIALIZED ] ( select | values | insert | update | delete )        [ SEARCH { BREADTH | DEPTH } FIRST BY column_name [, ...] SET search_seq_col_name ]
        [ CYCLE column_name [, ...] SET cycle_mark_col_name [ TO cycle_mark_value DEFAULT cycle_mark_default ] USING cycle_path_col_name ]
TABLE [ ONLY ] table_name [ * ]

URL: https://www.postgresql.org/docs/15/sql-select.html


postgres=#
```

</details><br>

### 13.3

- Read the psql command help and find out what \dS does then try it
- `\? dS`
- `\dS`

<details>
<summary>Terminal Output</summary>

```
postgres=# \?
General
  \copyright             show PostgreSQL usage and distribution terms
  \crosstabview [COLUMNS] execute query and display result in crosstab
  \errverbose            show most recent error message at maximum verbosity
  \g [(OPTIONS)] [FILE]  execute query (and send result to file or |pipe);
                         \g with no arguments is equivalent to a semicolon
  \gdesc                 describe result of query, without executing it
  \gexec                 execute query, then execute each value in its result
  \gset [PREFIX]         execute query and store result in psql variables
  \gx [(OPTIONS)] [FILE] as \g, but forces expanded output mode
  \q                     quit psql
  \watch [SEC]           execute query every SEC seconds

Help
  \? [commands]          show help on backslash commands
  \? options             show help on psql command-line options
  \? variables           show help on special variables
  \h [NAME]              help on syntax of SQL commands, * for all commands

Query Buffer
  \e [FILE] [LINE]       edit the query buffer (or file) with external editor
  \ef [FUNCNAME [LINE]]  edit function definition with external editor
  \ev [VIEWNAME [LINE]]  edit view definition with external editor
  \p                     show the contents of the query buffer
  \r                     reset (clear) the query buffer
  \w FILE                write query buffer to file

Input/Output
  \copy ...              perform SQL COPY with data stream to the client host
  \echo [-n] [STRING]    write string to standard output (-n for no newline)
  \i FILE                execute commands from file
  \ir FILE               as \i, but relative to location of current script
  \o [FILE]              send all query results to file or |pipe
  \qecho [-n] [STRING]   write string to \o output stream (-n for no newline)
  \warn [-n] [STRING]    write string to standard error (-n for no newline)

Conditional
  \if EXPR               begin conditional block
  \elif EXPR             alternative within current conditional block
  \else                  final alternative within current conditional block
  \endif                 end conditional block

Informational
  (options: S = show system objects, + = additional detail)
  \d[S+]                 list tables, views, and sequences
  \d[S+]  NAME           describe table, view, sequence, or index
  \da[S]  [PATTERN]      list aggregates
  \dA[+]  [PATTERN]      list access methods
  \dAc[+] [AMPTRN [TYPEPTRN]]  list operator classes
  \dAf[+] [AMPTRN [TYPEPTRN]]  list operator families
  \dAo[+] [AMPTRN [OPFPTRN]]   list operators of operator families
  \dAp[+] [AMPTRN [OPFPTRN]]   list support functions of operator families
  \db[+]  [PATTERN]      list tablespaces
  \dc[S+] [PATTERN]      list conversions
  \dconfig[+] [PATTERN]  list configuration parameters
  \dC[+]  [PATTERN]      list casts
  \dd[S]  [PATTERN]      show object descriptions not displayed elsewhere
  \dD[S+] [PATTERN]      list domains
  \ddp    [PATTERN]      list default privileges
  \dE[S+] [PATTERN]      list foreign tables
  \des[+] [PATTERN]      list foreign servers
  \det[+] [PATTERN]      list foreign tables
  \deu[+] [PATTERN]      list user mappings
  \dew[+] [PATTERN]      list foreign-data wrappers
  \df[anptw][S+] [FUNCPTRN [TYPEPTRN ...]]
                         list [only agg/normal/procedure/trigger/window] functions
  \dF[+]  [PATTERN]      list text search configurations
  \dFd[+] [PATTERN]      list text search dictionaries
  \dFp[+] [PATTERN]      list text search parsers
  \dFt[+] [PATTERN]      list text search templates
  \dg[S+] [PATTERN]      list roles
  \di[S+] [PATTERN]      list indexes
  \dl[+]                 list large objects, same as \lo_list
  \dL[S+] [PATTERN]      list procedural languages
  \dm[S+] [PATTERN]      list materialized views
  \dn[S+] [PATTERN]      list schemas
  \do[S+] [OPPTRN [TYPEPTRN [TYPEPTRN]]]
                         list operators
  \dO[S+] [PATTERN]      list collations
  \dp     [PATTERN]      list table, view, and sequence access privileges
  \dP[itn+] [PATTERN]    list [only index/table] partitioned relations [n=nested]
  \drds [ROLEPTRN [DBPTRN]] list per-database role settings
  \dRp[+] [PATTERN]      list replication publications
  \dRs[+] [PATTERN]      list replication subscriptions
  \ds[S+] [PATTERN]      list sequences
  \dt[S+] [PATTERN]      list tables
  \dT[S+] [PATTERN]      list data types
  \du[S+] [PATTERN]      list roles
  \dv[S+] [PATTERN]      list views
  \dx[+]  [PATTERN]      list extensions
  \dX     [PATTERN]      list extended statistics
  \dy[+]  [PATTERN]      list event triggers
  \l[+]   [PATTERN]      list databases
  \sf[+]  FUNCNAME       show a function's definition
  \sv[+]  VIEWNAME       show a view's definition
  \z      [PATTERN]      same as \dp

Large Objects
  \lo_export LOBOID FILE write large object to file
  \lo_import FILE [COMMENT]
                         read large object from file
  \lo_list[+]            list large objects
  \lo_unlink LOBOID      delete a large object

Formatting
  \a                     toggle between unaligned and aligned output mode
  \C [STRING]            set table title, or unset if none
  \f [STRING]            show or set field separator for unaligned query output
  \H                     toggle HTML output mode (currently off)
  \pset [NAME [VALUE]]   set table output option
                         (border|columns|csv_fieldsep|expanded|fieldsep|
                         fieldsep_zero|footer|format|linestyle|null|
                         numericlocale|pager|pager_min_lines|recordsep|
                         recordsep_zero|tableattr|title|tuples_only|
                         unicode_border_linestyle|unicode_column_linestyle|
                         unicode_header_linestyle)
  \t [on|off]            show only rows (currently off)
  \T [STRING]            set HTML <table> tag attributes, or unset if none
  \x [on|off|auto]       toggle expanded output (currently off)

Connection
  \c[onnect] {[DBNAME|- USER|- HOST|- PORT|-] | conninfo}
                         connect to new database (currently "postgres")
  \conninfo              display information about current connection
  \encoding [ENCODING]   show or set client encoding
  \password [USERNAME]   securely change the password for a user

Operating System
  \cd [DIR]              change the current working directory
  \getenv PSQLVAR ENVVAR fetch environment variable
  \setenv NAME [VALUE]   set or unset environment variable
  \timing [on|off]       toggle timing of commands (currently off)
  \! [COMMAND]           execute command in shell or start interactive shell

Variables
  \prompt [TEXT] NAME    prompt user to set internal variable
  \set [NAME [VALUE]]    set internal variable, or list all if no parameters
  \unset NAME            unset (delete) internal variable

postgres=# \dS
                         List of relations
   Schema   |              Name               |   Type   |  Owner
------------+---------------------------------+----------+----------
 pg_catalog | pg_aggregate                    | table    | postgres
 pg_catalog | pg_am                           | table    | postgres
 pg_catalog | pg_amop                         | table    | postgres
 pg_catalog | pg_amproc                       | table    | postgres
 pg_catalog | pg_attrdef                      | table    | postgres
 pg_catalog | pg_attribute                    | table    | postgres
 pg_catalog | pg_auth_members                 | table    | postgres
 pg_catalog | pg_authid                       | table    | postgres
 pg_catalog | pg_available_extension_versions | view     | postgres
 pg_catalog | pg_available_extensions         | view     | postgres
 pg_catalog | pg_backend_memory_contexts      | view     | postgres
 pg_catalog | pg_cast                         | table    | postgres
 pg_catalog | pg_class                        | table    | postgres
 pg_catalog | pg_collation                    | table    | postgres
 pg_catalog | pg_config                       | view     | postgres
 pg_catalog | pg_constraint                   | table    | postgres
 pg_catalog | pg_conversion                   | table    | postgres
 pg_catalog | pg_cursors                      | view     | postgres
 pg_catalog | pg_database                     | table    | postgres
 pg_catalog | pg_db_role_setting              | table    | postgres
 pg_catalog | pg_default_acl                  | table    | postgres
 pg_catalog | pg_depend                       | table    | postgres
 pg_catalog | pg_description                  | table    | postgres
 pg_catalog | pg_enum                         | table    | postgres
 pg_catalog | pg_event_trigger                | table    | postgres
 pg_catalog | pg_extension                    | table    | postgres
 pg_catalog | pg_file_settings                | view     | postgres
 pg_catalog | pg_foreign_data_wrapper         | table    | postgres
 pg_catalog | pg_foreign_server               | table    | postgres
 pg_catalog | pg_foreign_table                | table    | postgres
 pg_catalog | pg_group                        | view     | postgres
 pg_catalog | pg_hba_file_rules               | view     | postgres
 pg_catalog | pg_ident_file_mappings          | view     | postgres
 pg_catalog | pg_index                        | table    | postgres
 pg_catalog | pg_indexes                      | view     | postgres
 pg_catalog | pg_inherits                     | table    | postgres
 pg_catalog | pg_init_privs                   | table    | postgres
 pg_catalog | pg_language                     | table    | postgres
 pg_catalog | pg_largeobject                  | table    | postgres
 pg_catalog | pg_largeobject_metadata         | table    | postgres
 pg_catalog | pg_locks                        | view     | postgres
 pg_catalog | pg_matviews                     | view     | postgres
 pg_catalog | pg_namespace                    | table    | postgres
 pg_catalog | pg_opclass                      | table    | postgres
 pg_catalog | pg_operator                     | table    | postgres
 pg_catalog | pg_opfamily                     | table    | postgres
 pg_catalog | pg_parameter_acl                | table    | postgres
 pg_catalog | pg_partitioned_table            | table    | postgres
 pg_catalog | pg_policies                     | view     | postgres
 pg_catalog | pg_policy                       | table    | postgres
 pg_catalog | pg_prepared_statements          | view     | postgres
 pg_catalog | pg_prepared_xacts               | view     | postgres
 pg_catalog | pg_proc                         | table    | postgres
 pg_catalog | pg_publication                  | table    | postgres
 pg_catalog | pg_publication_namespace        | table    | postgres
 pg_catalog | pg_publication_rel              | table    | postgres
 pg_catalog | pg_publication_tables           | view     | postgres
 pg_catalog | pg_range                        | table    | postgres
 pg_catalog | pg_replication_origin           | table    | postgres
 pg_catalog | pg_replication_origin_status    | view     | postgres
 pg_catalog | pg_replication_slots            | view     | postgres
 pg_catalog | pg_rewrite                      | table    | postgres
 pg_catalog | pg_roles                        | view     | postgres
 pg_catalog | pg_rules                        | view     | postgres
 pg_catalog | pg_seclabel                     | table    | postgres
 pg_catalog | pg_seclabels                    | view     | postgres
 pg_catalog | pg_sequence                     | table    | postgres
 pg_catalog | pg_sequences                    | view     | postgres
 pg_catalog | pg_settings                     | view     | postgres
 pg_catalog | pg_shadow                       | view     | postgres
 pg_catalog | pg_shdepend                     | table    | postgres
 pg_catalog | pg_shdescription                | table    | postgres
 pg_catalog | pg_shmem_allocations            | view     | postgres
 pg_catalog | pg_shseclabel                   | table    | postgres
 pg_catalog | pg_stat_activity                | view     | postgres
 pg_catalog | pg_stat_all_indexes             | view     | postgres
 pg_catalog | pg_stat_all_tables              | view     | postgres
 pg_catalog | pg_stat_archiver                | view     | postgres
 pg_catalog | pg_stat_bgwriter                | view     | postgres
 pg_catalog | pg_stat_database                | view     | postgres
 pg_catalog | pg_stat_database_conflicts      | view     | postgres
 pg_catalog | pg_stat_gssapi                  | view     | postgres
 pg_catalog | pg_stat_progress_analyze        | view     | postgres
 pg_catalog | pg_stat_progress_basebackup     | view     | postgres
 pg_catalog | pg_stat_progress_cluster        | view     | postgres
 pg_catalog | pg_stat_progress_copy           | view     | postgres
 pg_catalog | pg_stat_progress_create_index   | view     | postgres
 pg_catalog | pg_stat_progress_vacuum         | view     | postgres
 pg_catalog | pg_stat_recovery_prefetch       | view     | postgres
 pg_catalog | pg_stat_replication             | view     | postgres
 pg_catalog | pg_stat_replication_slots       | view     | postgres
 pg_catalog | pg_stat_slru                    | view     | postgres
 pg_catalog | pg_stat_ssl                     | view     | postgres
 pg_catalog | pg_stat_subscription            | view     | postgres
 pg_catalog | pg_stat_subscription_stats      | view     | postgres
 pg_catalog | pg_stat_sys_indexes             | view     | postgres
 pg_catalog | pg_stat_sys_tables              | view     | postgres
 pg_catalog | pg_stat_user_functions          | view     | postgres
 pg_catalog | pg_stat_user_indexes            | view     | postgres
 pg_catalog | pg_stat_user_tables             | view     | postgres
 pg_catalog | pg_stat_wal                     | view     | postgres
 pg_catalog | pg_stat_wal_receiver            | view     | postgres
 pg_catalog | pg_stat_xact_all_tables         | view     | postgres
 pg_catalog | pg_stat_xact_sys_tables         | view     | postgres
 pg_catalog | pg_stat_xact_user_functions     | view     | postgres
 pg_catalog | pg_stat_xact_user_tables        | view     | postgres
 pg_catalog | pg_statio_all_indexes           | view     | postgres
 pg_catalog | pg_statio_all_sequences         | view     | postgres
 pg_catalog | pg_statio_all_tables            | view     | postgres
 pg_catalog | pg_statio_sys_indexes           | view     | postgres
 pg_catalog | pg_statio_sys_sequences         | view     | postgres
 pg_catalog | pg_statio_sys_tables            | view     | postgres
 pg_catalog | pg_statio_user_indexes          | view     | postgres
 pg_catalog | pg_statio_user_sequences        | view     | postgres
 pg_catalog | pg_statio_user_tables           | view     | postgres
 pg_catalog | pg_statistic                    | table    | postgres
 pg_catalog | pg_statistic_ext                | table    | postgres
 pg_catalog | pg_statistic_ext_data           | table    | postgres
 pg_catalog | pg_stats                        | view     | postgres
 pg_catalog | pg_stats_ext                    | view     | postgres
 pg_catalog | pg_stats_ext_exprs              | view     | postgres
 pg_catalog | pg_subscription                 | table    | postgres
 pg_catalog | pg_subscription_rel             | table    | postgres
 pg_catalog | pg_tables                       | view     | postgres
 pg_catalog | pg_tablespace                   | table    | postgres
 pg_catalog | pg_timezone_abbrevs             | view     | postgres
 pg_catalog | pg_timezone_names               | view     | postgres
 pg_catalog | pg_transform                    | table    | postgres
 pg_catalog | pg_trigger                      | table    | postgres
 pg_catalog | pg_ts_config                    | table    | postgres
 pg_catalog | pg_ts_config_map                | table    | postgres
 pg_catalog | pg_ts_dict                      | table    | postgres
 pg_catalog | pg_ts_parser                    | table    | postgres
 pg_catalog | pg_ts_template                  | table    | postgres
 pg_catalog | pg_type                         | table    | postgres
 pg_catalog | pg_user                         | view     | postgres
 pg_catalog | pg_user_mapping                 | table    | postgres
 pg_catalog | pg_user_mappings                | view     | postgres
 pg_catalog | pg_views                        | view     | postgres
 public     | customers                       | table    | postgres
 public     | customers_id_seq                | sequence | postgres
 public     | invoices                        | table    | postgres
 public     | invoices_id_seq                 | sequence | postgres
 public     | reservations                    | table    | postgres
 public     | reservations_id_seq             | sequence | postgres
 public     | room_types                      | table    | postgres
 public     | rooms                           | table    | postgres
(147 rows)


postgres=#
```

</details><br>

---

## 14. Displaying More Than Just Columns

`SELECT room_no, rate * 0.85 FROM rooms;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT room_no, rate * 0.85 FROM rooms;
 room_no | ?column?
---------+----------
     101 |  72.2500
     102 |  72.2500
     103 |  72.2500
     104 |  72.2500
     105 |  72.2500
     106 |  72.2500
     107 |  72.2500
     108 |  83.3000
     109 |  83.3000
     110 |  83.3000
     111 |  83.3000
     112 |  83.3000
     201 |  72.2500
     202 |  72.2500
     203 |  72.2500
     204 |  72.2500
     205 |  72.2500
     206 |  72.2500
     207 |  72.2500
     208 |  83.3000
     209 |  83.3000
     210 |  83.3000
     211 |  83.3000
     212 |  83.3000
     301 |  93.5000
     302 |  93.5000
     303 |  93.5000
     304 |  93.5000
     305 |  93.5000
     306 |  93.5000
     307 |  93.5000
     308 | 104.5500
     309 | 104.5500
     310 | 104.5500
     311 | 104.5500
     312 | 104.5500
     401 |  93.5000
     402 |  93.5000
     403 |  93.5000
     404 |  93.5000
     405 |  93.5000
     406 |  93.5000
     407 |  93.5000
     408 | 104.5500
     409 | 104.5500
     410 | 104.5500
     411 | 104.5500
     412 | 104.5500
(48 rows)


postgres=#
```

</details><br>

Use a **column alias** to give the expression a meaningful name:  
`SELECT room_no,
       rate * 0.85 AS discounted_rate
    FROM rooms;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT room_no,
postgres-#        rate * 0.85 AS discounted_rate
postgres-#     FROM rooms;
 room_no | discounted_rate
---------+-----------------
     101 |         72.2500
     102 |         72.2500
     103 |         72.2500
     104 |         72.2500
     105 |         72.2500
     106 |         72.2500
     107 |         72.2500
     108 |         83.3000
     109 |         83.3000
     110 |         83.3000
     111 |         83.3000
     112 |         83.3000
     201 |         72.2500
     202 |         72.2500
     203 |         72.2500
     204 |         72.2500
     205 |         72.2500
     206 |         72.2500
     207 |         72.2500
     208 |         83.3000
     209 |         83.3000
     210 |         83.3000
     211 |         83.3000
     212 |         83.3000
     301 |         93.5000
     302 |         93.5000
     303 |         93.5000
     304 |         93.5000
     305 |         93.5000
     306 |         93.5000
     307 |         93.5000
     308 |        104.5500
     309 |        104.5500
     310 |        104.5500
     311 |        104.5500
     312 |        104.5500
     401 |         93.5000
     402 |         93.5000
     403 |         93.5000
     404 |         93.5000
     405 |         93.5000
     406 |         93.5000
     407 |         93.5000
     408 |        104.5500
     409 |        104.5500
     410 |        104.5500
     411 |        104.5500
     412 |        104.5500
(48 rows)


postgres=#
```

</details><br>

---

## 15. Expressions in SQL

`* Multiply`

`/ Divide`

`+ Add`

`- Subtract`

`% Modulo (remainder)`

`(...) Parentheses (to override precedence)`

`||  String Concatenation`

For example, to display the weekly rate for a room (with 10% weekly discount):

`SELECT room_no, room_type, rate * 7 * 0.90 from rooms;`

<details>
<summary>Expand Answer</summary>

```
postgres=# SELECT room_no, room_type, rate * 7 * 0.90 from rooms;
 room_no |  room_type   | ?column?
---------+--------------+----------
     101 | PREMIUM      | 535.5000
     102 | PREMIUM      | 535.5000
     103 | PREMIUM      | 535.5000
     104 | PREMIUM      | 535.5000
     105 | PREMIUM      | 535.5000
     106 | PREMIUM      | 535.5000
     107 | PREMIUM      | 535.5000
     108 | PREMIUM PLUS | 617.4000
     109 | PREMIUM PLUS | 617.4000
     110 | PREMIUM PLUS | 617.4000
     111 | PREMIUM PLUS | 617.4000
     112 | PREMIUM PLUS | 617.4000
     201 | PREMIUM      | 535.5000
     202 | PREMIUM      | 535.5000
     203 | PREMIUM      | 535.5000
     204 | PREMIUM      | 535.5000
     205 | PREMIUM      | 535.5000
     206 | PREMIUM      | 535.5000
     207 | PREMIUM      | 535.5000
     208 | PREMIUM PLUS | 617.4000
     209 | PREMIUM PLUS | 617.4000
     210 | PREMIUM PLUS | 617.4000
     211 | PREMIUM PLUS | 617.4000
     212 | PREMIUM PLUS | 617.4000
     301 | PREMIER      | 693.0000
     302 | PREMIER      | 693.0000
     303 | PREMIER      | 693.0000
     304 | PREMIER      | 693.0000
     305 | PREMIER      | 693.0000
     306 | PREMIER      | 693.0000
     307 | PREMIER      | 693.0000
     308 | PREMIER PLUS | 774.9000
     309 | PREMIER PLUS | 774.9000
     310 | PREMIER PLUS | 774.9000
     311 | PREMIER PLUS | 774.9000
     312 | PREMIER PLUS | 774.9000
     401 | PREMIER      | 693.0000
     402 | PREMIER      | 693.0000
     403 | PREMIER      | 693.0000
     404 | PREMIER      | 693.0000
     405 | PREMIER      | 693.0000
     406 | PREMIER      | 693.0000
     407 | PREMIER      | 693.0000
     408 | PREMIER PLUS | 774.9000
     409 | PREMIER PLUS | 774.9000
     410 | PREMIER PLUS | 774.9000
     411 | FAMILY       | 774.9000
     412 | FAMILY       | 774.9000
(48 rows)


postgres=#
```

</details><br>

You can change the column heading using a **column alias**:

`SELECT room_no, room_type, rate * 7 * 0.90 as weekly_rate from rooms;`

<details>
<summary>Expand Answer</summary>

```
postgres=# SELECT room_no, room_type, rate * 7 * 0.90 as weekly_rate from rooms;
 room_no |  room_type   | weekly_rate
---------+--------------+-------------
     101 | PREMIUM      |    535.5000
     102 | PREMIUM      |    535.5000
     103 | PREMIUM      |    535.5000
     104 | PREMIUM      |    535.5000
     105 | PREMIUM      |    535.5000
     106 | PREMIUM      |    535.5000
     107 | PREMIUM      |    535.5000
     108 | PREMIUM PLUS |    617.4000
     109 | PREMIUM PLUS |    617.4000
     110 | PREMIUM PLUS |    617.4000
     111 | PREMIUM PLUS |    617.4000
     112 | PREMIUM PLUS |    617.4000
     201 | PREMIUM      |    535.5000
     202 | PREMIUM      |    535.5000
     203 | PREMIUM      |    535.5000
     204 | PREMIUM      |    535.5000
     205 | PREMIUM      |    535.5000
     206 | PREMIUM      |    535.5000
     207 | PREMIUM      |    535.5000
     208 | PREMIUM PLUS |    617.4000
     209 | PREMIUM PLUS |    617.4000
     210 | PREMIUM PLUS |    617.4000
     211 | PREMIUM PLUS |    617.4000
     212 | PREMIUM PLUS |    617.4000
     301 | PREMIER      |    693.0000
     302 | PREMIER      |    693.0000
     303 | PREMIER      |    693.0000
     304 | PREMIER      |    693.0000
     305 | PREMIER      |    693.0000
     306 | PREMIER      |    693.0000
     307 | PREMIER      |    693.0000
     308 | PREMIER PLUS |    774.9000
     309 | PREMIER PLUS |    774.9000
     310 | PREMIER PLUS |    774.9000
     311 | PREMIER PLUS |    774.9000
     312 | PREMIER PLUS |    774.9000
     401 | PREMIER      |    693.0000
     402 | PREMIER      |    693.0000
     403 | PREMIER      |    693.0000
     404 | PREMIER      |    693.0000
     405 | PREMIER      |    693.0000
     406 | PREMIER      |    693.0000
     407 | PREMIER      |    693.0000
     408 | PREMIER PLUS |    774.9000
     409 | PREMIER PLUS |    774.9000
     410 | PREMIER PLUS |    774.9000
     411 | FAMILY       |    774.9000
     412 | FAMILY       |    774.9000
(48 rows)


postgres=#
```

</details><br>

Use string concatenation to glue character data together:

`SELECT 'Customer name = ' || name FROM customers;`

<details>
<summary>Expand Answer</summary>

```
postgres=# SELECT 'Customer name = ' || name FROM customers;
                ?column?
-----------------------------------------
 Customer name = John Smith
 Customer name = Sue Jones
 Customer name = Alice Evans
 Customer name = Mohammed Trungpa
 Customer name = Steven King
 Customer name = Nadia Sethuraman
 Customer name = Melinda Marsh
 Customer name = Mart├¡n Sommer
 Customer name = Laurence Lebihan
 Customer name = Keith Stewart
 Customer name = Carlos Porter
 Customer name = Carine Schmitt
 Customer name = Jean King
 Customer name = Peter Ferguson
 Customer name = Janine Labrune
 Customer name = Jonas Bergulfsen
 Customer name = Susan Nelson
 Customer name = Zbyszek Piestrzeniewicz
 Customer name = Roland Keitel
 Customer name = Julie Murphy
 Customer name = Kwai Lee
 Customer name = Diego Freyre
 Customer name = Christina Berglund
 Customer name = Jytte Petersen
 Customer name = Mary Saveley
 Customer name = Eric Natividad
 Customer name = Jeff Young
 Customer name = Kelvin Leong
 Customer name = Juri Hashimoto
 Customer name = Wendy Victorino
 Customer name = Veysel Oeztan
 Customer name = Keith Franco
 Customer name = Isabel de Castro
 Customer name = Martine Ranc├®
 Customer name = Marie Bertrand
 Customer name = Jerry Tseng
 Customer name = Julie King
 Customer name = Mory Kentary
 Customer name = Michael Frick
 Customer name = Matti Karttunen
 Customer name = Rachel Ashworth
 Customer name = Dean Cassidy
 Customer name = Leslie Taylor
 Customer name = Elizabeth Devon
 Customer name = Yoshi Tamuri
 Customer name = Miguel Barajas
 Customer name = Julie Young
 Customer name = Brydey Walker
 Customer name = Fr├®d├®rique Citeaux
 Customer name = Mike Gao
 Customer name = Eduardo Saavedra
 Customer name = Mary Young
 Customer name = Horst Kloss
 Customer name = Palle Ibsen
 Customer name = Jean Fresni├¿re
 Customer name = Alejandra Camino
 Customer name = Valarie Thompson
 Customer name = Helen Bennett
 Customer name = Annette Roulet
 Customer name = Renate Messner
 Customer name = Paolo Accorti
 Customer name = Daniel Da Silva
 Customer name = Daniel Tonini
 Customer name = Henriette Pfalzheim
 Customer name = Elizabeth Lincoln
 Customer name = Peter Franken
 Customer name = Anna O'Hara
 Customer name = Giovanni Rovelli
 Customer name = Adrian Huxley
 Customer name = Marta Hernandez
 Customer name = Ed Harrison
 Customer name = Mihael Holz
 Customer name = Jan Klaeboe
 Customer name = Bradley Schuyler
 Customer name = Mel Andersen
 Customer name = Pirkko Koskitalo
 Customer name = Catherine Dewey
 Customer name = Steve Frick
 Customer name = Wing Huang
 Customer name = Julie Brown
 Customer name = Mike Graham
 Customer name = Ann Brown
 Customer name = William Brown
 Customer name = Ben Calaghan
 Customer name = Kalle Suominen
 Customer name = Philip Cramer
 Customer name = Francisca Cervantes
 Customer name = Jesus Fernandez
 Customer name = Brian Chandler
 Customer name = Patricia McKenna
 Customer name = Laurence Lebihan
 Customer name = Paul Henriot
 Customer name = Armand Kuger
 Customer name = Wales MacKinlay
 Customer name = Karin Josephs
 Customer name = Juri Yoshido
 Customer name = Dorothy Young
 Customer name = Lino Rodriguez
 Customer name = Braun Urs
 Customer name = Allen Nelson
 Customer name = Pascale Cartrain
 Customer name = Georg Pipps
 Customer name = Arnold Cruz
 Customer name = Maurizio Moroni
 Customer name = Akiko Shimamura
 Customer name = Dominique Perrier
 Customer name = Rita M├╝ller
 Customer name = Sarah McRoy
 Customer name = Michael Donnermeyer
 Customer name = Maria Hernandez
 Customer name = Alexander Feuer
 Customer name = Dan Lewis
 Customer name = Martha Larsson
 Customer name = Sue Frick
 Customer name = Roland Mendel
 Customer name = Leslie Murphy
 Customer name = Yu Choi
 Customer name = Mart├¡n Sommer
 Customer name = Sven Ottlieb
 Customer name = Violeta Benitez
 Customer name = Carmen Anton
 Customer name = Sean Clenahan
 Customer name = Franco Ricotti
 Customer name = Steve Thompson
 Customer name = Hanna Moos
 Customer name = Alexander Semenov
 Customer name = Raanan Altagar,G M
 Customer name = Jos├® Pedro Roel
 Customer name = Rosa Salazar
 Customer name = Sue Taylor
 Customer name = Thomas Smith
 Customer name = Valarie Franco
 Customer name = Tony Snowden
(133 rows)


postgres=#
```

</details><br>

---

## 16. Choosing the Rows

You can choose which rows to display by specifying some condition that must be matched:

```
SELECT id, name, phone, email, country
  FROM customers
  WHERE country = 'France';
```

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT id, name, phone, email, country
postgres-#   FROM customers
postgres-#   WHERE country = 'France';
 id  |         name         |      phone       |             email             | country
-----+----------------------+------------------+-------------------------------+---------
   9 | Laurence Lebihan     | 91.24.4555       | laurence.lebihan@xmzx.net     | France
  12 | Carine Schmitt       | 40.32.2555       | carine.schmitt@dftu.net       | France
  15 | Janine Labrune       | 40.67.8555       | janine.labrune@dlsh.net       | France
  25 | Mary Saveley         | 78.32.5555       | mary.saveley@yppl.net         | France
  34 | Martine Ranc├®       | 20.16.1555       | martine.ranc├®@xeqs.net       | France
  35 | Marie Bertrand       | (1) 42.34.2555   | marie.bertrand@glut.net       | France
  49 | Fr├®d├®rique Citeaux | 88.60.1555       | fr├®d├®rique.citeaux@vekn.net | France
  59 | Annette Roulet       | 61.77.6555       | annette.roulet@lgha.net       | France
  62 | Daniel Da Silva      | +33 1 46 62 7555 | daniel.da.silva@hijy.net      | France
  63 | Daniel Tonini        | 30.59.8555       | daniel.tonini@mxvw.net        | France
  91 | Laurence Lebihan     | 91.24.4555       | laurence.lebihan@xmzx.net     | France
  92 | Paul Henriot         | 26.47.1555       | paul.henriot@uwua.net         | France
 106 | Dominique Perrier    | (1) 47.55.6555   | dominique.perrier@bdim.net    | France
(13 rows)


postgres=#
```

</details><br>

### Comparison Operators

`=` Equality **Note: use only one = (equals) symbol to test for equality**

`<` Less Than

`>` Greater Than

`<=` Less Than or Equal

`>=` Greater Than or Equal

`!=` Not Equal

`<>` Or

### Comparing Numbers

When comparing numbers no punctuation is needed around the value, for example

`WHERE rate > 100`

### Comparing Character Data or Dates

When comparing character data or dates you must enclose the values in single quotes (apostrophes), for example

`WHERE name = 'Mary Saveley'`

### The Return

Only the rows that match the comparison test (called a **predicate**) are returned by the query.

The predicate can use columns not returned by the query

### Combining Tests in a Predicate

Use AND and OR to combine tests:

```
SELECT * FROM reservations
   WHERE room_no >= 200
     AND room_no < 300
     AND checkin_date >= '2018-01-01';
```

This lists reservations for rooms on the second floor (rooms 200 - 299) since the start of 2018. Note the format of the date value - this conforms to the ISO 8601 standard and should be used in preference to any other format to avoid ambiguity.

<details>

<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM reservations
postgres-#    WHERE room_no >= 200
postgres-#      AND room_no < 300
postgres-#      AND checkin_date >= '2018-01-01';
 id  | cust_id | room_no | checkin_date | checkout_date | no_guests | booking_date
-----+---------+---------+--------------+---------------+-----------+--------------
   1 |       3 |     204 | 2023-03-21   | 2023-03-24    |         1 | 2023-03-04
   5 |       6 |     211 | 2023-03-27   | 2023-03-30    |         2 | 2023-02-26
   7 |     102 |     202 | 2023-03-25   | 2023-03-30    |         2 | 2023-03-16
  10 |       2 |     208 | 2023-03-16   | 2023-03-22    |         2 | 2023-03-11
  13 |      25 |     206 | 2023-03-27   | 2023-03-30    |         2 | 2023-03-17
  18 |      15 |     201 | 2023-03-15   | 2023-03-17    |         2 | 2023-02-22
  26 |      97 |     210 | 2023-03-24   | 2023-03-30    |         2 | 2023-03-24
  35 |     114 |     203 | 2023-03-14   | 2023-03-18    |         1 | 2023-03-07
  39 |     129 |     206 | 2023-04-04   | 2023-04-06    |         2 | 2023-03-30
  52 |     115 |     203 | 2023-03-10   | 2023-03-13    |         1 | 2023-02-05
  55 |     109 |     202 | 2023-03-21   | 2023-03-23    |         1 | 2023-03-16
  56 |      91 |     211 | 2023-04-22   | 2023-04-27    |         2 | 2023-04-11
  58 |      88 |     206 | 2023-04-17   | 2023-04-18    |         1 | 2023-04-14
  69 |      43 |     204 | 2023-03-01   | 2023-03-06    |         2 | 2023-02-04
  77 |     115 |     202 | 2023-03-13   | 2023-03-15    |         1 | 2023-02-26
  82 |     106 |     206 | 2023-04-25   | 2023-04-30    |         1 | 2023-04-11
  83 |     130 |     209 | 2023-03-22   | 2023-03-23    |         1 | 2023-02-28
  94 |      29 |     212 | 2023-03-26   | 2023-03-29    |         1 | 2023-03-20
 100 |      18 |     211 | 2023-04-19   | 2023-04-21    |         2 | 2023-04-02
(19 rows)


postgres=#
```

</details><br>

Another example - to find cheap or Premier rooms on floors 1 and 2 - we might try this to start with:

```
SELECT * FROM rooms
   WHERE room_type = 'PREMIER'
      OR rate < 100.00
     AND room_no < 300;
```

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM rooms
postgres-#    WHERE room_type = 'PREMIER'
postgres-#       OR rate < 100.00
postgres-#      AND room_no < 300;
 room_no |  rate  |  room_type   | no_guests
---------+--------+--------------+-----------
     101 |  85.00 | PREMIUM      |         2
     102 |  85.00 | PREMIUM      |         2
     103 |  85.00 | PREMIUM      |         2
     104 |  85.00 | PREMIUM      |         2
     105 |  85.00 | PREMIUM      |         2
     106 |  85.00 | PREMIUM      |         2
     107 |  85.00 | PREMIUM      |         2
     108 |  98.00 | PREMIUM PLUS |         2
     109 |  98.00 | PREMIUM PLUS |         2
     110 |  98.00 | PREMIUM PLUS |         2
     111 |  98.00 | PREMIUM PLUS |         2
     112 |  98.00 | PREMIUM PLUS |         2
     201 |  85.00 | PREMIUM      |         2
     202 |  85.00 | PREMIUM      |         2
     203 |  85.00 | PREMIUM      |         2
     204 |  85.00 | PREMIUM      |         2
     205 |  85.00 | PREMIUM      |         3
     206 |  85.00 | PREMIUM      |         3
     207 |  85.00 | PREMIUM      |         3
     208 |  98.00 | PREMIUM PLUS |         2
     209 |  98.00 | PREMIUM PLUS |         2
     210 |  98.00 | PREMIUM PLUS |         2
     211 |  98.00 | PREMIUM PLUS |         3
     212 |  98.00 | PREMIUM PLUS |         3
     301 | 110.00 | PREMIER      |         2
     302 | 110.00 | PREMIER      |         2
     303 | 110.00 | PREMIER      |         2
     304 | 110.00 | PREMIER      |         2
     305 | 110.00 | PREMIER      |         2
     306 | 110.00 | PREMIER      |         2
     307 | 110.00 | PREMIER      |         2
     401 | 110.00 | PREMIER      |         2
     402 | 110.00 | PREMIER      |         2
     403 | 110.00 | PREMIER      |         2
     404 | 110.00 | PREMIER      |         2
     405 | 110.00 | PREMIER      |         2
     406 | 110.00 | PREMIER      |         2
     407 | 110.00 | PREMIER      |         2
(38 rows)


postgres=#
```

</details><br>

This isn't quite right - it returns rooms on the 3rd and 4th floors. Why?

### Overriding Evaluation Order

Just like any programming language, SQL has an evaluation order (precedence). For example, multiply and divide take precedence over add and subtract, so that:

`SELECT rate + 20 * 0.85 from rooms;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT rate + 20 * 0.85 from rooms;
 ?column?
----------
   102.00
   102.00
   102.00
   102.00
   102.00
   102.00
   102.00
   115.00
   115.00
   115.00
   115.00
   115.00
   102.00
   102.00
   102.00
   102.00
   102.00
   102.00
   102.00
   115.00
   115.00
   115.00
   115.00
   115.00
   127.00
   127.00
   127.00
   127.00
   127.00
   127.00
   127.00
   140.00
   140.00
   140.00
   140.00
   140.00
   127.00
   127.00
   127.00
   127.00
   127.00
   127.00
   127.00
   140.00
   140.00
   140.00
   140.00
   140.00
(48 rows)


postgres=#
```

</details><br>

is not the same as:

`SELECT (rate + 20) * 0.85 from rooms;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT (rate + 20) * 0.85 from rooms;
 ?column?
----------
  89.2500
  89.2500
  89.2500
  89.2500
  89.2500
  89.2500
  89.2500
 100.3000
 100.3000
 100.3000
 100.3000
 100.3000
  89.2500
  89.2500
  89.2500
  89.2500
  89.2500
  89.2500
  89.2500
 100.3000
 100.3000
 100.3000
 100.3000
 100.3000
 110.5000
 110.5000
 110.5000
 110.5000
 110.5000
 110.5000
 110.5000
 121.5500
 121.5500
 121.5500
 121.5500
 121.5500
 110.5000
 110.5000
 110.5000
 110.5000
 110.5000
 110.5000
 110.5000
 121.5500
 121.5500
 121.5500
 121.5500
 121.5500
(48 rows)


postgres=#
```

</details><br>

We can override the normal precedence by using parentheses (...) around parts of the expression, just as in JavaScript.

With compound predicates AND takes precedence over OR, so that to make the query give the intended results we need to use:

```
SELECT * FROM rooms
   WHERE (room_type = 'PREMIER'
      OR rate < 100.00)
     AND room_no < 300;
```

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM rooms
postgres-#    WHERE (room_type = 'PREMIER'
postgres(#       OR rate < 100.00)
postgres-#      AND room_no < 300;
 room_no | rate  |  room_type   | no_guests
---------+-------+--------------+-----------
     101 | 85.00 | PREMIUM      |         2
     102 | 85.00 | PREMIUM      |         2
     103 | 85.00 | PREMIUM      |         2
     104 | 85.00 | PREMIUM      |         2
     105 | 85.00 | PREMIUM      |         2
     106 | 85.00 | PREMIUM      |         2
     107 | 85.00 | PREMIUM      |         2
     108 | 98.00 | PREMIUM PLUS |         2
     109 | 98.00 | PREMIUM PLUS |         2
     110 | 98.00 | PREMIUM PLUS |         2
     111 | 98.00 | PREMIUM PLUS |         2
     112 | 98.00 | PREMIUM PLUS |         2
     201 | 85.00 | PREMIUM      |         2
     202 | 85.00 | PREMIUM      |         2
     203 | 85.00 | PREMIUM      |         2
     204 | 85.00 | PREMIUM      |         2
     205 | 85.00 | PREMIUM      |         3
     206 | 85.00 | PREMIUM      |         3
     207 | 85.00 | PREMIUM      |         3
     208 | 98.00 | PREMIUM PLUS |         2
     209 | 98.00 | PREMIUM PLUS |         2
     210 | 98.00 | PREMIUM PLUS |         2
     211 | 98.00 | PREMIUM PLUS |         3
     212 | 98.00 | PREMIUM PLUS |         3
(24 rows)


postgres=#
```

</details><br>

## More Predicate Types

### BETWEEN operator

The BETWEEN operator has the form a BETWEEN b AND c : checks that a is in the range b - c inclusive.

For example:

(Note that the AND in this case is not combining multiple predicates, it's part of the BETWEEN operator.)

`SELECT ... WHERE price BETWEEN 100 AND 250 ...`

`SELECT * FROM rooms WHERE rate BETWEEN 95 and 115;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM rooms WHERE rate BETWEEN 95 AND 115;
 room_no |  rate  |  room_type   | no_guests
---------+--------+--------------+-----------
     108 |  98.00 | PREMIUM PLUS |         2
     109 |  98.00 | PREMIUM PLUS |         2
     110 |  98.00 | PREMIUM PLUS |         2
     111 |  98.00 | PREMIUM PLUS |         2
     112 |  98.00 | PREMIUM PLUS |         2
     208 |  98.00 | PREMIUM PLUS |         2
     209 |  98.00 | PREMIUM PLUS |         2
     210 |  98.00 | PREMIUM PLUS |         2
     211 |  98.00 | PREMIUM PLUS |         3
     212 |  98.00 | PREMIUM PLUS |         3
     301 | 110.00 | PREMIER      |         2
     302 | 110.00 | PREMIER      |         2
     303 | 110.00 | PREMIER      |         2
     304 | 110.00 | PREMIER      |         2
     305 | 110.00 | PREMIER      |         2
     306 | 110.00 | PREMIER      |         2
     307 | 110.00 | PREMIER      |         2
     401 | 110.00 | PREMIER      |         2
     402 | 110.00 | PREMIER      |         2
     403 | 110.00 | PREMIER      |         2
     404 | 110.00 | PREMIER      |         2
     405 | 110.00 | PREMIER      |         2
     406 | 110.00 | PREMIER      |         2
     407 | 110.00 | PREMIER      |         2
(24 rows)


postgres=#
```

</details><br>

### IN operator

The IN operator, a IN (b, c, d, ...) checks if the value of a is equal to any of b, c, d, etc...

For example:

`SELECT ... WHERE room_no IN (201, 202, 204, 206) ...`

`SELECT * FROM rooms WHERE room_no IN (101, 105, 110);`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM rooms WHERE room_no IN (101, 105, 110);
 room_no | rate  |  room_type   | no_guests
---------+-------+--------------+-----------
     101 | 85.00 | PREMIUM      |         2
     105 | 85.00 | PREMIUM      |         2
     110 | 98.00 | PREMIUM PLUS |         2
(3 rows)


postgres=#
```

</details><br>

### INVERTING BETWEEN and IN

Both the BETWEEN and the IN operators can be inverted using:

`... a NOT BETWEEN b AND c ...`

`SELECT * FROM rooms WHERE rate NOT BETWEEN 90 and 120;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM rooms WHERE rate NOT BETWEEN 90 and 120;
 room_no |  rate  |  room_type   | no_guests
---------+--------+--------------+-----------
     101 |  85.00 | PREMIUM      |         2
     102 |  85.00 | PREMIUM      |         2
     103 |  85.00 | PREMIUM      |         2
     104 |  85.00 | PREMIUM      |         2
     105 |  85.00 | PREMIUM      |         2
     106 |  85.00 | PREMIUM      |         2
     107 |  85.00 | PREMIUM      |         2
     201 |  85.00 | PREMIUM      |         2
     202 |  85.00 | PREMIUM      |         2
     203 |  85.00 | PREMIUM      |         2
     204 |  85.00 | PREMIUM      |         2
     205 |  85.00 | PREMIUM      |         3
     206 |  85.00 | PREMIUM      |         3
     207 |  85.00 | PREMIUM      |         3
     308 | 123.00 | PREMIER PLUS |         2
     309 | 123.00 | PREMIER PLUS |         2
     310 | 123.00 | PREMIER PLUS |         2
     311 | 123.00 | PREMIER PLUS |         2
     312 | 123.00 | PREMIER PLUS |         2
     408 | 123.00 | PREMIER PLUS |         2
     409 | 123.00 | PREMIER PLUS |         2
     410 | 123.00 | PREMIER PLUS |         2
     411 | 123.00 | FAMILY       |         4
     412 | 123.00 | FAMILY       |         4
(24 rows)


postgres=#
```

</details><br>

`... a NOT IN (b, c, d, ...)`

`SELECT * FROM rooms WHERE room_type NOT IN ('PREMIUM', 'PREMIUM PLUS', 'PREMIER','PREMIER PLUS');`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM rooms WHERE room_type NOT IN ('PREMIUM', 'PREMIUM PLUS', 'PREMIER','PREMIER PLUS');
 room_no |  rate  | room_type | no_guests
---------+--------+-----------+-----------
     411 | 123.00 | FAMILY    |         4
     412 | 123.00 | FAMILY    |         4
(2 rows)


postgres=#
```

</details><br>

### LIKE operator

The LIKE operator tests for a match against a wildcard string as `a LIKE b` where a is being tested and b is the wildcard string.

The wildcard string contains text to be matched along with wildcard symbols `%` and `_`

`% (percent) matches any number of any characters`

`_ (underscore) matches exactly one of any character`

For example:

`name LIKE 'A%'` matches names starting with `A`

`SELECT * FROM customers WHERE name LIKE 'A%';`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM customers WHERE name LIKE 'A%';
 id  |       name        |           email            |      phone      |                  address                  |       city       | postcode |   country
-----+-------------------+----------------------------+-----------------+-------------------------------------------+------------------+----------+--------------
   3 | Alice Evans       | alice.evans001@hotmail.com | 0161 345 6789   | 3 High Road                               | Manchester       | m13 4ef  | UK
  56 | Alejandra Camino  | alejandra.camino@omet.net  | (91) 745 6555   | Gran V├¡a, 1                              | Madrid           | 28001    | Spain
  59 | Annette Roulet    | annette.roulet@lgha.net    | 61.77.6555      | 1 rue Alsace-Lorraine                     | Toulouse         | 31000    | France
  67 | Anna O'Hara       | anna.o"hara@hzjw.net       | 02 9936 8555    | 201 Miller Street, Level 15               | North Sydney     | 2060     | Australia
  69 | Adrian Huxley     | adrian.huxley@hmep.net     | +61 2 9495 8555 | Monitor Money Building, 815 Pacific Hwy   | Chatswood        | 2067     | Australia
  82 | Ann Brown         | ann.brown@xwkb.net         | (171) 555-0297  | 35 King George                            | London           | WX3 6FW  | UK
  93 | Armand Kuger      | armand.kuger@axkq.net      | +27 21 550 3555 | 1250 Pretorius Street                     | Hatfield         | 0028     | South Africa
 100 | Allen Nelson      | allen.nelson@eruo.net      | 6175558555      | 7825 Douglas Av.                          | Brickhaven       | 58339    | USA
 103 | Arnold Cruz       | arnold.cruz@awqa.net       | +63 2 555 3587  | 15 McCallum Street, NatWest Center #13-03 | Makati City      | 1227 MM  | Philippines
 105 | Akiko Shimamura   | akiko.shimamura@pipl.net   | +81 3 3584 0555 | 2-2-8 Roppongi                            | Minato-ku        | 106-0032 | Japan
 111 | Alexander Feuer   | alexander.feuer@hzrr.net   | 0342-555176     | Heerstr. 22                               | Leipzig          | 04179    | Germany
 126 | Alexander Semenov | alexander.semenov@xgru.net | +7 812 293 0521 | 2 Pobedy Square                           | Saint Petersburg | 196143   | Russia
(12 rows)


postgres=#
```

</details><br>

`name LIKE '_a%'` matches names that have `'a'` as the 2nd character (note the initial underscore '\_')

`SELECT * FROM customers WHERE name LIKE '_a%';`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM customers WHERE name LIKE '_a%';
 id  |        name        |            email            |      phone       |               address               |     city      | postcode  |   country
-----+--------------------+-----------------------------+------------------+-------------------------------------+---------------+-----------+-------------
   6 | Nadia Sethuraman   | nadia.sethuraman@mail.com   |                  | 135 Green Street                    | Manchester    | M10 4BG   | UK
   8 | Mart├¡n Sommer     | martin.sommer@dfgg.net      | (91) 555 22 82   | C/ Romero, 33                       | Madrid        | 28016     | Spain
   9 | Laurence Lebihan   | laurence.lebihan@xmzx.net   | 91.24.4555       | 12, rue des Bouchers                | Marseille     | 13008     | France
  11 | Carlos Porter      | carlos.porter@ortynuf.com   | 070 2679 6812    | 81 Bath Rd                          | Salisbury     | SA61 4GD  | UK
  12 | Carine Schmitt     | carine.schmitt@dftu.net     | 40.32.2555       | 54, rue Royale                      | Nantes        | 44000     | France
  15 | Janine Labrune     | janine.labrune@dlsh.net     | 40.67.8555       | 67, rue des Cinquante Otages        | Nantes        | 44000     | France
  25 | Mary Saveley       | mary.saveley@yppl.net       | 78.32.5555       | 2, rue du Commerce                  | Lyon          | 69004     | France
  34 | Martine Ranc├®     | martine.ranc├®@xeqs.net     | 20.16.1555       | 184, chauss├®e de Tournai           | Lille         | 59000     | France
  35 | Marie Bertrand     | marie.bertrand@glut.net     | (1) 42.34.2555   | 265, boulevard Charonne             | Paris         | 75012     | France
  40 | Matti Karttunen    | matti.karttunen@xkig.net    | 90-224 8555      | Keskuskatu 45                       | Helsinki      | 21240     | Finland
  41 | Rachel Ashworth    | rachel.ashworth@rzyb.net    | (171) 555-1555   | Fauntleroy Circus                   | Manchester    | EC2 5NT   | UK
  52 | Mary Young         | mary.young@ratm.net         | 3105552373       | 4097 Douglas Av.                    | Glendale      | 92561     | USA
  54 | Palle Ibsen        | palle.ibsen@bjqn.net        | 86 21 3555       | Smagsloget 45                       | ├àrhus        | 8200      | Denmark
  57 | Valarie Thompson   | valarie.thompson@brll.net   | 7605558146       | 361 Furth Circle                    | San Diego     | 91217     | USA
  61 | Paolo Accorti      | paolo.accorti@xcuw.net      | 011-4988555      | Via Monte Bianco 34                 | Torino        | 10100     | Italy
  62 | Daniel Da Silva    | daniel.da.silva@hijy.net    | +33 1 46 62 7555 | 27 rue du Colonel Pierre Avia       | Paris         | 75508     | France
  63 | Daniel Tonini      | daniel.tonini@mxvw.net      | 30.59.8555       | 67, avenue de lEurope               | Versailles    | 78000     | France
  70 | Marta Hernandez    | marta.hernandez@xqti.net    | 6175558555       | 39323 Spinnaker Dr.                 | Cambridge     | 51247     | USA
  73 | Jan Klaeboe        | jan.klaeboe@mpnl.net        | +47 2212 1555    | Drammensveien 126A, PB 211 Sentrum  | Oslo          | N 0106    | Norway
  77 | Catherine Dewey    | catherine.dewey@ndft.net    | (02) 5554 67     | Rue Joseph-Bens 532                 | Bruxelles     | B-1180    | Belgium
  85 | Kalle Suominen     | kalle.suominen@acif.net     | +358 9 8045 555  | Software Engineering Center, SEC Oy | Espoo         | FIN-02271 | Finland
  90 | Patricia McKenna   | patricia.mckenna@eert.net   | 2967 555         | 8 Johnstown Road                    | Cork          |           | Ireland
  91 | Laurence Lebihan   | laurence.lebihan@xmzx.net   | 91.24.4555       | 12, rue des Bouchers                | Marseille     | 13008     | France
  92 | Paul Henriot       | paul.henriot@uwua.net       | 26.47.1555       | 59 rue de l'Abbaye                  | Reims         | 51100     | France
  94 | Wales MacKinlay    | wales.mackinlay@omis.net    | 64-9-3763555     | 199 Great North Road                | Auckland      |           | New Zealand
  95 | Karin Josephs      | karin.josephs@gyfv.net      | 0251-555259      | Luisenstr. 48                       | M├╝nster      | 44087     | Germany
 101 | Pascale Cartrain   | pascale.cartrain@oggv.net   | (071) 23 67 2555 | Boulevard Tirou, 255                | Charleroi     | B-6000    | Belgium
 104 | Maurizio Moroni    | maurizio.moroni@nqnk.net    | 0522-556555      | Strada Provinciale 124              | Reggio Emilia | 42100     | Italy
 108 | Sarah McRoy        | sarah.mcroy@fjnn.net        | 04 499 9555      | 101 Lambton Quay, Level 11          | Wellington    |           | New Zealand
 110 | Maria Hernandez    | maria.hernandez@uzkx.net    | 2125558493       | 5905 Pompton St., Suite 750         | NYC           | 10022     | USA
 112 | Dan Lewis          | dan.lewis@bqfi.net          | 2035554407       | 2440 Pompton St.                    | Glendale      | 97561     | USA
 113 | Martha Larsson     | martha.larsson@abhf.net     | 0695-34 6555     | ├àkergatan 24                       | Br├ñcke       | S-844 67  | Sweden
 118 | Mart├¡n Sommer     | mart├¡n.sommer@wcoa.net     | (91) 555 22 82   | C/ Araquil, 67                      | Madrid        | 28023     | Spain
 121 | Carmen Anton       | carmen.anton@bhmy.net       | +34 913 728555   | c/ Gobelas, 19-1 Urb. La Florida    | Madrid        | 28023     | Spain
 125 | Hanna Moos         | hanna.moos@fmga.net         | 0621-08555       | Forsterstr. 57                      | Mannheim      | 68306     | Germany
 127 | Raanan Altagar,G M | raanan.altagar,g.m@mlap.net | + 972 9 959 8555 | 3 Hagalim Blv.                      | Herzlia       | 47625     | Israel
 132 | Valarie Franco     | valarie.franco@qait.net     | 6175552555       | 6251 Ingle Ln.                      | Boston        | 51003     | USA
(37 rows)


postgres=#
```

</details><br>

`name LIKE '%ow%'` matches names containing the sequence `'ow'` anywhere in the name

`SELECT * FROM customers WHERE name LIKE '%ow%';`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM customers WHERE name LIKE '%ow%';
 id  |     name      |         email          |     phone      |      address       |     city      | postcode |   country
-----+---------------+------------------------+----------------+--------------------+---------------+----------+-------------
  80 | Julie Brown   | julie.brown@zbfm.net   | 6505551386     | 7734 Strong St.    | San Francisco | 94217    | USA
  82 | Ann Brown     | ann.brown@xwkb.net     | (171) 555-0297 | 35 King George     | London        | WX3 6FW  | UK
  83 | William Brown | william.brown@wrbo.net | 2015559350     | 7476 Moss Rd.      | Newark        | 94019    | USA
 133 | Tony Snowden  | tony.snowden@rzcz.net  | +64 9 5555500  | Arenales 1938 3'A' | Auckland      |          | New Zealand
(4 rows)


postgres=#
```

</details><br>

`LIKE` can be inverted using `a NOT LIKE b`

`SELECT * FROM rooms WHERE room_type NOT LIKE 'P%';`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM rooms WHERE room_type NOT LIKE 'P%';
 room_no |  rate  | room_type | no_guests
---------+--------+-----------+-----------
     411 | 123.00 | FAMILY    |         4
     412 | 123.00 | FAMILY    |         4
(2 rows)


postgres=#
```

</details><br>

If you need to match for a string that includes one of the wildard characters `%` `_` `[]` `^` `|` you can use the 'escape' character, which defaults to `'\'` (backslash).

For example:

`str LIKE '% discount = 5\% %'` matches any value in str that contains `'discount = 5%'`

`LIKE` is case sensitive in many SQL implementations so to make a case insensitive match you should either convert the tested value to either all upper or all lower case, for example:

`lower(name) LIKE '%b%'` matches any name that contains the letters `B` or `b`

`SELECT * from customers WHERE lower(name) LIKE '%y%';`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * from customers WHERE lower(name) LIKE '%y%';
 id  |          name           |              email               |       phone        |                 address                 |     city      | postcode  |   country
-----+-------------------------+----------------------------------+--------------------+-----------------------------------------+---------------+-----------+-------------
  18 | Zbyszek Piestrzeniewicz | zbyszek.piestrzeniewicz@askt.net | (26) 642-7555      | ul. Filtrowa 68                         | Warszawa      | 01-012    | Poland
  20 | Julie Murphy            | julie.murphy@lrtc.net            | 0650 555 5787      | 5557 North Pendale Street               | San Francisco | 94217     | USA
  22 | Diego Freyre            | diego.freyre@amyr.net            | (91) 555 94 44     | C/ Moralzarzal, 86                      | Madrid        | 28034     | Spain
  24 | Jytte Petersen          | jytte.petersen@cpbn.net          | 31 12 3555         | Vinb├ªltet 34                           | Kobenhavn     | 1734      | Denmark
  25 | Mary Saveley            | mary.saveley@yppl.net            | 78.32.5555         | 2, rue du Commerce                      | Lyon          | 69004     | France
  27 | Jeff Young              | jeff.young@hahh.net              | 0212 555 7413      | 4092 Furth Circle, Suite 400            | NYC           | 10022     | USA
  30 | Wendy Victorino         | wendy.victorino@ueai.net         | +65 224 1555       | 106 Linden Road Sandown, 2nd Floor      | Singapore     | 069045    | Singapore
  31 | Veysel Oeztan           | veysel.oeztan@vqkn.net           | +47 2267 3215      | Brehmen St. 121, PR 334 Sentrum         | Bergen        | N 5804    | Norway
  36 | Jerry Tseng             | jerry.tseng@etea.net             | 6175555555         | 4658 Baden Av.                          | Cambridge     | 51247     | USA
  38 | Mory Kentary            | mory.kentary@nqfg.net            | +81 06 6342 5555   | 1-6-20 Dojima                           | Kita-ku       |  530-0003 | Japan
  42 | Dean Cassidy            | dean.cassidy@sntj.net            | +353 1862 1555     | 25 Maiden Lane, Floor No. 4             | Dublin        | 2         | Ireland
  43 | Leslie Taylor           | leslie.taylor@tunp.net           | 6175558428         | 16780 Pompton St.                       | Brickhaven    | 58339     | USA
  45 | Yoshi Tamuri            | yoshi.tamuri@juuq.net            | (604) 555-3392     | 1900 Oak St.                            | Vancouver     | V3F 2K1   | Canada
  47 | Julie Young             | julie.young@rmhl.net             | 6265557265         | 78934 Hillside Dr.                      | Pasadena      | 90003     | USA
  48 | Brydey Walker           | brydey.walker@kwtj.net           | +612 9411 1555     | Suntec Tower Three, 8 Temasek           | Singapore     | 038988    | Singapore
  52 | Mary Young              | mary.young@ratm.net              | 3105552373         | 4097 Douglas Av.                        | Glendale      | 92561     | USA
  69 | Adrian Huxley           | adrian.huxley@hmep.net           | +61 2 9495 8555    | Monitor Money Building, 815 Pacific Hwy | Chatswood     | 2067      | Australia
  74 | Bradley Schuyler        | bradley.schuyler@stie.net        | +31 20 491 9555    | Kingsfordweg 151                        | Amsterdam     | 1043 GR   | Netherlands
  77 | Catherine Dewey         | catherine.dewey@ndft.net         | (02) 5554 67       | Rue Joseph-Bens 532                     | Bruxelles     | B-1180    | Belgium
  94 | Wales MacKinlay         | wales.mackinlay@omis.net         | 64-9-3763555       | 199 Great North Road                    | Auckland      |           | New Zealand
  96 | Juri Yoshido            | juri.yoshido@klqb.net            | 6175559555         | 8616 Spinnaker Dr.                      | Boston        | 51003     | USA
  97 | Dorothy Young           | dorothy.young@cwtg.net           | 6035558647         | 2304 Long Airport Avenue                | Nashua        | 62005     | USA
 108 | Sarah McRoy             | sarah.mcroy@fjnn.net             | 04 499 9555        | 101 Lambton Quay, Level 11              | Wellington    |           | New Zealand
 109 | Michael Donnermeyer     | michael.donnermeyer@lvpk.net     |  +49 89 61 08 9555 | Hansastr. 15                            | Munich        | 80686     | Germany
 116 | Leslie Murphy           | leslie.murphy@lbgq.net           | 2035559545         | 567 North Pendale Street                | New Haven     | 97823     | USA
 117 | Yu Choi                 | yu.choi@vmpd.net                 | 2125551957         | 5290 North Pendale Street, Suite 200    | NYC           | 10022     | USA
 130 | Sue Taylor              | sue.taylor@wllx.net              | 4155554312         | 2793 Furth Circle                       | Brisbane      | 94217     | USA
 133 | Tony Snowden            | tony.snowden@rzcz.net            | +64 9 5555500      | Arenales 1938 3'A'                      | Auckland      |           | New Zealand
(28 rows)


postgres=#
```

</details><br>

Note: PostgreSQL also has the non-standard operator ILIKE that can perform a case-insensitive comparison - but avoid this to make code more portable.

### 17. Exercise 3

#### 17.1

- Which customers are from Norway?
- `SELECT * FROM customers WHERE country LIKE 'Norway';`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM customers WHERE country LIKE 'Norway';
 id |       name       |           email           |     phone     |              address               |  city   | postcode | country
----+------------------+---------------------------+---------------+------------------------------------+---------+----------+---------
 16 | Jonas Bergulfsen | jonas.bergulfsen@dxbn.net | 07-98 9555    | Erling Skakkes gate 78             | Stavern | 4110     | Norway
 31 | Veysel Oeztan    | veysel.oeztan@vqkn.net    | +47 2267 3215 | Brehmen St. 121, PR 334 Sentrum    | Bergen  | N 5804   | Norway
 73 | Jan Klaeboe      | jan.klaeboe@mpnl.net      | +47 2212 1555 | Drammensveien 126A, PB 211 Sentrum | Oslo    | N 0106   | Norway
(3 rows)


postgres=#
```

</details><br>

#### 17.2

- Which rooms can accommodate more than two people?
- `SELECT * FROM rooms WHERE no_guests > 2;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM rooms WHERE no_guests > 2;
 room_no |  rate  |  room_type   | no_guests
---------+--------+--------------+-----------
     205 |  85.00 | PREMIUM      |         3
     206 |  85.00 | PREMIUM      |         3
     207 |  85.00 | PREMIUM      |         3
     211 |  98.00 | PREMIUM PLUS |         3
     212 |  98.00 | PREMIUM PLUS |         3
     411 | 123.00 | FAMILY       |         4
     412 | 123.00 | FAMILY       |         4
(7 rows)


postgres=#
```

</details><br>

#### 17.3

- Which invoices are dated after one month ago?
- `SELECT * FROM invoices WHERE invoice_date >= '2023-04-02';`
- `SELECT * FROM invoices WHERE invoice_date <= CURRENT_DATE - INTERVAL '1 month';` (using DATE type)

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM invoices WHERE invoice_date >= '2023-04-02';
 id | res_id | total  | invoice_date | paid
----+--------+--------+--------------+------
 43 |     17 | 340.00 | 2023-04-05   | t
 44 |     99 | 440.00 | 2023-04-05   | t
 45 |     39 | 170.00 | 2023-04-06   | t
 46 |     38 | 110.00 | 2023-04-06   | t
 47 |     75 | 660.00 | 2023-04-06   | t
 48 |     41 | 615.00 | 2023-04-09   | t
 49 |    106 | 660.00 | 2023-04-10   | t
 50 |      2 | 246.00 | 2023-04-12   | t
 51 |     15 | 110.00 | 2023-04-12   | t
 52 |     57 | 246.00 | 2023-04-15   | t
 53 |     34 | 110.00 | 2023-04-16   | t
 54 |     58 |  85.00 | 2023-04-18   | t
 55 |     87 | 110.00 | 2023-04-20   | t
 56 |      3 | 369.00 | 2023-04-20   | t
 57 |    100 | 196.00 | 2023-04-21   | t
 58 |     45 | 660.00 | 2023-04-22   | t
 59 |     24 | 246.00 | 2023-04-23   | t
 60 |     32 | 110.00 | 2023-04-26   | t
 61 |     20 | 340.00 | 2023-04-27   | t
 62 |     56 | 490.00 | 2023-04-27   | t
 63 |     19 | 660.00 | 2023-04-28   | t
(21 rows)


postgres=#
```

</details><br>

#### 17.4

- How would last month's invoices change if we gave a discount of 15%
- `SELECT id, res_id, total * 0.85 as discount_total, invoice_date, paid FROM invoices WHERE invoice_date >= '2023-04-02';`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT id, res_id, total * 0.85 as discount_total, invoice_date, paid FROM invoices WHERE invoice_date >= '2023-04-02';
 id | res_id | discount_total | invoice_date | paid
----+--------+----------------+--------------+------
 43 |     17 |       289.0000 | 2023-04-05   | t
 44 |     99 |       374.0000 | 2023-04-05   | t
 45 |     39 |       144.5000 | 2023-04-06   | t
 46 |     38 |        93.5000 | 2023-04-06   | t
 47 |     75 |       561.0000 | 2023-04-06   | t
 48 |     41 |       522.7500 | 2023-04-09   | t
 49 |    106 |       561.0000 | 2023-04-10   | t
 50 |      2 |       209.1000 | 2023-04-12   | t
 51 |     15 |        93.5000 | 2023-04-12   | t
 52 |     57 |       209.1000 | 2023-04-15   | t
 53 |     34 |        93.5000 | 2023-04-16   | t
 54 |     58 |        72.2500 | 2023-04-18   | t
 55 |     87 |        93.5000 | 2023-04-20   | t
 56 |      3 |       313.6500 | 2023-04-20   | t
 57 |    100 |       166.6000 | 2023-04-21   | t
 58 |     45 |       561.0000 | 2023-04-22   | t
 59 |     24 |       209.1000 | 2023-04-23   | t
 60 |     32 |        93.5000 | 2023-04-26   | t
 61 |     20 |       289.0000 | 2023-04-27   | t
 62 |     56 |       416.5000 | 2023-04-27   | t
 63 |     19 |       561.0000 | 2023-04-28   | t
(21 rows)


postgres=#
```

</details><br>

#### 17.5

- List all customers whose second name starts with 'M' (hint: there's a space before the second name)
- `SELECT * FROM customers WHERE name LIKE '% M%_';`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM customers WHERE name LIKE '% M%_';
 id  |       name       |           email           |     phone     |          address           |     city      | postcode |   country
-----+------------------+---------------------------+---------------+----------------------------+---------------+----------+-------------
   7 | Melinda Marsh    | mel.marsh-123@gmail.com   | 070 1513 5671 | 7 Preston Road             | Oldham        | OL3 5XZ  | UK
  20 | Julie Murphy     | julie.murphy@lrtc.net     | 0650 555 5787 | 5557 North Pendale Street  | San Francisco | 94217    | USA
  60 | Renate Messner   | renate.messner@ebse.net   | 069-0555984   | Magazinweg 7               | Frankfurt     | 60528    | Germany
  90 | Patricia McKenna | patricia.mckenna@eert.net | 2967 555      | 8 Johnstown Road           | Cork          |          | Ireland
  94 | Wales MacKinlay  | wales.mackinlay@omis.net  | 64-9-3763555  | 199 Great North Road       | Auckland      |          | New Zealand
 104 | Maurizio Moroni  | maurizio.moroni@nqnk.net  | 0522-556555   | Strada Provinciale 124     | Reggio Emilia | 42100    | Italy
 107 | Rita M├╝ller     | rita.m├╝ller@gfsn.net     | 0711-555361   | Adenauerallee 900          | Stuttgart     | 70563    | Germany
 108 | Sarah McRoy      | sarah.mcroy@fjnn.net      | 04 499 9555   | 101 Lambton Quay, Level 11 | Wellington    |          | New Zealand
 115 | Roland Mendel    | roland.mendel@wclf.net    | 7675-3555     | Kirchgasse 6               | Graz          | 8010     | Austria
 116 | Leslie Murphy    | leslie.murphy@lbgq.net    | 2035559545    | 567 North Pendale Street   | New Haven     | 97823    | USA
 125 | Hanna Moos       | hanna.moos@fmga.net       | 0621-08555    | Forsterstr. 57             | Mannheim      | 68306    | Germany
(11 rows)


postgres=#
```

</details><br>

---

## 18 Using SQL Functions

You can use the built-in functions of SQL just as you can in JavaScript, but note that they are different (this is true of most programming languages) but there are also differences between SQL implementations.

You use functions to change values, usually of columns, wherever you can use a column, for example, in the selected list of values:

```
SELECT name, length(name) AS namelen, upper(email)
  FROM customers;
```

This query also uses a column alias (namelen) to provide a meaningful column heading.

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT name, length(name) AS namelen, upper(email)
postgres-#   FROM customers;
          name           | namelen |              upper
-------------------------+---------+----------------------------------
 John Smith              |      10 | J.SMITH@JOHNSMITH.ORG
 Sue Jones               |       9 | S.JONES1234@GMAIL.COM
 Alice Evans             |      11 | ALICE.EVANS001@HOTMAIL.COM
 Mohammed Trungpa        |      16 | MO.TRUNGPA@HOTMAIL.COM
 Steven King             |      11 | STEVE.KING123@HOTMAIL.COM
 Nadia Sethuraman        |      16 | NADIA.SETHURAMAN@MAIL.COM
 Melinda Marsh           |      13 | MEL.MARSH-123@GMAIL.COM
 Mart├¡n Sommer          |      14 | MARTIN.SOMMER@DFGG.NET
 Laurence Lebihan        |      16 | LAURENCE.LEBIHAN@XMZX.NET
 Keith Stewart           |      13 | KEITH.STEWART@GMAIL.COM
 Carlos Porter           |      13 | CARLOS.PORTER@ORTYNUF.COM
 Carine Schmitt          |      14 | CARINE.SCHMITT@DFTU.NET
 Jean King               |       9 | JEAN.KING@HJGP.NET
 Peter Ferguson          |      14 | PETER.FERGUSON@MXNX.NET
 Janine Labrune          |      14 | JANINE.LABRUNE@DLSH.NET
 Jonas Bergulfsen        |      16 | JONAS.BERGULFSEN@DXBN.NET
 Susan Nelson            |      12 | SUSAN.NELSON@FSVE.NET
 Zbyszek Piestrzeniewicz |      23 | ZBYSZEK.PIESTRZENIEWICZ@ASKT.NET
 Roland Keitel           |      13 | ROLAND.KEITEL@RIYS.NET
 Julie Murphy            |      12 | JULIE.MURPHY@LRTC.NET
 Kwai Lee                |       8 | KWAI.LEE@IMIC.NET
 Diego Freyre            |      12 | DIEGO.FREYRE@AMYR.NET
 Christina Berglund      |      18 | CHRISTINA.BERGLUND@CGGP.NET
 Jytte Petersen          |      14 | JYTTE.PETERSEN@CPBN.NET
 Mary Saveley            |      12 | MARY.SAVELEY@YPPL.NET
 Eric Natividad          |      14 | ERIC.NATIVIDAD@SWLL.NET
 Jeff Young              |      10 | JEFF.YOUNG@HAHH.NET
 Kelvin Leong            |      12 | KELVIN.LEONG@MQZY.NET
 Juri Hashimoto          |      14 | JURI.HASHIMOTO@FTTV.NET
 Wendy Victorino         |      15 | WENDY.VICTORINO@UEAI.NET
 Veysel Oeztan           |      13 | VEYSEL.OEZTAN@VQKN.NET
 Keith Franco            |      12 | KEITH.FRANCO@DLHA.NET
 Isabel de Castro        |      16 | ISABEL.DE.CASTRO@FPRO.NET
 Martine Ranc├®          |      14 | MARTINE.RANC├®@XEQS.NET
 Marie Bertrand          |      14 | MARIE.BERTRAND@GLUT.NET
 Jerry Tseng             |      11 | JERRY.TSENG@ETEA.NET
 Julie King              |      10 | JULIE.KING@YHFJ.NET
 Mory Kentary            |      12 | MORY.KENTARY@NQFG.NET
 Michael Frick           |      13 | MICHAEL.FRICK@JDEP.NET
 Matti Karttunen         |      15 | MATTI.KARTTUNEN@XKIG.NET
 Rachel Ashworth         |      15 | RACHEL.ASHWORTH@RZYB.NET
 Dean Cassidy            |      12 | DEAN.CASSIDY@SNTJ.NET
 Leslie Taylor           |      13 | LESLIE.TAYLOR@TUNP.NET
 Elizabeth Devon         |      15 | ELIZABETH.DEVON@BPCB.NET
 Yoshi Tamuri            |      12 | YOSHI.TAMURI@JUUQ.NET
 Miguel Barajas          |      14 | MIGUEL.BARAJAS@RSYQ.NET
 Julie Young             |      11 | JULIE.YOUNG@RMHL.NET
 Brydey Walker           |      13 | BRYDEY.WALKER@KWTJ.NET
 Fr├®d├®rique Citeaux    |      20 | FR├®D├®RIQUE.CITEAUX@VEKN.NET
 Mike Gao                |       8 | MIKE.GAO@PDRV.NET
 Eduardo Saavedra        |      16 | EDUARDO.SAAVEDRA@TIQA.NET
 Mary Young              |      10 | MARY.YOUNG@RATM.NET
 Horst Kloss             |      11 | HORST.KLOSS@BPZV.NET
 Palle Ibsen             |      11 | PALLE.IBSEN@BJQN.NET
 Jean Fresni├¿re         |      15 | JEAN.FRESNI├¿RE@UXSM.NET
 Alejandra Camino        |      16 | ALEJANDRA.CAMINO@OMET.NET
 Valarie Thompson        |      16 | VALARIE.THOMPSON@BRLL.NET
 Helen Bennett           |      13 | HELEN.BENNETT@QUET.NET
 Annette Roulet          |      14 | ANNETTE.ROULET@LGHA.NET
 Renate Messner          |      14 | RENATE.MESSNER@EBSE.NET
 Paolo Accorti           |      13 | PAOLO.ACCORTI@XCUW.NET
 Daniel Da Silva         |      15 | DANIEL.DA.SILVA@HIJY.NET
 Daniel Tonini           |      13 | DANIEL.TONINI@MXVW.NET
 Henriette Pfalzheim     |      19 | HENRIETTE.PFALZHEIM@HMIB.NET
 Elizabeth Lincoln       |      17 | ELIZABETH.LINCOLN@ELCT.NET
 Peter Franken           |      13 | PETER.FRANKEN@FSZX.NET
 Anna O'Hara             |      11 | ANNA.O"HARA@HZJW.NET
 Giovanni Rovelli        |      16 | GIOVANNI.ROVELLI@XRBZ.NET
 Adrian Huxley           |      13 | ADRIAN.HUXLEY@HMEP.NET
 Marta Hernandez         |      15 | MARTA.HERNANDEZ@XQTI.NET
 Ed Harrison             |      11 | ED.HARRISON@SVJB.NET
 Mihael Holz             |      11 | MIHAEL.HOLZ@DNJI.NET
 Jan Klaeboe             |      11 | JAN.KLAEBOE@MPNL.NET
 Bradley Schuyler        |      16 | BRADLEY.SCHUYLER@STIE.NET
 Mel Andersen            |      12 | MEL.ANDERSEN@NGGG.NET
 Pirkko Koskitalo        |      16 | PIRKKO.KOSKITALO@RCVA.NET
 Catherine Dewey         |      15 | CATHERINE.DEWEY@NDFT.NET
 Steve Frick             |      11 | STEVE.FRICK@UNAM.NET
 Wing Huang              |      10 | WING.HUANG@ROMC.NET
 Julie Brown             |      11 | JULIE.BROWN@ZBFM.NET
 Mike Graham             |      11 | MIKE.GRAHAM@NLPT.NET
 Ann Brown               |       9 | ANN.BROWN@XWKB.NET
 William Brown           |      13 | WILLIAM.BROWN@WRBO.NET
 Ben Calaghan            |      12 | BEN.CALAGHAN@BPRQ.NET
 Kalle Suominen          |      14 | KALLE.SUOMINEN@ACIF.NET
 Philip Cramer           |      13 | PHILIP.CRAMER@GMLF.NET
 Francisca Cervantes     |      19 | FRANCISCA.CERVANTES@SXXP.NET
 Jesus Fernandez         |      15 | JESUS.FERNANDEZ@CGXS.NET
 Brian Chandler          |      14 | BRIAN.CHANDLER@WDGI.NET
 Patricia McKenna        |      16 | PATRICIA.MCKENNA@EERT.NET
 Laurence Lebihan        |      16 | LAURENCE.LEBIHAN@XMZX.NET
 Paul Henriot            |      12 | PAUL.HENRIOT@UWUA.NET
 Armand Kuger            |      12 | ARMAND.KUGER@AXKQ.NET
 Wales MacKinlay         |      15 | WALES.MACKINLAY@OMIS.NET
 Karin Josephs           |      13 | KARIN.JOSEPHS@GYFV.NET
 Juri Yoshido            |      12 | JURI.YOSHIDO@KLQB.NET
 Dorothy Young           |      13 | DOROTHY.YOUNG@CWTG.NET
 Lino Rodriguez          |      14 | LINO.RODRIGUEZ@XSCN.NET
 Braun Urs               |       9 | BRAUN.URS@AOLS.NET
 Allen Nelson            |      12 | ALLEN.NELSON@ERUO.NET
 Pascale Cartrain        |      16 | PASCALE.CARTRAIN@OGGV.NET
 Georg Pipps             |      11 | GEORG.PIPPS@UYVB.NET
 Arnold Cruz             |      11 | ARNOLD.CRUZ@AWQA.NET
 Maurizio Moroni         |      15 | MAURIZIO.MORONI@NQNK.NET
 Akiko Shimamura         |      15 | AKIKO.SHIMAMURA@PIPL.NET
 Dominique Perrier       |      17 | DOMINIQUE.PERRIER@BDIM.NET
 Rita M├╝ller            |      12 | RITA.M├╝LLER@GFSN.NET
 Sarah McRoy             |      11 | SARAH.MCROY@FJNN.NET
 Michael Donnermeyer     |      19 | MICHAEL.DONNERMEYER@LVPK.NET
 Maria Hernandez         |      15 | MARIA.HERNANDEZ@UZKX.NET
 Alexander Feuer         |      15 | ALEXANDER.FEUER@HZRR.NET
 Dan Lewis               |       9 | DAN.LEWIS@BQFI.NET
 Martha Larsson          |      14 | MARTHA.LARSSON@ABHF.NET
 Sue Frick               |       9 | SUE.FRICK@NPGP.NET
 Roland Mendel           |      13 | ROLAND.MENDEL@WCLF.NET
 Leslie Murphy           |      13 | LESLIE.MURPHY@LBGQ.NET
 Yu Choi                 |       7 | YU.CHOI@VMPD.NET
 Mart├¡n Sommer          |      14 | MART├¡N.SOMMER@WCOA.NET
 Sven Ottlieb            |      12 | SVEN.OTTLIEB@DQYJ.NET
 Violeta Benitez         |      15 | VIOLETA.BENITEZ@YQSD.NET
 Carmen Anton            |      12 | CARMEN.ANTON@BHMY.NET
 Sean Clenahan           |      13 | SEAN.CLENAHAN@GZYW.NET
 Franco Ricotti          |      14 | FRANCO.RICOTTI@YCBK.NET
 Steve Thompson          |      14 | STEVE.THOMPSON@NIRJ.NET
 Hanna Moos              |      10 | HANNA.MOOS@FMGA.NET
 Alexander Semenov       |      17 | ALEXANDER.SEMENOV@XGRU.NET
 Raanan Altagar,G M      |      18 | RAANAN.ALTAGAR,G.M@MLAP.NET
 Jos├® Pedro Roel        |      16 | JOS├®.PEDRO.ROEL@QJMK.NET
 Rosa Salazar            |      12 | ROSA.SALAZAR@FZIK.NET
 Sue Taylor              |      10 | SUE.TAYLOR@WLLX.NET
 Thomas Smith            |      12 | THOMAS.SMITH@NVZE.NET
 Valarie Franco          |      14 | VALARIE.FRANCO@QAIT.NET
 Tony Snowden            |      12 | TONY.SNOWDEN@RZCZ.NET
(133 rows)


postgres=#
```

</details><br>

Functions are available that operate on all different datatypes.

Country names are mixed case so to make sure we always match regardless of the stored case we can use the lower function to find all customers from Manchester, UK:

```
SELECT * FROM customers
   WHERE lower(country) = 'uk'
     AND city = 'Manchester';
```

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT * FROM customers
postgres-#    WHERE lower(country) = 'uk'
postgres-#      AND city = 'Manchester';
 id |       name       |           email            |     phone      |      address      |    city    | postcode | country
----+------------------+----------------------------+----------------+-------------------+------------+----------+---------
  3 | Alice Evans      | alice.evans001@hotmail.com | 0161 345 6789  | 3 High Road       | Manchester | m13 4ef  | UK
  4 | Mohammed Trungpa | mo.trungpa@hotmail.com     | 0161 456 7890  | 25 Blue Road      | Manchester | M25 6GH  | UK
  6 | Nadia Sethuraman | nadia.sethuraman@mail.com  |                | 135 Green Street  | Manchester | M10 4BG  | UK
 41 | Rachel Ashworth  | rachel.ashworth@rzyb.net   | (171) 555-1555 | Fauntleroy Circus | Manchester | EC2 5NT  | UK
(4 rows)


postgres=#
```

</details><br>

Assuming room rates include VAT at 20%, list room rates after VAT increases to 23.5% (from 20%), but round to the nearest pound:

```
SELECT room_no, room_type, rate AS old_rate,
       round(rate * 100/120 * 123.5/100) AS new_rate
   FROM rooms;
```

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT room_no, room_type, rate AS old_rate,
postgres-#        round(rate * 100/120 * 123.5/100) AS new_rate
postgres-#    FROM rooms;
 room_no |  room_type   | old_rate | new_rate
---------+--------------+----------+----------
     101 | PREMIUM      |    85.00 |       87
     102 | PREMIUM      |    85.00 |       87
     103 | PREMIUM      |    85.00 |       87
     104 | PREMIUM      |    85.00 |       87
     105 | PREMIUM      |    85.00 |       87
     106 | PREMIUM      |    85.00 |       87
     107 | PREMIUM      |    85.00 |       87
     108 | PREMIUM PLUS |    98.00 |      101
     109 | PREMIUM PLUS |    98.00 |      101
     110 | PREMIUM PLUS |    98.00 |      101
     111 | PREMIUM PLUS |    98.00 |      101
     112 | PREMIUM PLUS |    98.00 |      101
     201 | PREMIUM      |    85.00 |       87
     202 | PREMIUM      |    85.00 |       87
     203 | PREMIUM      |    85.00 |       87
     204 | PREMIUM      |    85.00 |       87
     205 | PREMIUM      |    85.00 |       87
     206 | PREMIUM      |    85.00 |       87
     207 | PREMIUM      |    85.00 |       87
     208 | PREMIUM PLUS |    98.00 |      101
     209 | PREMIUM PLUS |    98.00 |      101
     210 | PREMIUM PLUS |    98.00 |      101
     211 | PREMIUM PLUS |    98.00 |      101
     212 | PREMIUM PLUS |    98.00 |      101
     301 | PREMIER      |   110.00 |      113
     302 | PREMIER      |   110.00 |      113
     303 | PREMIER      |   110.00 |      113
     304 | PREMIER      |   110.00 |      113
     305 | PREMIER      |   110.00 |      113
     306 | PREMIER      |   110.00 |      113
     307 | PREMIER      |   110.00 |      113
     308 | PREMIER PLUS |   123.00 |      127
     309 | PREMIER PLUS |   123.00 |      127
     310 | PREMIER PLUS |   123.00 |      127
     311 | PREMIER PLUS |   123.00 |      127
     312 | PREMIER PLUS |   123.00 |      127
     401 | PREMIER      |   110.00 |      113
     402 | PREMIER      |   110.00 |      113
     403 | PREMIER      |   110.00 |      113
     404 | PREMIER      |   110.00 |      113
     405 | PREMIER      |   110.00 |      113
     406 | PREMIER      |   110.00 |      113
     407 | PREMIER      |   110.00 |      113
     408 | PREMIER PLUS |   123.00 |      127
     409 | PREMIER PLUS |   123.00 |      127
     410 | PREMIER PLUS |   123.00 |      127
     411 | FAMILY       |   123.00 |      127
     412 | FAMILY       |   123.00 |      127
(48 rows)


postgres=#
```

</details><br>


For further information on SQL functions see the official PostgreSQL documentation at https://www.postgresql.org/docs/current/index.html

---

## 19. Date and Time in SQL

In SQL dates and times are held in an internal format but are represented externally (when entering values and displaying them) as strings;

-Text date format: 'YYYY-MM-DD' e.g. '2018-07-21' = 21 July 2018
-Time format: 'HH:mm:SS.ddd' e.g. '14:32'
-Date/Time format: 'YYYY-MM-DD HH:mm:SS.ddd' e.g. '2018-07-21 15:26:04'

You can perform arithmetic on dates and times, for example:

```
SELECT cust_id, room_no, checkin_date,
       checkout_date - checkin_date AS nights
   FROM reservations
   WHERE checkout_date = current_date + 1;
```

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT cust_id, room_no, checkin_date, checkout_Date - checkin_date AS nights FROM reservations WHERE checkout_date = current_d
ate + 2;
 cust_id | room_no | checkin_date | nights
---------+---------+--------------+--------
      44 |         | 2023-04-30   |      4
(1 row)


postgres=#
```

</details><br>

This query performs subtraction of one date from another (checkout_date - checkin_date) to calculate the number of nights the customer has stayed. It also performs addition (current_date + 1) to get tomorrow's date so that it lists all reservations that will be checking out tomorrow.

Note: current_date is a postgres function that returns the current date.

Also note that there are many ways to get the same result - you may explore those for yourself.

You can also represent time intervals but the representations can be complicated and we shall not cover them here.

---

## 20. Exercise 4

### 20.1
- Write a query to check that all booking dates are before their checkin dates
- `SELECT checkin_date, checkout_date FROM reservations WHERE checkin_date < checkout_date;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT checkin_date, checkout_date FROM reservations WHERE checkin_date < checkout_date;
 checkin_date | checkout_date
--------------+---------------
 2023-03-21   | 2023-03-24
 2023-04-10   | 2023-04-12
 2023-04-17   | 2023-04-20
 2023-03-23   | 2023-03-25
 2023-03-27   | 2023-03-30
 2023-03-25   | 2023-03-30
 2023-03-03   | 2023-03-06
 2023-03-16   | 2023-03-22
 2023-03-22   | 2023-03-23
 2023-03-27   | 2023-03-30
 2023-04-11   | 2023-04-12
 2023-04-01   | 2023-04-05
 2023-03-15   | 2023-03-17
 2023-04-22   | 2023-04-28
 2023-04-23   | 2023-04-27
 2023-03-21   | 2023-03-23
 2023-04-21   | 2023-04-23
 2023-03-24   | 2023-03-30
 2023-03-11   | 2023-03-12
 2023-05-24   | 2023-05-29
 2023-05-21   | 2023-05-24
 2023-06-02   | 2023-06-04
 2023-05-12   | 2023-05-13
 2023-05-04   | 2023-05-06
 2023-05-09   | 2023-05-13
 2023-05-06   | 2023-05-10
 2023-05-06   | 2023-05-11
 2023-05-24   | 2023-05-26
 2023-05-29   | 2023-06-01
 2023-05-30   | 2023-06-01
 2023-03-16   | 2023-03-17
 2023-04-25   | 2023-04-26
 2023-04-15   | 2023-04-16
 2023-03-14   | 2023-03-18
 2023-03-22   | 2023-03-27
 2023-03-07   | 2023-03-08
 2023-04-05   | 2023-04-06
 2023-04-04   | 2023-04-06
 2023-04-04   | 2023-04-09
 2023-03-03   | 2023-03-09
 2023-03-19   | 2023-03-24
 2023-04-16   | 2023-04-22
 2023-03-17   | 2023-03-18
 2023-03-23   | 2023-03-28
 2023-03-25   | 2023-03-30
 2023-03-10   | 2023-03-13
 2023-03-21   | 2023-03-23
 2023-04-22   | 2023-04-27
 2023-04-13   | 2023-04-15
 2023-04-17   | 2023-04-18
 2023-03-01   | 2023-03-07
 2023-03-23   | 2023-03-26
 2023-03-06   | 2023-03-07
 2023-03-04   | 2023-03-08
 2023-03-14   | 2023-03-20
 2023-03-01   | 2023-03-06
 2023-04-27   | 2023-05-02
 2023-03-19   | 2023-03-23
 2023-03-14   | 2023-03-16
 2023-03-31   | 2023-04-06
 2023-03-13   | 2023-03-15
 2023-04-25   | 2023-04-30
 2023-03-22   | 2023-03-23
 2023-03-16   | 2023-03-18
 2023-03-31   | 2023-04-01
 2023-04-19   | 2023-04-20
 2023-03-11   | 2023-03-13
 2023-03-21   | 2023-03-22
 2023-03-26   | 2023-03-29
 2023-03-31   | 2023-04-01
 2023-03-22   | 2023-03-24
 2023-04-01   | 2023-04-05
 2023-04-19   | 2023-04-21
 2023-03-04   | 2023-03-09
 2023-03-21   | 2023-03-23
 2023-04-04   | 2023-04-10
 2023-06-02   | 2023-06-04
 2023-06-02   | 2023-06-06
 2023-05-12   | 2023-05-13
 2023-05-05   | 2023-05-06
 2023-05-03   | 2023-05-09
 2023-05-22   | 2023-05-23
 2023-06-04   | 2023-06-09
 2023-05-17   | 2023-05-20
 2023-05-29   | 2023-06-02
 2023-05-06   | 2023-05-10
 2023-05-09   | 2023-05-12
 2023-06-04   | 2023-06-07
 2023-05-24   | 2023-05-27
 2023-05-11   | 2023-05-14
 2023-05-27   | 2023-06-02
 2023-05-11   | 2023-05-16
 2023-05-28   | 2023-05-30
 2023-05-09   | 2023-05-14
 2023-05-24   | 2023-05-29
 2023-05-09   | 2023-05-10
 2023-05-28   | 2023-05-31
 2023-05-14   | 2023-05-19
 2023-05-02   | 2023-05-05
 2023-04-30   | 2023-05-04
 2023-05-04   | 2023-05-08
 2023-06-04   | 2023-06-08
 2023-05-20   | 2023-05-22
 2023-05-13   | 2023-05-17
 2023-06-01   | 2023-06-07
 2023-05-26   | 2023-05-28
(106 rows)


postgres=#
```

</details><br>

### 20.2
- We plan to offer a discount of 10% on all Premier and Premier Plus rooms next month. How much would we gain on each room if occupancy rose by 5 nights over the month.
- ``

<details>
<summary>Terminal Output</summary>

```
insert here
```

</details><br>

### 20.3
- List all reservations for this month and the number of nights booked.
- `SELECT id, cust_id, room_no, (checkout_date - checkin_date) AS no_nights, no_guests, booking_date FROM reservations WHERE (EXTRACT(MONTH from checkin_date) = EXTRACT(MONTH FROM CURRENT_DATE) AND EXTRACT(MONTH FROM checkout_date) = EXTRACT(MONTH FROM CURRENT_DATE));`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT id, cust_id, room_no, (checkout_date - checkin_date) AS no_nights, no_guests, booking_date FROM reservations WHERE (EXTRACT(MONTH from checkin_date) = EXTRACT(MONTH FROM CURRENT_DATE) AND EXTRACT(MONTH FROM checkout_date) = EXTRACT(MONTH FROM CURRENT_DATE));

 id  | cust_id | room_no | no_nights | no_guests | booking_date
-----+---------+---------+-----------+-----------+--------------
   6 |     119 |         |         5 |         2 | 2023-04-29
   9 |      64 |         |         3 |         2 | 2023-04-29
  14 |      32 |         |         1 |         1 | 2023-04-21
  16 |      83 |         |         2 |         1 | 2023-04-23
  21 |      51 |         |         4 |         1 | 2023-04-29
  23 |      46 |         |         4 |         2 | 2023-04-20
  25 |      19 |         |         5 |         2 | 2023-04-12
  27 |      76 |         |         2 |         2 | 2023-04-29
  42 |     110 |         |         1 |         2 | 2023-04-14
  47 |      31 |         |         1 |         1 | 2023-04-12
  49 |      16 |         |         6 |         1 | 2023-04-29
  51 |     117 |         |         1 |         1 | 2023-04-29
  54 |      97 |         |         3 |         1 | 2023-04-29
  63 |      15 |         |         4 |         1 | 2023-04-19
  64 |      79 |         |         3 |         2 | 2023-04-29
  67 |       9 |         |         3 |         1 | 2023-04-29
  70 |      26 |         |         3 |         1 | 2023-04-20
  76 |      35 |         |         5 |         2 | 2023-04-18
  78 |     119 |         |         2 |         2 | 2023-04-29
  79 |      38 |         |         5 |         2 | 2023-04-29
  80 |      96 |         |         5 |         1 | 2023-04-29
  81 |      24 |         |         1 |         1 | 2023-04-26
  86 |      12 |         |         3 |         1 | 2023-04-29
  88 |      63 |         |         5 |         1 | 2023-04-29
  90 |      66 |         |         3 |         1 | 2023-04-26
  93 |     129 |         |         4 |         1 | 2023-04-18
  97 |     116 |         |         2 |         1 | 2023-04-29
 102 |      93 |         |         4 |         1 | 2023-04-25
 105 |     108 |         |         2 |         1 | 2023-04-29
(29 rows)


postgres=#
```

</details><br>

---

## 21. Eliminating Duplicates

"Which nationalities visit our hotel?":

`SELECT country FROM customers;`

But how many values do you see returned for each country? 
If two customers come from a particular country that country will appear twice in the output. 
If more than two come from the same country then... But we only need to know the different countries.

To see each country only once, use the keyword DISTINCT, as follows:

`SELECT DISTINCT country FROM customers;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT DISTINCT country FROM customers;
   country
--------------
 Spain
 Switzerland
 New Zealand
 Italy
 Russia
 Belgium
 Sweden
 Norway
 USA
 France
 Israel
 Netherlands
 South Africa
 Austria
 Poland
 Australia
 UK
 Hong Kong
 Ireland
 Germany
 Japan
 Singapore
 Denmark
 Canada
 Philippines
 Finland
 Portugal
(27 rows)


postgres=#
```

</details><br>

The keyword DISTINCT must appear immediately after the keyword SELECT. If more than one column is selected then DISTINCT applies to the combined values of those columns

---

## 22. Ordering the Returned Rows

If you want to see the data in a specific order
e.g. "List all customers alphabetically by name within each country":

```
SELECT id, name, phone, email, country
    FROM customers
    ORDER BY country, name;
```

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT id, name, phone, email, country
postgres-#     FROM customers
postgres-#     ORDER BY country, name;
 id  |          name           |       phone        |              email               |   country
-----+-------------------------+--------------------+----------------------------------+--------------
  69 | Adrian Huxley           | +61 2 9495 8555    | adrian.huxley@hmep.net           | Australia
  67 | Anna O'Hara             | 02 9936 8555       | anna.o"hara@hzjw.net             | Australia
  84 | Ben Calaghan            | 61-7-3844-6555     | ben.calaghan@bprq.net            | Australia
  14 | Peter Ferguson          | 03 9520 4555       | peter.ferguson@mxnx.net          | Australia
 122 | Sean Clenahan           | 61-9-3844-6555     | sean.clenahan@gzyw.net           | Australia
 102 | Georg Pipps             | 6562-9555          | georg.pipps@uyvb.net             | Austria
 115 | Roland Mendel           | 7675-3555          | roland.mendel@wclf.net           | Austria
  77 | Catherine Dewey         | (02) 5554 67       | catherine.dewey@ndft.net         | Belgium
 101 | Pascale Cartrain        | (071) 23 67 2555   | pascale.cartrain@oggv.net        | Belgium
  65 | Elizabeth Lincoln       | (604) 555-4555     | elizabeth.lincoln@elct.net       | Canada
  55 | Jean Fresni├¿re         | (514) 555-8054     | jean.fresni├¿re@uxsm.net         | Canada
  45 | Yoshi Tamuri            | (604) 555-3392     | yoshi.tamuri@juuq.net            | Canada
  24 | Jytte Petersen          | 31 12 3555         | jytte.petersen@cpbn.net          | Denmark
  54 | Palle Ibsen             | 86 21 3555         | palle.ibsen@bjqn.net             | Denmark
  85 | Kalle Suominen          | +358 9 8045 555    | kalle.suominen@acif.net          | Finland
  40 | Matti Karttunen         | 90-224 8555        | matti.karttunen@xkig.net         | Finland
  76 | Pirkko Koskitalo        | 981-443655         | pirkko.koskitalo@rcva.net        | Finland
  59 | Annette Roulet          | 61.77.6555         | annette.roulet@lgha.net          | France
  12 | Carine Schmitt          | 40.32.2555         | carine.schmitt@dftu.net          | France
  62 | Daniel Da Silva         | +33 1 46 62 7555   | daniel.da.silva@hijy.net         | France
  63 | Daniel Tonini           | 30.59.8555         | daniel.tonini@mxvw.net           | France
 106 | Dominique Perrier       | (1) 47.55.6555     | dominique.perrier@bdim.net       | France
  49 | Fr├®d├®rique Citeaux    | 88.60.1555         | fr├®d├®rique.citeaux@vekn.net    | France
  15 | Janine Labrune          | 40.67.8555         | janine.labrune@dlsh.net          | France
  91 | Laurence Lebihan        | 91.24.4555         | laurence.lebihan@xmzx.net        | France
   9 | Laurence Lebihan        | 91.24.4555         | laurence.lebihan@xmzx.net        | France
  35 | Marie Bertrand          | (1) 42.34.2555     | marie.bertrand@glut.net          | France
  34 | Martine Ranc├®          | 20.16.1555         | martine.ranc├®@xeqs.net          | France
  25 | Mary Saveley            | 78.32.5555         | mary.saveley@yppl.net            | France
  92 | Paul Henriot            | 26.47.1555         | paul.henriot@uwua.net            | France
 111 | Alexander Feuer         | 0342-555176        | alexander.feuer@hzrr.net         | Germany
 125 | Hanna Moos              | 0621-08555         | hanna.moos@fmga.net              | Germany
  64 | Henriette Pfalzheim     | 0221-5554327       | henriette.pfalzheim@hmib.net     | Germany
  53 | Horst Kloss             | 0372-555188        | horst.kloss@bpzv.net             | Germany
  95 | Karin Josephs           | 0251-555259        | karin.josephs@gyfv.net           | Germany
  75 | Mel Andersen            | 030-0074555        | mel.andersen@nggg.net            | Germany
 109 | Michael Donnermeyer     |  +49 89 61 08 9555 | michael.donnermeyer@lvpk.net     | Germany
  66 | Peter Franken           | 089-0877555        | peter.franken@fszx.net           | Germany
  86 | Philip Cramer           | 0555-09555         | philip.cramer@gmlf.net           | Germany
  60 | Renate Messner          | 069-0555984        | renate.messner@ebse.net          | Germany
 107 | Rita M├╝ller            | 0711-555361        | rita.m├╝ller@gfsn.net            | Germany
  19 | Roland Keitel           | +49 69 66 90 2555  | roland.keitel@riys.net           | Germany
 119 | Sven Ottlieb            | 0241-039123        | sven.ottlieb@dqyj.net            | Germany
  50 | Mike Gao                | +852 2251 1555     | mike.gao@pdrv.net                | Hong Kong
  42 | Dean Cassidy            | +353 1862 1555     | dean.cassidy@sntj.net            | Ireland
  90 | Patricia McKenna        | 2967 555           | patricia.mckenna@eert.net        | Ireland
 127 | Raanan Altagar,G M      | + 972 9 959 8555   | raanan.altagar,g.m@mlap.net      | Israel
 123 | Franco Ricotti          | +39 022515555      | franco.ricotti@ycbk.net          | Italy
  68 | Giovanni Rovelli        | 035-640555         | giovanni.rovelli@xrbz.net        | Italy
 104 | Maurizio Moroni         | 0522-556555        | maurizio.moroni@nqnk.net         | Italy
  61 | Paolo Accorti           | 011-4988555        | paolo.accorti@xcuw.net           | Italy
 105 | Akiko Shimamura         | +81 3 3584 0555    | akiko.shimamura@pipl.net         | Japan
  38 | Mory Kentary            | +81 06 6342 5555   | mory.kentary@nqfg.net            | Japan
  74 | Bradley Schuyler        | +31 20 491 9555    | bradley.schuyler@stie.net        | Netherlands
  81 | Mike Graham             | +64 9 312 5555     | mike.graham@nlpt.net             | New Zealand
 108 | Sarah McRoy             | 04 499 9555        | sarah.mcroy@fjnn.net             | New Zealand
 133 | Tony Snowden            | +64 9 5555500      | tony.snowden@rzcz.net            | New Zealand
  94 | Wales MacKinlay         | 64-9-3763555       | wales.mackinlay@omis.net         | New Zealand
  73 | Jan Klaeboe             | +47 2212 1555      | jan.klaeboe@mpnl.net             | Norway
  16 | Jonas Bergulfsen        | 07-98 9555         | jonas.bergulfsen@dxbn.net        | Norway
  31 | Veysel Oeztan           | +47 2267 3215      | veysel.oeztan@vqkn.net           | Norway
 103 | Arnold Cruz             | +63 2 555 3587     | arnold.cruz@awqa.net             | Philippines
  18 | Zbyszek Piestrzeniewicz | (26) 642-7555      | zbyszek.piestrzeniewicz@askt.net | Poland
  33 | Isabel de Castro        | (1) 356-5555       | isabel.de.castro@fpro.net        | Portugal
  98 | Lino Rodriguez          | (1) 354-2555       | lino.rodriguez@xscn.net          | Portugal
 126 | Alexander Semenov       | +7 812 293 0521    | alexander.semenov@xgru.net       | Russia
  48 | Brydey Walker           | +612 9411 1555     | brydey.walker@kwtj.net           | Singapore
  26 | Eric Natividad          | +65 221 7555       | eric.natividad@swll.net          | Singapore
  30 | Wendy Victorino         | +65 224 1555       | wendy.victorino@ueai.net         | Singapore
  93 | Armand Kuger            | +27 21 550 3555    | armand.kuger@axkq.net            | South Africa
  56 | Alejandra Camino        | (91) 745 6555      | alejandra.camino@omet.net        | Spain
 121 | Carmen Anton            | +34 913 728555     | carmen.anton@bhmy.net            | Spain
  22 | Diego Freyre            | (91) 555 94 44     | diego.freyre@amyr.net            | Spain
  51 | Eduardo Saavedra        | (93) 203 4555      | eduardo.saavedra@tiqa.net        | Spain
  88 | Jesus Fernandez         | +34 913 728 555    | jesus.fernandez@cgxs.net         | Spain
 128 | Jos├® Pedro Roel        | (95) 555 82 82     | jos├®.pedro.roel@qjmk.net        | Spain
   8 | Mart├¡n Sommer          | (91) 555 22 82     | martin.sommer@dfgg.net           | Spain
 118 | Mart├¡n Sommer          | (91) 555 22 82     | mart├¡n.sommer@wcoa.net          | Spain
  23 | Christina Berglund      | 0921-12 3555       | christina.berglund@cggp.net      | Sweden
 113 | Martha Larsson          | 0695-34 6555       | martha.larsson@abhf.net          | Sweden
  99 | Braun Urs               | 0452-076555        | braun.urs@aols.net               | Switzerland
  71 | Ed Harrison             | +41 26 425 50 01   | ed.harrison@svjb.net             | Switzerland
  72 | Mihael Holz             | 0897-034555        | mihael.holz@dnji.net             | Switzerland
   3 | Alice Evans             | 0161 345 6789      | alice.evans001@hotmail.com       | UK
  82 | Ann Brown               | (171) 555-0297     | ann.brown@xwkb.net               | UK
  11 | Carlos Porter           | 070 2679 6812      | carlos.porter@ortynuf.com        | UK
  44 | Elizabeth Devon         | (171) 555-2282     | elizabeth.devon@bpcb.net         | UK
  58 | Helen Bennett           | (198) 555-8888     | helen.bennett@quet.net           | UK
   1 | John Smith              | 0151 123 4567      | j.smith@johnsmith.org            | UK
  10 | Keith Stewart           | 078 4679 1282      | keith.stewart@gmail.com          | UK
   7 | Melinda Marsh           | 070 1513 5671      | mel.marsh-123@gmail.com          | UK
   4 | Mohammed Trungpa        | 0161 456 7890      | mo.trungpa@hotmail.com           | UK
   6 | Nadia Sethuraman        |                    | nadia.sethuraman@mail.com        | UK
  41 | Rachel Ashworth         | (171) 555-1555     | rachel.ashworth@rzyb.net         | UK
   5 | Steven King             | 01245 134 4678     | steve.king123@hotmail.com        | UK
   2 | Sue Jones               | 0201 234 5678      | s.jones1234@gmail.com            | UK
 131 | Thomas Smith            | (171) 555-7555     | thomas.smith@nvze.net            | UK
 100 | Allen Nelson            | 6175558555         | allen.nelson@eruo.net            | USA
  89 | Brian Chandler          | 2155554369         | brian.chandler@wdgi.net          | USA
 112 | Dan Lewis               | 2035554407         | dan.lewis@bqfi.net               | USA
  97 | Dorothy Young           | 6035558647         | dorothy.young@cwtg.net           | USA
  87 | Francisca Cervantes     | 2155554695         | francisca.cervantes@sxxp.net     | USA
  13 | Jean King               | 07025 551 838      | jean.king@hjgp.net               | USA
  27 | Jeff Young              | 0212 555 7413      | jeff.young@hahh.net              | USA
  36 | Jerry Tseng             | 6175555555         | jerry.tseng@etea.net             | USA
  80 | Julie Brown             | 6505551386         | julie.brown@zbfm.net             | USA
  37 | Julie King              | 2035552570         | julie.king@yhfj.net              | USA
  20 | Julie Murphy            | 0650 555 5787      | julie.murphy@lrtc.net            | USA
  47 | Julie Young             | 6265557265         | julie.young@rmhl.net             | USA
  29 | Juri Hashimoto          | 0650 555 6809      | juri.hashimoto@fttv.net          | USA
  96 | Juri Yoshido            | 6175559555         | juri.yoshido@klqb.net            | USA
  32 | Keith Franco            | 2035557845         | keith.franco@dlha.net            | USA
  28 | Kelvin Leong            | 0215 555 1555      | kelvin.leong@mqzy.net            | USA
  21 | Kwai Lee                | 0212 555 7818      | kwai.lee@imic.net                | USA
 116 | Leslie Murphy           | 2035559545         | leslie.murphy@lbgq.net           | USA
  43 | Leslie Taylor           | 6175558428         | leslie.taylor@tunp.net           | USA
 110 | Maria Hernandez         | 2125558493         | maria.hernandez@uzkx.net         | USA
  70 | Marta Hernandez         | 6175558555         | marta.hernandez@xqti.net         | USA
  52 | Mary Young              | 3105552373         | mary.young@ratm.net              | USA
  39 | Michael Frick           | 2125551500         | michael.frick@jdep.net           | USA
  46 | Miguel Barajas          | 6175557555         | miguel.barajas@rsyq.net          | USA
 129 | Rosa Salazar            | 2155559857         | rosa.salazar@fzik.net            | USA
  78 | Steve Frick             | 9145554562         | steve.frick@unam.net             | USA
 124 | Steve Thompson          | 3105553722         | steve.thompson@nirj.net          | USA
 114 | Sue Frick               | 4085553659         | sue.frick@npgp.net               | USA
 130 | Sue Taylor              | 4155554312         | sue.taylor@wllx.net              | USA
  17 | Susan Nelson            | 0415 555 1450      | susan.nelson@fsve.net            | USA
 132 | Valarie Franco          | 6175552555         | valarie.franco@qait.net          | USA
  57 | Valarie Thompson        | 7605558146         | valarie.thompson@brll.net        | USA
 120 | Violeta Benitez         | 5085552555         | violeta.benitez@yqsd.net         | USA
  83 | William Brown           | 2015559350         | william.brown@wrbo.net           | USA
  79 | Wing Huang              | 5085559555         | wing.huang@romc.net              | USA
 117 | Yu Choi                 | 2125551957         | yu.choi@vmpd.net                 | USA
(133 rows)


postgres=#
```

</details><br>

You can can add ASC (ascending, the default) or DESC (descending) after each column name in the ORDER BY clause to control the direction of sorting.

For example:

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT id, name, country, city
postgres-#     FROM customers
postgres-#     ORDER BY country DESC, city;
 id  |          name           |   country    |       city
-----+-------------------------+--------------+-------------------
  28 | Kelvin Leong            | USA          | Allentown
 132 | Valarie Franco          | USA          | Boston
  96 | Juri Yoshido            | USA          | Boston
 100 | Allen Nelson            | USA          | Brickhaven
  46 | Miguel Barajas          | USA          | Brickhaven
  43 | Leslie Taylor           | USA          | Brickhaven
  37 | Julie King              | USA          | Bridgewater
 130 | Sue Taylor              | USA          | Brisbane
 124 | Steve Thompson          | USA          | Burbank
  29 | Juri Hashimoto          | USA          | Burlingame
  36 | Jerry Tseng             | USA          | Cambridge
  70 | Marta Hernandez         | USA          | Cambridge
 112 | Dan Lewis               | USA          | Glendale
  52 | Mary Young              | USA          | Glendale
  13 | Jean King               | USA          | Las Vegas
  89 | Brian Chandler          | USA          | Los Angeles
  97 | Dorothy Young           | USA          | Nashua
 120 | Violeta Benitez         | USA          | New Bedford
  79 | Wing Huang              | USA          | New Bedford
  32 | Keith Franco            | USA          | New Haven
 116 | Leslie Murphy           | USA          | New Haven
  83 | William Brown           | USA          | Newark
 110 | Maria Hernandez         | USA          | NYC
  39 | Michael Frick           | USA          | NYC
  27 | Jeff Young              | USA          | NYC
  21 | Kwai Lee                | USA          | NYC
 117 | Yu Choi                 | USA          | NYC
  47 | Julie Young             | USA          | Pasadena
  87 | Francisca Cervantes     | USA          | Philadelphia
 129 | Rosa Salazar            | USA          | Philadelphia
  57 | Valarie Thompson        | USA          | San Diego
  80 | Julie Brown             | USA          | San Francisco
  20 | Julie Murphy            | USA          | San Francisco
 114 | Sue Frick               | USA          | San Jose
  17 | Susan Nelson            | USA          | San Rafael
  78 | Steve Frick             | USA          | White Plains
  58 | Helen Bennett           | UK           | Cowes
  44 | Elizabeth Devon         | UK           | Liverpool
   1 | John Smith              | UK           | Liverpool
   2 | Sue Jones               | UK           | London
 131 | Thomas Smith            | UK           | London
  82 | Ann Brown               | UK           | London
   4 | Mohammed Trungpa        | UK           | Manchester
  41 | Rachel Ashworth         | UK           | Manchester
   6 | Nadia Sethuraman        | UK           | Manchester
   3 | Alice Evans             | UK           | Manchester
   5 | Steven King             | UK           | Newtown
   7 | Melinda Marsh           | UK           | Oldham
  11 | Carlos Porter           | UK           | Salisbury
  10 | Keith Stewart           | UK           | Tadworth
  99 | Braun Urs               | Switzerland  | Bern
  71 | Ed Harrison             | Switzerland  | Fribourg
  72 | Mihael Holz             | Switzerland  | Gen├¿ve
 113 | Martha Larsson          | Sweden       | Br├ñcke
  23 | Christina Berglund      | Sweden       | Lule├Ñ
  51 | Eduardo Saavedra        | Spain        | Barcelona
 121 | Carmen Anton            | Spain        | Madrid
   8 | Mart├¡n Sommer          | Spain        | Madrid
  88 | Jesus Fernandez         | Spain        | Madrid
 118 | Mart├¡n Sommer          | Spain        | Madrid
  56 | Alejandra Camino        | Spain        | Madrid
  22 | Diego Freyre            | Spain        | Madrid
 128 | Jos├® Pedro Roel        | Spain        | Sevilla
  93 | Armand Kuger            | South Africa | Hatfield
  30 | Wendy Victorino         | Singapore    | Singapore
  48 | Brydey Walker           | Singapore    | Singapore
  26 | Eric Natividad          | Singapore    | Singapore
 126 | Alexander Semenov       | Russia       | Saint Petersburg
  98 | Lino Rodriguez          | Portugal     | Lisboa
  33 | Isabel de Castro        | Portugal     | Lisboa
  18 | Zbyszek Piestrzeniewicz | Poland       | Warszawa
 103 | Arnold Cruz             | Philippines  | Makati City
  31 | Veysel Oeztan           | Norway       | Bergen
  73 | Jan Klaeboe             | Norway       | Oslo
  16 | Jonas Bergulfsen        | Norway       | Stavern
  94 | Wales MacKinlay         | New Zealand  | Auckland
 133 | Tony Snowden            | New Zealand  | Auckland
  81 | Mike Graham             | New Zealand  | Auckland
 108 | Sarah McRoy             | New Zealand  | Wellington
  74 | Bradley Schuyler        | Netherlands  | Amsterdam
  38 | Mory Kentary            | Japan        | Kita-ku
 105 | Akiko Shimamura         | Japan        | Minato-ku
  68 | Giovanni Rovelli        | Italy        | Bergamo
 123 | Franco Ricotti          | Italy        | Milan
 104 | Maurizio Moroni         | Italy        | Reggio Emilia
  61 | Paolo Accorti           | Italy        | Torino
 127 | Raanan Altagar,G M      | Israel       | Herzlia
  90 | Patricia McKenna        | Ireland      | Cork
  42 | Dean Cassidy            | Ireland      | Dublin
  50 | Mike Gao                | Hong Kong    | Central Hong Kong
 119 | Sven Ottlieb            | Germany      | Aachen
  75 | Mel Andersen            | Germany      | Berlin
  86 | Philip Cramer           | Germany      | Brandenburg
  53 | Horst Kloss             | Germany      | Cunewalde
  19 | Roland Keitel           | Germany      | Frankfurt
  60 | Renate Messner          | Germany      | Frankfurt
  64 | Henriette Pfalzheim     | Germany      | K├Âln
 111 | Alexander Feuer         | Germany      | Leipzig
  66 | Peter Franken           | Germany      | M├╝nchen
  95 | Karin Josephs           | Germany      | M├╝nster
 125 | Hanna Moos              | Germany      | Mannheim
 109 | Michael Donnermeyer     | Germany      | Munich
 107 | Rita M├╝ller            | Germany      | Stuttgart
  34 | Martine Ranc├®          | France       | Lille
  25 | Mary Saveley            | France       | Lyon
  91 | Laurence Lebihan        | France       | Marseille
   9 | Laurence Lebihan        | France       | Marseille
  15 | Janine Labrune          | France       | Nantes
  12 | Carine Schmitt          | France       | Nantes
  35 | Marie Bertrand          | France       | Paris
  62 | Daniel Da Silva         | France       | Paris
 106 | Dominique Perrier       | France       | Paris
  92 | Paul Henriot            | France       | Reims
  49 | Fr├®d├®rique Citeaux    | France       | Strasbourg
  59 | Annette Roulet          | France       | Toulouse
  63 | Daniel Tonini           | France       | Versailles
  85 | Kalle Suominen          | Finland      | Espoo
  40 | Matti Karttunen         | Finland      | Helsinki
  76 | Pirkko Koskitalo        | Finland      | Oulu
  54 | Palle Ibsen             | Denmark      | ├àrhus
  24 | Jytte Petersen          | Denmark      | Kobenhavn
  55 | Jean Fresni├¿re         | Canada       | Montr├®al
  65 | Elizabeth Lincoln       | Canada       | Tsawassen
  45 | Yoshi Tamuri            | Canada       | Vancouver
  77 | Catherine Dewey         | Belgium      | Bruxelles
 101 | Pascale Cartrain        | Belgium      | Charleroi
 115 | Roland Mendel           | Austria      | Graz
 102 | Georg Pipps             | Austria      | Salzburg
  69 | Adrian Huxley           | Australia    | Chatswood
 122 | Sean Clenahan           | Australia    | Glen Waverly
  14 | Peter Ferguson          | Australia    | Melbourne
  67 | Anna O'Hara             | Australia    | North Sydney
  84 | Ben Calaghan            | Australia    | South Brisbane
(133 rows)


postgres=#
```

</details><br>

This will sort the data into descending alphabetic order of country then ascending order of city name within each country.

### Limiting the Number of Rows

You can reduce the number of rows returned by using the `LIMIT` clause at the end of the query:

```
SELECT id, name, phone, email, country
  FROM customers
  ORDER BY country, name
  LIMIT 20;
```

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT id, name, phone, email, country
postgres-#   FROM customers
postgres-#   ORDER BY country, name
postgres-#   LIMIT 20;
 id  |       name        |      phone       |           email            |  country
-----+-------------------+------------------+----------------------------+-----------
  69 | Adrian Huxley     | +61 2 9495 8555  | adrian.huxley@hmep.net     | Australia
  67 | Anna O'Hara       | 02 9936 8555     | anna.o"hara@hzjw.net       | Australia
  84 | Ben Calaghan      | 61-7-3844-6555   | ben.calaghan@bprq.net      | Australia
  14 | Peter Ferguson    | 03 9520 4555     | peter.ferguson@mxnx.net    | Australia
 122 | Sean Clenahan     | 61-9-3844-6555   | sean.clenahan@gzyw.net     | Australia
 102 | Georg Pipps       | 6562-9555        | georg.pipps@uyvb.net       | Austria
 115 | Roland Mendel     | 7675-3555        | roland.mendel@wclf.net     | Austria
  77 | Catherine Dewey   | (02) 5554 67     | catherine.dewey@ndft.net   | Belgium
 101 | Pascale Cartrain  | (071) 23 67 2555 | pascale.cartrain@oggv.net  | Belgium
  65 | Elizabeth Lincoln | (604) 555-4555   | elizabeth.lincoln@elct.net | Canada
  55 | Jean Fresni├¿re   | (514) 555-8054   | jean.fresni├¿re@uxsm.net   | Canada
  45 | Yoshi Tamuri      | (604) 555-3392   | yoshi.tamuri@juuq.net      | Canada
  24 | Jytte Petersen    | 31 12 3555       | jytte.petersen@cpbn.net    | Denmark
  54 | Palle Ibsen       | 86 21 3555       | palle.ibsen@bjqn.net       | Denmark
  85 | Kalle Suominen    | +358 9 8045 555  | kalle.suominen@acif.net    | Finland
  40 | Matti Karttunen   | 90-224 8555      | matti.karttunen@xkig.net   | Finland
  76 | Pirkko Koskitalo  | 981-443655       | pirkko.koskitalo@rcva.net  | Finland
  59 | Annette Roulet    | 61.77.6555       | annette.roulet@lgha.net    | France
  12 | Carine Schmitt    | 40.32.2555       | carine.schmitt@dftu.net    | France
  62 | Daniel Da Silva   | +33 1 46 62 7555 | daniel.da.silva@hijy.net   | France
(20 rows)


postgres=#
```

</details><br>

The `LIMIT` clause is not normally used without the `ORDER BY` clause - without the `ORDER BY` clause rows can be returned in any arbitrary sequence.

Not all SQL implementations of SQL support `LIMIT`, some use `TOP` while Oracle uses `ROWNUM`.

---

## 23. Exercise 5

### 23.1
- List the different room types and rates for all rooms avoiding duplicates.
- `SELECT DISTINCT rate, room_type FROM rooms;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT DISTINCT rate, room_type FROM rooms;
  rate  |  room_type
--------+--------------
 110.00 | PREMIER
 123.00 | FAMILY
  85.00 | PREMIUM
  98.00 | PREMIUM PLUS
 123.00 | PREMIER PLUS
(5 rows)


postgres=#
```

</details><br>

### 23.2
- List customers' names addresses and phone numbers in alphabetic order of names.
- `SELECT name, address, phone FROM customers ORDER BY name;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT name, address, phone FROM customers ORDER BY name;
          name           |                  address                   |       phone
-------------------------+--------------------------------------------+--------------------
 Adrian Huxley           | Monitor Money Building, 815 Pacific Hwy    | +61 2 9495 8555
 Akiko Shimamura         | 2-2-8 Roppongi                             | +81 3 3584 0555
 Alejandra Camino        | Gran V├¡a, 1                               | (91) 745 6555
 Alexander Feuer         | Heerstr. 22                                | 0342-555176
 Alexander Semenov       | 2 Pobedy Square                            | +7 812 293 0521
 Alice Evans             | 3 High Road                                | 0161 345 6789
 Allen Nelson            | 7825 Douglas Av.                           | 6175558555
 Ann Brown               | 35 King George                             | (171) 555-0297
 Anna O'Hara             | 201 Miller Street, Level 15                | 02 9936 8555
 Annette Roulet          | 1 rue Alsace-Lorraine                      | 61.77.6555
 Armand Kuger            | 1250 Pretorius Street                      | +27 21 550 3555
 Arnold Cruz             | 15 McCallum Street, NatWest Center #13-03  | +63 2 555 3587
 Ben Calaghan            | 31 Duncan St. West End                     | 61-7-3844-6555
 Bradley Schuyler        | Kingsfordweg 151                           | +31 20 491 9555
 Braun Urs               | Hauptstr. 29                               | 0452-076555
 Brian Chandler          | 6047 Douglas Av.                           | 2155554369
 Brydey Walker           | Suntec Tower Three, 8 Temasek              | +612 9411 1555
 Carine Schmitt          | 54, rue Royale                             | 40.32.2555
 Carlos Porter           | 81 Bath Rd                                 | 070 2679 6812
 Carmen Anton            | c/ Gobelas, 19-1 Urb. La Florida           | +34 913 728555
 Catherine Dewey         | Rue Joseph-Bens 532                        | (02) 5554 67
 Christina Berglund      | Berguvsv├ñgen 8                            | 0921-12 3555
 Dan Lewis               | 2440 Pompton St.                           | 2035554407
 Daniel Da Silva         | 27 rue du Colonel Pierre Avia              | +33 1 46 62 7555
 Daniel Tonini           | 67, avenue de lEurope                      | 30.59.8555
 Dean Cassidy            | 25 Maiden Lane, Floor No. 4                | +353 1862 1555
 Diego Freyre            | C/ Moralzarzal, 86                         | (91) 555 94 44
 Dominique Perrier       | 25, rue Lauriston                          | (1) 47.55.6555
 Dorothy Young           | 2304 Long Airport Avenue                   | 6035558647
 Ed Harrison             | Rte des Arsenaux 41                        | +41 26 425 50 01
 Eduardo Saavedra        | Rambla de Catalu├▒a, 23                    | (93) 203 4555
 Elizabeth Devon         | 12, Berkeley Gardens Blvd                  | (171) 555-2282
 Elizabeth Lincoln       | 23 Tsawassen Blvd.                         | (604) 555-4555
 Eric Natividad          | Bronz Sok., Bronz Apt. 3/6 Tesvikiye       | +65 221 7555
 Fr├®d├®rique Citeaux    | 24, place Kl├®ber                          | 88.60.1555
 Francisca Cervantes     | 782 First Street                           | 2155554695
 Franco Ricotti          | 20093 Cologno Monzese, Alessandro Volta 16 | +39 022515555
 Georg Pipps             | Geislweg 14                                | 6562-9555
 Giovanni Rovelli        | Via Ludovico il Moro 22                    | 035-640555
 Hanna Moos              | Forsterstr. 57                             | 0621-08555
 Helen Bennett           | Garden House, Crowther Way 23              | (198) 555-8888
 Henriette Pfalzheim     | Mehrheimerstr. 369                         | 0221-5554327
 Horst Kloss             | Taucherstra├ƒe 10                          | 0372-555188
 Isabel de Castro        | Estrada da sa├║de n. 58                    | (1) 356-5555
 Jan Klaeboe             | Drammensveien 126A, PB 211 Sentrum         | +47 2212 1555
 Janine Labrune          | 67, rue des Cinquante Otages               | 40.67.8555
 Jean Fresni├¿re         | 43 rue St. Laurent                         | (514) 555-8054
 Jean King               | 8489 Strong St.                            | 07025 551 838
 Jeff Young              | 4092 Furth Circle, Suite 400               | 0212 555 7413
 Jerry Tseng             | 4658 Baden Av.                             | 6175555555
 Jesus Fernandez         | Merchants House, 27-30 Merchant's Quay     | +34 913 728 555
 John Smith              | 11 New Road                                | 0151 123 4567
 Jonas Bergulfsen        | Erling Skakkes gate 78                     | 07-98 9555
 Jos├® Pedro Roel        | C/ Romero, 33                              | (95) 555 82 82
 Julie Brown             | 7734 Strong St.                            | 6505551386
 Julie King              | 25593 South Bay Ln.                        | 2035552570
 Julie Murphy            | 5557 North Pendale Street                  | 0650 555 5787
 Julie Young             | 78934 Hillside Dr.                         | 6265557265
 Juri Hashimoto          | 9408 Furth Circle                          | 0650 555 6809
 Juri Yoshido            | 8616 Spinnaker Dr.                         | 6175559555
 Jytte Petersen          | Vinb├ªltet 34                              | 31 12 3555
 Kalle Suominen          | Software Engineering Center, SEC Oy        | +358 9 8045 555
 Karin Josephs           | Luisenstr. 48                              | 0251-555259
 Keith Franco            | 149 Spinnaker Dr., Suite 101               | 2035557845
 Keith Stewart           | 84 Town Lane                               | 078 4679 1282
 Kelvin Leong            | 7586 Pompton St.                           | 0215 555 1555
 Kwai Lee                | 897 Long Airport Avenue                    | 0212 555 7818
 Laurence Lebihan        | 12, rue des Bouchers                       | 91.24.4555
 Laurence Lebihan        | 12, rue des Bouchers                       | 91.24.4555
 Leslie Murphy           | 567 North Pendale Street                   | 2035559545
 Leslie Taylor           | 16780 Pompton St.                          | 6175558428
 Lino Rodriguez          | Jardim das rosas n. 32                     | (1) 354-2555
 Maria Hernandez         | 5905 Pompton St., Suite 750                | 2125558493
 Marie Bertrand          | 265, boulevard Charonne                    | (1) 42.34.2555
 Marta Hernandez         | 39323 Spinnaker Dr.                        | 6175558555
 Mart├¡n Sommer          | C/ Araquil, 67                             | (91) 555 22 82
 Mart├¡n Sommer          | C/ Romero, 33                              | (91) 555 22 82
 Martha Larsson          | ├àkergatan 24                              | 0695-34 6555
 Martine Ranc├®          | 184, chauss├®e de Tournai                  | 20.16.1555
 Mary Saveley            | 2, rue du Commerce                         | 78.32.5555
 Mary Young              | 4097 Douglas Av.                           | 3105552373
 Matti Karttunen         | Keskuskatu 45                              | 90-224 8555
 Maurizio Moroni         | Strada Provinciale 124                     | 0522-556555
 Mel Andersen            | Obere Str. 57                              | 030-0074555
 Melinda Marsh           | 7 Preston Road                             | 070 1513 5671
 Michael Donnermeyer     | Hansastr. 15                               |  +49 89 61 08 9555
 Michael Frick           | 2678 Kingston Rd., Suite 101               | 2125551500
 Miguel Barajas          | 7635 Spinnaker Dr.                         | 6175557555
 Mihael Holz             | Grenzacherweg 237                          | 0897-034555
 Mike Gao                | Bank of China Tower, 1 Garden Road         | +852 2251 1555
 Mike Graham             | 162-164 Grafton Road, Level 2              | +64 9 312 5555
 Mohammed Trungpa        | 25 Blue Road                               | 0161 456 7890
 Mory Kentary            | 1-6-20 Dojima                              | +81 06 6342 5555
 Nadia Sethuraman        | 135 Green Street                           |
 Palle Ibsen             | Smagsloget 45                              | 86 21 3555
 Paolo Accorti           | Via Monte Bianco 34                        | 011-4988555
 Pascale Cartrain        | Boulevard Tirou, 255                       | (071) 23 67 2555
 Patricia McKenna        | 8 Johnstown Road                           | 2967 555
 Paul Henriot            | 59 rue de l'Abbaye                         | 26.47.1555
 Peter Ferguson          | 636 St Kilda Road, Level 3                 | 03 9520 4555
 Peter Franken           | Berliner Platz 43                          | 089-0877555
 Philip Cramer           | Maubelstr. 90                              | 0555-09555
 Pirkko Koskitalo        | Torikatu 38                                | 981-443655
 Raanan Altagar,G M      | 3 Hagalim Blv.                             | + 972 9 959 8555
 Rachel Ashworth         | Fauntleroy Circus                          | (171) 555-1555
 Renate Messner          | Magazinweg 7                               | 069-0555984
 Rita M├╝ller            | Adenauerallee 900                          | 0711-555361
 Roland Keitel           | Lyonerstr. 34                              | +49 69 66 90 2555
 Roland Mendel           | Kirchgasse 6                               | 7675-3555
 Rosa Salazar            | 11328 Douglas Av.                          | 2155559857
 Sarah McRoy             | 101 Lambton Quay, Level 11                 | 04 499 9555
 Sean Clenahan           | 7 Allen Street                             | 61-9-3844-6555
 Steve Frick             | 3758 North Pendale Street                  | 9145554562
 Steve Thompson          | 3675 Furth Circle                          | 3105553722
 Steven King             | 19 Bed Street                              | 01245 134 4678
 Sue Frick               | 3086 Ingle Ln.                             | 4085553659
 Sue Jones               | 120 Old Street                             | 0201 234 5678
 Sue Taylor              | 2793 Furth Circle                          | 4155554312
 Susan Nelson            | 5677 Strong St.                            | 0415 555 1450
 Sven Ottlieb            | Walserweg 21                               | 0241-039123
 Thomas Smith            | 120 Hanover Sq.                            | (171) 555-7555
 Tony Snowden            | Arenales 1938 3'A'                         | +64 9 5555500
 Valarie Franco          | 6251 Ingle Ln.                             | 6175552555
 Valarie Thompson        | 361 Furth Circle                           | 7605558146
 Veysel Oeztan           | Brehmen St. 121, PR 334 Sentrum            | +47 2267 3215
 Violeta Benitez         | 1785 First Street                          | 5085552555
 Wales MacKinlay         | 199 Great North Road                       | 64-9-3763555
 Wendy Victorino         | 106 Linden Road Sandown, 2nd Floor         | +65 224 1555
 William Brown           | 7476 Moss Rd.                              | 2015559350
 Wing Huang              | 4575 Hillside Dr.                          | 5085559555
 Yoshi Tamuri            | 1900 Oak St.                               | (604) 555-3392
 Yu Choi                 | 5290 North Pendale Street, Suite 200       | 2125551957
 Zbyszek Piestrzeniewicz | ul. Filtrowa 68                            | (26) 642-7555
(133 rows)


postgres=#
```

</details><br>

### 23.3
- List customers' names, addresses, city and country in ascending order of country then reverse order of city within country.
- `SELECT name, address, city, country FROM customers ORDER BY country, city DESC;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT name, address, city, country FROM customers ORDER BY country, city DESC;
          name           |                  address                   |       city        |   country
-------------------------+--------------------------------------------+-------------------+--------------
 Ben Calaghan            | 31 Duncan St. West End                     | South Brisbane    | Australia
 Anna O'Hara             | 201 Miller Street, Level 15                | North Sydney      | Australia
 Peter Ferguson          | 636 St Kilda Road, Level 3                 | Melbourne         | Australia
 Sean Clenahan           | 7 Allen Street                             | Glen Waverly      | Australia
 Adrian Huxley           | Monitor Money Building, 815 Pacific Hwy    | Chatswood         | Australia
 Georg Pipps             | Geislweg 14                                | Salzburg          | Austria
 Roland Mendel           | Kirchgasse 6                               | Graz              | Austria
 Pascale Cartrain        | Boulevard Tirou, 255                       | Charleroi         | Belgium
 Catherine Dewey         | Rue Joseph-Bens 532                        | Bruxelles         | Belgium
 Yoshi Tamuri            | 1900 Oak St.                               | Vancouver         | Canada
 Elizabeth Lincoln       | 23 Tsawassen Blvd.                         | Tsawassen         | Canada
 Jean Fresni├¿re         | 43 rue St. Laurent                         | Montr├®al         | Canada
 Jytte Petersen          | Vinb├ªltet 34                              | Kobenhavn         | Denmark
 Palle Ibsen             | Smagsloget 45                              | ├àrhus            | Denmark
 Pirkko Koskitalo        | Torikatu 38                                | Oulu              | Finland
 Matti Karttunen         | Keskuskatu 45                              | Helsinki          | Finland
 Kalle Suominen          | Software Engineering Center, SEC Oy        | Espoo             | Finland
 Daniel Tonini           | 67, avenue de lEurope                      | Versailles        | France
 Annette Roulet          | 1 rue Alsace-Lorraine                      | Toulouse          | France
 Fr├®d├®rique Citeaux    | 24, place Kl├®ber                          | Strasbourg        | France
 Paul Henriot            | 59 rue de l'Abbaye                         | Reims             | France
 Daniel Da Silva         | 27 rue du Colonel Pierre Avia              | Paris             | France
 Dominique Perrier       | 25, rue Lauriston                          | Paris             | France
 Marie Bertrand          | 265, boulevard Charonne                    | Paris             | France
 Janine Labrune          | 67, rue des Cinquante Otages               | Nantes            | France
 Carine Schmitt          | 54, rue Royale                             | Nantes            | France
 Laurence Lebihan        | 12, rue des Bouchers                       | Marseille         | France
 Laurence Lebihan        | 12, rue des Bouchers                       | Marseille         | France
 Mary Saveley            | 2, rue du Commerce                         | Lyon              | France
 Martine Ranc├®          | 184, chauss├®e de Tournai                  | Lille             | France
 Rita M├╝ller            | Adenauerallee 900                          | Stuttgart         | Germany
 Michael Donnermeyer     | Hansastr. 15                               | Munich            | Germany
 Hanna Moos              | Forsterstr. 57                             | Mannheim          | Germany
 Karin Josephs           | Luisenstr. 48                              | M├╝nster          | Germany
 Peter Franken           | Berliner Platz 43                          | M├╝nchen          | Germany
 Alexander Feuer         | Heerstr. 22                                | Leipzig           | Germany
 Henriette Pfalzheim     | Mehrheimerstr. 369                         | K├Âln             | Germany
 Roland Keitel           | Lyonerstr. 34                              | Frankfurt         | Germany
 Renate Messner          | Magazinweg 7                               | Frankfurt         | Germany
 Horst Kloss             | Taucherstra├ƒe 10                          | Cunewalde         | Germany
 Philip Cramer           | Maubelstr. 90                              | Brandenburg       | Germany
 Mel Andersen            | Obere Str. 57                              | Berlin            | Germany
 Sven Ottlieb            | Walserweg 21                               | Aachen            | Germany
 Mike Gao                | Bank of China Tower, 1 Garden Road         | Central Hong Kong | Hong Kong
 Dean Cassidy            | 25 Maiden Lane, Floor No. 4                | Dublin            | Ireland
 Patricia McKenna        | 8 Johnstown Road                           | Cork              | Ireland
 Raanan Altagar,G M      | 3 Hagalim Blv.                             | Herzlia           | Israel
 Paolo Accorti           | Via Monte Bianco 34                        | Torino            | Italy
 Maurizio Moroni         | Strada Provinciale 124                     | Reggio Emilia     | Italy
 Franco Ricotti          | 20093 Cologno Monzese, Alessandro Volta 16 | Milan             | Italy
 Giovanni Rovelli        | Via Ludovico il Moro 22                    | Bergamo           | Italy
 Akiko Shimamura         | 2-2-8 Roppongi                             | Minato-ku         | Japan
 Mory Kentary            | 1-6-20 Dojima                              | Kita-ku           | Japan
 Bradley Schuyler        | Kingsfordweg 151                           | Amsterdam         | Netherlands
 Sarah McRoy             | 101 Lambton Quay, Level 11                 | Wellington        | New Zealand
 Mike Graham             | 162-164 Grafton Road, Level 2              | Auckland          | New Zealand
 Tony Snowden            | Arenales 1938 3'A'                         | Auckland          | New Zealand
 Wales MacKinlay         | 199 Great North Road                       | Auckland          | New Zealand
 Jonas Bergulfsen        | Erling Skakkes gate 78                     | Stavern           | Norway
 Jan Klaeboe             | Drammensveien 126A, PB 211 Sentrum         | Oslo              | Norway
 Veysel Oeztan           | Brehmen St. 121, PR 334 Sentrum            | Bergen            | Norway
 Arnold Cruz             | 15 McCallum Street, NatWest Center #13-03  | Makati City       | Philippines
 Zbyszek Piestrzeniewicz | ul. Filtrowa 68                            | Warszawa          | Poland
 Lino Rodriguez          | Jardim das rosas n. 32                     | Lisboa            | Portugal
 Isabel de Castro        | Estrada da sa├║de n. 58                    | Lisboa            | Portugal
 Alexander Semenov       | 2 Pobedy Square                            | Saint Petersburg  | Russia
 Eric Natividad          | Bronz Sok., Bronz Apt. 3/6 Tesvikiye       | Singapore         | Singapore
 Wendy Victorino         | 106 Linden Road Sandown, 2nd Floor         | Singapore         | Singapore
 Brydey Walker           | Suntec Tower Three, 8 Temasek              | Singapore         | Singapore
 Armand Kuger            | 1250 Pretorius Street                      | Hatfield          | South Africa
 Jos├® Pedro Roel        | C/ Romero, 33                              | Sevilla           | Spain
 Mart├¡n Sommer          | C/ Romero, 33                              | Madrid            | Spain
 Jesus Fernandez         | Merchants House, 27-30 Merchant's Quay     | Madrid            | Spain
 Diego Freyre            | C/ Moralzarzal, 86                         | Madrid            | Spain
 Mart├¡n Sommer          | C/ Araquil, 67                             | Madrid            | Spain
 Carmen Anton            | c/ Gobelas, 19-1 Urb. La Florida           | Madrid            | Spain
 Alejandra Camino        | Gran V├¡a, 1                               | Madrid            | Spain
 Eduardo Saavedra        | Rambla de Catalu├▒a, 23                    | Barcelona         | Spain
 Christina Berglund      | Berguvsv├ñgen 8                            | Lule├Ñ            | Sweden
 Martha Larsson          | ├àkergatan 24                              | Br├ñcke           | Sweden
 Mihael Holz             | Grenzacherweg 237                          | Gen├¿ve           | Switzerland
 Ed Harrison             | Rte des Arsenaux 41                        | Fribourg          | Switzerland
 Braun Urs               | Hauptstr. 29                               | Bern              | Switzerland
 Keith Stewart           | 84 Town Lane                               | Tadworth          | UK
 Carlos Porter           | 81 Bath Rd                                 | Salisbury         | UK
 Melinda Marsh           | 7 Preston Road                             | Oldham            | UK
 Steven King             | 19 Bed Street                              | Newtown           | UK
 Nadia Sethuraman        | 135 Green Street                           | Manchester        | UK
 Rachel Ashworth         | Fauntleroy Circus                          | Manchester        | UK
 Alice Evans             | 3 High Road                                | Manchester        | UK
 Mohammed Trungpa        | 25 Blue Road                               | Manchester        | UK
 Thomas Smith            | 120 Hanover Sq.                            | London            | UK
 Sue Jones               | 120 Old Street                             | London            | UK
 Ann Brown               | 35 King George                             | London            | UK
 John Smith              | 11 New Road                                | Liverpool         | UK
 Elizabeth Devon         | 12, Berkeley Gardens Blvd                  | Liverpool         | UK
 Helen Bennett           | Garden House, Crowther Way 23              | Cowes             | UK
 Steve Frick             | 3758 North Pendale Street                  | White Plains      | USA
 Susan Nelson            | 5677 Strong St.                            | San Rafael        | USA
 Sue Frick               | 3086 Ingle Ln.                             | San Jose          | USA
 Julie Murphy            | 5557 North Pendale Street                  | San Francisco     | USA
 Julie Brown             | 7734 Strong St.                            | San Francisco     | USA
 Valarie Thompson        | 361 Furth Circle                           | San Diego         | USA
 Francisca Cervantes     | 782 First Street                           | Philadelphia      | USA
 Rosa Salazar            | 11328 Douglas Av.                          | Philadelphia      | USA
 Julie Young             | 78934 Hillside Dr.                         | Pasadena          | USA
 Michael Frick           | 2678 Kingston Rd., Suite 101               | NYC               | USA
 Jeff Young              | 4092 Furth Circle, Suite 400               | NYC               | USA
 Maria Hernandez         | 5905 Pompton St., Suite 750                | NYC               | USA
 Kwai Lee                | 897 Long Airport Avenue                    | NYC               | USA
 Yu Choi                 | 5290 North Pendale Street, Suite 200       | NYC               | USA
 William Brown           | 7476 Moss Rd.                              | Newark            | USA
 Leslie Murphy           | 567 North Pendale Street                   | New Haven         | USA
 Keith Franco            | 149 Spinnaker Dr., Suite 101               | New Haven         | USA
 Wing Huang              | 4575 Hillside Dr.                          | New Bedford       | USA
 Violeta Benitez         | 1785 First Street                          | New Bedford       | USA
 Dorothy Young           | 2304 Long Airport Avenue                   | Nashua            | USA
 Brian Chandler          | 6047 Douglas Av.                           | Los Angeles       | USA
 Jean King               | 8489 Strong St.                            | Las Vegas         | USA
 Mary Young              | 4097 Douglas Av.                           | Glendale          | USA
 Dan Lewis               | 2440 Pompton St.                           | Glendale          | USA
 Marta Hernandez         | 39323 Spinnaker Dr.                        | Cambridge         | USA
 Jerry Tseng             | 4658 Baden Av.                             | Cambridge         | USA
 Juri Hashimoto          | 9408 Furth Circle                          | Burlingame        | USA
 Steve Thompson          | 3675 Furth Circle                          | Burbank           | USA
 Sue Taylor              | 2793 Furth Circle                          | Brisbane          | USA
 Julie King              | 25593 South Bay Ln.                        | Bridgewater       | USA
 Leslie Taylor           | 16780 Pompton St.                          | Brickhaven        | USA
 Allen Nelson            | 7825 Douglas Av.                           | Brickhaven        | USA
 Miguel Barajas          | 7635 Spinnaker Dr.                         | Brickhaven        | USA
 Juri Yoshido            | 8616 Spinnaker Dr.                         | Boston            | USA
 Valarie Franco          | 6251 Ingle Ln.                             | Boston            | USA
 Kelvin Leong            | 7586 Pompton St.                           | Allentown         | USA
(133 rows)


postgres=#
```

</details><br>


### 23.4
- List the room number, type and the cost of staying 5 nights in each of the top 15 most expensive rooms.
- `SELECT room_no, rate * 5 as cost_of_five_nights, room_type FROM rooms ORDER BY rate DESC, room_no ASC LIMIT 15;`

<details>
<summary>Terminal Output</summary>

```
postgres=# SELECT room_no, rate * 5 as cost_of_five_nights, room_type FROM rooms ORDER BY rate DESC, room_no ASC LIMIT 15;
 room_no | cost_of_five_nights |  room_type
---------+---------------------+--------------
     308 |              615.00 | PREMIER PLUS
     309 |              615.00 | PREMIER PLUS
     310 |              615.00 | PREMIER PLUS
     311 |              615.00 | PREMIER PLUS
     312 |              615.00 | PREMIER PLUS
     408 |              615.00 | PREMIER PLUS
     409 |              615.00 | PREMIER PLUS
     410 |              615.00 | PREMIER PLUS
     411 |              615.00 | FAMILY
     412 |              615.00 | FAMILY
     301 |              550.00 | PREMIER
     302 |              550.00 | PREMIER
     303 |              550.00 | PREMIER
     304 |              550.00 | PREMIER
     305 |              550.00 | PREMIER
(15 rows)


postgres=#
```

</details><br>

---
