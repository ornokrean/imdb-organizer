# imdb-organizer
A small script to rearrange a list of movies and tv shows by type->genre->rating.

## Input
1. A list of rows, each contains either:
 - A list organizing element, such a "Movies"/"TV Shows", or "Genre" sub-organizer. They will be marked with `#` or `##`. 
 - A movie or TV Show title. it can contain a checklist prefix, such a `- [ ] ` or `- [x]`, that will be followed with the rating as ` 0.0 | `.

A full line exmaple, for the boys tv show:
```
# TV Shows:
## Action:
- [x] 8.7 | The Boys
```

