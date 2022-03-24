1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

````SQL
CREATE TABLE employee(
    id INT,
    name VARCHAR(50),
    birthday DATE,
    email VARCHAR(100)
);
````


2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

````SQL
insert into employee (id, name, birthday, email) values (1, 'Idell', '2007-04-02', 'ispratley0@google.it');
insert into employee (id, name, birthday, email) values (2, 'Derward', '1972-06-04', 'dflori1@whitehouse.gov');
insert into employee (id, name, birthday, email) values (3, 'Daron', '1997-07-05', 'dmorlon2@illinois.edu');
insert into employee (id, name, birthday, email) values (4, 'Alix', '1995-01-12', 'ayanshonok3@tumblr.com');
insert into employee (id, name, birthday, email) values (5, 'Allene', '2000-08-24', null);
insert into employee (id, name, birthday, email) values (6, 'Trev', '1997-07-26', 'tmessent5@livejournal.com');
insert into employee (id, name, birthday, email) values (7, 'Merrielle', '1990-09-06', 'mcoumbe6@feedburner.com');
insert into employee (id, name, birthday, email) values (8, 'Bondie', '1991-02-12', 'bmushet7@tiny.cc');
insert into employee (id, name, birthday, email) values (9, 'Rudolph', '1973-05-20', 'rgomersal8@fastcompany.com');
insert into employee (id, name, birthday, email) values (10, 'Byran', '2000-05-31', null);
insert into employee (id, name, birthday, email) values (11, 'Perceval', '2006-10-07', 'pmussillia@google.com.au');
insert into employee (id, name, birthday, email) values (12, 'Marya', '1969-01-22', 'mwealthallb@archive.org');
insert into employee (id, name, birthday, email) values (13, 'Ronica', '2010-11-10', 'rdunbabinc@yandex.ru');
insert into employee (id, name, birthday, email) values (14, 'Tamma', '1982-05-07', 'tcorkd@opensource.org');
insert into employee (id, name, birthday, email) values (15, 'Hayward', '2016-09-23', 'hsabbinse@yellowbook.com');
insert into employee (id, name, birthday, email) values (16, 'Mada', '1973-10-11', 'mfalkusf@creativecommons.org');
insert into employee (id, name, birthday, email) values (17, 'Alejandro', '1991-08-22', 'anaperg@unicef.org');
insert into employee (id, name, birthday, email) values (18, 'Gradey', '2020-05-04', 'ggraylingh@liveinternet.ru');
insert into employee (id, name, birthday, email) values (19, 'Luella', '1975-02-28', 'lmaccoveneyi@msn.com');
insert into employee (id, name, birthday, email) values (20, 'Wynnie', '2004-07-04', 'wvalentinuzzij@domainmarket.com');
insert into employee (id, name, birthday, email) values (21, 'Quintin', '2007-10-07', 'qthemannk@ibm.com');
insert into employee (id, name, birthday, email) values (22, 'Aldwin', '2002-02-07', 'aghelerdinil@phoca.cz');
insert into employee (id, name, birthday, email) values (23, 'Muffin', '1997-01-19', 'mwaddamsm@squidoo.com');
insert into employee (id, name, birthday, email) values (24, 'Francklin', '2009-03-02', 'fshirlandn@pinterest.com');
insert into employee (id, name, birthday, email) values (25, 'Selinda', '2018-07-29', null);
insert into employee (id, name, birthday, email) values (26, 'Nicki', null, 'nmothersdalep@springer.com');
insert into employee (id, name, birthday, email) values (27, 'Theresa', '1987-01-04', null);
insert into employee (id, name, birthday, email) values (28, 'Abram', '2010-02-04', null);
insert into employee (id, name, birthday, email) values (29, 'Lucy', '2013-12-04', null);
insert into employee (id, name, birthday, email) values (30, 'Thorstein', '2005-08-22', 'tmottinit@comsenz.com');
insert into employee (id, name, birthday, email) values (31, 'Pip', '1975-07-18', 'pyeatesu@sciencedirect.com');
insert into employee (id, name, birthday, email) values (32, 'Bernard', '1983-09-15', 'bohederscollv@blogspot.com');
insert into employee (id, name, birthday, email) values (33, 'Salome', null, 'srycew@mail.ru');
insert into employee (id, name, birthday, email) values (34, 'Marlon', '2011-11-16', 'mrozyckix@irs.gov');
insert into employee (id, name, birthday, email) values (35, 'Benedicta', null, 'bpainteny@ustream.tv');
insert into employee (id, name, birthday, email) values (36, 'Amitie', null, null);
insert into employee (id, name, birthday, email) values (37, 'Carol', '1976-02-20', 'cbentje10@icio.us');
insert into employee (id, name, birthday, email) values (38, 'Otha', '2020-05-14', null);
insert into employee (id, name, birthday, email) values (39, 'Brooke', null, 'brasper12@fotki.com');
insert into employee (id, name, birthday, email) values (40, 'Anet', null, 'abeasley13@paginegialle.it');
insert into employee (id, name, birthday, email) values (41, 'Brnaby', '1988-03-28', 'bschreiner14@mashable.com');
insert into employee (id, name, birthday, email) values (42, 'Prent', null, 'pheiden15@comcast.net');
insert into employee (id, name, birthday, email) values (43, 'Andre', '2018-12-18', 'ablankley16@php.net');
insert into employee (id, name, birthday, email) values (44, 'Nichol', '1970-10-12', 'nminto17@homestead.com');
insert into employee (id, name, birthday, email) values (45, 'Caritta', '2020-11-21', 'ctheobalds18@dmoz.org');
insert into employee (id, name, birthday, email) values (46, 'Teodor', '1995-01-19', 'tdibartolommeo19@blinklist.com');
insert into employee (id, name, birthday, email) values (47, 'Leticia', null, 'lcrabbe1a@forbes.com');
insert into employee (id, name, birthday, email) values (48, 'Rica', '1995-03-05', 'rmargrem1b@github.com');
insert into employee (id, name, birthday, email) values (49, 'Vite', null, 'vchoat1c@usnews.com');
insert into employee (id, name, birthday, email) values (50, 'Aubrey', '1996-10-22', 'ascurr1d@list-manage.com');

````
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

````SQL
UPDATE employee SET birthday = '2020-03-15',
name = 'UPDATE',
email = 'UPDATE@gmail.com',
WHERE id = 1;

UPDATE employee SET birthday = '2020-03-15',
name = 'UPDATE',
email = 'UPDATE@gmail.com',
WHERE id = 2;

UPDATE employee SET birthday = '2020-03-15',
name = 'UPDATE',
email = 'UPDATE@gmail.com',
WHERE id = 3;

UPDATE employee SET birthday = '2020-03-15',
name = 'UPDATE',
email = 'UPDATE@gmail.com',
WHERE id = 4;

UPDATE employee SET birthday = '2020-03-15',
name = 'UPDATE',
email = 'UPDATE@gmail.com',
WHERE id = 5;
````

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

````SQL
DELETE FROM employee WHERE id = 20;

DELETE FROM employee WHERE id = 21;

DELETE FROM employee WHERE id = 22;

DELETE FROM employee WHERE id = 23;

DELETE FROM employee WHERE id = 24;
````
