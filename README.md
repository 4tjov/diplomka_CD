# Diplomka
Diplomová práce zdrojový kód

## Požadavky
Iplementaci a testování vznikaly na operačním systému Ubuntu 20.04

Python 3.8.10

Brownie v1.17.1 - Python development framework for Ethereum

Slither 0.8.2

JS Node v16.14.2

## Brownie
V adresáři src/contracts jsou smart kontrakty PWN aplikace a testovacích tokenů.

### Kompilace
`$brownie compile`

### Lokální nasazení

V tomto lokálním nasazení testuji základní use case, popsaný v dipolomové práci.

`$brownie run scripts/deploy_pwn.py`


### Testování

`$brownie test coverage`

A pro zobrazení coverage graficky je potřeba zaponout GUI.

`$brownie gui`
