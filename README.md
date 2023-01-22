# ITSTEP-JAVA-HW20230118
Fullstack project - Server (Java – SpringBoot)

Создать REST API с помощью Spring BOOT.
Стандартные CRUD операции:
показать все,
добавить
изменить
удалить

Database creation (MySQL)

CREATE DATABASE db_note;
USE db_note;

CREATE TABLE notes(
	  id int primary key not null auto_increment,
    note_author varchar(25),
    note_title varchar(50),
    note_text text
);

insert into notes(note_author, note_title, note_text) values ('Ivan Ivanenko', 'note #1', 'Ivanenkos first note');
insert into notes(note_author, note_title, note_text) values ('Petrenko', 'note #2', 'Petrenko note oll inf...');
insert into notes(note_author, note_title, note_text) values ('Sergienko Sergiy', 'my note', 'What is a note');

select * from notes;
