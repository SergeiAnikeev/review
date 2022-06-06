## Review APP

## Table of contents
- [General info](#general-info)
- [Functionality](#functionality)
- [Site online](#site-online)
## General info
The app uses local data stored in `data.js` with properties: 
- `id`
- `name`
- `job`
- `image`
- `text`
## Functionality
- Button `<` shows a previous person in an array `people` (stored in `data.js`)
- Button `>` goes to the next person in the array
- Button `Surprise me` picks randomly person from the `people` array
- Functionality prevents choosing a number out of array indexes, the next person after the last one moves to the first person in the array and if we press the previous person when we are at the first index, it shifts to the last one.
## Site online
There is a link where you can find this project online:
[review-react-app-2022](https://review-react-app-2022.netlify.app/)