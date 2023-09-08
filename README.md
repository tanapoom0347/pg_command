# pg_command  
  
import  
psql -U postgres -d chinook -q -f 1.sql  
  
export  
pg_dump -U postgres -p 5432 -d chinook -W -f 2.sql  
