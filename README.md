# Pravo

#### 1. https://testometrika.com/a/WPT4SA6XIK5u5B16Spid8g/

Лучшее тестовое в мире :D

#### 2. 
```js
function getFieldInfo(caseTypeInfo, tag) {
        const field = caseTypeInfo.Blocks
                .reduce((acc, block) => {acc.push(...block.Lines); return acc}, [])
                .reduce((acc, line) => {acc.push(...line.Fields); return acc}, [])
                .find(field => field.Tag === tag)

        return field? field: `Tag not found`;
}
```

#### 3. Что не так с json
Если вопрос про валидность JSON, то он валидный. Скорее всего он должен выглядить так:
```bash
{
    "message": {
        "datezakl":null,
        "numberdogovor":null
        }
}
```
