# 🧪 JavaScript Regex Cheat Sheet

A handy reference for regular expressions in JavaScript.

---

## 🔤 Character Sets (`[...]`)

| Pattern        | Matches                    |
| -------------- | -------------------------- |
| `[abc]`        | a, b, or c                 |
| `[^abc]`       | NOT a, b, or c             |
| `[a-z]`        | any lowercase letter       |
| `[A-Z]`        | any uppercase letter       |
| `[0-9]`        | any digit                  |
| `[a-zA-Z0-9 ]` | letters, digits, and space |

---

## 🔢 Quantifiers

| Pattern | Meaning               |
| ------- | --------------------- |
| `*`     | 0 or more times       |
| `+`     | 1 or more times       |
| `?`     | 0 or 1 time           |
| `{n}`   | Exactly n times       |
| `{n,}`  | At least n times      |
| `{n,m}` | Between n and m times |

---

## 🌀 Metacharacters

| Symbol | Meaning                            |
| ------ | ---------------------------------- |
| `.`    | Any character except newline       |
| `\d`   | Digit (0–9)                        |
| `\D`   | Non-digit                          |
| `\w`   | Word character (a-z, A-Z, 0–9, \_) |
| `\W`   | Non-word character                 |
| `\s`   | Whitespace (space, tab, newline)   |
| `\S`   | Non-whitespace                     |

---

## 🎯 Anchors

| Symbol | Meaning         |
| ------ | --------------- |
| `^`    | Start of string |
| `$`    | End of string   |
| `\b`   | Word boundary   |

---

## 📌 Examples

| Expression   | Matches                                          |
| ------------ | ------------------------------------------------ |
| `/\d+/`      | One or more digits                               |
| `/^[A-Z]/`   | Starts with an uppercase letter                  |
| `/[^\w\s]/g` | Special characters (not letters, digits, spaces) |
| `/['"_]/g`   | Single quotes, double quotes, underscore         |

---

> 💡 Tip: Use regex with `.replace()`, `.match()`, `.test()`, `.search()` in JavaScript.

---

Made with 💻 by a crypto samurai-in-training 🥷🔥
