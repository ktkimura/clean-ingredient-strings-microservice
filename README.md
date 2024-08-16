# Microservice for cleaning up ingredient strings
A simple microservice that uses a JSON file as a communication pipe. microC.js will "clean" up an array of ingredient strings by removing any measurement or details so only the ingredient name is left behind. For example, "¼ teaspoon salt, or more to taste" is reduced to "salt". This reduction is necessary for my main program that matches user-entered ingredient strings to ingredients in a given recipe. Since my main program cannot handle quantities just yet, this is a workaround solution to ensure the ingredient comparison feature can work to some degree.
## Dependencies
- Node.js
- node-watch
- fs
