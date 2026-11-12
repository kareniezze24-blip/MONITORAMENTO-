# Controle de rompimentos (protótipo)

Protótipo visual para registrar e acompanhar rompimentos de fibra (FTTH e backbone), com passagem de informação entre equipes.

**Todos os dados são fictícios.** Não digite informações reais neste site: ele é público.

## Telas
- **Dashboard**: indicadores, pendências mais antigas e reincidências
- **Pendências**: rompimentos abertos (em vermelho quando passam de 1 dia)
- **Finalizados**: rompimentos encerrados, com validação registrada
- **Trechos**: mapa esquemático com o dono de cada trecho (própria, A, C ou K)
- **Escala**: escala mensal (plantão 05h às 00h; fins de semana e feriados em rodízio)
- **Ocorrências**: quantas vezes cada rota ou PON caiu, separado por mês, com frequência das PONs e planilha para baixar (CSV, abre no Excel)

## Como ver
Abra o `index.html` no navegador. Os dados ficam só no navegador de quem usa.

## Publicar no GitHub Pages
1. Suba os arquivos para o repositório
2. Settings, Pages, Source: Deploy from a branch, branch `main`, pasta `/ (root)`

## Próximas etapas
- Backend (API) e banco de dados para compartilhar os registros entre as equipes
- Login e perfis (técnico, supervisor, administrador)
- Anexar fotos e exportar para Excel
- Avisos por Teams ou WhatsApp e integração com o sistema de monitoramento

Em produção o sistema roda em servidor interno, acessível só pela VPN. Dados reais nunca devem ser enviados a este repositório.
