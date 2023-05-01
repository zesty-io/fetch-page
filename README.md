# fetch-page
NPM Javascript package for fetching JSON data of a Zesty.io CMS page

# How to Install

Install from NPM or Yarn

```
npm install @zesty-io/fetch-page
```

# How to Use

Fetch page requires on the url of the page you're fetching data for and an env value with  Zesty Config JSON object. Having access to the URL from `window.location.pathname` or your routing middle ware is neccesary to feed the function. 


Zesty config value in your ENV are a requirement. An Example of the Zesty.io JSON object is below, you may also copy the JSON file from the `examples` folder. This value must be stringfied when it is saved. 

```
{
  "instance_zuid": "8-xyzxyz-7xyzxy",
  "stage": "https://xyz-dev.webengine.zesty.io",
  "production": "https://www.myproductiondomain.com",
  "stage_password": "",
  "auth": "",
  "src_dir": "",
  "options": {
    "skip_config_overwrite": false,
    "model_ignore_list": ["6-xyz"]
  },
  "runinstaller": true
}
```

