<div id="container">
  <h1 id="header">muhashi</h1>
</div>


<style>
  /**
    Typewriter effect by Kevin Powell:
    Copyright (c) 2024 by Kevin (https://codepen.io/kevinpowell/pen/ExWZzmm)

    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
  */
  :root {
    --bg-color: #fff;
    --typewriterSpeed: 1s;
    --typewriterCharacters: 7;
  }

  #container {
    display: flex;
    flex-direction: row;
    justify-content: center;
    width: 100%;
    align-items: center;
  }

  h1 {
    position: relative;
    font-family: "Source Code Pro", monospace;
    position: relative;
    width: max-content;
  }

  h1::before,
  h1::after {
    content: "";
    position: absolute;
    top: 0;
    right: 0;
    bottom: 0;
    left: 0;
  }

  h1::before {
    background: var(--bg-color);
    animation: typewriter var(--typewriterSpeed)
      steps(var(--typewriterCharacters)) 1s forwards;
  }

  h1::after {
    width: 0.125em;
    background: black;
    animation: typewriter var(--typewriterSpeed)
        steps(var(--typewriterCharacters)) 1s forwards,
      blink 1s steps(var(--typewriterCharacters)) 5 forwards;
  }

  @keyframes typewriter {
    to {
      left: 100%;
    }
  }

  @keyframes blink {
    0%, 49% {
        opacity: 1;
    }
    50%, 100% {
        opacity: 0;
    }
  }
</style>