# hvrd.tk
Simple site to access Harvard University Library's EZproxy system

## Instructions
If you are trying to access an online resource that requires Harvard's institutional access, copy the URL and paste it into the box above. **Be sure to include _http://_.** You will be redirected to HarvardKey if you aren't currently signed in. You will then be redirected to your unlocked content.</p>

## Help!
If you are having difficulties using this site, please be sure that the site your are trying to access is part of one of [these databases](http://ezp-prod1.hul.harvard.edu/menu). If you're still having problems, feel free to contact me](mailto:benjamin_lee@college.harvard.edu?subject=hvrd.tk problem)

## How it works
Much like [huds.tk](http://huds.tk)([GitHub](https://github.com/Benjamin-Lee/huds.tk)), this site is a Flask app run on AWS Lambda via Zappa. It parses the URL submitted and redirects to the corresponding EZproxy URL. 