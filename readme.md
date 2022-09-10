INSERT into movie (title,runtime,director,release_year)values('krish','02:00:00','roshan','2006');
INSERT into movie (title,runtime,director,release_year)values('snake','02:05:00','khan','2007');
INSERT into movie (title,runtime,director,release_year)values('sholay','04:00:00','salman','1975');
DELETE from movie where title= 'krish';

SELECT title,release_year from movie;
