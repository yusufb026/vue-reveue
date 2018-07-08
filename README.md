# revue

A reddit clone built with Vue.js and Flask

![Screenshot](https://raw.githubusercontent.com/Lanseuo/revue/master/screenshot.png)

## Installation

```bash
git clone https://github.com/Lanseuo/revue.git
cd revue
```

```bash
# install dependencies for client
cd client
npm install
```

```bash
# install requirements for server
cd ../server
pip3 install -r requirements.txt
```

```bash
nano config.py
```

```python
flask_secret_key = "CHANGEME"

image_upload_folder = ".../revue/server/images"
```

## Usage

```bash
cd client

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

```
cd server
python3 app.py
```

## Made with

- [Vue.js](https://vuejs.org/) - JavaScript Framwork
- [axios](https://github.com/axios/axios) - HTTP client
- [Flask](https://flask.pooco.com) - Web Framework
- [MongoEngine](https://github.com/MongoEngine/mongoengine) - Object-Document-Mapper for MongoDB

## Meta

Lucas Hild - [https://lucas-hild.de](https://lucas.hild.de)  
This project is licensed under the MIT License - see the LICENSE file for details
