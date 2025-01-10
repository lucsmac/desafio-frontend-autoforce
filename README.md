# Desafio Técnico - Desenvolvedor Front-end Junior

Bem-vindo(a) ao desafio técnico da vaga de **Desenvolvedor Front-end Junior**! 🎉

O objetivo deste desafio é avaliar suas habilidades técnicas em desenvolvimento front-end com React, seu olhar para detalhes e sua capacidade de escrever um código limpo, escalável e fácil de manter.

Esperamos que você demonstre domínio em aspectos fundamentais de desenvolvimento web, como responsividade, acessibilidade, performance e boas práticas.


## 🎯 Objetivo do Desafio

Você deverá construir uma página baseada no protótipo fornecido ([link do layout no Figma](https://www.figma.com/design/mEuuuja11kYw9M9swY69wl/Desafio-Genius?node-id=0-1&p=f&t=go1lJa0CjhRyCFY3-0)). Essa página exibe informações sobre um veículo e dados institucionais, obtidos por meio de uma **Fake API** que você deve implementar.


## 🛠️ Requisitos Técnicos

### 1. **Tecnologias e Ferramentas**

- Utilize **React puro** (sem frameworks adicionais como Next.js ou Remix).
- Escolha a abordagem que considerar mais adequada para gerenciar estado e interagir com a API (e.g., Context API, hooks, etc.).
- Utilize CSS ou pré-processadores (como Sass) para estilização.
- Opcionalmente, use bibliotecas para gerenciamento de responsividade (e.g., CSS Grid, Flexbox).

### 2. **Fake API**

- Você pode estruturar a Fake API como preferir (JSON Server, arquivos estáticos, ou mesmo mock em memória).
- A Fake API deve conter:
  - **Endpoint de veículo** (`/vehicle`): fornece os dados do veículo exibido na página.
  - **Endpoint de dados institucionais** (`/company`): fornece informações institucionais exibidas no rodapé.

### 3. **Qualidades do Front-end**

Seu projeto será avaliado com base em:

- **Responsividade:** O layout deve se ajustar a diferentes tamanhos de tela.
- **Performance:** Minimize carregamentos desnecessários e otimize o tempo de resposta da interface.
- **Acessibilidade:** Use boas práticas como labels, ARIA e navegação com teclado.
- **Escalabilidade:** Estruture o código para facilitar a adição de novas funcionalidades.
- **Design:** Garanta que a interface final esteja alinhada ao protótipo fornecido.


## 📝 Instruções

### Etapas para completar o desafio:

1. **Setup do Projeto**

   - Crie uma aplicação React usando `create-react-app` ou uma configuração própria.
   - Organize o código seguindo boas práticas de arquitetura (ex.: separação de componentes, hooks, etc.).

2. **Fake API**
   - Estruture e disponibilize a Fake API localmente ou como parte do seu projeto.
   - Utilize os seguintes dados como base:

#### Dados do Veículo (`/vehicle`)

```json
{
  "id": 1,
  "name": "BMW Série 4 Cabrio",
  "price": 179950,
  "features": {
    "consumption": "14.7 km/l",
    "engine": "999 cm3",
    "power": "75 cv",
    "speed": "154 km/h"
  },
  "image": "link_da_imagem_do_veículo",
  "legal_text": "Valor de tabela (código 823839), ano/modelo 18/19 à vista a partir de R$ 179.950 ou financiado com entrada de R$ 40.490 (40%) e mais 24 prestações mensais de R$ 1.286, taxa de juros 0% a.m. e 0% a.a. Total da operação: R$ 205.874. Oferta válida para veículos com pintura sólida."
}
```

#### Dados Institucionais (`/company`)

```json
{
  "company_name": "AUTO FORCE PLATAFORMA DE MARKETING DIGITAL LTDA",
  "cnpj": "22.580.947/0001-06",
  "address": "Av. Prudente de Morais, 3966, Lagoa Nova, Natal/RN – CEP 59056-200",
  "phone": "84987654321",
  "whatsapp": "84912345678"
}
```

> Observação: Os campos phone e whatsapp devem ser exibidos no front-end com uma formatação apropriada (e.g., (84) 99999-9999).

3. **Desenvolvimento da Página**

   - Siga o protótipo para criar o layout, garantindo fidelidade ao design.
   - Faça uso de boas práticas para estilização e responsividade.

4. **Entrega**
   - Faça o upload do código em um repositório público no GitHub.
   - Inclua um arquivo `README.md` no repositório explicando:
     - Como executar a aplicação.
     - Quais decisões técnicas foram tomadas.
     - Quais melhorias adicionais poderiam ser feitas, caso houvesse mais tempo.


## 🔍 Avaliação

Os critérios de avaliação incluem:

1. **Qualidade do Código:** clareza, organização e consistência.
2. **Fidelidade ao Protótipo:** quão próximo o resultado final está do design proposto.
3. **Boas Práticas:** aplicação de padrões modernos de desenvolvimento.
4. **Funcionalidade:** a aplicação funciona conforme o esperado?
5. **Criatividade:** ideias ou melhorias além do escopo proposto serão valorizadas.


## 🌟 Sugestões Extras

Os itens abaixo **não são obrigatórios nem desclassificatórios**, mas, para se destacar, considere adicionar as seguintes funcionalidades:

1. **Captura de Leads:** Ao clicar no botão "Tenho Interesse", exiba um modal ou formulário para capturar informações do usuário (ex.: nome, telefone e e-mail).
2. **Navegação para Outras Ofertas:** Adicione um componente que permita navegar para outras ofertas, como uma carrossel ou lista de veículos disponíveis.
3. **Detalhes de Compartilhamento:** Inclua botões de compartilhamento social (ex.: WhatsApp, Facebook) para facilitar o envio do link do veículo.
4. **Animações:** Adicione animações leves para transições e interações do usuário, garantindo uma experiência fluida.
5. **Teste Básico:** Crie um teste unitário para validar que os dados do veículo estão sendo corretamente renderizados na interface.
6. **Estilização**: Use variáveis no CSS para temas ou cores.
7. **Documentação**: Documente seu código com comentários relevantes.

---

## 📩 Dúvidas

Caso tenha alguma dúvida, entre em contato com o recrutador:

- **Pedro Duca:** pedro.duca@autoforce.com

Boa sorte e acelere no desafio! 🚀
