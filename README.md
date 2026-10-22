# SpaceJur

Site institucional e landing de inscrição do Preparatório OAB da SpaceJur (Hub Jurídico, Manauara Shopping, Manaus). HTML, CSS e JS puros, sem build.

- `index.html`: site institucional
- `preparatorio-oab/index.html`: landing de inscrição
- `assets/style.css`: estilo compartilhado

Para rodar localmente:

```
python3 -m http.server 8080
```

## Pendências antes de ir ao ar

- `CRM_ENDPOINT` em `preparatorio-oab/index.html` está vazio: o envio do formulário é apenas simulado.
- Botões "Consultoria gratuita" e "WhatsApp" do site apontam para `#`.
- Placeholders de conteúdo: `[data]` (início das aulas), `R$ [●]` (investimento), `[mini-currículo]` e foto do Prof. Hamilton.
