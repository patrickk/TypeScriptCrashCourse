# TypeScript Crash Course 

## Notes

- `tsc FILENAME.ts -w` will watch .ts file and update .js file when change/saved 

- Declare type of data as such:
```
let myString: string;
let myNum: number;
let myBool: boolean;
let myVar: any;
//Any is whatever data type 
myString = 'Hello World'; 
```

- For arrays: 
```
    //Only strings are allowed in strArr
    let strArr: string[];
    //Only num are allowed in numArr
    let numArr: number[];
    let boolArr: boolean[];
    //Another method 
    //This will only allow strings in arrays as //well
    let strArr1: Array<string>;
```


## TODO
- Continute at 18:58, goes over Tupules 

## Credit 
- https://www.youtube.com/watch?v=rAy_3SIqT-E