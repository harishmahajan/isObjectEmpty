#check object is empty or not

# npm i isemptyobjectcheck --save

### Installation in project
```bash
npm install react-native-simple-encryption --save
```

# Example
```
var checkObject = require('isemptyobjectcheck');

var datas1=[2,5,1,7];
var datas2=[];
var datas3={"Name":"Harish"};
var datas4={};

console.log(checkObject.isEmpty(datas1)); // Return false
console.log(checkObject.isEmpty(datas2)); // Return true
console.log(checkObject.isEmpty(datas3)); // Return false
console.log(checkObject.isEmpty(datas4)); // Return true
````

# Donate

https://www.paypal.me/HarishMahajan