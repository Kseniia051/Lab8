<<<<<<< HEAD
# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) (or [oxc](https://oxc.rs) when used in [rolldown-vite](https://vite.dev/guide/rolldown)) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
=======
# Лабораторная работа №8. Введение в React + JSX

## Описание приложения

Это простое ToDo-приложение, реализованное с помощью React.  
Приложение позволяет:  
- Добавлять новые задачи  
- Удалять отдельные задачи  
- Очистить весь список  
- Сохранять задачи в `localStorage`, чтобы они оставались после перезагрузки страницы

---

## Скриншоты

<img width="580" height="296" alt="image" src="https://github.com/user-attachments/assets/170b6bd8-e41e-4c9d-9753-339b17dedbc9" />
<img width="578" height="358" alt="image" src="https://github.com/user-attachments/assets/2e28c40f-6cb1-468e-bd3e-279752dce5c0" />

---

## Краткое объяснение

### Компоненты, пропсы и состояние
- **Компонент** — это изолированная и переиспользуемая часть интерфейса. В проекте компоненты: `App`, `AddTaskForm`, `ToDoList`, `ToDoItem`.  
- **Пропсы (props)** — это данные, которые передаются от родителя к дочернему компоненту. Например, функции `addTask` и `removeTask` передаются в дочерние компоненты через props.  
- **Состояние (state)** — это внутренние данные компонента, которые могут меняться со временем. В проекте `tasks` хранится в `useState` в `App.jsx`.

### Роль ИИ
- ИИ помог сгенерировать основу кода всех компонентов ToDo-приложения и подсказал, как реализовать добавление, удаление и очистку задач.  
- Дополнительные улучшения (стили, сохранение в `localStorage`) были добавлены вручную.

### Компонентный подход
- Вместо того чтобы вручную управлять DOM, мы разбили интерфейс на независимые компоненты.  
- Каждый компонент отвечает за свою часть функционала, что делает код более читаемым и удобным для поддержки.  
- Компонентный подход упрощает работу с состоянием и передачей данных между частями приложения.
>>>>>>> 4044e6f81c1b93fe58827874c6680361673b523c
