Table of Contents
===
[About](#about)  
[How to edit word dictionary](#edit)  
[How to use](#use)

<a name="about"><h3>About</h3></a>
----
This program was written on [**Ruby**](https://www.ruby-lang.org/en/). It is simple implementation of [**hangman**](https://en.wikipedia.org/wiki/Hangman_(game)) to play in console. Functionality is _obvious_.

#### View
```
Всем привет!
Слово: __ __ __ __ __ __ __
            _______
            |/
            |
            |
            |
            |
            |
            |
            |
          __|________
          |         |
Ошибки (0): 
У вас осталось ошибок: 7
Введите следующую букву:
```

<a name="edit"><h3>How to edit word dictionary</h3></a>
----
Open ```/data/words.txt```
```
РУБИ
...
СЧАСТЬЕ
```
Simply add there your words (one word per line).

Example:
```
РУБИ
...
СЧАСТЬЕ
КОТ
```

<a name="use"><h3>How to use</h3></a>
---------------
First of all **Ruby** & **Git** must be installed (on Debian based):
```
sudo apt install ruby git
```
clone repo: 
```
git clone https://github.com/moonmeander47/hangman.git && cd hangman
```
run:
```
ruby main.rb
```
