# assemble-helper-breaklines

This helper allows you transform the regular breakline notation `\n`, into html tag `<br />`, if it's present on the data-json file.


## Install

- Install the module and save to devDependcies
``` 
$ npm install assemble-helper-breaklines --save-dev
```

- Add the module name into the Gruntfile.js options
```
options: { helpers: ['*-helper-breaklines'] } }
```

- Enjoy


## Usage

```hbs
<p>{{breaklines textdata}}</p>
```

## Example

#### JSON file with a regular breakline notation (\n)

```json
[{
	"user-nickname": "R.Quintero",
	"user-location": "",
	"review-text": "this helper 'helped me' a lot \n and I can use it EVERYWHERE!",
	"rating": 5
}]
```

Result

```html
	<p> this helper 'helped me' a lot <br /> and I can use it EVERYWHERE! </p>
```


## Related info

* [grunt-init-assemble](https://github.com/assemble/grunt-init-assemble): Initialize new Assemble projects, with example mixins, helpers, templates and data.
* [handlebars-helpers](https://github.com/assemble/handlebars-helpers)
* [Assemble's documentation](http://assemble.io)
* [assemble-less](https://github.com/assemble/assemble-less)
* [assemble-examples](https://github.com/assemble/assemble-examples)


## Author

**[Rolando Quintero](http://github.com/rquinterof)**

+ [http://twitter.com/rquinterof](http://twitter.com/rquinterof)
+ [http://github.com/rquinterof](http://github.com/rquinterof)


## Copyright and license

Copyright 2016 & MIT © [Rolando Quintero](http://web2.us)
