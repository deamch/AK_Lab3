# Lab №3

### Ключі, які пітримуються:
    -a, --all - shows options list
    -e, --echo - echo given text
    -h, --help => Виводить повідомлення допомоги.
    -v, --version => Виводить значення версії за замовчуванням.
    -s, --size => Може як і мати аргумети, так і не мати, Виводить аргумент у разі його наявності. 
    -f, --file => Потребує аргумети, виводить аргумент.

### Приклади виконання:
     >run -a --all
    Parameters list:
    -a or --all
    -e or --echo
    -h or --help
    -j or --just-do-it
    -s or --save
    You`ve specified help option, but help is deprecated. Use -j or --just-do-it instead...
    Short help option
    Pull yourself together man, you`re need no help.
---
     >run -e --echo
    You echoed this: Some text
    Saving data to = result.txt
---
     >run -h --help
    You`ve used help option.
    Unfortunatelly program is help-less :(
    Try -h or --help.
---
     >run --version
    You`ve used version option.
    Current version = 1.0.0.
    Try -v or --version.
---
     >run -s
    You`ve used size option without value
    Try -s or --size.
---
     >run -s1
    You`ve used size option with value 1
    Try -s or --size.
---
     >run -fHello
    You`ve used file option (value is needed).
    File = Hello
    Try -f or --file.
---
     >run -e
    Error.
    Error code: 404.
    You`ve used unknown option or didn`t clarify value for the existing one.
