# Mihalenko Maxim

<img src="static/images/maxim.jpg" width="150px" alt="my photo">

### Contact:

* Email - mihalenko.maxim21@gmail.com
* [LinkedIn](https://www.linkedin.com/in/frontend-mihalenko/)
* [Telegram](https://t.me/MihalenkoMaxim)
* Nickname in discord - **maxon_klakson (@MaxonKlakson6)**

*******

### About me

I have 1 year non-commercial experience in frontend. My main aim is developing in sphere that I chose and be professional.

First time I learnt frontend on my own, then I went to course *Frontend development* in **TeachMeSkills** school. Over this time I've done many JS tasks and implemented a few projects such as **responsive layout pages, React applications**.

Now I expand my knowledge via: reading books, articles, documentation, watching videos and to consolidate information I implement pet-projects. 

*******

### Skills

* HTML
* CSS, SCSS, styled-components
* JavaScript, TypeScript
* React, Redux-toolkit, Formik
* Axios, socket.io
* Material UI, Chakra UI
* git

******

### Code examples

#### It's [kata](https://www.codewars.com/kata/51b6249c4612257ac0000005) from code wars it is Roman Numbers task
```
function solution(roman) {
  let result = 0;
  const romansNumbers = {
    I: 1,
    V: 5,
    X: 10,
    L: 50,
    C: 100,
    D: 500,
    M: 1000,
  };
  for (let i = 0; i < roman.length; i++) {
    if (romansNumbers[roman[i + 1]] > romansNumbers[roman[i]]) {
      result -= romansNumbers[roman[i]];
      continue;
    }
    result += romansNumbers[roman[i]];
  }
  return result;
}
```
#### It's [kata](https://www.codewars.com/kata/576757b1df89ecf5bd00073b) from code wars it is Build Tower task

```
const towerBuilder = (nFloors) => {
  const pyramid = new Array(nFloors);
  const maxLength = nFloors * 2 - 1;
  let start = 0;
  let end = maxLength;

  for(let i = 0; i < nFloors; i ++) {
    pyramid[i] = [];
    pyramid[i].length = maxLength;

    for(let j = 0; j < pyramid[i].length; j++) {
      if(j < start) {
        pyramid[i][j] = ' ';
        continue;
      }
      if(j >= end) {
        pyramid[i][j] = ' ';
        continue;
      }
      pyramid[i][j] = '*';
    }
    pyramid[i] = pyramid[i].join('');
    start++;
    end--;
  }

  return pyramid.reverse();
}
```

******

### Projects

#### [Online-store](https://github.com/MaxonKlakson6/online-store)

It's project that I've done as diploma on TeachMeSkills school. This project was implemented as full-stack application.
Project includes all functional which necessary in online-stores.

Used technologies: 

```
"dependencies": {
    "@emotion/react": "^11.10.4",
    "@emotion/styled": "^11.10.4",
    "@mui/icons-material": "^5.10.6",
    "@mui/material": "^5.10.5",
    "@reduxjs/toolkit": "^1.8.5",
    "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^14.4.3",
    "@types/jest": "^27.5.2",
    "@types/node": "^17.0.45",
    "@types/react": "^18.0.20",
    "@types/react-dom": "^18.0.6",
    "axios": "^0.27.2",
    "formik": "^2.2.9",
    "lodash": "^4.17.21",
    "moment": "^2.29.4",
    "node-sass": "^7.0.3",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-redux": "^8.0.2",
    "react-router-dom": "^6.4.0",
    "react-scripts": "5.0.1",
    "react-toastify": "^9.0.8",
    "redux-persist": "^6.0.0",
    "reselect": "^4.1.6",
    "typescript": "^4.8.3",
    "web-vitals": "^2.1.4",
    "yup": "^0.32.11"
  },
```

#### [Tic-tac-toe](https://github.com/MaxonKlakson6/tic-tac-toe)

It is full-stack application where you can play tic-tac-toe with other user. In this project I've also implemented backend. 

Used technologies:

```
"dependencies": {
    "@testing-library/jest-dom": "^5.16.5",
    "@testing-library/react": "^13.4.0",
    "@testing-library/user-event": "^13.5.0",
    "@types/jest": "^27.5.2",
    "@types/node": "^16.11.66",
    "@types/react": "^18.0.21",
    "@types/react-dom": "^18.0.6",
    "history": "^5.3.0",
    "lodash": "^4.17.21",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-router-dom": "^6.4.2",
    "react-scripts": "5.0.1",
    "socket.io-client": "^4.5.3",
    "typescript": "^4.8.4",
    "web-vitals": "^2.1.4"
  },
```

******

### Courses

* *TeachMeSkills frontend development* - March 2022 - October 2022
* *Underground English school* - March 2021 - January 2022

******

### Languages 

* **English** - A2
* **Russian** - native