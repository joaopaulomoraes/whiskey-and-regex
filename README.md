# 🥃 Whiskey & `/regex/`

The main objective of this project is to help you understand regular expressions in a relaxed way, with clear examples and practical approaches, accompanied by a shot of whiskey or similar, but you can follow with gin and tonic as well.

## Metacharacters

| Metacharacter | Name           | Characteristic | Function                        |
|:-------------:|:---------------|:---------------|:--------------------------------|
|      `.`      | Dot            | Represent      | Any character                   |
|     `[]`      | List           | Represent      | List of allowed characters      |
|     `[^]`     | Denied list    | Represent      | List of prohibited characters   |
|      `?`      | Optional       | Quantify       | Zero or one                     |
|      `*`      | Asterisk       | Quantify       | Zero, one or more               |
|      `+`      | Plus           | Quantify       | One or more                     |
|     `{}`      | Curly brackets | Quantify       | From one value to another       |
|      `^`      | Circumflexus   | Anchor         | Start of line                   |
|      `$`      | Dollar sign    | Anchor         | End of line                     |
|     `\b`      | Border         | Anchor         | Beginning or end of word        |
|      `\`      | Escape         | Other          | Make something literal          |
|     `\|`      | Or             | Other          | Or one or the other             |
|     `()`      | Group          | Other          | Delimits a group                |
|     `\1`      | Rearview       | Other          | Text married in a certain group |

### Dot `.`

The dot is a wildcard character that matches anything, including itself.

```js
/whisk.y/
```

With its traditional combination of rye [whiskey](#dot), sweet vermouth, and bitters, the Manhattan is an icon in the [whisk*y](#dot) world. It is to [whiskey](#dot) what the martini is to gin and the base for countless cocktails. You can make it with bourbon, Canadian whisky, or any other style, and it's a splendid recipe to use when trying out any new-to-you brand of [whisk.y](#dot).

#### Time to relax

```js
/9.m/
```

[9pm](#time-to-relax) is a good time to drink whiskey, but it's not a good time to drink coffee, in which case [9am](#time-to-relax) would be a more appropriate time. [9pm](#time-to-relax) can also be a good time for a cup of tea if you've already exceeded your daily whiskey quota.

#### Time to walk

```js
/ca./
```

It is not recommended to drive a [car](#time-to-walk) if you drink a shot of whiskey, or any other alcoholic beverage. Maybe it's better to enjoy your [cat](#time-to-walk)'s company or prepare a new shot.

## License

This project is licensed under the MIT License.
