# EcoPonto GO

Assistente de reciclagem para Goiânia – GO, com foco em usabilidade e acessibilidade.
Projeto da Atividade Extensionista III (UNINTER) – ODS 11, 12 e 13.

## Tecnologias
HTML5, CSS3 e JavaScript (sem frameworks). Testes: Python + Playwright.

## Como usar
Abra `index.html` no navegador (de preferência em modo celular).

## Testes
```
pip install playwright && playwright install chromium
python tests/test_app.py
```

## Fluxo de versionamento (GitHub Flow)
`main` sempre estável; uma branch curta por funcionalidade (`feature/mapa`, `feature/acessibilidade`); commits descritivos; merge via Pull Request.

## Observação
Os pontos de coleta são dados de demonstração com localização aproximada.
