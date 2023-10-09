# macho-ts

This is a rewrite of Fedor Indutny's macho nodejs library in TypeScript.

Simple and incomplete Mach-O binary format parser.

## Usage

```typescript
const data = fs.readFileSync(process.execPath);
const exec = macho.parse(data);
console.log(exec.filetype);
```

See test/ for more details

#### LICENSE

This software is licensed under the MIT License.

Copyright pancake, 2023
Copyright Fedor Indutny, 2014-2016.
