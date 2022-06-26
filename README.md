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

## Output
The script will print out the new list, reordered in the following fashion:
```
# Movies

## Genre 1

- [] 8.2 | Movie 1
- [] 8.1 | Movie 2
- [] 8.0 | Movie 3
- [] 7.6 | Movie 4
- [] 5.2 | Movie 5
- [x] 9.2 | Movie 6
- [x] 6.2 | Movie 7
- [x] 3.2 | Movie 8

## Genre 2
.
.
.

# TV Shows

## Genre 1

- [] 8.2 | Show 1
- [] 8.1 | Show 2
- [] 8.0 | Show 3
- [] 7.6 | Show 4
- [] 5.2 | Show 5
- [x] 9.2 | Show 6
- [x] 6.2 | Show 7
- [x] 3.2 | Show 8

## Genre 2
.
.
.
```
