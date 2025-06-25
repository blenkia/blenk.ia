# Site Blenk.IA - Agência de Fluxo de Vendas e Automações com IA

## 📋 Sobre o Projeto

Site profissional desenvolvido para a agência Blenk.IA, especializada em fluxo de vendas e automações com inteligência artificial. O site foi criado com React e Tailwind CSS, seguindo as melhores práticas de design moderno e responsivo.

## 🚀 Como Hospedar na Netlify

### Opção 1: Deploy via Drag & Drop (Mais Simples)

1. Acesse [netlify.com](https://netlify.com) e faça login ou crie uma conta
2. Na dashboard, procure pela seção "Sites" 
3. Arraste e solte a pasta `dist` (que está dentro do projeto) diretamente na área indicada
4. Aguarde o upload e deploy automático
5. Seu site estará disponível em uma URL gerada automaticamente

### Opção 2: Deploy via Git (Recomendado para atualizações futuras)

1. Faça upload do código para um repositório no GitHub
2. Na Netlify, clique em "New site from Git"
3. Conecte sua conta do GitHub e selecione o repositório
4. Configure as seguintes opções:
   - **Build command**: `pnpm run build`
   - **Publish directory**: `dist`
5. Clique em "Deploy site"

## 📁 Estrutura do Projeto

```
bia-agency-site/
├── dist/                 # Arquivos de produção (usar para Netlify)
├── src/
│   ├── assets/          # Logos e imagens
│   ├── components/      # Componentes React
│   ├── App.jsx         # Componente principal
│   └── main.jsx        # Ponto de entrada
├── index.html          # Template HTML
└── package.json        # Dependências do projeto
```

## 🎨 Características do Site

- **Design Responsivo**: Funciona perfeitamente em desktop, tablet e mobile
- **Cores da Marca**: Verde (#2ECC71), preto e branco conforme solicitado
- **Seções Incluídas**:
  - Hero Section com CTA principal
  - Seção de Problema/Solução
  - Seção de Vendas
  - O que faz parte da assessoria (4 cards)
  - Etapas do método (Exploração, Lapidação, Escala, Extração)
  - Seção de custos de mercado
  - Formulário de contato completo
  - Footer profissional

## 🔧 Funcionalidades

- **CTAs Inteligentes**: Todos os botões direcionam para o formulário de contato
- **Navegação Suave**: Scroll automático entre seções
- **Formulário Completo**: Campos para nome, email, WhatsApp, empresa, setor e faturamento
- **Design Profissional**: Layout moderno e clean que transmite confiança

## 📱 Responsividade

O site foi desenvolvido com design responsivo, garantindo uma experiência perfeita em:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (até 767px)

## 🎯 Próximos Passos

1. Faça o upload dos arquivos para a Netlify
2. Configure um domínio personalizado (opcional)
3. Configure formulário de contato (recomenda-se Netlify Forms ou integração com serviços como Formspree)
4. Configure Google Analytics para acompanhar visitantes

## 📞 Suporte

Para dúvidas sobre hospedagem ou modificações no site, consulte a documentação da Netlify ou entre em contato com o desenvolvedor.

---

**Desenvolvido com ❤️ para Blenk.IA**

