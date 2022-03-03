

[Start]

Export telegram chat as "JSON" and place it in the same folder as telegram.exe
Start telegram.exe


[Config]

"tg_config.json" is the configuration file editable by any text editor.


Settings:

"start_date" - Will count message from this day to present 
	format - "start_date": "YYYY-MM-DD"  (Y - year, M - month, D - day)


"detailed_view" - Can be set to true or false.
	format - "detailed_view": true/false	
	if set to true it will show stats for individual accounts

"users" - List of People and accounts they own
	format - {"name": "Person",
		  "Accounts": ["Account name","Account name"] 
		 }


		
