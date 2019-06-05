# 🚀 Yet another emoji support 😎

![icon](website/images/icon.png)

This is the IntelliJ plugin that supports inserting emoji in editor using content assist.

The reason it named "Yet another" is the fact that I ([@shiraji](https://github.com/shiraji)) already released [emoji IntelliJ plugin](https://github.com/shiraji/emoji) before. And this is another way of supporting emoji insertion

## ❓ How to use it ❓

1. Type ":" and emoji name
1. Open code completion

![screenshot](website/images/emoji.gif)

## 📛 Name 📛

The name of emoji comes from "CLDR Short Name". All spaces are replaced with "_".

## 🌍 Supported inserting 🌎 location 🌏

The emoji content assist is limited to show following location:

* Comments (Any languages)
* String (Some languages)
* IntelliJ Commit Message

The list of supported languages are:

* Go
* Java
* JavaScript
* TypeScript
* Kotlin
* PHP
* Python
* Ruby
* XML
* YAML

Feel free to send PR if you want to support other languages 😉

## 😀 Supported emoji 🏴

The supported emoji is between 😀 (U+1F600) to 🏴󠁧󠁢󠁷󠁬󠁳󠁿 (U+1F3F4 U+E0067 U+E0062 U+E0077 U+E006C U+E0073 U+E007F) (See https://unicode.org/emoji/charts/full-emoji-list.html)

## 👩‍🔧 How to install 👨‍🔧

Use the IDE's plugin manager to install the latest version of the plugin.

## 🙈 Known Issue 🙉

* Some emoji are not rendered like US flag 🇺🇸 (See https://youtrack.jetbrains.com/issue/IDEA-166522)


## 📄 LICENSE 📃

```
Copyright 2019 Yoshinori Isogai

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
