# today-be

Add files:

	1.composer update 
	  bootstrap/cache directory must be present and writable. if you got this error then run this command.

	2. cd bootstrap 
	3. sudo mkdir cache
	4. sudo chmod -R 777 bootstrap/
	5. composer update
	6. sudo mkdir framework 
	7. sudo mkdir {sessions,views,cache}
	8. sudo chmod -R 777 storage/

	Add the .env file
	Add the public file.