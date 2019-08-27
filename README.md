# Opdrachten met PHP

# Opdracht 1

Gegeven de volgende lijst met personen:

```php
$people = [
    [
        'name' => 'SidOfc',
        'age'  => 24,
        'birth_month' => 'October'
    ],
    [
        'name' => 'julicolo',
        'age'  => 23,
        'birth_month' => 'December'
    ]
]
```

Sorteer de personen in de bovenstaande `$people` variabelen op basis van `birth_month`.
Zorg hierbij dat latere maanden "hoger" in de output lijst komen te staan dan eerdere maanden.

Resultaat:

```php
$people = [
    [
        'name' => 'julicolo',
        'age'  => 23,
        'birth_month' => 'December'
    ],
    [
        'name' => 'SidOfc',
        'age'  => 24,
        'birth_month' => 'October'
    ]
]
```
