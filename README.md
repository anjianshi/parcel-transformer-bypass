# parcel-transformer-bypass

Skip files from transform.  
(These files will output originally.)

## Installation

```shell
npm i -D parcel-transformer-bypass
```

or use `yarn`

```shell
yarn add --dev parcel-transformer-bypass
```


## Configuration

Add a `.parcelrc` into your project root directory (next to package.json):

```json
{
  "extends": "@parcel/config-default",
  "transformers": {
    "files-to-bypass/*.*": ["parcel-transformer-bypass"]
  }
}
```
