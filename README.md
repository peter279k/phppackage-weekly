# phppackages-weekly

A barebones PHP app that makes use of the [Silex](http://silex.sensiolabs.org/) web framework, which can easily be deployed to Heroku.

## Deploying

Install the [Heroku Toolbelt](https://toolbelt.heroku.com/).

```bash
$ git clone https://github.com/peter279k/phppackages-weekly.git
# or clone your own fork

$ cd phppackages-weekly
$ heroku create
$ git push heroku master
$ heroku open
```

or you can refer:

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## To do

- Complete the sample homepage.
- Complete the subscribe form page.
- Complete the weekly lists page.
- Complete the functionality of subscribing mailing lists.
- Complete the functionality of rendring weekly packages lists.
- complete the unit testing for this Web application...

## The data sources

- RSS: [Planet PHP](http://www.planet-php.net/)
- RSS: [PHPDeveloper.org](http://www.phpdeveloper.org/)
- RSS: [reddit.com/php](http://www.reddit.com/r/php/)
- RSS: [PHPBuilder](http://www.phpbuilder.com/)
- Weekly news: [PHHPWeekly](http://phpweekly.com/)

## Techniques

- frontend:semantic-ui and jQuery 3.0+
- backend :PHP(Silex framework) and Twig(PHP template engine)

