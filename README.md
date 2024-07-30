# Load paths demo

Demoing how to configure [load paths](https://sass-lang.com/documentation/cli/dart-sass/#load-path) with the Sass CLI, and have them work in [Some Sass](https://github.com/wkillerud/some-sass) as well.

## Settings

For this to work, use the `somesass.loadPaths` setting:

```json
{
	"somesass.loadPaths": ["shared/"]
}
```

## Try it yourself

Clone the repo and run `npm install`, then `npm test` to run the Sass compiler with a load path.
