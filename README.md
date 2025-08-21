# TypeScript_Learning
##Initialize Node.js Project (Optional but Recommended):
    Open the integrated terminal in VS Code (Ctrl+` or "Terminal > New Terminal").
    Run npm init -y to create a package.json file, which manages project dependencies.

##Install TypeScript:
    In the terminal, install TypeScript globally or as a development dependency:
        **Global: npm install -g typescript **(allows tsc command anywhere)
        Local: npm install --save-dev typescript (recommended for project-specific versions)

##Initialize TypeScript Configuration:
    Create a tsconfig.json file to configure the TypeScript compiler. In the terminal, run: tsc --init
    This generates a tsconfig.json file with default settings. You can customize options like target (output JavaScript version), module (module system), and outDir (output directory for compiled JavaScript).

##Create Your First TypeScript File:
    In your project folder, create a new file named index.ts (or any other .ts extension).
    Add some basic TypeScript code, for example:
        let message: string = "Hello, TypeScript!";
        console.log(message);

##Compile TypeScript to JavaScript:
    In the terminal, compile your TypeScript file: tsc index.ts
    This will generate a index.js file (or whatever your outDir specifies) in the same directory, containing the compiled JavaScript.

##Run the JavaScript File:
    Execute the compiled JavaScript file using Node.js: node index.js
    You should see the output of your console.log in the terminal.

Optional: Running TypeScript Directly with ts-node

For a more streamlined development workflow, you can install 'ts-node' to run TypeScript files directly without a separate compilation step:
        Install ts-node: npm install --save-dev ts-node
        Run TypeScript: npx ts-node index.ts

This allows you to execute your .ts files directly, which is convenient for development and testing.