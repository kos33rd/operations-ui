#### Использование

```jsx static
import { GhostButton } from '@samokat/operations-ui'


//...
<GhostButton>Войти</GhostButton>
//...
```

#### Примеры

Размеры: medium, small
```js
<div style={{ width: '300px', display: 'flex', justifyContent: 'space-between' }}>
  <GhostButton size="medium">Войти</GhostButton>
  <GhostButton size="small">Войти</GhostButton>
</div>
```


Отключенная кнопка
```js
<GhostButton disabled={true}>Войти</GhostButton>
```

c иконкой и текстом
```js
import { Logout } from '@samokat/operations-icons';
<GhostButton icon={Logout}>Выйти</GhostButton>
```

только иконка
```js
import { Logout } from '@samokat/operations-icons';
<GhostButton icon={Logout} />
```