# Ionic navigation query param bug

### How to reproduce
1. Clone this repo and run `npm i` and `npm run dev`
2. Click the button "Go to nested page"
3. The url is "/tabs/tab1/foo?foo=bar" (which is intended)
4. Click Tab1 in the navigation, so you return to the parent route "/tabs/tab1"
5. Click Tab2 in the navigation
6. Click Tab1 again and it will now somehow inherit the previous query param "/tabs/tab1?foo=bar"

### Example video can be downloaded here
https://github.com/rishoej/ionic-navigation-query-param-bug/blob/main/Example.mov
