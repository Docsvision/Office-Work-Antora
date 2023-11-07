# Жизненный цикл дела

Для карточки Дело в приложении Делопроизводство настроены состояния:

- «Подготавливается» – в этом состоянии определяются регистрационные данные дела.
- «Формируется» – в дело можно списывать документы.
- «Закрыто» – дело закрыто, списание в него разрешено только в случае, если в карточке дела установлен флаг Разрешить списание в закрытое дело.

> Состояния карточки Дело определяются в Конструкторе состояний и могут быть изменены администратором Docsvision.

Состояния дел изменяются вместе с изменением состояния номенклатуры, к которой они принадлежат, или кнопками ленты инструментов в самой карточке Дело.