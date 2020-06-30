##Executar
```
$ npm install
```
```
$ node index.js
```


##Credentials format

###Algorithmia

File: algorithmia.json

```
{
  "apiKey": "sim8As72h56j3mBYqEOSHfLE4k81"
}
```

###Watson Natural Language Understanding

File: watson-nlu.json

```
{
  "apikey": "Qynm-JBOd9m7JqEAFSvSt4feydYO4Pt0xYvAfaNEY2LW",
  "iam_apikey_description": "Auto generated apikey during resource-key operation for Instance - crn:v1:bluemix:public:natural-language-understanding:us-south:a/ffcb2c250e19bc335de2e9f1533711c8:4423b565-1e77-4d4c-a56e-656b3af7ac0d::",
  "iam_apikey_name": "auto-generated-apikey-27b6655f-6a69-40ba-a46a-60ae25b6d10a",
  "iam_role_crn": "crn:v1:bluemix:public:iam::::serviceRole:Manager",
  "iam_serviceid_crn": "crn:v1:bluemix:public:iam-identity::a/ffcb2c250e19bc335de2e9f1533711c8::serviceid:ServiceId-3b990ca3-62e6-4445-b303-84239f956d01",
  "url": "https://gateway.watsonplatform.net/natural-language-understanding/api"
}
```

###Custom Search API

File: google-search.json

```
{
  "apiKey": "API_KEY_AQUI",
  "searchEngineId": "ID_MECANISMO_DE_BUSCA"
}
```

## Dependências do ImageMagick

### Download da versão ImageMagick-7.0.10-22-Q16-HDRI-x64-dll
https://imagemagick.org/script/download.php

### Instalação
Durante a instalação selecionar as seguintes opções:
* add application directory to your system path
* Install FFmpeg
* Install legacy utilities (e.g. convert)


## Dependências do FFMPEG

### Videoshow
```
$ npm i videoshow
```
### FFmpeg
```
$ npm install ffmpeg
```
### @ffmpeg-installer/ffmpeg
```
$ npm install --save @ffmpeg-installer/ffmpeg
```
### @ffprobe-installer/ffprobe
```
$ npm install --save @ffprobe-installer/ffprobe
```
### Open
```
$ npm install open
```
##3 FFMPEG no windows
* Para fazer o download do ffmpeg, entre no site oficial do ffmpeg: https://www.ffmpeg.org/download.html

* Para utilizar o ffmpeg é necessário colocar a pasta ffmpeg\bin no PATH do Windows.
