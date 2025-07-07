To inject 

 sqlcmd -S localhost -U <u> -P <pass> -d <db> -i .\Downloads\countries-states-cities-database-master\sqlserver\<files>.sql

 what modified:
 - 3 countries with null subregion_id: 9, 30, 96
 - make state_code nullable