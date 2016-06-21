# ![](favicon.ico) Password Generator

> a simple password generator for myself.

![qq20160621-0 2x](https://cloud.githubusercontent.com/assets/1147451/16234937/99630060-3805-11e6-90f2-c204d6581df5.png)

## Algorithm

- Information:

```json
{id: "username/email", app: "website/app"}
```

- 1Password:

Your origin password (maybe easy to remember) -> SHA-1 

- Generate Password:

information (JSON) + 1 password (SHA-1) -> Base64 -> substring(0, 8)