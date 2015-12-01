# apidocs
queryManagerAPIdocs

###To Install:

Change the following 3 entries:
- in `api.json` file change `host` accordingly
- in `index.html` file change the url in the [line 36](https://github.com/3cixty/apidocs/blob/master/index.html#L36) to reflect the `host`
- in `swagger-ui.js` file find 

  ``` javascript
  showPetStore: function(){
    this.trigger('update-swagger-ui', {
      url:'https://<host>/api.json'
    });
  },
  ```
  and change the `url` to reflect the `host`.
- rename `apidocs` to `httpdocs`  
- copy the folder `apidocs` to `/var/www/apidocs.3cixty.com/`

###To Access

Use `https://apidocs.3cixty.com`

