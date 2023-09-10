# pg_command  
  
import  
psql -U postgres -d chinook -f 1.sql  
\i C:/wnpp/nginx/html/user123/database.sql  
  
export  
pg_dump -U postgres -p 5432 -d chinook -W -f 2.sql  
pg_dump -U postgres --format p --inserts dvdrental > 3.sql    
