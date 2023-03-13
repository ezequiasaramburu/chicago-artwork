<h1 align="center">
  Chicago Art App
</h1>

<h4 align="center">A React Native app written in Typescript to browse among Chicago artworks.</h4>

<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-to-use">How To Use</a> •
  <a href="#dependencies">Dependencies</a> •
</p>

## Key Features

* IOS and Android support
* Backend integration
* Infinite scroll

## How To Use

```bash
# Clone this repository
$ git clone git@github.com:ezequiasaramburu/modakChallenge.git
# Install dependencies
$ yarn
# Install pods
$ cd ios && pod-install
# Run the app
$ yarn ios or yarn android
```

## Summary

In order to avoid errors I used TypeScript. I try to splice the code as much as possible to get cleaner code and more maintainable. Is the reason why I use the following folder structure
```
component
    components.tsx
    index.ts
    types.ts
    hooks.ts
    styles.ts
```
In the case of dependencies I tried the fewer as possible.
* react-navigation (Used to create a root stack for the navigation, useful if app stars growing)

Also I've implemented absolute paths in order to avoid long imports e.g: `../../../../Component/...` 


## Dependencies

This software uses the following open source packages:

- [react-navigation](https://reactnavigation.org/)

