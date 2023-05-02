## 1. Logging in to the Database

`<cmd> <databaseName> <username>`

```
( <cmd> <databaseName> <username> )
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

## 2. Postgres Help

`help`

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

</details>

## 4. List All Tables In The Current Database

`\dt`

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

## 5. The SELECT Statement

`SELECT ... FROM ...;`

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

</details>

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

---

## 7. Return ALL Columns

```
SELECT * FROM rooms;
```

---

## 8. See What Columns Exist in a Table

`\d <table_name>`

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

---

## 9. UPPER/lower case

The use of UPPER/lower case is only to emphasise and differentiate the SQL keywords (upper case) from the other names (lower case) e.g. column and table names.  
**SQL keywords are not case-sensitive.**

---

## 10. Scrolling the Results

```
Space       Next screenful
'B'         Previous screenful
Down Arrow  Next line
Up Arrow    Previous line
'Q'         Quit back to prompt
```

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

</details>

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

</details>

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

</details>

---

## 12. PSQL Commands

The psql commands are not SQL and are specific to PostgreSQL (although most other RDBMS's have commands to perform similar jobs). These commands let you display information, execute system commands, etc. Use \? to display a summary of all the psql commands.

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

</details>

### 13.2

- Display the help for the SELECT command (Note: we will not be covering ALL of this syntax!)
- \h SELECT

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

</details>

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

</details>

---

## 14 Displaying More Than Just Columns

`SELECT room_no, rate * 0.85 FROM rooms;`

```
+---------+-------------+
| room_no | rate * 0.85 |
+---------+-------------+
|     101 |     72.2500 |
|     102 |     72.2500 |
|     103 |     72.2500 |
```

Use a **column alias** to give the expression a meaningful name:
`SELECT room_no,
       rate * 0.85 AS discounted_rate
    FROM rooms;`

```
+---------+-----------------+
| room_no | discounted_rate |
+---------+-----------------+
|     101 |         72.2500 |
|     102 |         72.2500 |
|     103 |         72.2500 |
```

### 15 Expressions in SQL

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

</details>

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

</details>

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

</details>

---
