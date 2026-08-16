# 💰 Controle de Dívidas - PWA

Aplicativo para gerenciar dívidas e parcelas, funcionando offline como Progressive Web App.

## 🚀 Funcionalidades

- ✅ Cadastro de dívidas com parcelas automáticas
- ✅ Controle de status (pendente, pago, atrasado)
- ✅ Dashboard com métricas em tempo real
- ✅ Filtros por status e credor
- ✅ Gráfico de progresso de cada dívida
- ✅ Exportação de dados (JSON)
- ✅ Funciona offline (PWA)
- ✅ Responsivo (celular, tablet, desktop)

## 📱 Como Instalar

### Android (Chrome)
1. Abra o app no Chrome
2. Toque no menu (3 pontos)
3. Selecione "Adicionar à tela inicial"
4. Confirme "Instalar"

### iOS (Safari)
1. Abra o app no Safari
2. Toque no botão "Compartilhar"
3. Selecione "Adicionar à tela inicial"
4. Confirme "Adicionar"

### Desktop (Chrome)
1. Abra o app no Chrome
2. Clique no ícone de instalação na barra de endereço
3. Confirme "Instalar"

## 🛠️ Tecnologias

- HTML5
- CSS3 (design moderno e responsivo)
- JavaScript (ES6+)
- IndexedDB (armazenamento local)
- PWA (Service Worker, Manifest)

## 📊 Estrutura de Dados

### Dívida
```javascript
{
  id: 1,
  credor: "Banco do Brasil",
  descricao: "Empréstimo Pessoal",
  valorTotal: 5000,
  numParcelas: 12,
  dataInicio: "2024-01-15",
  juros: 1.5
}