## Tilwindcss setup

Step 1: Run the following commands

```
npm install -D tailwindcss
npx tailwindcss init
```

Step 2: Update tailwind.config.js file to include this line:
```
content: ["*.{ht,js}"],
```

Step 3: create src/input.css to include:
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Step 4: Include the src/output.css file to html

step 5: Run the following command:
```
npx tailwindcss -i ./src/input.css -o ./src/output.css --watch
```