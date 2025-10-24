# HOW TO INSTALL TYPESCRIPT 7

`npm install -D @typescript/native-preview`

`npx tsgo -v`

`npm install -D typescript` install typescript to generate tsconfig

`npx tsc --init`

configure the tsconfig.json

```json
{
      "compilerOptions": {
        "target": "esnext",
        "lib": ["esnext", "dom", "dom.iterable"],
        "module": "NodeNext",
        "strict": true,
        "skipLibCheck": true
      }
    }
```

If you are using Visual Studio Code, enable the experimental tsgo feature for better integration:
Open the command palette (Ctrl+Shift+P or Cmd+Shift+P).
Run "TypeScript Native Preview: Enable (Experimental)".
Alternatively, add "typescript.experimental.useTsgo": true to your JSON settings.
Write and compile TypeScript code:
Create your TypeScript files (e.g., index.ts) and then compile them using tsgo.
    `npx tsgo`
This will compile your TypeScript files using the new tsgo compiler.