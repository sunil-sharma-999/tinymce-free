### Instal tech specific binding for tinymce

```bash
pnpm i @tinymce/tinymce-react
```

### Install tinymce@6 since it has MIT license

```bash
pnpm i tinymce@6
```

### Copy tinymce package to public folder or anywhere it can be accessed

```bash
cp -r ./node_modules/tinymce/ ./public/"
```

### Use tinymceScriptSrc (check docs for specific property in other bindings) to point to the tinymce.min.js file

if deployed on remote server, provide url

```jsx
tinymceScriptSrc={"/tinymce/tinymce.min.js"}
```

Now, tinymce can be used in the app without API key
