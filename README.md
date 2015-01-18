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

[Install AWS EC2 API tools](http://docs.aws.amazon.com/AWSEC2/latest/CommandLineReference/set-up-ec2-cli-linux.html)

Build for xen
```
mirage configure --xen
make run
```

TODO: Create AMI and deploy it

## Resources

* [Mirage](https://github.com/mirage/mirage)
* [How to setup AWS EC2 API tools](http://docs.aws.amazon.com/AWSEC2/latest/CommandLineReference/set-up-ec2-cli-linux.html)