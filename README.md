# Скачать Redshift Render для Сinema 4D, Houdini, Blender, Maya, 3ds Max
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fredrender%2Fredshift-v3.0.61&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=&edge_flat=false)](https://hits.seeyoufarm.com)
![Alt text](https://github.com/redrender/redshift-v3.0.61/blob/main/redshift-image.jpeg?raw=true "REDSHIFT")

Для версий Redshift 3.0 под Windows и Linux требуются последние или новейшие драйверы Nvidia. Эти версии содержат поддержку OptiX7, которая является частью драйвера Nvidia. Редшифт для Мак версии 3.0.45 и выше требуется macOS Big Sur 11.3 или выше. Если вы получаете неожиданные ошибки "License Mismatch", вам необходимо обновить macOS.

**[🔥Скачать крякнутую версию](https://t.me/+UYvAWYziQ5Y4ZWFi)**

## Примечания к сборке:

### Maya
- XGen IGS теперь рендериться, даже если автозагрузка не включена у xgenToolkit
- Когда новая shading группа назначается к XGen IGS, она теперь работает исправно
- Шум больше не "плавает" при использовании reference object
- Настройки параметров файлов RenderView HDR/LDR теперь синхронизируются с настройками output файлов Redshift
- Исправлена проблема, из-за которой интерфейс Physical Light не обновлял элементы управления тенью корректно при изменении ноды света

### 3ds Max
- Настройки параметров RenderView HDR/LDR теперь синхронизируются со сценой (Environment & Effects > Redshift Post FX > Output Switches)
- Добавлена поддержка Displacement в Incandescent material
- Привели в порядок интерфейс Incandescent material

### Houdini
- Исправлена проблема с метадатой EXR в прокси сценах
- Включены OSL ноды в сборке для Мак
- Настройки файлов RenderView HDR/LDR теперь синхронизируются с настройками RS ROP

### Во всех сборках
- Оптимизирован direct lightig, чтобы избежать ЧП, когда освещение не было сэмплировано в достаточной степени
- Исправлено недавно выявленный баг, из-за которого текстуры с mip-map имели черную заливку
- Исправлено выявленный баг в версии 3.0.60, из-за которого out-of-core система текстур могла крашиться,
