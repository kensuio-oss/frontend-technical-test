# Frontend exercise

## Data

The data shows various statistics about other existing data. 3 different sets are presented that correspond to real usage.

- drinks-various-data.json: various statistics on drinks and other related or unrelated numbers.
- network-data.json: Some statistics about network / communication data
- wheather-data.json: Same for wheather data

## Requirements

We need to show the user the data in both tabular format and chart.
There should be interaction between the graph and the tabular data.
For instance, when hovering on a line of the graph, hightlight a column in the table.

To complete this behaviour, we would like to be able to change data on the fly. Allow the user to choose
a point on the graph and allow to change it on the fly. Ideally, the change should be propagated to the backend
but it can also stay in the frontend.

### Functional Requirements

We leave a lot to decide on the functional side. We would prefer a nice look & feel but you can use bootstrap or another popular CSS framework. Provide a way to navigate through the 3 different data sets.

### Technical Requirements

- Use ReactJS via create react app
- You **have to use Redux** (hint: at Kensu, we use redux-toolkit)
- Ideally the chart should be based on D3.js but there are many libraries that add charting on top of D3, you should preferably use one of those.
- Handle the loading of the data, success and errors via redux.
- Choose the way to serve the json but it should just work by running npm start. If there is an external server, please make it easy to use. It just be done with the webpack dev server.
- You should share via Github or Gitlab but keep the repo private.
