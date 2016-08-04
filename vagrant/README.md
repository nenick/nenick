# Jekyll devlopment environment

### Start Vagrant

```
vagrant up
```

### Start Jekyll

```
vagrant ssh -c "jekyll server -s /srv/website --watch -P 8124 --host 0.0.0.0"
```

### Access generated sites

```
http://127.0.0.1:1234
```