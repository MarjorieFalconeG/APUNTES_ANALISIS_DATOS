SELECT
FROM
JOIN
ON
WHERE
GROUP BY — count sum avg
HAVING — count sum avg
ORDER BY
LIMIT



|| -- concatena

IF EXISTS;

select cast ((valor/ 100)+1 as numeric(3,2) )

select to_char(add_months(date('20250903'),-1),'YYYYMM');

select to_date(pv_fecha_proceso, 'YYYYMMDD');

select substr('abcdefg' , 1, 3); --primero 3 caracteres

select extract()

select substr('abcdefg' , 4); --desde el 4 hasta el final

select substr('abcdefg' , length('abcdefg') -4 +1 ,4 ); -- ultimo 4 caracteres (método portable)

nvl( conteo_nps, 0) -- los null le asigna 0 COL

row_number () over (partition by nombre_dataset_tec order by fecha desc) nfila -- repetidos

distinct()

replace( nombre_tabla, '_ind_2024' ,'')

case when nombre_tabla like '%_ind' then 'final' else 'eliminar' end