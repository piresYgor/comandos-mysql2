# comandos-mysql2

CREATE DATABASE Nikkel;

USE Nikkel;

CREATE TABLE usuário (id INT(45) primary key not null auto_increment, email VARCHAR(100), senha INT(45) );

SELECT * FROM usuário;

CREATE TABLE transações (id INT(45) primary key not null auto_increment, valor INT(45), descrição VARCHAR(100), dia_de_lançamento INT(45), forma_de_lançamento VARCHAR(100));

SELECT * FROM transações;
