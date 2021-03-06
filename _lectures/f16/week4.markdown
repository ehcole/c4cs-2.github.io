---
permalink: /lectures/f16/week4.html
---

class: center, middle

# Build Systems

.copyright[
<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a>
** [Pat Pannuto](http://patpannuto.com) / Marcus Darden **
]


---


# Q: What is a Build System?

???

 - AKA: Build Automation Software
 - Script/automate compilation

--

# Q: Who has used a one?

???

 - Everyone in 280 and beyond


---


# Make, the Grandbinary of them all

 - Automate compiling and linking
 - Easily repeat long/complex commands
 - Eliminate unnecessary work

???

 - Stuart Feldman, 1976, Bell Labs
 - Replaced shell scripts commonly used


---


# Make syntax
## (in 2 lines or less)

--

```bash
target: dependencies
        rules
```

???

 - target: The thing we're trying to build
 - dependencies: The thing(s) that must come before
 - rules: The steps needed to build target once the dependencies are all here


---


# Let's Makefile!

- Build a sentence
    - Subject
    - Verb
    - Object


---


# Other build systems

--

## make-based

- GNU make
- nmake
- ...

--

## Non-make/Proprietary

- Bazel (Google's tool)
- Buck (Facebook's tool)
- MSBuild (Microsoft's tool)
- xcodebuild (Apple's tool)
- ...

--

## Other languages for scripting and building

- Rake (ruby)
- Apache Ant (Java + XML)
- A-A-P (python)
- sbt (Scala)
- ...


---


# Why stop at compilation?

What else could we automate?

--

- Build script generation
- Installation
- Testing
- Continuous Integration (CI)

???

- make-based tools build well and then... bash
- proprietary tools integrate with or control IDEs
- CI tools use build systems, IDE aware, Notifications


---


# Closing remarks

- **New section!!**
- Max points from Advanced Exercises in 3 or more sections
- Reminder: You must submit to staff at OH

???

- 30 total AE points
- (10 + 2) + (10 + 2 + 2) + (10 + 2 + 2) + (5 + 2 + 2) = 49
- Missing AE in two sections = Max AE score of 28 points (6 AE)
