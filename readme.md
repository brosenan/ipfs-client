# TOC
   - [add(stream, cb(err, hash))](#addstream-cberr-hash)
   - [cat(hash)](#cathash)
<a name=""></a>
 
<a name="addstream-cberr-hash"></a>
# add(stream, cb(err, hash))
should return a hash of the given stream.

```js
$S.run(gen, done);
```

<a name="cathash"></a>
# cat(hash)
should return a readable stream producing the file underlying the hash.

```js
$S.run(gen, done);
```

should report error if hash is not found.

```js
$S.run(gen, done);
```

