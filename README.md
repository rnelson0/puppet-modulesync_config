# ModuleSync Configs

Module sync configurations for Rob Nelson's Puppet modules

## How to use it

Installation:

```bash
$ bundle install
$ bundle exec msync update --help
```

Examples
--------

module sync one specific module:

```
msync update -f {module_name}
```

module sync one module and review changes before submitting changes:
```
$ msync update -f {module_name} --noop
$ cd modules/{module_name}
# edit then git commit/push
```
