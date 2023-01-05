This is a quick project that consumes the dog.ceo api (https://dog.ceo/dog-api/) and the dogs api from api-ninjas (https://api-ninjas.com/api/dogs) to provide detailed information on all breeds of dogs.
Clone the repository locally and create a settings.py file with the following variables and it will run smoothly:
BASE_DIR = Path(__file__).resolve().parent.parent
TEMPLATES_DIR = os.path.join(BASE_DIR,'templates')
STATIC_DIR = os.path.join(BASE_DIR,'static')
