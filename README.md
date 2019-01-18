# Forestry Developer Assessment

Requires Ruby v2.4.4

## API

### Run

```
rails s
```

### Instructions

With the provided rails project, implement the /repos API endpoint. The endpoint should aggregate GitHub repository data from the following sources:

* https://api.github.com/users/forestryio/repos
* the provided JSON file (in repos.json)

The API endpoint should
* only return repositories where repository.fork is false.
* return JSON encoded data
* be filterable by programming language and created date
* be sortable by stars, watchers, and forks


*Please show your work. Do not submit one big commit*