# ecommerce-backend
According to [Shopify](https://www.shopify.com/enterprise/global-ecommerce-statistics), "The global ecommerce market is expected to total $5.7 trillion in 2022. That figure is estimated to grow over the next few years, showing that borderless ecommerce is becoming a profitable option for online retailers.
Two years ago, only 17.8% of sales were made from online purchases. That number is expected to reach 20.8% in 2023, a 2 percentage point increase in ecommerce market share. Growth is expected to continue, reaching 23% by 2025, which translates to a 5.2 percentage point increase in just five years."

Thus tracking and managing the data of online products, tags, and categories is paramount to not only maintaining shop stock, but also tracking data and trends. 

This database allows the user to POST, PUT, and DELETE routes in Insomnia.
A video walkthrough is seen [here](https://drive.google.com/file/d/1IVOxGC0_4f7x2d42mz5JJSM1oRlxNeDq/view)

## Installation

No installation used; the database is ran through Insomnia.
Setup is done by first installing the node packages using
```npm i```
MySQL is then invoked using the command
```mysql -u root -p``` followed by the password
the seeds are initalized by running
```npm run seed```
then the database is ran by the command 
```node server.js```

## Usage

The database is manipulated through the application Insomnia by running the various route commands, initalized with the request 'http://localhost:3001/api/'

![image](https://github.com/l-antonello/ecommerce-backend/assets/122548483/4c8972f8-8069-4d34-865f-03ba028f917a)


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
