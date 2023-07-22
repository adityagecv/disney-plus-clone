# disney-plus-clone
This is a clone of disney hotstar (2021). Live demo: https://aditya-gec-vaishali-disney-clone.netlify.app/


# Getting Started

## Requirements

1. node (v14.0.0)
2. yarn (1.22.19)
3. git (optional)


## Install dependencies

To install the dependencies run the following command:

```bash
yarn # or yarn install
```

## To run in development mode

First you need to create an `.env` file in the root directory with the following configuration:

```.env
REACT_APP_API_KEY=<YourKeys>
REACT_APP_AUTH_DOMAIN=<YourKeys>
REACT_APP_PROJECT_ID=<YourKeys>
REACT_APP_STORAGE_BUCKET=<YourKeys>
REACT_APP_SENDER_ID=<YourKeys>
REACT_APP_APP_ID=<YourKeys>
REACT_APP_MEASUREMENT_ID=<YourKeys>
```

Replace your key with the keys you have on you firebase console.

To run in development mode run the following command:

```bash
yarn start
```

visit [http://localhost:3000](http://localhost:3000).

## To build

Run the following command to build

```bash
yarn build
```

# LICENSE
This project is licensed under MIT.
