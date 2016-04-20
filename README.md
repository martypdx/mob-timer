# mob-timer

Simple web page for running a timer to switch during pair (or mob) prgramming.

Clone this repository or cut and paste the `index.html`. Use your favorite 
static web server or open the file if your OS/browser supports it.

The browser will throw up an alert when timer goes off which should bring it into focus
even if your in your IDE.

#### example install

```sh
> git clone https://github.com/martypdx/mob-timer.git
...
> cd mob-timer
> npm i -g http-server //simple static server
...
> http-server -o
```

#### change the interval

Default is 20 minutes. Set the [`minutesPer`](https://github.com/martypdx/mob-timer/blob/master/index.html#L43) 
variable to change.

#### green and red orbs

As each iterations begins, a green circle is added to the page. After three circles, they will appear red. 
This is intended to let you know you need to _take a break_ (then just refresh page to start again).

#### es6?

There's a pure es6 version available on the [`es6ify branch`](https://github.com/martypdx/mob-timer/blob/es6ify/index.html)
