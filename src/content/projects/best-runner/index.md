---
title: "Best Runner"
tags:
  [
    "React",
    "React-router",
    "Redux",
    "Redux-Reselect",
    "styled-components",
    "Material UI",
    "Canvas.js",
  ]
date: "2020-08-10"
websiteLink: "https://bestrunner.netlify.app/"
githubLink: "https://github.com/codemyjourney/Best-Runner"
---

**This App allows you to track your workouts activity, and to view the weekly chart based on your activity.**

---

#### Overview and Goals:

**1. Add a new workout / Edit the existing one:**

- **by distance in km;**
- **by date;**
- **by type (walk/run/bike/ski)**
- **include a comment;**

**3. Delete the existing workout;**

**4. Filter Workouts:**

- **by date:** oldest-newest, newest-oldest;
- **by type:** bike/walk/run/ski;
- **by km:** max-min, min-max

#### App construction.

- **React.js** to build the front-end;
- **Redux** for state managemet;
- **React-router** for routing;
- **Redux-reselect** to implement complex filter to memoize expensive calculations;
- **Redux-persist** to save data in localStorage;
- **Material UI** for Forms and Input Fields;
- **Styled Components** to keep the concerns of styling and element architecture separated and make components more readable.
- **Canvas.js** to make the weekly chart with the data;
