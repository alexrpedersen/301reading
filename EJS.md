# EJS

## What is EJS
### EJS stands for Embedded JavaScript, which describes it well: it is essentially HTML with JavaScript-based features embedded for templating. This lets you use iterate over your flexible metadata, include partials, and more.

#### EJS is familiar, as it’s primarily HTML, but with additional features that allow you to efficiently reuse pieces of your project. If you have an existing HTML project, all you have to do is rename the file with the .ejs extension, and you can start using any of EJS’ features.

## Controls for EJS

#### Control flow with <% %>
#### Escaped output with <%= %> (escape function configurable)
#### Unescaped raw output with <%- %>
#### Newline-trim mode ('newline slurping') with -%> ending tag
#### Whitespace-trim mode (slurp all whitespace) for control flow with <%_ _%>
#### Custom delimiters (e.g., use <? ?> instead of <% %>)