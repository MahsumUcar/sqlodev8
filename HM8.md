1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

```
CREATE TABLE employee(
	id INTEGER PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birtday DATE,
	email VARCHAR(100)
);
```

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

```
insert into employee (id, name, birtday, email) values (1, 'Emmit', '1980-09-27', 'ecamellini0@jalbum.net');
insert into employee (id, name, birtday, email) values (2, 'Deina', '2006-02-10', 'dthormann1@cnbc.com');
insert into employee (id, name, birtday, email) values (3, 'Elfie', '1984-09-25', 'estaner2@eventbrite.com');
insert into employee (id, name, birtday, email) values (4, 'Carmelle', '1942-07-16', 'cobradane3@auda.org.au');
insert into employee (id, name, birtday, email) values (5, 'Alva', '1975-02-17', 'areyson4@cafepress.com');
insert into employee (id, name, birtday, email) values (6, 'Roseline', '1941-02-07', 'rkynge5@pagesperso-orange.fr');
insert into employee (id, name, birtday, email) values (7, 'Maryjane', '1965-06-22', 'mphetteplace6@ifeng.com');
insert into employee (id, name, birtday, email) values (8, 'Merle', '1954-11-12', 'mninnotti7@java.com');
insert into employee (id, name, birtday, email) values (9, 'Gannon', '1927-08-05', 'gshellum8@networksolutions.com');
insert into employee (id, name, birtday, email) values (10, 'Audie', '1929-01-14', 'aklemke9@lulu.com');
insert into employee (id, name, birtday, email) values (11, 'Dulcia', '1986-09-25', 'dmadrea@wp.com');
insert into employee (id, name, birtday, email) values (12, 'Ollie', '1940-11-16', 'obabbidgeb@ovh.net');
insert into employee (id, name, birtday, email) values (13, 'Dolorita', '1980-11-25', 'dlynec@1688.com');
insert into employee (id, name, birtday, email) values (14, 'Barbra', '1983-03-18', 'bgillaspyd@arstechnica.com');
insert into employee (id, name, birtday, email) values (15, 'Aurora', null, 'agossagee@cam.ac.uk');
insert into employee (id, name, birtday, email) values (16, 'Tan', null, 'tchadwinf@amazon.co.uk');
insert into employee (id, name, birtday, email) values (17, 'Sallyanne', null, 'seasong@plala.or.jp');
insert into employee (id, name, birtday, email) values (18, 'Leshia', '1960-01-26', null);
insert into employee (id, name, birtday, email) values (19, 'Ki', '2004-01-07', null);
insert into employee (id, name, birtday, email) values (20, 'Constance', null, null);
insert into employee (id, name, birtday, email) values (21, 'Rinaldo', '1953-05-06', 'rfreckletonk@privacy.gov.au');
insert into employee (id, name, birtday, email) values (22, 'Selia', null, 'singredal@macromedia.com');
insert into employee (id, name, birtday, email) values (23, 'Rudy', '1973-09-07', 'rgattym@ovh.net');
insert into employee (id, name, birtday, email) values (24, 'Jorrie', '1969-08-12', 'jcareswelln@w3.org');
insert into employee (id, name, birtday, email) values (25, 'Hortense', '1973-12-27', 'hwalkowskio@sitemeter.com');
insert into employee (id, name, birtday, email) values (26, 'Olly', null, 'owabersinkep@sogou.com');
insert into employee (id, name, birtday, email) values (27, 'Cal', '1985-01-22', 'cmcphersonq@huffingtonpost.com');
insert into employee (id, name, birtday, email) values (28, 'Irita', '2009-05-14', 'imapplethorper@163.com');
insert into employee (id, name, birtday, email) values (29, 'Mala', '1953-10-05', 'mmuldowneys@hugedomains.com');
insert into employee (id, name, birtday, email) values (30, 'Mariya', '1993-08-13', 'mperkinst@blogspot.com');
insert into employee (id, name, birtday, email) values (31, 'Thomasine', '1947-01-25', 'tcallabyu@freewebs.com');
insert into employee (id, name, birtday, email) values (32, 'Garwood', null, 'gkerwoodv@goodreads.com');
insert into employee (id, name, birtday, email) values (33, 'Orelee', null, 'ohawkesw@amazon.de');
insert into employee (id, name, birtday, email) values (34, 'Wynne', '1983-05-22', 'wworboysx@is.gd');
insert into employee (id, name, birtday, email) values (35, 'Sigrid', '1957-05-05', 'spineauxy@psu.edu');
insert into employee (id, name, birtday, email) values (36, 'Pia', '1924-09-07', 'plinnockz@taobao.com');
insert into employee (id, name, birtday, email) values (37, 'Gertrud', '1986-01-14', 'gloughlin10@huffingtonpost.com');
insert into employee (id, name, birtday, email) values (38, 'Cassie', null, null);
insert into employee (id, name, birtday, email) values (39, 'Barbaraanne', '1978-06-23', 'bbarrar12@adobe.com');
insert into employee (id, name, birtday, email) values (40, 'Betsy', '1968-08-26', 'bilyenko13@intel.com');
insert into employee (id, name, birtday, email) values (41, 'Liza', '2000-11-23', null);
insert into employee (id, name, birtday, email) values (42, 'Farlie', '1936-02-10', 'fkilbee15@pbs.org');
insert into employee (id, name, birtday, email) values (43, 'Reeta', '1927-04-07', 'rtuftin16@sbwire.com');
insert into employee (id, name, birtday, email) values (44, 'Isaiah', '2006-07-26', 'idyche17@prweb.com');
insert into employee (id, name, birtday, email) values (45, 'Lila', '1999-06-10', 'lrecord18@samsung.com');
insert into employee (id, name, birtday, email) values (46, 'Aylmer', null, 'anaden19@soundcloud.com');
insert into employee (id, name, birtday, email) values (47, 'Dagny', null, 'dpessold1a@opensource.org');
insert into employee (id, name, birtday, email) values (48, 'Bartholemy', '1971-05-08', 'bbroggetti1b@cmu.edu');
insert into employee (id, name, birtday, email) values (49, 'Evelina', '1931-03-24', 'egalvan1c@house.gov');
insert into employee (id, name, birtday, email) values (50, 'Freddy', '1962-12-09', 'fiori1d@edublogs.org');
```

3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

```
UPDATE employee
SET name = 'Update name'
WHERE email = 'ecamellini0@jalbum.net'
RETURNING *;

UPDATE employee
SET birtday = '2000-01-01'
WHERE id = 2
RETURNING *;


UPDATE employee
SET email = 'update@mail.com'
WHERE name = 'Elfie'
RETURNING *;

UPDATE employee
SET name = 'XXXXXXX'
WHERE name LIKE 'A%' 
RETURNING *;

UPDATE employee
SET birtday = NULL
WHERE id > 45
RETURNING *;

```

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

```
DELETE FROM employee
WHERE birtday IS NULL
RETURNING*;

DELETE FROM employee
WHERE email IS NULL
RETURNING*;

DELETE FROM employee
WHERE name LIKE 'C%'
RETURNING*;

DELETE FROM employee
WHERE id > 40
RETURNING*;

DELETE FROM employee
WHERE birtday BETWEEN '1965-01-01' AND '2000-01-01'
RETURNING*;
```


