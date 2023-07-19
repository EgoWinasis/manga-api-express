

# Usage
1. Clone this repository
    ```bash
  
    ```
2. Install dependecies (`yarn` or `npm install`)
3. Start the development environment (*if you haven't installed nodemon globally, you can do `npm i nodemon --save`)
    ```bash
    npm run dev or npm run start
    ```
4. visit http://localhost:3000/api

# Documentation


## All Manga
Get Latest Manga Update
```
/manga/page/[pagenumber]
```
example : https://mangamint.kaedenoki.net/api/manga/page/1

## Popular Manga
Get Popular Manga
```
/manga/popular/[pageNumber]
```
example : https://mangamint.kaedenoki.net/api/manga/popular/1

## Detail Manga
```
/manga/detail/[endpoint]
```
example : https://mangamint.kaedenoki.net/api/manga/detail/after-transformation-mine-and-her-wild-fantasy/

## Search Manga by Name
```
/search/[query]
```
example : https://mangamint.kaedenoki.net/api/search/komi%20san

## Genre List
```
/genres
```
example : https://mangamint.kaedenoki.net/api/genres

## Genre Detail
```
/genres/[endpoint]/[pagenumber]
```
example : https://mangamint.kaedenoki.net/api/genres/action/1

## Recommended Manga
```
/recommended
```
example : https://mangamint.kaedenoki.net/api/recommended

## Manhua List (Chinese Comic)
```
/manhua/[pageNumber]
```
example : https://mangamint.kaedenoki.net/api/manhua/1

## Manhwa List (Korean Comic)
```
/manhwa/[pageNumber]
```
example : https://mangamint.kaedenoki.net/api/manhua/1

## Chapter
```
/chapter/[chapterEndpoint]
```
example :https://mangamint.kaedenoki.net/api/chapter/after-transformation-mine-and-her-wild-fantasy-chapter-70-bahasa-indonesia/

