# @studyportals/jsdoc-to-markdown@v1.0.2

<a href="https://www.npmjs.com/package/@studyportals/jsdoc-to-markdown" title="View this project on NPM" target="_blank"><img src="https://img.shields.io/npm/v/@studyportals/jsdoc-to-markdown.svg?style=flat" alt="NPM version" /></a>
<a href="https://www.npmjs.com/package/@studyportals/jsdoc-to-markdown" title="View this project on NPM" target="_blank"><img src="https://img.shields.io/npm/l/@studyportals/jsdoc-to-markdown.svg?style=flat" alt="NPM license" /></a>
<a href="https://www.npmjs.com/package/@studyportals/jsdoc-to-markdown" title="View this project on NPM" target="_blank"><img src="https://img.shields.io/npm/dm/@studyportals/jsdoc-to-markdown.svg?style=flat" alt="NPM downloads" /></a>
<a href="https://david-dm.org/studyportals/jsdoc-to-markdown" title="View this project on David" target="_blank"><img src="https://img.shields.io/david/studyportals/jsdoc-to-markdown.svg?style=flat" alt="Dependencies" /></a>
<a href="https://david-dm.org/studyportals/jsdoc-to-markdown" title="View this project on David" target="_blank"><img src="https://img.shields.io/david/dev/studyportals/jsdoc-to-markdown.svg?style=flat" alt="Development Dependencies" /></a>

Generate `README.md` based on package.json and corresponding `*.js` files.

<a name="module_@studyportals/jsdoc-to-markdown"></a>

## @studyportals/jsdoc-to-markdown
**Example**  
In the `"scripts"` section of `package.json`, add a `docs` task. For example:
```json
{
  "scripts": {
    "docs": "jsdoc2md"
  }
}
```

Now, project documentation is generated like so:

```sh
$ npm run docs
```

In node:
```JavaScript
const JsdocToMarkdown = require('@studyportals/jsdoc-to-markdown');
JsdocToMarkdown();
```
<a name="exp_module_@studyportals/jsdoc-to-markdown--JsdocToMarkdown"></a>

### JsdocToMarkdown() ⇒ <code>Date</code> ⏏
These properties from the package.json are used to build the documentation:
- <a href="https://docs.npmjs.com/files/package.json#name" target="_blank">name</a>
- <a href="https://docs.npmjs.com/files/package.json#version" target="_blank">version</a>
- <a href="https://docs.npmjs.com/files/package.json#repository" target="_blank">repository</a>
- <a href="https://docs.npmjs.com/files/package.json#description" target="_blank">description</a>
- <a href="https://docs.npmjs.com/files/package.json#main" target="_blank">main</a>
- <a href="https://docs.npmjs.com/files/package.json#directorieslib" target="_blank">directories.lib</a>

**Kind**: Exported function  
**Returns**: <code>Date</code> - The date when README.md is generated.  

_README.md generated at: Wed Jun 28 2017 13:09:47 GMT+0800 (China Standard Time)_