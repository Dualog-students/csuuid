# __CSUUID__

What this package does:

* Converts a base64 encoded C# GUID in MongoDB to a string GUID.
* Converts a string GUID to a base64 encoded C# GUID


## __Installation__

Clone this repo and run: 

```bash
$ npm install -g .
```

## __Usage__

Convert string GUID to base64:
```bash
csuuid -u "ff3b9053-b735-4562-812c-a2ba66dfc4ec"
U5A7/zW3YkWBLKK6Zt/E7A==   
```

Convert base64 to GUID string: 
```bash
csuuid -b "U5A7/zW3YkWBLKK6Zt/E7A=="
ff3b9053-b735-4562-812c-a2ba66dfc4ec
```