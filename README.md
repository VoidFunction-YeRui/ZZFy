# ZZFy

> This article was fully machine-translated (because I don't speak English)

## Warning
Don't download version 0.0.1 at all!!! (It won't even run)

## How to use it

Too Easy:
```python
import zzfy
print(zzfy.fy_etc(s="Some Texts...", o=()))
```
Then, you can get the translated text. (That can't be right)

Arguments:
- s: The English text you want to translate
- o: Do you want to output the process
  - `o` is a tuple parameter that can have two valid elements: `"s"` and `"r"`.
    - If `o` contains `"s"`, then the text will be output after removing some symbols and converting it to lowercase (and then it will be split into new words)
    - If `o` contains `"r"`, then a list of the words split into new ones will be output.

And then... that's it?  
Exactly, ZZFy is that simple!

## More features
You can customize the dictionary:

```python
import zzfy

dct = {}    # You can customize it
print(
  zzfy.fy_etc_(
    e=zzfy.split(
      s="...",
      dct=dct,
      vt=zzfy.VT,
      ct=zzfy.CT,
      o=()
    ),
    dct=dct,
    tdct=zzfy.TDCT  # For transliteration
  )
)
```
