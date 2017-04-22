# EvtTabCarreira

## Evento: evtTabCarreira

## Alias: 


## Modo de USO

```php
use NFePHPSocial\Event;

$std = new \stdClass();$evt = Event::evtTabCarreira($configJson, $std);
```

Onde:
- $std são inseridos os dados referentes ao evento.
- $configJson contêm as informações básicas da empresa.

A classe pode retornar: string XML, string JSON ou array com os dados
