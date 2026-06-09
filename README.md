# 🧮 Bash Arithmetic Operators — Complete Guide with Examples (2026)

![Linux](https://img.shields.io/badge/Linux-Guide-blue)
![Level](https://img.shields.io/badge/Level-Beginner%20to%20Intermediate-green)
![Updated](https://img.shields.io/badge/Updated-2026-orange)
![Focus](https://img.shields.io/badge/Focus-Bash%20Math-important)

> Want your Bash scripts to perform calculations automatically?  
> Arithmetic operators are essential for counters, loops, automation, monitoring scripts, and system administration tasks.

📖 **[Full Guide (operators + calculations + real examples → linuxteck.com)](https://www.linuxteck.com/bash-script-arithmetic-operators/?utm_source=github&utm_medium=repo&utm_campaign=bash-arithmetic)**

---

## ⚡ 1-Minute Understanding

If you remember just this:

- `+` → Addition
- `-` → Subtraction
- `*` → Multiplication
- `/` → Division
- `%` → Modulus (remainder)

💡 Arithmetic operators make Bash scripts dynamic and intelligent.

---

## 🖼️ Preview

> Performing calculations inside Bash scripts

![Preview](https://github.com/linuxteck/bash-script-arithmetic-operators/blob/main/17.png)

---

## 🧠 Why This Guide Exists

Many Linux users learn Bash commands but never explore arithmetic operations.

Without arithmetic:
- No counters
- No calculations
- No automation logic

This guide helps you:
- Perform calculations in Bash
- Understand arithmetic operators
- Build smarter automation scripts

---

## 🔄 Common Arithmetic Operators

| Operator | Description | Example |
|-----------|------------|----------|
| `+` | Addition | `5 + 2` |
| `-` | Subtraction | `10 - 4` |
| `*` | Multiplication | `3 * 5` |
| `/` | Division | `20 / 4` |
| `%` | Modulus | `10 % 3` |
| `++` | Increment | `count++` |
| `--` | Decrement | `count--` |

---

## 👉 Want all examples, operators, and scripting techniques?  
Read here:  
https://www.linuxteck.com/bash-script-arithmetic-operators/?utm_source=github&utm_medium=repo

---

## 🚀 Quick Practice (Copy-Paste Ready)

```bash
# Addition
echo $((5 + 3))

# Subtraction
echo $((10 - 4))

# Multiplication
echo $((6 * 7))

# Division
echo $((20 / 5))

# Modulus
echo $((10 % 3))
```

---

## 🧪 Using Variables

```bash
#!/bin/bash

a=10
b=5

sum=$((a + b))

echo "Result: $sum"
```

---

## 🧪 Increment Counter Example

```bash
#!/bin/bash

counter=1

((counter++))

echo $counter
```

---

## 🔄 Real-World Use Cases

```bash
# Disk usage calculations
# Backup counters
# Loop iterations
# User quota checks
# Monitoring scripts
# Performance reports
```

---

## ⚠️ Common Mistakes

| Mistake | Impact |
|----------|---------|
| Missing `$(( ))` | Calculation fails |
| Using spaces incorrectly | Syntax errors |
| Expecting decimal math | Bash supports integers by default |
| Forgetting variable expansion | Incorrect output |

---

## 🎯 Who Gets the Most Value

| You Are | Benefit |
|---------|--------|
| 🟢 Beginner | Learn Bash fundamentals |
| 🔵 Sysadmin | Automate calculations |
| 🔴 DevOps Engineer | Build smarter scripts |
| 🟡 Developer | Improve scripting skills |

---

## 🔗 More LinuxTeck Guides You'll Want

> 📂 *Part of the **LinuxTeck Master Series** — practical Linux guides*

- 🔀 https://www.linuxteck.com/bash-conditional-statements/
- 🧠 https://www.linuxteck.com/bash-if-statement-complete-guide-with-examples/
- 🎛️ https://www.linuxteck.com/bash-case-statement-with-examples/
- 📝 https://www.linuxteck.com/bash-quoting-rules-for-cleaner-shell-scripts/
- 🔍 https://github.com/linuxteck?tab=repositories

---

## ✍️ About LinuxTeck

**https://www.linuxteck.com** publishes practical, real-world Linux guides — no fluff, no filler.  
If you're learning Bash scripting, these guides will save you hours.

⭐ Found this useful? Star this repo — it helps more Linux learners discover it  
🔁 Share with your team — especially if they're learning Bash automation 😄  
👤 https://github.com/linuxteck

---

**Topics:** bash • arithmetic • shell-scripting • linux • automation • scripting • devops • sysadmin • bash-programming • linux-basics
