# ✂️ Yan Barbeiro — sistema de agendamento

Protótipo web acadêmico para organizar agendamentos e a rotina de uma barbearia.

## ✨ O que você encontra

- Fluxo de agendamento para clientes, em etapas.
- Seleção de serviços, profissionais, datas e horários.
- Painel do barbeiro com resumo da agenda.
- Área administrativa para gerenciar a operação.
- Integração com Firebase Firestore e persistência local de endereços.

## 🧰 Tecnologias

HTML · CSS · JavaScript · Bootstrap · Firebase Firestore

## ▶️ Executar localmente

Os módulos JavaScript precisam ser servidos por HTTP. Na pasta do projeto, inicie um servidor local:

```bash
python -m http.server 8000
```

Acesse `http://localhost:8000` no navegador.

## 📁 Estrutura principal

| Arquivo | Responsabilidade |
| --- | --- |
| `index.html` | Telas e componentes da aplicação |
| `styles.css` | Estilos |
| `core.js` | Firebase, estado global e utilitários |
| `cliente.js` | Agendamento do cliente |
| `barbeiro.js` | Painel do profissional |
| `admin.js` | Administração |

> **Protótipo acadêmico:** as credenciais demonstrativas e a autenticação no cliente não devem ser usadas para proteger dados reais. Para produção, configure autenticação e regras de segurança no Firebase.
