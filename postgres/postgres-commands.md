Export step

pg_dump -U kong -t <table_name> -a -f /tmp/table_name.sql kong

Import step

psql -U kong -d kong -f table_name.sql