При сборке:
1. "Unable to open trace" - возникает при запущенном дев и запуске сборки. Выключи дев режим
2. "ReferenceError: localStorage is not defined" Проверь что localstorage не undefined.  `if (typeof localStorage !== 'undefined') ...`
