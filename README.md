
# Compra Barato

Aplicativo mobile gratuito para comparar preços de supermercados por lista de compras, destacar o supermercado mais barato e abrir a rota até o local escolhido — ajudando o usuário a economizar tempo e dinheiro com decisões rápidas e confiáveis.

---

# Visão geral

Compra Barato permite ao usuário montar listas de compras com autocomplete, calcular o total da lista em supermercados próximos usando preços atualizados, exibir a economia em R$ e %, destacar visualmente a melhor opção e iniciar navegação até o mercado selecionado. O foco do MVP é velocidade, precisão de preços e simplicidade de uso.

---

# Funcionalidades principais (MVP)

- Lista de compras: adicionar/editar/remover itens; autocomplete e sugestões.

- **Comparação de preços**: cálculo do total por supermercado e ordenação por menor preço.

 - **Destaque do mais barato**: etiqueta visual clara e exibição de economia (R$ e %).

- **Abrir rota**: integração com app de mapas para iniciar navegação.

- **Cache offline básico**: usar últimos preços quando a rede estiver instável.

- **Permissões e privacidade**: solicitação contextual de localização com explicação do uso.

---

# Tecnologias sugeridas

- **Mobile**: React Native ou Flutter.

- **Backend**: Node.js (Express) ou Python (FastAPI).

- **Banco de dados**: PostgreSQL.

- **Mapas**: Google Maps SDK / Mapbox.

- **Analytics**: Amplitude / Mixpanel.

- **Hospedagem**: Heroku / Vercel / AWS (EC2, RDS).

---

# Métricas para o MVP

- **Ativação**: % usuários que criam lista e comparam.

- **Conversão para rota**: % que clicam em “Abrir rota”.

- **Economia média**  (R$) por usuário.

- **Tempo para resultado** (meta < 2s).
---

# Roadmap curto (próximos passos)

- Piloto segmentado (150–300 usuários).

- Ajustes de UX e correção de dados conforme feedback.

- Escalar fontes de preço e cobertura geográfica.

- Parcerias com redes e integração de inventário (opcional futuro).