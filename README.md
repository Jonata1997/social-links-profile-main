# Social Links Profile 🔗

Uma solução elegante e responsiva do desafio **Frontend Mentor** - Social Links Profile. Este projeto apresenta um card de perfil minimalista com links para redes sociais, implementado com HTML puro e CSS moderno.

## 🎯 Visão Geral

Este é um componente de card de perfil social que exibe informações sobre um usuário (nesse caso, Jessica Randall) e fornece links diretos para suas redes sociais. O design é limpo, centrado e totalmente responsivo.

## 📁 Estrutura do Projeto

```
.
├── index.html              # Estrutura HTML do perfil
├── style.css               # Estilos principais do projeto
├── reset.css               # CSS reset customizado
├── variables.css           # Variáveis CSS (cores e temas)
├── images/
│   ├── avatar-jessica.jpeg # Foto de perfil do usuário
│   └── favicon-32x32.png   # Favicon do site
└── README.md               # Este arquivo
```

## 🎨 Recursos

- **Design Responsivo**: Otimizado para todos os tamanhos de tela
- **Card de Perfil**: Componente limpo e centrado com:
  - Foto de perfil circular
  - Nome do usuário
  - Localização
  - Biografia pessoal
  - Links para redes sociais
- **Variáveis CSS**: Sistema de cores facilmente customizável
- **Tipografia Modern**: Utiliza Google Fonts (Inter)
- **Dark Mode Ready**: Estrutura preparada para tema escuro

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Marcação semântica
- **CSS3** - Estilos avançados com variáveis e flexbox
- **Google Fonts** - Tipografia (Inter)

## 📋 Seções do Projeto

### Arquivos Principais

| Arquivo | Descrição |
|---------|-----------|
| `index.html` | Estrutura HTML com card, imagem e links sociais |
| `style.css` | Estilos do card, tipografia e disposição dos elementos |
| `variables.css` | Definição de cores e valores reutilizáveis |
| `reset.css` | Reset de estilos padrão do navegador |

### Pasta Images

- `avatar-jessica.jpeg` - Foto de perfil do usuário (90x90px circular)
- `favicon-32x32.png` - Ícone da aba do navegador

## 🚀 Como Usar

1. **Clone o repositório** (se necessário):
   ```bash
   git clone <url-do-repositorio>
   cd social-links-profile-main
   ```

2. **Abra o arquivo** no navegador:
   - Duplo clique em `index.html` ou
   - Arraste o arquivo para a aba do navegador

3. **Customize conforme necessário**:
   - Edite `index.html` para alterar informações pessoais
   - Modifique `variables.css` para mudar cores
   - Atualize links da rede social com suas URLs

## 🎭 Personalização

### Mudar Cores
Edite `variables.css`:
```css
:root {
  --background-color: #141414;
  --card-color: #262626;
  --text-color: #ffffff;
  /* ... outras cores */
}
```

### Mudar Informações do Usuário
Edite `index.html`:
```html
<h1 class="name">Seu Nome</h1>
<p class="location">Your City, Country</p>
<p class="bio">"Sua biografia aqui"</p>
```

### Adicionar Links Reais
Substitua os `href="#"` pelos links reais de suas redes:
```html
<li><a href="https://github.com/seu-usuario">GitHub</a></li>
```

## 💡 Desafio Frontend Mentor

Este projeto foi desenvolvido como solução do desafio **Social Links Profile** do Frontend Mentor, focando em:
- Precisão no design
- Responsividade
- Código limpo e bem organizado
- Boas práticas CSS

## 📱 Responsividade

O projeto utiliza:
- **Flexbox** para alinhamento e distribuição
- **Unidades relativas** (px, %) para dimensionamento adaptativo
- **Variáveis CSS** para fácil manutenção

## 🔗 Links Úteis

- [Frontend Mentor](https://www.frontendmentor.io/) - Plataforma de desafios
- [Google Fonts - Inter](https://fonts.google.com/specimen/Inter) - Tipografia utilizada

## 📝 Notas

- Todos os links sociais estão com `href="#"` - atualize com suas URLs reais
- As imagens estão em formato JPEG e PNG dentro da pasta `images/`
- O projeto segue boas práticas de acessibilidade com atributos `alt`

## 👤 Autor

Desenvolvido como parte do curso **DevQuest** - Desafios Frontend Mentor.

---

**Última atualização**: Fevereiro de 2026

