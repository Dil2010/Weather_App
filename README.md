
# Weather App

This is a simple app to demonstrate weather


## Tech Stack

**Client:** React

**Server:** Not Applicable


## Features

- Ontime weather report
- Change location




## Installation

Install my-project with npm

```bash
  create-react-app weather_app
  cd weather_app
  

```
    
## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **https://api.openweathermap.org/data/2.5/weather?q&units=imperial&appid=895284fb2d2c50a520ea537456963d9c**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **https://api.openweathermap.org/data/2.5/weather?q=${location}&units=imperial&appid=895284fb2d2c50a520ea537456963d9c**. Id of item to fetch |




## License

[MIT](https://choosealicense.com/licenses/mit/)


## Run Locally

Clone the project

```bash
  git clone https://github.com/Dil2010/Weather_App
```

Go to the project directory

```bash
  cd my-project
```

Install dependencies

```bash
  npm install
```




## Screenshots

![Sunnyside for Desktop](/Weather.png)



