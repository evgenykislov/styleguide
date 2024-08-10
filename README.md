# Google Style Guides

The main goal of the fork is to give a translation 
of C++ Google Style Guide into Russian. So ...

# Руководства по стилю от Google

Наверное, у каждого известного проекта с открытым исходным кодом есть 
руководство по стилю: набор соглашений (иногда противоречивых) о том, 
 как писать код для проекта. Обусловлено это тем, что намного легче 
 понять код, особенно когда его очень много, если он оформлен единообразно.
 
"Руководство" охватывает множество областей, от правил именования переменных до
 использования глобальных переменных или исключений. Этот проект
 ([evgenykislov/styleguide](https://github.com/evgenykislov/styleguide))
 объединяет руководства, которые (в исходной редакции) используются в коде для Google. 
 Если вы редактируете код от Google, то здесь можно прочитать
 о тех принципах по которым он оформляется.


*   [AngularJS Style Guide][angular]
*   [Common Lisp Style Guide][cl]
*   [Руководство по стилю C++ (рус)][cpp_ru], [C++ Style Guide (eng)][cpp_eng]
*   [C# Style Guide][csharp]
*   [Go Style Guide][go]
*   [HTML/CSS Style Guide][htmlcss]
*   [JavaScript Style Guide][js]
*   [Java Style Guide][java]
*   [Objective-C Style Guide][objc]
*   [Python Style Guide][py]
*   [R Style Guide][r]
*   [Shell Style Guide][sh]
*   [Swift Style Guide][swift]
*   [TypeScript Style Guide][ts]
*   [Vim script Style Guide][vim]

Также здесь есть [cpplint][cpplint] -
 инструмент, помогающий соответствовать стилю, и [google-c-style.el][emacs] - 
 файл с настройками для Emacs.

Кроме того, если в проекте требуется новый формат XML-документа, то 
обратите внимание на [XML Document Format][xml]. В дополнение к текущим правилам
 он содержит советы по созданию своих собственных правил или адаптации 
 существующих, форматированию XML-документа, использованию элементов и атрибутов.

Руководства по стилю в этом проекте распространяются под лицензией CC-By 3.0 License,
 которая позволяет вам распространять эти документы.
 Подробнее можно прочитать на [https://creativecommons.org/licenses/by/3.0/][ccl].

Также есть ещё руководство, которое размещается отдельно, вне проекта. Это
[Effective Dart][dart].

## Внешнее участие

Руководства по стилю (за небольшими исключениями) скопированы с внутренних документов Google с целью помочь разработчикам работать над проектами Google или проектами с открытым исходным кодом. Как результат, изменения в руководствах по стилю  делаются сначала во внутренних документах, потом изменения копируются во внешний документ. Поэтому **Внешнее участие не допускается**. Pull request-ы будут закрываться без объяснения причин. Очевидные ошибки или технические неточности теоретически могут быть приняты, однако в любом случае документы изменяются с учётом внутреннего применения в Google.

# Google Style Guides

Every major open-source project has its own style guide: a set of conventions
(sometimes arbitrary) about how to write code for that project. It is much
easier to understand a large codebase when all the code in it is in a consistent
style.

“Style” covers a lot of ground, from “use camelCase for variable names” to
“never use global variables” to “never use exceptions.” This project
([google/styleguide](https://github.com/google/styleguide)) links to the style
guidelines we use for Google code. If you are modifying a project that
originated at Google, you may be pointed to this page to see the style guides
that apply to that project.


*   [AngularJS Style Guide][angular]
*   [Common Lisp Style Guide][cl]
*   [C++ Style Guide][cpp_eng]
*   [C# Style Guide][csharp]
*   [Go Style Guide][go]
*   [HTML/CSS Style Guide][htmlcss]
*   [JavaScript Style Guide][js]
*   [Java Style Guide][java]
*   [JSON Style Guide][json]
*   [Markdown Style Guide][markdown]
*   [Objective-C Style Guide][objc]
*   [Python Style Guide][py]
*   [R Style Guide][r]
*   [Shell Style Guide][sh]
*   [Swift Style Guide][swift]
*   [TypeScript Style Guide][ts]
*   [Vim script Style Guide][vim]

This project also contains [cpplint][cpplint], a tool to assist with style guide
compliance, and [google-c-style.el][emacs], an Emacs settings file for Google
style.

If your project requires that you create a new XML document format, the
[XML Document Format Style Guide][xml] may be helpful. In addition to actual
style rules, it also contains advice on designing your own vs. adapting an
existing format, on XML instance document formatting, and on elements vs.
attributes.

The style guides in this project are licensed under the CC-By 3.0 License, which
encourages you to share these documents. See
[https://creativecommons.org/licenses/by/3.0/][ccl] for more details.

The following Google style guide lives outside of this project:

*  [Effective Dart][dart]
*  [Kotlin Style Guide][kotlin]

## Contributing

With few exceptions, these style guides are copies of Google's internal style
guides to assist developers working on Google owned and originated open source
projects. Changes to the style guides are made to the internal style guides
first and eventually copied into the versions found here. **External
contributions are not accepted.** Pull requests are regularly closed without
comment.

People can file [issues using the GitHub tracker][gh-tracker]. Issues that raise
questions, justify changes on technical merits, or point out obvious mistakes
may get some engagement and could in theory lead to changes, but we are
primarily optimizing for Google's internal needs.

<a rel="license" href="https://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a>

[cpp_eng]: https://htmlpreview.github.io/?https://github.com/evgenykislov/styleguide/blob/ru_cpp/cppguide.html
[cpp_ru]: https://htmlpreview.github.io/?https://github.com/evgenykislov/styleguide/blob/ru_cpp/cppguide_ru.html
[csharp]: https://google.github.io/styleguide/csharp-style.html
[swift]: https://google.github.io/swift/
[objc]: objcguide.md
[gh-tracker]: https://github.com/google/styleguide/issues
[go]: go/
[java]: https://htmlpreview.github.io/?https://github.com/evgenykislov/styleguide/blob/ru_cpp/javaguide.html
[json]: https://google.github.io/styleguide/jsoncstyleguide.xml
[kotlin]: https://developer.android.com/kotlin/style-guide
[py]: https://htmlpreview.github.io/?https://github.com/evgenykislov/styleguide/blob/ru_cpp/pyguide.html
[r]: https://htmlpreview.github.io/?https://github.com/evgenykislov/styleguide/blob/ru_cpp/Rguide.html
[sh]: https://google.github.io/styleguide/shellguide.html
[htmlcss]: https://htmlpreview.github.io/?https://github.com/evgenykislov/styleguide/blob/ru_cpp/htmlcssguide.html
[js]: https://htmlpreview.github.io/?https://github.com/evgenykislov/styleguide/blob/ru_cpp/jsguide.html
[markdown]: https://google.github.io/styleguide/docguide/style.html
[ts]: https://google.github.io/styleguide/tsguide.html
[angular]: https://htmlpreview.github.io/?https://github.com/evgenykislov/styleguide/blob/ru_cpp/angularjs-google-style.html
[cl]: https://htmlpreview.github.io/?https://github.com/evgenykislov/styleguide/blob/ru_cpp/lispguide.xml
[vim]: https://htmlpreview.github.io/?https://github.com/evgenykislov/styleguide/blob/ru_cpp/vimscriptguide.xml
[cpplint]: https://github.com/evgenykislov/styleguide/blob/ru_cpp/cpplint/README
[emacs]: https://htmlpreview.github.io/?https://github.com/evgenykislov/styleguide/blob/ru_cpp/google-c-style.el
[xml]: https://htmlpreview.github.io/?https://github.com/evgenykislov/styleguide/blob/ru_cpp/xmlstyle.html
[dart]: https://www.dartlang.org/guides/language/effective-dart
[ccl]: https://creativecommons.org/licenses/by/3.0/
