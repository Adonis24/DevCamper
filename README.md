# DevCamper

DevCamper API written in Node, Express and MongoDB

## Install Dependencies

```
npm install
```

## Run App

```
# Run in dev mode
npm run dev

# Run in prod mode
npm start
```

## import data

It takes the data from \_data/ and imports it into the DB

```
node seeder -import
```

## delete data

It cleans the whole DB by removing everything

```
node seeder -destroy
```
