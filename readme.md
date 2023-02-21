# flask template
## contains:
### sqlalchemy
### CORS
# simple example

##### live site
# on netlify
https://prismatic-centaur-f28a5d.netlify.app/
# on github
https://narnav.github.io/flask_sqlachemy_cors_render/


# Update DB create 
    with app.app_context():
        db.create_all()
        app.run(debug=True)

# Run on mac:
    create a virtual enviroment
    mac: python3 -m venv .venv 
    pc: py -m virtualenv env
# activate:
    mac: source .venv/bin/activate
    pc: .env\script\activate
# prepare the environment
    pip install -r .\requirements.txt
    flask run