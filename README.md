# 📖 Цель

Целью проекта является стандартизация рефератов, отчетов по лабораторным работам, а также пояснительных записок к курсовым и дипломным проектам в соотстветствии с требованиями [БГУИР](https://www.bsuir.by).

Основной задачей является создание преамбулы для документов LaTeX, составленной для соблюдения требований к оформлению пояснительных записок и отчетов.

Оформление настраивается в соответствии с документом [СТАНДАРТ ПРЕДПРИЯТИЯ. ДИПЛОМНЫЕ ПРОЕКТЫ (РАБОТЫ). ОБЩИЕ ТРЕБОВАНИЯ СТП 01—2017](https://library.bsuir.by/m/12_101945_1_141950.pdf).

 # 📃  Использование

Рекомендуемое окружение для разработки:
- Редактор кода VS Code с установленным плагином [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
- Компилятор [TeX Live](https://www.tug.org/texlive/)

Для того, чтобы использовать преамбулу, необходимо выполнить следующие шаги:
1. Инициализировать директорию стилей styles и поместить в нее файл стиля оформления списка использованной литературы [belarus-specific-utf8gost780u.bst](https://github.com/Qurcaivel/bsuir-latex/blob/main/styles/belarus-specific-utf8gost780u.bst). В данной директории рекомендуется помещать файлы, задающие стиль или команды, используемые для оформления, не определенного стандартом.
2. Инициализировать директорию графических ресурсов images. В данную директорию рекомендуется помещать файлы, представляющие изображения в тексте. 

В качестве примера использования преамбулы можно использовать [этот](https://github.com/Qurcaivel/bsuir-couse) курсовой проект.

# ✍️ Примечание

В настоящее время преамбула для документов не является полным соответствием стандарту и обеспечивает выполнение основных пунктов по оформлению документа.

Основой для написания преамбулы главным образом послужил существующий [проект](https://github.com/mstyura/bsuir-diploma-latex) под [устаревший стандарт](http://www.bsuir.by/m/12_100229_1_80040.pdf).

В исходном коде преамбулы могут присутствовать ошибки и не самые удачные решения, что является следствием малого опыта работы с LaTeX.

Преамбула будет дополняться и редактироваться по мере установления несоответствий со стандартом, помощь в доработке и исправлениях приветствуется.
# 💀 Авторы

- Гений, плейбой, миллиардер, филантроп, а так же автор преамбулы - **Леша** ([Qurcaivel](https://github.com/Qurcaivel)). Главный пропагандист LaTeX на ЭВС (возможно).
- Автор README, по совместительству - главный вдохновитель написания пояснительных записок по курсовым проектым на LaTeX - **Саша** ([heycarl](https://github.com/heycarl)). 
# 🙏 Благодраности

 - Безусловно, главным мотиватором и жизненным коучем является **Демидович Геннадий Николаевич (a.k.a. DGN DGN1248)**.
 - Благодаря [стикерам](https://t.me/addstickers/DGN_DGN_1248) от **Ильи** ([Googlash](https://github.com/Googlash)) не пропадало настроение писать новые строчки этого документа, а конспект по СТП01-2017 наполнялся все новыми и новыми сраницами. 
 