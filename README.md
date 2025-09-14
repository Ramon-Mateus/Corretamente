# Corretamente

## Sitemap

```mermaid

flowchart LR

Login --> Dashboard
Login --> Registro
Registro --> Dashboard
Dashboard --> det[Detalhar cliente]
Dashboard --> ed[Editar cliente]
det[Detalhar cliente] --> ge[Gerar recibo de locacao]
```