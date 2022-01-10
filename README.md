# postgreSQL_odev8
PostgreSQL -  Sekizinci ödev - Ilgar Babashli

# _Q1_ 
test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

# _Ans_
CREATE TABLE employee (
	id INTEGER,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);

# _Q2_ 
Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

# _Ans_
insert into employee (id, name, birthday, email) values (1, 'Misti Stucksbury', '1952-04-22', 'mstucksbury0@nps.gov');
insert into employee (id, name, birthday, email) values (2, 'Rice Antonoczyk', '1998-03-17', 'rantonoczyk1@pinterest.com');
insert into employee (id, name, birthday, email) values (3, 'Sigismond Rabidge', '2000-09-18', 'srabidge2@digg.com');
insert into employee (id, name, birthday, email) values (4, 'Carson Puve', '2001-10-09', 'cpuve3@opera.com');
insert into employee (id, name, birthday, email) values (5, 'Simmonds Hannan', '1984-09-11', 'shannan4@squidoo.com');
insert into employee (id, name, birthday, email) values (6, 'Wilhelm Crampin', '1987-06-02', 'wcrampin5@posterous.com');
insert into employee (id, name, birthday, email) values (7, 'Sybil Capsey', '2002-07-27', 'scapsey6@yellowpages.com');
insert into employee (id, name, birthday, email) values (8, 'Amandi Kemell', '1978-01-11', 'akemell7@odnoklassniki.ru');
insert into employee (id, name, birthday, email) values (9, 'Weber Gobel', '1972-09-19', 'wgobel8@army.mil');
insert into employee (id, name, birthday, email) values (10, 'Peyton Heakey', '1971-11-10', 'pheakey9@hhs.gov');
insert into employee (id, name, birthday, email) values (11, 'Murray Hasson', '1997-01-27', 'mhassona@networksolutions.com');
insert into employee (id, name, birthday, email) values (12, 'Shirlene Profit', '1971-09-18', 'sprofitb@ezinearticles.com');
insert into employee (id, name, birthday, email) values (13, 'Gilligan Dripp', '1977-10-05', 'gdrippc@nasa.gov');
insert into employee (id, name, birthday, email) values (14, 'Lauraine Cafferty', '1956-02-07', 'lcaffertyd@google.com.br');
insert into employee (id, name, birthday, email) values (15, 'Kathie Borzoni', '1979-05-22', 'kborzonie@delicious.com');
insert into employee (id, name, birthday, email) values (16, 'Anallese Winnett', '1986-01-06', 'awinnettf@skyrock.com');
insert into employee (id, name, birthday, email) values (17, 'Emlen Thomkins', '1998-01-03', 'ethomkinsg@jigsy.com');
insert into employee (id, name, birthday, email) values (18, 'Hodge Janway', '1984-07-07', 'hjanwayh@altervista.org');
insert into employee (id, name, birthday, email) values (19, 'Filbert Laurenz', '1982-02-07', 'flaurenzi@tamu.edu');
insert into employee (id, name, birthday, email) values (20, 'Fancie Farrand', '1971-08-03', 'ffarrandj@angelfire.com');
insert into employee (id, name, birthday, email) values (21, 'Zacharias Stigers', '1956-01-31', 'zstigersk@google.ru');
insert into employee (id, name, birthday, email) values (22, 'Menard Stable', '1947-04-05', 'mstablel@omniture.com');
insert into employee (id, name, birthday, email) values (23, 'De witt Careswell', '1955-09-17', 'dwittm@t-online.de');
insert into employee (id, name, birthday, email) values (24, 'Farley Andre', '2002-07-03', 'fandren@zdnet.com');
insert into employee (id, name, birthday, email) values (25, 'Berk Le Provest', '1949-01-20', 'bleo@nsw.gov.au');
insert into employee (id, name, birthday, email) values (26, 'Hamlen Byrnes', '1960-12-11', 'hbyrnesp@usgs.gov');
insert into employee (id, name, birthday, email) values (27, 'Vally McGinn', '1973-06-12', 'vmcginnq@cbc.ca');
insert into employee (id, name, birthday, email) values (28, 'Archibald Oulett', '1980-06-09', 'aoulettr@webs.com');
insert into employee (id, name, birthday, email) values (29, 'Merrily Brennan', '1953-02-11', 'mbrennans@yolasite.com');
insert into employee (id, name, birthday, email) values (30, 'Arden Kenewell', '1969-11-13', 'akenewellt@joomla.org');
insert into employee (id, name, birthday, email) values (31, 'Cirillo McWilliams', '1969-08-17', 'cmcwilliamsu@ebay.co.uk');
insert into employee (id, name, birthday, email) values (32, 'Kerianne Cheesley', '1971-07-15', 'kcheesleyv@goo.gl');
insert into employee (id, name, birthday, email) values (33, 'Leese Ickeringill', '1953-05-11', 'lickeringillw@oaic.gov.au');
insert into employee (id, name, birthday, email) values (34, 'Niki Linthead', '1985-10-16', 'nlintheadx@businessweek.com');
insert into employee (id, name, birthday, email) values (35, 'Faun Presslie', '1960-09-04', 'fpressliey@vimeo.com');
insert into employee (id, name, birthday, email) values (36, 'Lilias Sendley', '1983-02-03', 'lsendleyz@sciencedaily.com');
insert into employee (id, name, birthday, email) values (37, 'Enoch Mileham', '1963-11-24', 'emileham10@addtoany.com');
insert into employee (id, name, birthday, email) values (38, 'Sheeree Ablitt', '1986-02-18', 'sablitt11@odnoklassniki.ru');
insert into employee (id, name, birthday, email) values (39, 'Wilek Martinetto', '1949-06-08', 'wmartinetto12@bloglovin.com');
insert into employee (id, name, birthday, email) values (40, 'Geraldine Pitceathly', '1991-02-19', 'gpitceathly13@360.cn');
insert into employee (id, name, birthday, email) values (41, 'Nealy Chace', '1976-02-08', 'nchace14@yale.edu');
insert into employee (id, name, birthday, email) values (42, 'Olimpia Attle', '1978-12-15', 'oattle15@hubpages.com');
insert into employee (id, name, birthday, email) values (43, 'Trenna Dent', '2003-05-30', 'tdent16@exblog.jp');
insert into employee (id, name, birthday, email) values (44, 'Skipper Halliday', '1972-04-08', 'shalliday17@netvibes.com');
insert into employee (id, name, birthday, email) values (45, 'Colette Verman', '1984-02-05', 'cverman18@canalblog.com');
insert into employee (id, name, birthday, email) values (46, 'Calv Kurth', '1951-08-01', 'ckurth19@hao123.com');
insert into employee (id, name, birthday, email) values (47, 'Beau Dimeloe', '1960-11-10', 'bdimeloe1a@about.me');
insert into employee (id, name, birthday, email) values (48, 'Salli Neenan', '1999-12-04', 'sneenan1b@gov.uk');
insert into employee (id, name, birthday, email) values (49, 'Adriana Grayshan', '1986-03-30', 'agrayshan1c@cornell.edu');
insert into employee (id, name, birthday, email) values (50, 'Byrle Moorcraft', '1950-01-20', 'bmoorcraft1d@dion.ne.jp');

# _Q3_ 
Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

# _Ans_
1)
UPDATE employee
	SET id = 95
WHERE name LIKE 'Sybil%'
RETURNING *;

2) 
UPDATE employee
	SET birthday = NULL
WHERE email LIKE 'b%'
RETURNING *;

3)
UPDATE employee
	SET email = 'unacceptable',
		name = 'fake name'
WHERE name LIKE ('Em%')
RETURNING *;

4)
UPDATE employee
	SET id = 32
WHERE birthday = '2001-10-09'
RETURNING *;

5)
UPDATE employee
	SET birthday = '1998-11-03'
WHERE name LIKE 'Am%'
RETURNING *;

# _Q4_ 
Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

# _Ans_
1)
DELETE FROM employee
WHERE name LIKE 'Am%'
RETURNING *;

2)
DELETE FROM employee
WHERE id = 31
RETURNING *;

3)
DELETE FROM employee
WHERE name LIKE '%e%s'
RETURNING *;

4)
DELETE FROM employee
WHERE email ILIKE ('%.ru')
RETURNING *;

5)

DELETE FROM employee
WHERE birthday = '2000-09-18'
RETURNING *;
