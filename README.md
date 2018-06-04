"# Javascript - Typescript"
 
npm init -  create package.json
npm install typescript 
npm install typescript --save-dev
create one product.ts file and write the below code in it
==============
class product{
    name:string = 'blank';
    age:number = 18;
    sal:number=500;

    toString() : string{
        return "["+this.name+this.age+"]";
    }

}
============
run this - > tsc product.ts
it create the product.js file

to compilte all the file ts file = tsc 
it generate the product.js files

tsc --watch == automatically check the changes. and create the .js file

compile with npm

tsc --init  =  create the tsconfig.js file
 Modify the tsconfig.js  -     "outDir": "./dist",  
 
and modify the package.json - > 
  "scripts": {
    "test": "test",
    "build": "tsc --watch"
  },
  
  now run the   > npm run build 

  
  
  
==========================