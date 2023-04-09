# Just Weather Project

Hello to [BigDevSoon](https://bigdevsoon.me/) 👋

Develop a sleek application that provides users with daily weather updates for their current or selected locations. The app should display essential weather details. Challenge yourself by integrating a third-party API for hourly and daily forecasts. Additionally, allow users to save their recent searches for quick and easy access.

## How to start

1. Start the project in our [app](https://app.bigdevsoon.me/) to get a feel for it.
2. Review the requirements listed below in this README.
3. Go through the design images on the [project's page](https://app.bigdevsoon.me/projects/just-weather) and import the `.fig` file into Figma to understand the layout and design elements.
4. Clone this repository or use [GitHub Codespaces](https://github.com/features/codespaces) to set up the project environment.
5. Choose your preferred technology stack and overwrite repository files as needed to set up your project structure. We included a few files and the `assets` folder for convenience, extracted from the design.
6. Begin coding, either using the Freerun mode to work on each card individually or the Speedrun mode to work at your own pace. Be sure to follow the guidelines outlined below.
7. Have a strong desire to learn and improve your skills as a Big Developer. 🚀

## Requirements

- [ ] Start by researching and exploring an API such as [Weather API](https://www.weatherapi.com/), studying its documentation to understand what data it returns, and configuring it with your API key. Use icons from the API for rendering weather icons except for the weather details that we provide.
- [ ] Add a search bar with debouncing, loading, and empty states for search results to the navigation, along with a logo, showing around 5 results.
- [ ] Display location, day/night temperature section, for either the user's current location or the one that is searched.
- [ ] Display an hourly forecast for the next 24 hours section, for either the user's current location or the one that is searched. It should be horizontally scrollable and start at 00:00 and end at 23:00.
- [ ] Display the weather details section, for either the user's current location or the one that is searched.
- [ ] If the user denies location access, default to a random capital city in the world.
- [ ] Allow users to switch between Fahrenheit and Celsius temperature units in the navigation.
- [ ] Save recent searches, so when users focus on the search field, it shows the recent search results. Users can delete all recent searches or delete them one by one by clicking on the trash icon.
- [ ] Add skeleton animation loading to both pages for a better user experience.
- [ ] Handle API request failures by showing only the navigation and error boundary page.

## Guidelines

1. Aim for pixel-perfect implementation of the design. Use tools like [PixelParallel](https://chrome.google.com/webstore/detail/pixelparallel-by-htmlburg/iffnoibnepbcloaaagchjonfplimpkob?hl=en) or other techniques to ensure accuracy.
2. Write clean and efficient code. Use extensions like [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) and [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint) for formatting and errors, and consider using [GitHub Copilot](https://github.com/features/copilot) and [VSCode](https://code.visualstudio.com/) as your code editor.
3. Follow a [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow). Keep your commits small and descriptive, organize your work into separate branches, and use pull requests for code reviews.

Remember, the cleaner and more accurate your code is, the faster you can finish and the better you'll feel about your work.
So let's make it happen! 💡

## Submitting project

Once you've completed the project and unlocked the Submit step in our app, it's time to deploy your project to [Vercel](https://vercel.com/), [Netlify](https://www.netlify.com/), or [GitHub Pages](https://pages.github.com/) (if you haven't done so already). Keep in mind that we've added a `<bds />` tag to the `index.html` file, and we'll check for it when you submit your Project URL. So don't forget to include it! You'll also need to provide the project title and the primary frontend technology used. Good luck!

## We're in Beta and getting better every day!

Hey there, Big Developer! We wanted to take a moment to thank you for participating in our project and helping us improve our platform. We're always looking for ways to make our app better, so if you have any feedback or suggestions, please feel free to let us know.

Happy coding! 🚀
