# Proposta Completa — Up_agencia

## 1. Visão Geral
Website moderno com foco em conversões vindas de Reels/TikTok. Paleta: azul (#2563EB) e branco. Principais seções: Hero, serviços, simulador de investimento, prova social e CTAs diretos para WhatsApp/Direct.

## 2. Tabela de Preços (Resumo)

| Pacote | Desenvolvimento Web | Criação de Vídeos | Divulgação / Tráfego | Investimento Estimado (EUR / R$) |
|---|---:|---|---|---:|
| Start Up | Landing Page Alta Conversão + SEO Básico | 2 Vídeos Verticais (Reels/TikTok) | Configuração de Perfil + Links | 450 € / R$ 2.500 |
| Growth Up (Recomendado) | Site Interativo Completo + Calculadora + Botão WhatsApp | 6 Vídeos Profissionais Curtos | Gestão de Anúncios (Meta Ads / TikTok Ads) | 850 € / R$ 4.800 |
| Pro Up (Premium) | Website Completo / E-commerce + Área de Gestão | 12 Vídeos Mensais + Edição Avançada | Campanha Completa de Escala + Suporte VIP | 1.500 € / R$ 8.500 |

> Observação: preços em reais são estimativas; ajuste para moeda local e impostos.

## 3. Código-Fonte
O site interativo foi gerado em `index.html` (código pronto para hospedar). O simulador atualiza o valor em tempo real e direciona para WhatsApp.

## 4. Estratégia de Divulgação
- Produção de criativos curtos (10s) otimizados para Reels/TikTok.
- Funil: Anúncio -> Simulador (site) -> Conversa no WhatsApp/Direct.
- Testes A/B de criativo + segmentação por interesse e comportamento.
- Escala progressiva: começar com verba reduzida, otimizar e então escalar campanhas vencedoras.
- Métricas-chaves: CPA, CTR, CVR (conversão de lead para reunião), CAC.

## 5. Implantação Rápida (Checklist)
- Registrar domínio da Up_agencia.
- Hospedar (Netlify, Vercel, ou hospedagem compartilhada) com SSL automático.
- Atualizar link do WhatsApp em `index.html` com número oficial.
- Conectar Google Analytics / Meta Pixel / TikTok Pixel.
- Configurar campanhas iniciais com públicos lookalike e remarketing.

## 6. Próximos passos sugeridos
1. Revisar e confirmar preços finais e escopo do pacote escolhido.
2. Fornecer número de WhatsApp e ativos de marca (logo, fontes, cores).
3. Preparar 2 criativos iniciais para teste A/B.
4. Publicar o site e iniciar campanhas de reconhecimento e tráfego.

---
Arquivo do site: [index.html](index.html)

## 7. Publicação automática (GitHub Pages)

Incluí um workflow de GitHub Actions que publica o conteúdo do repositório para o GitHub Pages automaticamente sempre que houver push para a branch `main`.

Passos para publicar agora:

1. Confirme que o repositório remoto está correto e faça push das alterações para `main`.
2. O workflow `.github/workflows/deploy-pages.yml` fará o deploy para a branch `gh-pages` automaticamente.
3. Aguarde alguns minutos e acesse `https://<seu-usuario>.github.io/<nome-do-repositorio>/` ou configure um domínio personalizado (CNAME).

Se preferir que eu faça o push e publique, autorize-me a executar o push no repositório (vou tentar usar as credenciais disponíveis no Codespace). Caso prefira, siga as instruções de push abaixo.

Comandos para publicar manualmente (local ou Codespace):

```bash
git add .
git commit -m "Site Up_agencia: versão profissional + workflow de deploy"
git push origin main
```

Após o push, verifique a aba 'Actions' no GitHub para acompanhar o deployment.
