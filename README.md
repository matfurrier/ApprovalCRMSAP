# Sistema de Aprovações SAP 🚀

Este repositório contém a implementação de um sistema de aprovações automatizado integrado com o SAP/CRM. Permite aos usuários enviar pedidos de aprovação e visualizar o status de suas solicitações em tempo real.

## Funcionalidades 🛠

- **Autenticação Segura**: Autenticação segura para garantir que apenas usuários autorizados possam enviar e aprovar solicitações.
- **Envio de Pedidos de Aprovação**: Interface amigável para enviar novos pedidos de aprovação.
- **Aprovação/Rejeição de Pedidos**: Capacidade de aprovar ou rejeitar pedidos pendentes.
- **Notificações por E-mail**: Notificações por e-mail automáticas sobre o status da aprovação.
- **Registro de Atividades**: Registro completo de todas as atividades relacionadas a pedidos de aprovação.
- **Relatórios Detalhados**: Geração de relatórios detalhados para análise de desempenho e auditoria.

## Integração com SAP/CRM 💼

A integração com o SAP/CRM é feita através de uma API segura, proporcionando uma transição suave e precisa dos dados entre os sistemas.

## Tecnologias Utilizadas 💻

- **Backend**: Python, Express.js
- **Frontend**: React.js
- **Banco de Dados**: SAP HANA
- **Autenticação**: OAuth 2.0
- **Notificações**: SMTP

## Como Usar 📖

Este aplicativo foi criado para facilitar o processo de aprovação de pedidos no ambiente SAP/CRM. Abaixo estão as principais funcionalidades e como utilizá-las:

1. **Pedidos de Aprovação**:
   - Na tela inicial, temos todos os pedidos que foram inseridos pelo SAP ou CRM
   - Os pedidos podem estar em três estados: Pendente, Aprovado ou Rejeitado.
![principal](https://github.com/matfurrier/ApprovalCRMSAP/assets/30526394/cc6ac30f-6709-4d52-947c-412469048584)

2. **Detalhes dos Pedidos** :
   - Neste componente que se abre, você tem uma visão mais abrangente do item.
   - Você pode ver todos os detalhes e tomar uma decisão de aprovação ou rejeição.
![detalhes](https://github.com/matfurrier/ApprovalCRMSAP/assets/30526394/82cf75c6-a9e0-4c56-8cce-b034594400df)

3. **Notificações por E-mail**:
   - Receba notificações por e-mail sempre que o status de um pedido mudar.
   - As notificações por e-mail incluem detalhes do pedido e informações sobre quem aprovou ou rejeitou o pedido.
![email](https://github.com/matfurrier/ApprovalCRMSAP/assets/30526394/7e99754e-9d1e-4180-a139-65a7266acf67)

## Como Contribuir 👥
Valorizamos a contribuição da comunidade para aprimorar a segurança e eficácia da assinatura digital. Se você tiver sugestões, melhorias ou encontrar problemas, fique à vontade para abrir uma [issue](https://github.com/matfurrier/ApprovalsSAP/issues) ou enviar um pull request. Seu feedback é bem-vindo!

## 📄 Licença
Este projeto está licenciado sob a Licença MIT. Consulte o arquivo `LICENSE` para obter mais informações.

## 📬 Contato
Para mais informações ou dúvidas sobre o DS Sign, entre em contato através do e-mail [matfurrier@gmail.com](mailto:matfurrier@gmail.com).

Link do Projeto: [https://github.com/matfurrier/ApprovalCRMSAP](https://github.com/matfurrier/ApprovalCRMSAP)
