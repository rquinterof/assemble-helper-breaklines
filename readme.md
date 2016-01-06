# assemble-helper-breaklines

This helper allows you transform the regular breakline notation `\n`, into html tag `<br />`, if it's present on the data-json file.


## Install

- Install the module and save to devDependcies
``` 
$ npm install assemble-helper-breaklines --save-dev
```

- Add a pattern or the entire name to use that module in the options
```
options: { helpers: ['*-helper-breaklines'] } }
```

- Enjoy


## Usage

```hbs
<p>{{breaklines textdata}}</p>
```

## Example

### JSON file with a regular breakline notation (\n)

```json
[{
	"user-nickname": "R.Quintero",
	"user-location": "",
	"review-text": "this helper 'helps' me a lot \n and I can used it EVERYWHERE!",
	"rating": 5
}]
```

## License

MIT © [Rolando Quintero](http://web2.us)
