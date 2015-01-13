# Try Mirage OS

## Getting started

Check that we use OCaml >= 4.01.0 and < 4.02.0
```
opam switch 4.01.0
eval `opam config env`
```

Install Mirage
```
opam install mirage
```

### Unix

Build for unix
```
mirage configure --unix
make run
```

### Xen

Install AWS CLI tools
```
sudo pip install awscli
```

Build for xen
```
mirage configure --unix
make run
```

TODO: Create AMI and deploy it

## Resources

* [Mirage](https://github.com/mirage/mirage)
* [AWS CLI tools](http://aws.amazon.com/cli/)
