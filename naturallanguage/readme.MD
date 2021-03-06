# Overview

Unlike programming languages - natural languages exists and are in every day use. They do suffer from heavy legacy (~ 2021 years of legacy) and tends to be really difficult 
to parse and analyze by computer applications. There exists enourmous amount of different approaches and techiques to parse, analyse and extract natural language.

Here are some articles related to that one for example:

* [In Russian: Изучаем синтаксические парсеры для русского языка](https://m.habr.com/ru/company/sberbank/blog/418701/), 2018.

Language itself can be collected into it's own database of words, lingistic rules related to language itself.

Such attempt can be observes for example in universal dependencies:

* [Universal Dependencies](https://universaldependencies.org/)

and content, which is organized by them:

* [CoNLL 2018 Shared Task](http://universaldependencies.org/conll18/)

Unlike programming languages - natural languages suffer from lack of proper structuratization and not being able to define a program in clearly defined state.

This can be observed from outcome of CoNLL results - all results are expressed in percentage of success. Computer based parsing however is one problem, after 
application can understand and speak natural language - there will come problem of misunderstanding between human and computer program.

This can be sometimes observed in politics, which often refer to conversation, which goes nowhere, or does not produce any useful result.

Changing natural language and teaching [8 billion people](https://www.worldometers.info/world-population/) new artifically created language also sounds like mission impossible.

Natural languages can be simplified in natural way, by minimizing used vocabulary and lingustic rules. Such behavior can be observed for example in [Toki Pona](https://en.wikipedia.org/wiki/Toki_Pona).

But natural language improvement still does not mean that it can be easily parsed as a program by computer application.

Program languages evolve by themselves - for example there exists programming language standards like C++11 (2011), C++13 (2013)... C++20 (2020), where
natural languages does not evolve or changes much.

The main direction of natural language parsing is however clear - best outcome percentage match for fastest parsing time. Programming languages also evolve in performance direction (faster to compile, faster to link, faster to test and so on). Common goal is performance, but libraries used for programming languages and for natural languages are different - for example [TurkuNLP](https://github.com/TurkuNLP/Turku-neural-parser-pipeline) for example uses [TensorFlow library](https://github.com/tensorflow/tensorflow) to improve parsing performance.

If we however compare programming and natural languages:

Programming language, pseudo C#:

```
foreach( var part in car.Parts )
{
    part.color = Colors.Yellow;
}
```

English natural language:

```
Let's paint all car parts to yellow.
```

For programming languages there is some semantic sugar (`'{'`, `'}'`), which in a turn cannot be easily expressed in natural language ("Foreach open bracket part dot color will be yellow close bracket"). Programming language allows clear modelling, where `class Car` would have a property `Color`, whereas natural language lacks of proper structurization, but also allows to more freedom on what you can express via natural language. Express more also means more ambiguity. Which form is shorter and what you can model by each language category is questionable and depends on context.

It's obvious that modelling is programming language richness, but it might also lead to overabstraction - creating difficult to use model.
Same problem might persist also for natural language itself - for example law texts is known to be difficult to comprehend.
