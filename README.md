# Docker-AMPP

Docker example with Apache, MySql, PHP and PHPMyAdmin

- PHP 7.2.6
- Mysql 8.0.16
- PHPMyAdmin 4.8

I use docker-compose as an orchestrator.

## Usage
```bash
docker-compose up -d
```

Open phpmyadmin at [http://localhost:8000](http://localhost:8000)
Open web browser to look at a simple php example at [http://localhost:8001](http://localhost:8001)

Run mysql client:

- `docker-compose exec db mysql -u root -p` 

Enjoy !

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)

