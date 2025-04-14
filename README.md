<!-- Template by https://github.com/othneildrew/Best-README-Template -->

<br />
<p align="center">
  <a href="https://github.com/milanbhatiya59/letusdebate">
    <img src="https://i.ibb.co/7Yhn3wB/change-my-mind-min.png" alt="Header photo" >
  </a>

  <h3 align="center">Let Us Debat</h3>

  <p align="center">
    A debate app built with React Native / Expo. Using Firebase as backend.
    <br />
    <br />
    <a href="https://twitter.com/anilsenay">Contact me</a>
    ·
    <a href="https://github.com/milanbhatiya59/letusdebate/issues">Report Bug</a>
    ·
    <a href="https://github.com/milanbhatiya59/letusdebate/issues">Request Feature</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
  * [Built With](#built-with)
  * [About the app](#about-the-app)
* [Screens](#screens)
   * [Welcome & Login](#welcome---login)
   * [Feed & Explore](#feed---explore)
   * [Discussion](#discussion)
   * [Profile](#profile)
   * [Notifications](#notifications)
   * [Join debate / Start new round / Post argument](#join-debate---start-new-round---post-argument)
* [Getting Started](#getting-started)
  * [Prerequisites](#prerequisites)
  * [Installation](#installation)
* [Issues / Feature Plans](#issues---future-plans)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

<!-- ABOUT THE PROJECT -->
## About The Project

Let Us Debat was a project I was making with Kotlin but I aborted the project. Then last month I started this project from scratch with React Native this time to learn more and get more experience in React Native. I wanted to make this project in 1 month as a goal. So everything I've done is a month of labor. ~90% of my goals are done. After all, I have a working project although it has some problems. These problems are not a big deal but I am done with this project now. I will continue to develop this project in places. I used Firebase as backend, I will create my own backend one day if I start development in backend. Because some parts of the app are not working well because of Firebase's limits. If you like my project and want to cooperate please contact with me ^^

### About the app
This is a debate app basically. You can create a debate on any topic to challenge a user to change your mind. You will present your ideas in rounds. At the end of rounds, there is a voting period to allow other users to vote on your opinions. After all, the most voted user wins the debate. If you already changed your mind and gave up, you can anytime finish the debate and let the opponent win. I also added a point system for win and loss but it is not effective right now because I did not finalize the rank system yet.

### Built With
* [React Native](https://reactnative.dev/)
* [Expo](https://expo.io/)
* [Firebase](https://firebase.google.com/docs/web/setup)
* [React Navigation](https://reactnavigation.org/)
* [Formik](https://formik.org/docs/overview)
* [date-fns](https://date-fns.org/)
* [react-native-snap-carousel](https://github.com/archriss/react-native-snap-carousel)
* [react-native-notifier](https://github.com/seniv/react-native-notifier)
* [react-native-collapsible](https://github.com/oblador/react-native-collapsible)

<!-- Remaining content stays unchanged except the repo URL -->
## Getting Started

### Prerequisites

* expo-cli
```sh
npm install expo-cli --global
```

### Installation

1. You need a firebase configuration file. Contact me to get a test configuration file. Without that config, firebase will not work.
2. Clone the repo
```sh
git clone https://github.com/milanbhatiya59/letusdebate.git
```
3. Install NPM packages
```sh
npm install
```
4. Put your filebase.config.js file to `src/consts/`

5. Start the expo metro bundler
```sh
npm start
```

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be, learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
