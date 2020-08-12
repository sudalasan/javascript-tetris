# Tetris on Ainize!

### Step.1 Fork javascript-tetris

Fork this repo and check your forked repo
`https://github.com/${YOUR-GITHUB-ID}/javascript-tetris`

![](https://raw.githubusercontent.com/ainize-team/javascript-tetris/master/res/fork-repo.gif)


### Step.2 Create Dockerfile, and paste below code in the Dockerfile
```
FROM nginx:alpine

COPY www /www
COPY nginx.conf /etc/nginx/conf.d/default.conf

EXPOSE 80

CMD (tail -F /var/log/nginx/access.log &) && exec nginx -g "daemon off;"
```

![](https://raw.githubusercontent.com/ainize-team/javascript-tetris/master/res/create-dockerfile.gif)

### Step.3 Sign up and apply beta test at [Ainize.ai](https://ainize.ai)

### Step.4 Deploy Tetris on Ainize ([Tutorial](https://ai-network.gitbook.io/ainize-tutorials/ainize/hello-world#ainize-steps))

1. Enter your Github repo url, `https://github.com/${YOUR-GITHUB-ID}/javascript-tetris`
2. Add 'master' branch
2. Set port as 80

![](https://raw.githubusercontent.com/ainize-team/javascript-tetris/master/res/deploy.gif)

### Step.5 Enjoy tetris

https://master-javascript-tetris-laeyoung.endpoint.ainize.ai/ (change __laeyoung__ to __YOUR-GITHUB-ID__)

and update __Run on Ainize__ button as yours

[![Run on Ainize](https://ainize.herokuapp.com/static/images/run_on_ainize_button.svg)](https://ainize.web.app/redirect?git_repo=github.com/Laeyoung/javascript-tetris)


Javascript Tetris
=================

An HTML5 Tetris Game

 * [play the game](http://codeincomplete.com/projects/tetris/)
 * read a [blog article](http://codeincomplete.com/posts/2011/10/10/javascript_tetris/)
 * view the [source](https://github.com/jakesgordon/javascript-tetris)

>> _*SUPPORTED BROWSERS*: Chrome, Firefox, Safari, Opera and IE9+_

License
=======

[MIT](http://en.wikipedia.org/wiki/MIT_License) license.
