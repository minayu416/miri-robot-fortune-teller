---
layout: default
---

**If you want visit Chinese description, please refer [README in Github](https://github.com/minayu416/miri_demo/blob/develop/README.md)**


## Introduction

> Facing the unknown, we feel scared, confused, but novel and interesting.
>
> When you choose a card or look at the life chart, it might give you hints of future, suggestion of life, some messages you need to know ...
>
> In this moment, Miri born. She will provide you more methods to recognize your mind, sometimes give explanation.

<br>

Miri’s main development concept is `divination and fortune-telling`. It moves the traditional flows of divination and fortune-telling to software and the Internet. Through the message mode, it guides users follow the process and ask questions which are confused to them, getting the results from the selected divination method and explains it.

At the same time, it also provides methods related to physical and mental healing, adjust the mental situation depend the selected cards.

I hope to make `Miri` form a robot fortune teller, she can like a real fortune teller, using a variety of divination tools and understand different numerology knowledge, to help the dazed and confused friends solve their problems and adjust their minds.

## Features

`Miri` will be set as a little girl about 10 years old. She has a strange personality and cute. She has been interested in numerology and ancient divination since she was a child. She learned numerology and divination by self-taught to help people who come to solve their confusion.

In current version, it can be used on the social software `Line` and `Telegram`. The message language can choose to use `Chinese` or `English`.

<br>

It provides seven divination methods, including six divination and one combination divination.

- Six divination：Runes、Rider Tarot、Lenormand、Moon Blocks、Nature's Whispers、Inspirational Wisdom
- Combination divination：`Combine` Runes、Lenormand、Nature's Whispers and Inspirational Wisdom, getting the combination results.

<br>

`Runes`: In ancient Northern Europe, witches used Runes carved on stone or wood to divinate about upcoming wars and ordeals. It consists of 25 Rune alphabets. Each Rune has its own meaning. Some Runes have different interpretations depend upright and reversed positions, it needs to be extend the imagination based on the meaning of Runes, or with other Runes and situation.

`Rider Tarot`: The most commonly heard method in divination. There are 78 cards in total, with upright and reversed positions, and there are 156 different kinds of meaning. In addition to being familiar with the meaning of 78 cards, the fortuneteller also needs to extend his imagination based on the card mearning, and understand that different cards will have different interpretations.

`Lenormand`: It is composed of 36 cards with living objects. The card pattern is made of living objects such as `flowers`, `fish`, `towers` and other living objects. It needs to be extended and imagined by the meaning of living objects. It also needs to be interactively explained with other cards. For example, the `book` card symbolizes knowledge, reading, research, higher education, and further education courses. 

`Moon Blocks`: It is composed of two wooden half-moon cups with a concave flat surface. It is a divination for traditional temples to inquire about gods and Buddhas. There are four answers (three often appear): 1. Holy Cup (one convex and one flat), 2. Angry Cup (two convexes), 3. Laughing Cup (two flats), 4. Standing Cup (stand up) , But it rarely appears, so there is no such option).

1. `Holy Cup` stands for OK, Agree, and Executable
2. `Angry Cup` means not good, disagree, do not recommend, and there is no need to ask again if the matter has not changed significantly
3. `Laughing Cup` means Don’t understand the question, You already have the answer in your heart, This kind of question does not need to be asked, or The outcome has not been decided, usually at this time you need to ask additional questions for analysis: Do I need to ask the question more clear? 、Is it the implementation according to the inner thoughts? 、Is the ending undecided yet? 

`Nature's Whispers`: composed of 50 cards containing shorten phrases, and explained by the phrases. For example, “take a breath” means that the person needs to rest or stop acting, while “big harvest” is Indicates that the current situation or predicament will be a beneficial exercise for oneself.
This card is classified as a spiritual healing card.


`Inspirational Wisdom`: composed of 44 cards with long sentences. The long sentences bring motivational sentences that drive the adjustment of the soul.
This divination is classified as a spiritual healing card.

<br>

The divination flow is:

1. Choose a method: choose one from the seven divination methods
2. Choose an arrangement: Some methods provide arrangement with special meanings or card numbers. You can refer to the introduction to think about what arrangement you need to match with question (some methods skip if there is not arrangement)
3. Enter the meditation: stop at a meditation message, follow the meditation guidelines, think about yourself and the questions you want to ask in your head
4. Get results: Click the button to get the divination results
5. Obtain explanation: Interpret the divination results according to your own situation and the accompanying explanation content

## User Flow

First time to use, need to set language of message

Currently provide `English` and `Chinese` options

<img src="https://mingjungyu.files.wordpress.com/2021/08/img_7808.jpg" width="250"/>

<br>

After setting language, it will pop out the user guide message

You can click button to get 4 charts user guide, or enter menu.

<img src="https://mingjungyu.files.wordpress.com/2021/08/img_7818.jpg" width="250"/>

_We highly suggest you to read our User Guide before use in first time_

**Now, it's your turn!**

## Development History

**2017/12** Register LINE official account: Miri, and try to connect account with python program. The first version can only make echo responses of text messages, that is, respond to whatever the users send. There is not AI or semantic analysis related knowledge. The skills of Python was also very low.

**2019/5** To further developed Miri, start to create a python project and try to develop the back-end program. At this stage, due to work and study in the first company, the master of python technology has gradually matured, and the newly created python program is connected with the LINE Miri account. It can processed text messages, using jieba and NLTK to analyze the incoming message, and set some replies to respond. At this time, there was no clear plan for Miri to be developed. I only know that I want to turn Miri into Siri in the future.

**2019/10/19** Had some expected features and have thought how to train Miri for a long time. Finally because lacked of main concept so decided to develop one simple divination feature: Runes. Made a database for storing responses, allowing Miri to store the received messages in the database and reply messages. 

**2019/10/25** 

1. Re-designed the program structure
2. Extended Runes divination feature to three arragement.
3. Designed user flow with template message (Line use Carousel Template Message)

**2021/2/21**

Released the previous version for second stable version.

**2021/3/1**

Planed and Implemented third version

Since I have improved ability to design program architecture in my second job, and understanded Python and software development more deep, I decided to implement more features in Miri during the time after leaving the job.

- Decided to position Miri as a divination robot
- Refactored the code of the entire project for conform to multiple front-end interface and more back-end features
- Expected Telegram Bot to be added to the third edition
- 6 or at least 3 divination methods are expected to be developed
- Added English language dialogue
- Optimized Chinese explanation
- Optimized the user interface of Line

**2021/08/11**

Complete the development of the third version and entering user testing.

Plan features in future:

- Miri fortune-telling chatbot change to Miri robot fortune-teller (it means Miri is a robot fortune-teller not software)
- Implement web/app front end (towards independence and not rely any other platforms)
- Optimize the back-end program structure/code/performance speed
- Re-draw the picture of the cards used by each divination method
- Develop graphical functions of astralogy chart and Ziwei
- Add more divination methods
- Optimiz card interpretation/depth interpretation/combination interpretation (make it closer to the human situation)

<hr>

```
The development is still progressing...
```

More content and thinking please refer [README](https://github.com/minayu416/miri_demo/blob/develop/README.md) and [My Personal Blog](https://minayu.site/en/) 