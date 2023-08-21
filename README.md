# wcheck
Small weather conditions/forecast CLI tool in Go

### Setup
1. Get a free API key from [WeatherAPI](https://www.weatherapi.com/)
2. Export the ```WEATHERAPI_KEY``` in your ```.zshrc```

```bash
git clone git@github.com:albertofp/wcheck.git
cd wcheck
go build
sudo mv wcheck /usr/local/bin
```

### Usage

```bash
wcheck
```
You can pass the name of a city as a runtime argument:

```bash
wcheck Rio de Janeiro
```



