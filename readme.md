# Very good flask template
## contains:
### sqlalchemy
### CORS
# simple example

# Update DB create 
    with app.app_context():
        db.create_all()
        app.run(debug=True)

# Run:
    create a virtual enviroment
    py -m virtualenv env
# activate:
    env\script\activate
# prepare the environment
    pip install -r .\requirements.txt
    flask run