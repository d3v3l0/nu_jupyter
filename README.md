# Jupyter Notebook support for Nushell

![Example of Jupyter running Nushell](jupyter_example.png)

This is a very(!) experimental kernel for Jupyter for running Nushell. It currently requires 0.11.1 or later.

To install and run the kernel:

```
> cd nu_jupyter
nu_jupyter> jupyter kernelspec install ../nu_jupyter --user
nu_jupyter> jupyter lab
```

Limitations:

* This currently is limited to single line commands to Nu. We'd like to lift this limitation in the future.
* State is not kept between runs. This is also something that will change in future versions.
