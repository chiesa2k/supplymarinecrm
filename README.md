# Supply Marine HVAC Management System
## Gestão de Equipamentos e Manutenções

Sistema web completo para gestão de equipamentos HVAC, RDOs, colaboradores e serviços.

---

## 📋 Características

✅ **Dashboard Executivo** - KPIs, gráficos com números visíveis  
✅ **Gestão de RDOs** - Criar, editar, deletar, expandir, exportar CSV  
✅ **35 Equipamentos Reais** - Dados técnicos completos da FPSO Bacalhau  
✅ **Gestão de Colaboradores** - Add, edit, delete, histórico de RDOs  
✅ **Catálogo de Serviços** - 8 serviços com CRUD completo  
✅ **Design Responsivo** - Funciona em desktop, tablet e mobile  
✅ **Paleta Supply Marine** - Cores oficiais da empresa  
✅ **Zero Dependências** - HTML5 + CSS3 + Vanilla JavaScript  

---

## 📁 Estrutura do Projeto

```
supply-marine-hvac/
├── index.html          # Aplicativo web completo
├── README.md           # Este arquivo
└── .gitignore         # Arquivo de exclusão Git
```

---

## 💻 Como Usar Localmente

### Opção 1: Abrir Diretamente
```bash
# Simplesmente abra o arquivo em um navegador
open index.html
```

### Opção 2: Usar um Servidor Local
```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (http-server)
npx http-server

# Com PHP
php -S localhost:8000
```

Acesse: `http://localhost:8000`

---

## 📊 Dados Inclusos

### Equipamentos
- **35 equipamentos** HVAC reais da FPSO Bacalhau
- Especificações técnicas completas (TR, kW, BTU/h)
- Compressores, condensadores, refrigerantes
- Tipos de atividades e locais

### Colaboradores
- **6 colaboradores (fictícios)** pré-cadastrados
- Contatos, cargos, especialidades
- Rastreamento de RDOs

### Serviços
- **8 tipos de serviços** disponíveis
- Descrições, categorias, periodicidades
- Custos estimados (fictícios)

### RDOs
- Funcionalidade completa de CRUD
- Exportação para CSV
- Validação de formulários

---

## 🎨 Paleta de Cores Supply Marine

| Cor | Código | Uso |
|-----|--------|-----|
| Primária Escura | #003366 | Headers, backgrounds |
| Primária Média | #1a5490 | Hover effects |
| Secundária | #0066CC | Buttons, links |
| Secundária Claro | #3399FF | Active tabs |
| Sucesso | #00AA44 | Status ok |
| Aviso | #FF9900 | Warnings |
| Erro | #CC0000 | Deletions |
| Branco | #FFFFFF | Backgrounds |

---

## 📱 Responsividade

A aplicação é 100% responsiva e funciona em:
- ✅ Desktop (1920px+)
- ✅ Tablet (768px - 1024px)
- ✅ Mobile (< 768px)

---

## 🔒 Segurança

- ✅ Armazenamento em memória (sem persistência entre reloads)
- ✅ Validação de formulários no cliente
- ✅ Sem dados sensíveis expostos
- ✅ Sem backend necessário

**Nota**: Para persistência de dados, integre com um backend (Node.js, PHP, Python, etc.)

---

## 🔄 Atualizar Dados

### Adicionar Novo Equipamento

Edite o arquivo `index.html` e localize a seção `equipamentos` no JavaScript:

```javascript
app.equipamentos.push({
    tag: "NOVO-TAG",
    tipo: "Tipo de Equipamento",
    fabricante: "Fabricante",
    modelo: "Modelo",
    tr: 0.00,
    kw: 0.0,
    btu: 0,
    tipoAtiv: "Tipo de Atividade",
    local: "Local",
    compressor: "Compressor",
    condensador: "Condensador",
    refrigerante: "Refrigerante"
});
```

### Adicionar Novo Serviço

```javascript
app.servicos.push({
    id: "SRV009",
    nome: "Nome do Serviço",
    desc: "Descrição",
    categoria: "Categoria",
    periodicidade: "Periodicidade",
    custo: 0
});
```

---

## 📈 Funcionalidades Principais

### Dashboard
- 4 KPIs com números em tempo real
- Gráfico de Status de Equipamentos (com números visíveis)
- Gráfico de RDOs por Status (com números visíveis)
- Atualização automática

### RDO (Relatório de Ordem)
- ✅ **Criar** - Novo RDO com auto-increment de ID
- ✅ **Expandir** - Ver todos os detalhes
- ✅ **Editar** - Modificar dados
- ✅ **Deletar** - Com confirmação
- ✅ **Filtrar** - Por status e colaborador
- ✅ **Exportar** - Download em CSV

### Equipamentos
- ✅ **Visualizar** - 35 equipamentos reais
- ✅ **Expandir** - Ver especificações técnicas completas
- ✅ **Editar** - Modificar dados
- ✅ **Deletar** - Remove RDOs vinculadas
- ✅ **Filtrar** - Por local e tipo

### Colaboradores
- ✅ **Adicionar** - Novo colaborador
- ✅ **Editar** - Modificar informações
- ✅ **Deletar** - Remover colaborador
- ✅ **Visualizar** - Histórico de RDOs

### Serviços
- ✅ **Expandir** - Ver detalhes completos
- ✅ **Editar** - Modificar serviço
- ✅ **Deletar** - Remover serviço
- ✅ **Catálogo** - 8 serviços disponíveis

---

## 🛠️ Próximas Fases

- [ ] Backend (Node.js / Python / PHP)
- [ ] Banco de dados (PostgreSQL / MySQL)
- [ ] Autenticação de usuários
- [ ] Persistência de dados
- [ ] Notificações por email
- [ ] Integração com IoT
- [ ] Mobile app
- [ ] API REST

---

## 📞 Suporte

**Supply Marine - HVAC Solutions**
- Website: www.supplymarine.com.br
- Email: achiesa@supplymarine.com.br

---

## 📄 Licença

Este projeto é propriedade da Supply Marine, sobre o desenvolvimento e cuidados de Andrey.

---

## 👥 Colaboradores

- Supply Marine

---

## 📝 Changelog

### v1.0 (30/10/2025)
- ✅ Lançamento inicial
- ✅ 35 equipamentos (Ficticios)
- ✅ CRUD completo para todos os módulos
- ✅ Dashboard com gráficos e números
- ✅ Exportação CSV
- ✅ Design responsivo

---

**Desenvolvido com ❤️ para Supply Marine**

*Sistema de Gestão HVAC - Supply Marine*
=======
# supplymarinecrm
