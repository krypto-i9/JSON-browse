# BrowseJSON

Explore JSON files in CLI.

## Installation

Use npm to install browsejson

```bash
npm install -g browsejson
```

Use yarn to install browsejson

```bash
yarn global add browsejson
```

## Usage

```bash
browsejson [filepath]
```

If browsejson isn't a global package(not used -g flag) then use,

```bash
npx browsejson [filepath]
```

Replace [filepath] with file you want to open with browsejson.

## Examples

### Import files to browsejson

![alt text](https://i.ibb.co/pbjWLq9/browsejson-startup.png)

### help command

```
help
```

![help](https://i.ibb.co/sWCvwLk/browsejson-help.png)

### print command

```
print
```

![print](https://i.ibb.co/kXdf6gH/browsejson-print.png)

### print keys command

```
print keys
```

![print keys](https://i.ibb.co/4SkyNZ7/browsejson-print-keys.png)

### print keys pass command

```
print keys pass
```

![print keys pass](https://i.ibb.co/sQ3h8LL/browsejson-print-keys-pass.png)

### list all command

where [key] is key of JSON array.

```
list all [key]
```

![list all](https://i.ibb.co/bN7DDVT/browsejson-list-all-key.png)

### print clipboard command

clipboard stores results of previous operations

```
print clipboard
```

![print clipboard](https://i.ibb.co/mTx5Z4p/browsejson-print-clipboard.png)

### save clipboard command

write clipboard results to file.

```
save clipboard [filepath]
```

![save clipboard](https://i.ibb.co/jWYbTzv/browsejson-save-clipboard.png)

### cd command

navigate in JSON file.

```
cd [key]
```

navigate multiple key at a time

```
cd [key1>key2>key3]
```

navigate back

```
cd ..
```

![cd](https://i.ibb.co/dDmh9Yb/browsejson-navigate.png)

### set command

write existing key with new value or create new key and value.

```
set key_value [key] {value}
```

### remove command

remove key and value if exist.

```
remove [key]
```

![remove](https://i.ibb.co/bBn7gWf/browsejson-remove-key.png)

## Contributing

[Pull requests](https://github.com/krypto-i9/browsejson/issues) are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[CC0-1.0 License](https://choosealicense.com/licenses/cc0-1.0/)
