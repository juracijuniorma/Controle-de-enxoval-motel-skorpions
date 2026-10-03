# 🛏️ Controle de Enxoval Motel Skorpions

Sistema web e aplicativo para controle de enxoval e gerenciamento de saídas/retornos de lavanderia do **Motel Skorpions**.

---

## 📱 Funcionalidades
- **Painel de Saldo:** Monitoramento em tempo real do Estoque Limpo (Rouparia), itens Em Lavagem, Avarias e Total Geral.
- **Itens Gerenciados:** Lençol de Casal, Fronha de Casal, Pano de Piso e Toalha de Banho.
- **Controle de Envolvidos:** Registro do funcionário do motel que conferiu/enviou/recebeu e do entregador/coletor da lavanderia.
- **Segurança e Auditoria:** Alterações e exclusões exigem identificação (ID de funcionário e Senha), mantendo registro histórico de quem fez a correção.
- **Impressão de Comprovante:** Geração de comprovante de coleta/entrega formatado para assinatura.
- **Exportação de Dados:** Exportação de histórico completo em arquivo Excel (.CSV).
- **Suporte a PWA (Aplicativo):** Pode ser instalado diretamente no celular (Android/iOS) ou PC, funcionando offline.

---

## 🔑 Credenciais Padrão de Autorização (Alteração/Exclusão)

Para realizar edições ou exclusões de lançamentos no sistema, utilize um dos acessos cadastrados:

| ID / Matrícula | Senha | Usuário |
| :--- | :--- | :--- |
| `101` | `1234` | Carlos (Gerente) |
| `102` | `1234` | Ana (Supervisora) |
| `ADMIN` | `admin` | Administrador |

---

## 💻 Tecnologias Utilizadas
- **HTML5**
- **CSS3** (Mobile-first e Design Responsivo)
- **JavaScript ES6+** (Armazenamento via `localStorage`, Service Worker e PWA)

---

## 📱 Como Instalar como Aplicativo

1. Acesse o sistema pelo navegador do celular ou computador.
2. Clique no banner azul no topo da página ou utilize a opção **"Adicionar à tela inicial"** / **"Instalar aplicativo"** do seu navegador (Chrome/Safari/Edge).
