This is a simple example of the charm usage:

```
git clone git://github.com/rochacon/charms.git
cd charms
juju deploy --repository . local:gandalf
juju deploy mongodb
juju add-relation gandalf mongodb
juju expose gandalf
```
