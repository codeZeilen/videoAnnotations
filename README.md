# observe.dev

A video annotation tool that can be used to annotate videos hosted on Youtube. The resulting annotations are stored in a Google Sheet.

## Requirements

This project runs with node `18.17` to `18.20`.

## Setup

- Install dependencies

```
yarn install
```

- Configure Google Sheets API key and client id

  - Copy .env.tmpl to .env
  - Fill in API key and client id

- Build the project

```
yarn run build
```

_Note:_ You might have to prepend `NODE_OPTIONS=--openssl-legacy-provider` to the build command in case you run into issues involving hash computations.

## Running

You can start the server using:

```
yarn run start
```

_Note:_ You might again have to prepend `NODE_OPTIONS=--openssl-legacy-provider` to the start command.
