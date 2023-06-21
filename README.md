
# Movie-Search-App
It is basically Website of movie searching using HTML, CSS, vanilla JavaScript and using OMDB API's 


## Authors
@*Vipul Sonawane*


## Details
- This app is basically search for movies, were users can view details about individual movies, and add movies to favorite section.
- It includes the container for the search results, and the container for the favorite movies.
- There is an event listener attached to the search which listens for input events and sends a request to the **OMDB API's** to search for movies matching the user's input. The response from the API is display a card for each movie in the search results. Each card includes a "favorite" button and a "view details" button.
- The code also includes functions for storing and retrieving the favorites list from local storage.

## API Reference

####

```http
  GET api/keys
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **be7ce634**. API key |

- Movie Search
```http
  Search API Link: http://www.omdbapi.com/?s=${movie name}&apikey=be7ce634
```

- Get Movie by id
```http
  Details API Link: http://www.omdbapi.com/?i=${movie id}&apikey=be7ce634ET api/keys
```
## 🔗GitHub Hosted Link:
```http
 https://vipul1907.github.io/Movie_Search_App.github.io/
```
