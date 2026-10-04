# Interaction Language

[English](#english) | [Русский](#русский)

Status / Статус: early working version / ранняя рабочая версия.

## English

### Operational commands

**Discuss** — explore options and consequences. Does not mean approval, implementation, or file changes.

**Approved** — the clearly identified current decision is accepted. Approval does not automatically extend to unrelated decisions.

**Record** — put an already accepted decision into durable project documentation.

**Implement** — turn an accepted decision into a working implementation. Implementation is not verification.

**Do not code** — continue analysis, design, or documentation without changing implementation code.

**Verify** — check the actual result against the required state.

### Statuses

`Proposal` — not yet accepted.

`Approved` — accepted decision.

`Candidate` — solution or implementation exists but has not passed the required verification.

`PASS` — the required verification has succeeded.

`Deprecated` — retained for continuity but not recommended for new work.

### Information states

When relevant, distinguish:

`fact` · `decision` · `proposal` · `hypothesis` · `candidate`

Do not silently turn one state into another.

### Formats

`TSV` — structured tabular data.

`plain text` — when a table adds no value.

`short command block` — terminal or shell instructions.

`monospaced diagram` — structure or spatial relationships.

### Project languages

A project may maintain its own `INTERACTION-LANGUAGE.md`.

`common Interaction Language → project language → current context`

Project language extends the common language and should not duplicate it without need.

## Русский

### Операционные команды

**Обсуждаем** — исследовать варианты и последствия. Не означает утверждение решения, реализацию или изменение файлов.

**Одобрено** — текущее ясно определённое решение принято. Одобрение не распространяется автоматически на другие решения.

**Фиксируем** — внести уже принятое решение в долговременную документацию проекта.

**Реализуем** — перевести принятое решение в рабочую реализацию. Реализация не равна проверке.

**Не кодируем** — продолжать анализ, проектирование или документирование без изменения кода реализации.

**Проверяем** — проверить фактический результат на соответствие требуемому состоянию.

### Статусы

`Предложение` — ещё не принято.

`Утверждено` — решение принято.

`Candidate` — решение или реализация существует, но ещё не прошло необходимую проверку.

`PASS` — требуемая проверка успешно пройдена.

`Deprecated` — элемент сохраняется для понимания прошлого контекста, но больше не рекомендуется.

### Состояния информации

Когда это важно, различать:

`факт` · `решение` · `предложение` · `гипотеза` · `candidate`

Не превращать одно состояние в другое молча.

### Форматы

`TSV` — структурированные табличные данные.

`обычный текст` — если таблица не нужна.

`короткий блок команд` — терминал и shell.

`моноширинная схема` — структура и пространственные отношения.

### Проектные языки

Проект может поддерживать собственный `INTERACTION-LANGUAGE.md`.

`общий Interaction Language → язык проекта → текущий контекст`

Проектный язык расширяет общий и не должен без необходимости его дублировать.
