# CDN
This is just my private cdn.

# Usage
```html
// load any GitHub release, commit, or branch
// note: we recommend using npm for projects that support it
https://cdn.jsdelivr.net/gh/aalfiann/cdn@version/path/to/file


// load jQuery from argon assets v1.0.0
https://cdn.jsdelivr.net/gh/aalfiann/cdn@1.0.0/argon/assets/vendor/jquery/jquery.min.js


// use a version range instead of a specific version
https://cdn.jsdelivr.net/gh/aalfiann/cdn@1.0/argon/assets/vendor/jquery/jquery.min.js

https://cdn.jsdelivr.net/gh/aalfiann/cdn@1/argon/assets/vendor/jquery/jquery.min.js


// omit the version completely to get the latest one
// you should NOT use this in production
https://cdn.jsdelivr.net/gh/aalfiann/cdn/argon/assets/vendor/jquery/jquery.min.js


// add ".min" to any JS/CSS file to get a minified version
// if one doesn't exist, we'll generate it for you

https://cdn.jsdelivr.net/gh/aalfiann/cdn@1.0.0/argon/assets/vendor/jquery/core.min.js


// add / at the end to get a directory listing
https://cdn.jsdelivr.net/gh/aalfiann/cdn/
```