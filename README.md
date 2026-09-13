# react-quill

> A Quill component for React.

---

## Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Repository Structure](#repository-structure)
4. [Key Components](#key-components)
5. [Setup & Installation](#setup--installation)
6. [Running the Application](#running-the-application)
7. [Infrastructure & CI/CD](#infrastructure--cicd)
8. [Contributing](#contributing)

---

## Overview

**react-quill** is part of the [Unacademy](https://github.com/unacademy) engineering ecosystem.

A Quill component for React.

**Topics / Tags:** `approvers-1`

---

## Tech Stack

| Attribute | Value |
|-----------|-------|
| **Primary Language** | JavaScript |
| **Framework / Platform** | React |
| **Package Manager** | npm / yarn |

### Dependencies

**Runtime Dependencies:**
- `@types/quill`
- `lodash`
- `quill`

**Dev Dependencies:**
- `@types/chai`
- `@types/lodash`
- `@types/mocha`
- `@types/react`
- `@types/react-dom`
- `@types/sinon`
- `blanket`
- `chai`
- `chai-enzyme`
- `cheerio`


---

## Repository Structure

```
react-quill/
├── .github
├── .gitignore
├── .prettierrc
├── .travis.yml
├── CHANGELOG.md
├── LICENSE
├── README.md
├── cypress.json
├── demo/
│   ├── index.html
│   ├── index.js
│   ├── quill.snow.css
│   ├── react-quill.js
│   ├── test.html
├── package.json
├── src
├── test/
│   ├── index.js
│   ├── index.spec.js
│   ├── polyfills
│   ├── setup.js
│   ├── utils.js
├── tsconfig.json
├── webpack.config.js
├── yarn.lock
```

---

## Key Components

Below is an analysis of the key files and modules:

| File / Directory | Purpose |
|-----------------|---------|
| `CHANGELOG.md` | Source file |
| `LICENSE` | Source file |
| `README.md` | Source file |
| `cypress.json` | Source file |
| `demo/index.html` | Source file |
| `demo/index.js` | Source file |
| `demo/quill.snow.css` | Source file |
| `demo/react-quill.js` | Source file |
| `demo/test.html` | Source file |
| `package.json` | Source file |
| `src/index.tsx` | Source file |
| `test/index.js` | Source file |
| `test/index.spec.js` | Source file |
| `test/polyfills/MutationObserver.js` | Source file |
| `test/polyfills/getSelection.js` | Source file |
| `test/setup.js` | Source file |

> **Note:** Only the first 20 non-trivial files are listed. See the repository tree above for the complete structure.

---

## Setup & Installation

### Prerequisites

- Git (`git --version`)
- JavaScript runtime installed



### Steps

```bash
# 1. Clone the repository
git clone git@github.com:unacademy/react-quill.git
cd react-quill

# 2. Install dependencies
npm install      # or yarn install
```

### Available Scripts

```bash
# build
npm run build   # npm run build:lib && npm run build:dist && npm run build:css

# build:lib
npm run build:lib   # tsc

# build:dist
npm run build:dist   # webpack

# build:css
npm run build:css   # cpx 'node_modules/quill/dist/quill.*.css' dist

# watch
npm run watch   # tsc --watch

# pretest
npm run pretest   # npm run build

# test
npm run test   # npm run test:unit && npm run test:coverage && npm run test:browser

# test:unit
npm run test:unit   # mocha --recursive --require=./test/setup.js -R spec test/index

# test:coverage
npm run test:coverage   # mocha --recursive --require=./test/setup.js -R mocha-text-cov test/index

# test:browser
npm run test:browser   # cypress run

```


---

## Running the Application

_Refer to the project's build system or CI configuration._

---

## Infrastructure & CI/CD

- Test suite present — run tests before submitting PRs

---

## Contributing

1. Create a feature branch: `git checkout -b feat/your-feature`
2. Commit your changes: `git commit -m "feat: describe your change"`
3. Push and open a PR targeting `master`
4. Ensure all CI checks pass before requesting review

---

## Original README (Excerpt)

> ReactQuill [![Build Status](https://travis-ci.org/zenoamaro/react-quill.svg?branch=master)](https://travis-ci.org/zenoamaro/react-quill) [![npm](https://img.shields.io/npm/v/react-quill.svg)](https://www.npmjs.com/package/react-quill)
[![npm downloads](https://img.shields.io/npm/dt/react-quill.svg?maxAge=2592000)](http://www.npmtrends.com/react-quill)
==============================================================================

A [Quill] component for [React].

See a [live demo] or [Codepen](http://codepen.io/alexkrolick/pen/xgyOXQ/left?editors=0010#0).

[Quill]: https://quilljs.com
[React]:

---

*This README was auto-generated on 2026-09-14 by the Unacademy repo-summarizer tool.*
*For corrections or additions, edit this file directly or open an issue.*
