# Palindrome Checker

Enter a word to check whether it reads the same forwards and backwards.

## Overview

Palindrome Checker lets a user enter a word and determine whether it is a palindrome.

The browser sends the entered word to a Node.js server, which reverses the word and compares the two values without regard to capitalization. The result is then returned to the page and displayed to the user.

## Features

- Accepts a word from the user
- Checks the word without regard to capitalization
- Reverses and compares the submitted value
- Displays whether the word is a palindrome
- Uses a Node.js HTTP server and API endpoint to process the request

## Technologies

<p>
  <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" title="HTML">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML" width="40" height="40">
  </a>
  &nbsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" title="CSS">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS" width="40" height="40">
  </a>
  &nbsp;
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" title="JavaScript">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" width="40" height="40">
  </a>
  &nbsp;
  <a href="https://nodejs.org/" title="Node.js">
    <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" width="40" height="40">
  </a>
</p>

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/nilesleesmith/simply-check-a-palindrome.git
```

2. Open the project folder:

```bash
cd simply-check-a-palindrome
```

3. Start the Node.js server:

```bash
node server.js
```

4. Open the application in a browser:

```text
http://localhost:8000
```

No additional packages or installation steps are required.

## Live Site

https://simply-check-a-palindrome.onrender.com

## Screenshots

![Simply check a palindrome desktop view](.\screenshots\simply-check-a-palindrome-desktop.png)