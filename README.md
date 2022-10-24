# Interfaces

Установите зависимости:

```
npm install
```

В файле `src/Interfaces.ts` выполните следующие задания:

1. Найдите и исправьте ошибку в данных, возвращаемых функцией `getPerson`.
2. Допишите функцию `getStudentsData` так, чтобы она возвращала массив из указанных в комментарии данных. Данные должны храниться в объектах, соответствующих интерфейсу `IStudentData`.

```TypeScript
export function getStudentsData(): IStudentData[] {
    return [
        {
            name: 'Ivan',
            secondName: 'Petrov',
            age: 20,
            phone: '+7(555)555-55-50',
        },
        {
            name: 'Stepan',
            secondName: 'Petrov',
            age: 19,
            phone: '+7(555)555-55-51',
        },
        {
            name: 'Petr',
            secondName: 'Ivanov',
            age: 19,
        },
    ];

    /**
     * Данные студентов которые нужно передать:
     *
     * 1. Ivan Petrov 20 лет +7(555)555-55-50
     * 2. Stepan Petrov 19 лет +7(555)555-55-51
     * 3. Pert Ivanov 19 лет
     *
     */
}
```

Проверить себя можно запустив команду `npm run test`.

После выполнения задания создайте pull request с решением.
