# Template for creating a Excel Add-in in React with Functions

A scaffolding template for a basic Excel Add-in in Typescript

- Functions included out of the box
  - Default function namespace "REX" - so all functions can be invoked by "REX.{FUNCTION_NAME}"
  - You can change it in manifest.xml under `<bt:String id="Functions.Namespace" DefaultValue="REX"/>` property

- React with Microsoft's default FluentUI components