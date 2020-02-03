# Stock Trading Web App
A stock trading web app built on Flask with an aim to learn about backends. 

- Buy, sell, check price of stocks in realtime
- View portfolio of your stocks
- View history of purchase and sale of stocks

### My Learning Objectives:

I'll be following Miguel Grinberg's Mega-Tutorial practices for structuring my app with my taste sprinkled in some places.

Topics I plan to master by the end of this project:

- [x] caching in detail
- [x] databases, ORMs
- [ ] deployment to cloud
- [ ] cookies, session management
- [ ] authentication, authorization
- [ ] WSGI servers and werkzeug (flask is based on werkzeug)
- [ ] web security - eliminate OWASP top ten security risks from the app 
- [ ] REST APIs in detail - Read Roy Fielding's paper
- [ ] client side validation via JavaScript, AJAX
- [ ] scalability, testing, CI & CD
- [ ] QA

### Quick Development Setup

Fork. Clone. Make sure you `cd` to `stock-trading-app` directory. Set upstream and origin.

Install or update to the latest version of `Python` if you haven't already.

Time to get started. Feel free to create an issue if you get stuck or if you need help :)

```
# Installs pipenv globally
pip install pipenv

# The below command installs dependencies in a pipenv's virtualenv
pipenv install

# Activates virtualenv subshell
pipenv shell

# Runs the app, served at http://127.0.0.1:5000 by default
flask run
```
