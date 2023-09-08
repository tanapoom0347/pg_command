# pg_command  
  
import  
psql -U postgres -d chinook -f 1.sql  
  
export  
pg_dump -U postgres --format p --inserts dvdrental > 3.sql    
