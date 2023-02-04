---
title: Github star, fork, and watch stats. 
---

I attempted to find a solution that would allow me to track who forks, stars, and watches my GitHub repositories simultaneously. However, after a brief search, I was unable to find such a tool. As a result, I decided to work on [this script](https://github.com/dragona/github-stat).


This ```https://github.com/nelsonic/github-scraper``` is an exciting GitHub scraper but one, it is not in python and two it only reports the watchers, stars and forks counts
without the account information 
```
  watchers: 3,
  stars: 8,
  forks: 1,
  ...
```

What I need is something like this:

```
                                                   stargazers (68)    watcher (20)    forks (100)    
https://github.com/account_1                              *                *              *    
https://github.com/account_2                              *                *              *    
https://github.com/account_3                              *                *              *    
https://github.com/account_4                              *                *              *   
```

