# kapitan-demo-child

This is a Kapitan repo that pull it's configuration from a parent 

* https://github.com/myspotontheweb/kapitan-demo

# Project Structure

```
├── compiled
│   └── my_target
│       ├── application.yaml
│       └── secret.yaml
├── inventory
│   ├── classes
│   │   └── common.yml
│   └── targets
│       └── my_target.yml
```

The single target "my_target.yml" generates two YAML files under the [compiled](compiled/my_target) directory.

The remote configuration is specified here:

* [inventory/classes/common.yml](inventory/classes/common.yml)

# Build

```
make
```
