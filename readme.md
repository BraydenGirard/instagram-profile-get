# Instagram profile get

Get image data from a public Instagram profile 

## Example usage

```javascript
var instagramProfileGet = require 'instagram-profile-get';

(async () => {
    try {
        const result = await instagram('crossfitcornwall');
        console.log(result);
    } catch(err) {
        console.log(err);
    }
})
```