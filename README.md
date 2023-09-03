# LMS Frontend 

### Setup instruction

1. Clone the project
```
    git clone https://github.com/bhishekthakur/lms-frontend-hn.git
```

2. Move into the directory

``` 
   cd lms-frontend-hn
```

3.install dependencies

```
   npm i
```

4. run the server

```
    npm run dev
```

1. install tailwind css
```
    npm install -D tailwindcss
```

2. create tailwind config file
  ````
     npx tailwindcss init
  ```

3. Add file extension to tailwind config file in the content property
```
    "./src/**/*.{html,js, jsx, ts, tsx}"
```

4. Add the tailwind directives at the top of the `index.css` file
```
    @taiwind base;
    @tailwind components;
    @tailwind utilities;
```