# Vietnamese-slug
Vietnamese Slug help you create slug from vietnamese words easily.
## Install
```js
npm install --save vietnamese-slug
```

## For example:
```js
var slug = require('vietnamese-slug');
var input = 'Đây là một tiêu đề tiếng việt';
var output = slug(input);
console.log(output);
// Output: day-la-mot-tieu-de-tieng-viet
```
The dash '-' is the default separator but you can choose what separator you want.

```js
var slug = require('vietnamese-slug');
console.log(slug('Đây là tiếng việt', '_'));
// Output: day_la_tieng_viet
``` 
More features will be updated soon.  
Thank you for your choosing. Happy coding.

God bless you!!!
