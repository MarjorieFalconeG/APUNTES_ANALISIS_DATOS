—cargar desde un csv
load data infile ‘data.csv’ into table table fields terminate by ‘,’ lines terminated by ‘\n’ ignore 1 rows;

— descargar una consulta a un csv
create extenal table ‘C:\ .csv’ using ( delimiter ‘,’ escapeChar ‘\’ remotesource odbc) as
select ******

