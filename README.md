# Vue Advanced Workshop

This is the companion repository to the Vue Advanced Workshop.

Link to slides: https://goo.gl/U8TUqE

## Prerequisites

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en/) version 6+

## Setup

1. Clone this repo:

  ``` bash
  git clone https://github.com/yyx990803/workshop-vueconf18.git vue-workshop
  ```

2. Install dependencies (for automated tests):

  ``` bash
  cd workshop-vueconf18
  yarn
  # or
  npm install
  ```

## Usage

### Automated Tests

For each exercise there will be an automated test case to check if your implementation meets the requirements. To run the test for a given exercise (e.g. 1.1), run:

``` bash
yarn test 1.1
# or
npm test -- 1.1
```

You can also run the test in watch mode (which automatically re-runs the tests as you edit the files) with:

``` bash
yarn test 1.1 --watch
# or
npm test -- 1.1 --watch
```

### Solution Branche

This repo contains two branches: the `master` branch is where you will be working on the exercises, and the `solutions` branch contains the full solutions to each exercise.

To avoid switching back and forth between the working branch and solutions, you can look at the solutions on GitHub instead.
