# ODEV8
1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

# CEVAPLAR
1. - TABLO OLUŞTURMA İŞLEMİ
        * ```CREATE TABLE employee ( id INTEGER, name VARCHAR(50), birthday DATE, email VARCHAR(100) );```

2. - 'Mockaroo' ile VERİ EKLEME İŞLEMİ
        * ```insert into employee (id, name, birthday, email) values (1, 'Erda', '1915-09-29', 'ekoene0@google.cn');```
```insert into employee (id, name, birthday, email) values (2, 'Elly', '1974-06-10', 'eussher1@telegraph.co.uk');```
```insert into employee (id, name, birthday, email) values (3, 'Willa', '1954-06-24', 'whandley2@1und1.de');```
```insert into employee (id, name, birthday, email) values (4, 'Judith', null, 'jfawckner3@github.com');```
```insert into employee (id, name, birthday, email) values (5, 'Kali', null, 'kmunning4@cloudflare.com');```
```insert into employee (id, name, birthday, email) values (6, 'Cammie', '1934-03-06', 'cdog5@abc.net.au');```
```insert into employee (id, name, birthday, email) values (7, 'Jocko', '1955-08-30', 'jelloy6@multiply.com');```
```insert into employee (id, name, birthday, email) values (8, 'Rosemarie', '1906-07-14', 'rfellona7@europa.eu');```
```insert into employee (id, name, birthday, email) values (9, 'Murdock', '1917-11-17', 'msalkeld8@nationalgeographic.com');```
```insert into employee (id, name, birthday, email) values (10, 'Derick', '1975-03-23', 'dkennsley9@alibaba.com');```
```insert into employee (id, name, birthday, email) values (11, 'Lilas', '1984-02-14', 'lcrimpea@java.com');```
```insert into employee (id, name, birthday, email) values (12, 'Loraine', '1906-12-29', null);```
```insert into employee (id, name, birthday, email) values (13, 'Vi', null, 'vambrogettic@is.gd');```
```insert into employee (id, name, birthday, email) values (14, 'Nevsa', '1979-08-10', 'nwithinshawd@qq.com');```
```insert into employee (id, name, birthday, email) values (15, 'Delaney', '1955-10-01', 'dchrstinee@icio.us');```
```insert into employee (id, name, birthday, email) values (16, 'Jacqui', '1982-06-27', 'jivashevf@google.ca');```
```insert into employee (id, name, birthday, email) values (17, 'Meghann', '1954-03-16', 'mstutterg@histats.com');```
```insert into employee (id, name, birthday, email) values (18, 'Efrem', null, 'eclurowh@telegraph.co.uk');```
```insert into employee (id, name, birthday, email) values (19, 'Zebadiah', '1974-08-29', null);```
```insert into employee (id, name, birthday, email) values (20, 'Horatius', null, 'hwestfieldj@symantec.com');```
```insert into employee (id, name, birthday, email) values (21, 'Zsazsa', '1940-02-06', 'zmaneylawsk@fastcompany.com');```
```insert into employee (id, name, birthday, email) values (22, 'Nicol', '1901-01-14', 'ntregidol@vimeo.com');```
```insert into employee (id, name, birthday, email) values (23, 'Edan', '1957-08-05', 'ewoolstonm@uol.com.br');```
```insert into employee (id, name, birthday, email) values (24, 'Cart', '1920-05-03', 'csommerlien@cornell.edu');```
```insert into employee (id, name, birthday, email) values (25, 'Shela', '1962-10-26', null);```
```insert into employee (id, name, birthday, email) values (26, 'Susana', '1910-09-16', 'solunneyp@princeton.edu');```
```insert into employee (id, name, birthday, email) values (27, 'Carolyne', '1912-01-29', 'ckubalekq@blogs.com');```
```insert into employee (id, name, birthday, email) values (28, 'Chelsae', '1993-09-28', 'csimonassir@blogtalkradio.com');```
```insert into employee (id, name, birthday, email) values (29, 'Verge', null, 'vbelchs@discuz.net');```
```insert into employee (id, name, birthday, email) values (30, 'Jessy', null, 'jdanniellt@ted.com');```
```insert into employee (id, name, birthday, email) values (31, 'Dollie', '1945-07-02', 'dbartolicu@uol.com.br');```
```insert into employee (id, name, birthday, email) values (32, 'Delano', null, 'djensenv@cpanel.net');```
```insert into employee (id, name, birthday, email) values (33, 'Arabel', null, 'aminchindenw@nydailynews.com');```
```insert into employee (id, name, birthday, email) values (34, 'Pebrook', '1989-06-09', 'polivasx@people.com.cn');```
```insert into employee (id, name, birthday, email) values (35, 'Flore', '1986-11-25', null);```
```insert into employee (id, name, birthday, email) values (36, 'Blinnie', '1915-04-14', 'bstuddertz@amazon.co.jp');```
```insert into employee (id, name, birthday, email) values (37, 'Gustavus', '1905-12-10', 'gwaleworke10@webnode.com');```
```insert into employee (id, name, birthday, email) values (38, 'Nye', '1993-02-24', 'nbrentnall11@europa.eu');```
```insert into employee (id, name, birthday, email) values (39, 'Sela', '1957-01-22', 'sshera12@disqus.com');```
```insert into employee (id, name, birthday, email) values (40, 'Beverlee', '1983-06-19', 'bhallows13@clickbank.net');```
```insert into employee (id, name, birthday, email) values (41, 'Jaimie', '1955-12-17', 'joflaverty14@cbc.ca');```
```insert into employee (id, name, birthday, email) values (42, 'Oberon', '1969-11-25', 'ochatenier15@webmd.com');```
```insert into employee (id, name, birthday, email) values (43, 'Aryn', '1951-04-20', 'anobles16@1und1.de');```
```insert into employee (id, name, birthday, email) values (44, 'Micah', '1970-05-18', null);```
```insert into employee (id, name, birthday, email) values (45, 'Donelle', '1967-01-19', 'dcastagnone18@storify.com');```
```insert into employee (id, name, birthday, email) values (46, 'Evaleen', '1919-06-30', null);```
```insert into employee (id, name, birthday, email) values (47, 'Marysa', null, 'mmorffew1a@ovh.net');```
```insert into employee (id, name, birthday, email) values (48, 'Sansone', '1993-04-21', 'salexsandrowicz1b@hc360.com');```
```insert into employee (id, name, birthday, email) values (49, 'Hamilton', '1964-05-03', 'hkoschek1c@e-recht24.de');```
```insert into employee (id, name, birthday, email) values (50, 'Ferdinanda', null, 'fclemenson1d@tuttocitta.it');```

3. - UPDATE İŞLEMLERİ
        * ```UPDATE employee SET name = 'Hasan Basri', birthday = '1820-06-12', email = 'dargahasanbasri@gmail.com' WHERE id = 1 RETURNING *;```
        * ```UPDATE employee SET id = 55, birthday = '2020-04-22', email = 'elly@gmail.com' WHERE name = 'Elyy' RETURNING *;```
        * ```UPDATE employee SET id = 80, name = 'Enes', email = 'enes@gmail.com' WHERE birthday = '1954-06-24' RETURNING *;```
        * ```UPDATE employee SET id = 58, name = 'Vexana', birthday = '1999-10-30' WHERE email = 'jelloy6@multiply.com' RETURNING *;```
        * ```UPDATE employee SET name = 'Hüseyin', birthday = '2010-09-18', email = 'huseyin@gmail.com' WHERE id = 12 RETURNING *;```

4. - DELETE İŞLEMLERİ
        * ```DELETE FROM employee WHERE id = 4 RETURNING *;```
        * ```DELETE FROM employee WHERE name = 'Kali' RETURNING *;```
        * ```DELETE FROM employee WHERE birthday = '1906-07-14' RETURNING *;``` 
        * ```DELETE FROM employee WHERE email = 'dkennsley9@alibaba.com' RETURNING *;```
        * ```DELETE FROM employee WHERE name = 'Vi' RETURNING *;``` 