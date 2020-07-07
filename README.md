# Identicon

Generate identicons based on a given string.

It's based on [Github Identicons](https://github.blog/2013-08-14-identicons/).

## Usage Examples
To use this app, just call `Identicon.generate/1`:

```shell
iex> Identicon.generate("zeller")
```
A 250x250 `png` file, the identicon, will be create at the project's root directory:

![](https://drive.google.com/uc?export=view&id=1hs9jyARhz10YJ1Dm7mjVvNuusyM2-V-0)


The same string will aways generate the same identicon.
