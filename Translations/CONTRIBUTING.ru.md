# Участие в проекте

🌐
[Azerbaijani][AZ],
[bahasa Indonesia][ID],
[Basa Jawa][JV],
[Català][CA]،
[Čeština][CZ],
[Dansk][DA],
[Deutsch][DE],
[English][EN],
[Español][ES],
[Français][FR],
[Galego][GL],
[Italiano][IT],
[Kurdi][KU],
[Kurdî][KU],
[Lietuvių][LT],
[Mongolia][MN],
[Nederlands][NL],
[Norsk][NO],
[Polski][PL],
[Português][PT_BR],
[Русский][RU],
[Svenska][SV],
[tiếng Việt][VI],
[Türkçe][TR],
[Ελληνικά][GR],
[Українська][UK]،
[العربية][AR],
[हिन्दी][HI_IN],
[한국어][KO_KR],
[日本語][JA],
[正體中文][ZH_TW],
[简体中文][ZH_CN]

[AR]:CONTRIBUTING.ar.md
[AZ]:CONTRIBUTING.az.md
[CA]:CONTRIBUTING.ca.md
[CZ]:CONTRIBUTING.cz.md
[DA]:CONTRIBUTING.da.md
[DE]:CONTRIBUTING.de.md
[EN]:../CONTRIBUTING.md
[ES]:CONTRIBUTING.es.md
[FR]:CONTRIBUTING.fr.md
[GL]:CONTRIBUTING.gl.md
[GR]:CONTRIBUTING.gr.md
[HI_IN]:CONTRIBUTING.hi_in.md
[ID]:CONTRIBUTING.id.md
[IT]:CONTRIBUTING.it.md
[JA]:CONTRIBUTING.ja.md
[JV]:CONTRIBUTING.jv.md
[KO_KR]:CONTRIBUTING.ko_kr.md
[KU]:CONTRIBUTING.ku.md
[LT]:CONTRIBUTING.lt.md
[MN]:CONTRIBUTING.mn.md
[NL]:CONTRIBUTING.nl.md
[NO]:CONTRIBUTING.no.md
[PL]:CONTRIBUTING.pl.md
[PT_BR]:CONTRIBUTING.pt_br.md
[RU]:CONTRIBUTING.ru.md
[SV]:CONTRIBUTING.sv.md
[TR]:CONTRIBUTING.tr.md
[UK]:CONTRIBUTING.uk.md
[VI]:CONTRIBUTING.vi.md
[ZH_CN]:CONTRIBUTING.zh_cn.md
[ZH_TW]:CONTRIBUTING.zh_tw.md

Исходный код в этом репозитории был оцифрован вручную с бумажных распечаток, поэтому опечатки и другие расхождения были внесены случайно. Код следует изменить так, чтобы он соответствовал следующим отсканированным распечаткам:

- [AGC printouts for Comanche][8]
- [AGC printouts for Luminary][9]

Следующий веб-сайт можно использовать, чтобы легко перемещаться по отсканированным распечаткам как Comanche, так и Luminary: https://28gpc.csb.app/

## Полезные расширения

GitHub имеет встроенную поддержку синтаксиса языка ассемблера AGC. К сожалению, ваш редактор кода этого не умеет, однако существуют расширения языка AGC, которые обеспечивают подсветку синтаксиса для следующих редакторов:

- [Atom][Atom]†
- [CodeBlocks][CodeBlocks]
- [Eclipse][Eclipse]
- [Kate][Kate]
- [ProgrammersNotepad][ProgrammersNotepad]
- [Sublime Text 3][Sublime Text]†
- [TextPad][TextPad]
- [Vim][Vim]
- [Visual Studio Code][VisualStudioCode]†
- [jEdit][jEdit]

† Поддерживает автоматическое форматирование

[Atom]:https://github.com/Alhadis/language-agc
[CodeBlocks]:https://github.com/virtualagc/virtualagc/tree/master/Contributed/SyntaxHighlight/CodeBlocks
[Eclipse]:https://github.com/virtualagc/virtualagc/tree/master/Contributed/SyntaxHighlight/Eclipse
[Kate]:https://github.com/virtualagc/virtualagc/tree/master/Contributed/SyntaxHighlight/Kate
[ProgrammersNotepad]:https://github.com/virtualagc/virtualagc/tree/master/Contributed/SyntaxHighlight/ProgrammersNotepad
[Sublime Text]:https://github.com/jimlawton/AGC-Assembly
[TextPad]:https://github.com/virtualagc/virtualagc/tree/master/Contributed/SyntaxHighlight/TextPad
[Vim]:https://github.com/wsdjeg/vim-assembly
[VisualStudioCode]:https://github.com/wopian/agc-assembly
[jEdit]:https://github.com/virtualagc/virtualagc/tree/master/Contributed/SyntaxHighlight/jEdit

## Форматирование

**Примечание:** GitHub и отмеченные выше расширения автоматически обеспечат использование правильного форматирования.

- Используйте отступ табуляцией.
- Используйте ширину табуляции 8.
- Удаляйте конечные пробелы.

## Что мне проверять?

Любые расхождения между сканами и исходным кодом в этом репозитории.

### Комментарии

Комментарии в транскрибированном коде **ДОЛЖНЫ** **точно** совпадать со сканами.

Распространённые проблемы, на которые следует обращать внимание при вычитке, включают, но не ограничиваются следующим:

#### Опечатки

В некоторых местах оригинальные разработчики допускали опечатки при написании комментариев. Некоторые из них были ошибочно исправлены во время первоначальной оцифровки, однако оцифровка также внесла опечатки, которых не было в сканах.

Например, если оцифрованные комментарии содержали `SPACECRAFT`, но в сканах было напечатано `SPAECRAFT`, то оцифровку **НЕОБХОДИМО** исправить на `SPAECRAFT` (пропущено `C`).

Аналогично, если слово содержит опечатку в оцифровке, но написано правильно в сканах, то опечатку **НЕОБХОДИМО** исправить.

#### Пробелы

Пробелы между двумя символами в комментариях **ДОЛЖНЫ** совпадать со сканами. В большинстве случаев (см. обсуждение в [#316][10]) это:

- Одиночный пробел для новых слов.
- Двойной пробел для новых предложений.
- Тройной пробел для отступов.

Не все страницы в сканах следуют этому обобщению; если в сканах стоит только один пробел вместо двойного, используйте один пробел.

### Разрывы строк

- Разрывы строк *с* `R0000` в столбце 1 должны точно соответствовать сканам.
- Разрывы строк *без* `R0000` в столбце 1 должны содержать только 1 или 2 пустые строки подряд.
  - Если пустых строк больше 2, удалите лишние разрывы строк.
    - Строки с `R0000` в столбце 1 при этом не учитываются.
  - На исходных изображениях они создавались непечатаемой цифрой в столбце 8. Значение 2 задавало двойной интервал (одна пустая строка), а 3 — тройной интервал (две пустые строки). Значения 4–8 были определены, но никогда не использовались. Подробнее об этом читайте в [#159][7].

Например, следующее:

```plain
R0819   SUBROUTINE TO SKIP...
R0820




 0821   LAMPTEST  CS  IMODES33
```

должно стать:

```plain
R0819   SUBROUTINE TO SKIP...
R0820


 0820   LAMPTEST  CS  IMODES33
```

## Примечание

Прежде чем создавать PR, пожалуйста, убедитесь, что ваши изменения согласуются со сканами!

[0]:https://github.com/chrislgarry/Apollo-11/pull/new/master
[1]:http://www.ibiblio.org/apollo/ScansForConversion/Luminary099/
[2]:http://www.ibiblio.org/apollo/ScansForConversion/Comanche055/
[6]:https://github.com/wopian/agc-assembly#user-settings
[7]:https://github.com/chrislgarry/Apollo-11/issues/159
[8]:http://www.ibiblio.org/apollo/ScansForConversion/Comanche055/
[9]:http://www.ibiblio.org/apollo/ScansForConversion/Luminary099/
[10]:https://github.com/chrislgarry/Apollo-11/pull/316#pullrequestreview-102892741
