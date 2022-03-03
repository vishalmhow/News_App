
# NewsApp

This App will show news headline along with Covid Tracker.
In the Covid Tracker section we are showing Covid history data and can be filter by particular state.

App is wtritten in Swift 5, followed MVVM, used async/await for API calls and Concurrent operations.

# Package Dependencies

# Charts library to rendar chart of Covid data

Only one third party libary have used as Package Dependency:
Charts.

Before compile the code just download package dependency.


## API Reference

#### Get all items

```http
  GET https://newsapi.org/v2/everything?q=tesla&from=2022-01-27&sortBy=publishedAt&apiKey=
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get Covid History Data

```http
  GET https://api.covidtracking.com/v2/us/daily.json
```

#### To get State Specific Covid Data
```http
  GET https://api.covidtracking.com/v2/states/us/daily.json
```

## 🚀 About Me
I am iOS App developer!

# Hi, I'm Vishal! 👋


