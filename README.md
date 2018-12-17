# exif-image
 Get EXIF ​​data from image
 
 ## Installation 
```sh
npm install exif-image --save
yarn add exif-image
bower install exif-image --save
```

## Usage
### Javascript
```javascript
var exif_image = require('exif-image');
var boys = exif_image.getOrientation(file, callback);

function callback(data) {
 console.log(data);
}

```
```sh
Output should be 1 | 2 | 3 ... 8 -> This is equivalent to the EXIF code in the image
```
### TypeScript
```typescript
import { getOrientation } from 'exif-image';
getOrientation(file, callback);

function callback(data) {
 console.log(data);
}

```
```sh
Output should be 1 | 2 | 3 ... 8 -> This is equivalent to the EXIF code in the image
```
