# Frontend exercise

## Data

The data shows various statistics about other existing data. 3 different sets are presented that correspond to real usage. This is only 3 examples of type of data we receive. The stats property
is a generic key/value object, no assumptions can be made about the keys. The value is always a
number.

- drinks-various-data.json: various statistics on drinks and other related or unrelated numbers.
- network-data.json: Some statistics about network / communication data
- wheather-data.json: Same for wheather data

## Requirements

We need to show the user the data in both tabular format and chart. Provide a way to navigate through the 3 different data sets. All data present in each json should be shown on the page in the chart and in the table.

There should be interaction between the graph and the tabular data.
For instance, when hovering on a line of the graph, hightlight a column in the table.

### Functional Requirements

We leave a lot to decide on the functional side. We would prefer a nice look & feel but you can use bootstrap or another popular CSS framework. If you make assumptions, document them in the readme.

### Technical Requirements

- Use ReactJS via create react app
- Use TypeScript as language for this app
- You **have to use Redux** (hint: at Kensu, we use redux-toolkit)
- You should use a charting library.
- Handle the loading of the data, success and errors via redux.
- Choose the way to serve the json but it should just work by running npm start. If there is an external server, please make it easy to use. It can just be done with the webpack dev server.
- It would really be appreciated if you would show in your solution how you deal with unit testing.
- You should share via Github or Gitlab but keep the repo private.
