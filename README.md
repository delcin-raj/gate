# Dev workflow

We are using tailwindcss.

```bash
npx tailwindcss -i ./src/css/input.css -o ./dist/output.css --watch
```

The above command will automatically update the `output.css` file for any change
that you make to `index.html`.

Open `index.html` in a webbrowser and refresh for the change to reflect.
