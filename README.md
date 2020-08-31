[![Netlify Status](https://api.netlify.com/api/v1/badges/6d27f2e6-fd25-4042-80f2-0a54171d9b31/deploy-status)](https://app.netlify.com/sites/dataforgoodisrael/deploys)

# Chalom!
Here is the source code of our **previous** website ([DataforGoodIsrael.com](https://DataforGoodIsrael.com)).

Now it looks different 😁 but we keep it as a reference if we want to build another website with [Hugo](https://gohugo.io/) & [Netlify](https://www.netlify.com/).

## Installation
1. Make sure to install [install hugo](https://gohugo.io/getting-started/installing/).
For linux, just:
```shell
sudo apt-get install hugo
```
2. Clone the repo:
```shell
git clone https://github.com/DataforGoodIsrael/dataforgoodisrael.github.io.git
```

## Usage
Go in the created directory and run the server offline:
```shell
cd dataforgoodisrael.github.io
hugo server
```

## Update the hugo theme
```
git submodule update --init --recursive
git submodule foreach git pull origin master
```

## Deployment
Every push to the master branch will automatically be deployed by [netlify](https://www.netlify.com/).

## License
[MIT](LICENSE).
