---
title: "Install"
date: 2022-05-15T12:19:01-05:00
---

## The install command!

{{< note >}} You can use this flags on the: **install** command and the **add**
alias {{< /note >}}

| Flags           | Description                           |
| --------------- | ------------------------------------- |
| --host [host]   | Change from deno.land/x to other      |
| -s, --std [std] | Add a dependency from the std library |
| -h, --help      | The CLI help message                  |

DPM does not download files on the computer, only write the correct url on the
_dpm_imports.json_ file and make a experience of development like **NodeJS** and
**NPM or Yarn**

For install dependencies from the [deno.land/x](https://deno.land/x/) register
you need only write:

```
dpm install draco dlog2
```

For install dependencies from the [deno std](https://deno.land/std) register you
need only use this!

```
dpm install flag async http path --std
## You need put the name of the library and the flag -s or --std
```

For install dependencies from other host you need run:

```
dpm install example_dep --host nest.land
```

---

Made with ♥ in Ecuador and the World
