intellij-config
===============

Custom configuration for IntelliJ IDEA - code styles, file templates, live templates.

JavaScript's code style is based on the popular [Airbnb's JavaScript style guide](https://github.com/airbnb/javascript).

Installation
--------------

Shut down IntelliJ IDEA.

Depending on the operating system, go to the IntelliJ IDEA's configuration directory:-

* Windows: <code>~\\.IntelliJIdeaXX\config</code>
* Linux: <code>~/.IntelliJIdeaXX/config</code>
* OS X: <code>~/Library/Preferences/IntelliJIdeaXX</code>

Under the configuration directory, replace the following subdirectories:-

    <INTELLIJ-IDEA-CONFIG_DIR>
    ├── codestyles           <--- Replace this dir
    ├── colors
    ├── componentVersions
    ├── consoles
    ├── eval
    ├── extensions
    ├── fileTemplates        <--- Replace this dir
    ├── ideTalk
    ├── inspection
    ├── javascript
    ├── jdbc-drivers
    ├── options
    ├── quicklists
    ├── tasks                
    ├── templates            <--- Replace this dir
    └── trp

Start IntelliJ IDEA.

Upon IntelliJ IDEA restart, you may need to select the code style from the `Settings / Preferences Dialog`.

Code Styles Usage
-----------------

`Alt + Cmd + L` (Mac) and `Alt + Ctrl + L` (Windows).

Live Templates Usage
--------------------

#### Groovy - Spock

|Shortcut                                |Description                                                                |
|----------------------------------------|---------------------------------------------------------------------------|
|`def + <Tab>`                           |Spock - def given when then                                                |

#### JavaScript

|Shortcut                                |Description                                                                |
|----------------------------------------|---------------------------------------------------------------------------|
|`cl     + <Tab>`                        |`console.log(..)`                                                          |
|`af     + <Tab>`                        |ES6 - arrow function : `(..) => { .. }`                                    |
|`de     + <Tab>`                        |ES6 - describe()                                                           |
|`it     + <Tab>`                        |ES6 - it()                                                                 |
