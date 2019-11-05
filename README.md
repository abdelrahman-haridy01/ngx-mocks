# NgxMocks

Best way to get a full fake REST API.
Make a Full fake REST API, MakePOST, PUT, PATCH or DELETE requests, Fake Register and login Api with jwt.

## How to use it?

Run `git clone https://github.com/Abdelrahman-haridy/ngx-mocks.git` for clone a repo. Then run `npm i` on project path after install all packages run `npm start`.Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
Use `http://localhost:3000/` for check Defualt API's by [getpostman](https://www.getpostman.com/). Also You can check defualt API's in `server/api.json` path.

## Custom API's

Edit `api.json` as your app requirments. Example
```json
{
    "users": [
        {
            "id": 1,
            "name": "Abhar",
            "email": "Abdelrahman.haridy01@gmail.com",
            "password": "123456a"
        },
        {
            "id": 2,
            "name": "Abdelrahman",
            "email": "Abdelrahman@abharworks.com",
            "password": "123456b"
        }
    ],
    "notes": [
        {
            "id": 1,
            "title": "text title",
            "description": "exp desc text",
            "userId": 1
        },
        {
            "id": 2,
            "title": "text title2",
            "description": "exp desc text3",
            "userId": 1
        },
        {
            "id": 3,
            "title": "text title3",
            "description": "exp desc text3",
            "userId": 2
        }
    ],
    "about": {
        "title": "About",
        "description": "exp abour text"
    }
}
```

## API's Example

```
POST   /auth/login      --> email, password
POST   /auth/register   --> name, email, password
GET    /users
GET    /notes/1
GET    /users/1/notes
POST   /notes
PUT    /notes/1
PATCH  /notes/1
DELETE /notes/1
```

## Further help

To get more help on the Angular go check out the [Angular](https://angular.io/).
To get more help on the JWT go check out the [JWT](https://jwt.io/).
To get more help on the Bootstrap go check out the [Bootstrap](https://getbootstrap.com/).
To get more help on json-server go check out the [json-server README](https://github.com/typicode/json-server/blob/master/README.md).

## Author

Abdelrahman Haridy - [AbharWorks](http://abharworks.com/)

