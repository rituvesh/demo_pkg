# demo_pkg
demo_pkg

-- run below commands to create very basic npm package
-- login to your npm account
npm adduser
npm login

-- Create basic files and directory 

mkdir demo_pkg
cd demo_pkg
touch package.json

-- add below to package.json 
{
  "name": "@rituvesh/demo_pkg",
  "version": "1.0.0"
}

-- finally publish it public 
npm publish --access=public


-- and see the package at 

https://www.npmjs.com/package/@rituvesh/demo_pkg
