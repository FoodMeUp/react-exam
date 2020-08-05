# react-exam

We do love __Beer__ and we want to make an App to order some :beer: !

To do so we will use the following [API](https://punkapi.com/documentation/v2)

## Rules

You will use __React__, and __Typescript__ (state management technology is up to you: Redux, Swr, React-Query, Recoil, Context, ...)
There will be 3 pages (__beer list__, __beer detail__, __beer cart__)
If the page is being reloaded we still have the cart being filled

Beer list:
- Display __all the beers paginated__ with an image, name, volume (you can paginate or use infinite loading)
- We can __order__ a beer
- We can see if the beer has been __ordered or not__
- We can navigate to the __beer detail__ and __beer cart__ pages

Beer detail:
- The beer detail will display detailed informations: image, name, description, volume, ingredients, brewers_tips, and more if you feel the need ;)
- We can see if the beer has been __ordered or not__
- We can navigate to the __beer list__ and __beer cart__ pages

Beer cart:
- Display a simple list of beers contained in the cart with image and name
- We can navigate to the __beer detail__ and __beer list__ pages

## Bonus feature

- Implement __tests__ (you can choose your tools: Stoybook, Jest, Cypress, QAWolf, ...)
- Add __linters__
- The app can run in though __Docker__ environment
