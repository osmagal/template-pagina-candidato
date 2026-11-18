# **Template: Página do Candidato**

Template moderno, responsivo e personalizável para páginas de apresentação e campanhas de candidatos políticos (Vereadores, Prefeitos, Deputados, etc.) ou figuras públicas.

---

## **Visão Geral**

Este template foi projetado para oferecer uma apresentação clara, profissional e acessível das propostas, biografia, notícias e canais de contato do candidato.

### **Recursos Principais**
- **Design Responsivo:** Otimizado para dispositivos móveis, tablets e desktops.
- **Seções Estruturadas:**
  - Hero com foto, slogan e número do candidato.
  - Biografia e trajetória política/social.
  - Principais eixos e propostas de governo.
  - Galeria de fotos e eventos.
  - Notícias e comunicados de campanha.
  - Formulário de contato, voluntariado e links para redes sociais.
- **Pronto para Deploy:** Configurado para hospedagem no [Firebase Hosting](https://firebase.google.com/docs/hosting) ou qualquer servidor estático (GitHub Pages, Vercel, Netlify).

---

## **Tecnologias Utilizadas**

- **HTML5 & CSS3**
- **Bootstrap 5**
- **JavaScript (Vanilla)**
- **Font Awesome & Bootstrap Icons**
- **Owl Carousel & Lightbox**
- **Firebase Hosting** (Arquivos `firebase.json` e `.firebaserc` inclusos)

---

## **Estrutura de Pastas**

```text
template-pagina-candidato/
├── public/
│   ├── css/            # Folhas de estilo (Bootstrap e customizado)
│   ├── img/            # Imagens, fotos e logotipos
│   ├── js/             # Scripts interativos
│   ├── lib/            # Bibliotecas de terceiros (Owl Carousel, Lightbox, etc.)
│   ├── 404.html        # Página de erro 404 personalizada
│   └── index.html      # Página principal da campanha
├── .firebaserc         # Configuração de projeto Firebase
├── firebase.json       # Parâmetros de deploy do Firebase Hosting
└── README.md           # Documentação do projeto
```

---

## **Como Personalizar**

1. Abra a pasta `public/`.
2. Edite `index.html` para alterar:
   - Nome, número e cargo do candidato.
   - Meta tags para compartilhamento em redes sociais (Open Graph / Twitter Cards).
   - Biografia, propostas e redes sociais.
3. Substitua as imagens na pasta `public/img/` pelas fotos oficiais da campanha.

---

## **Como Fazer o Deploy no Firebase Hosting**

1. Instale o Firebase CLI (caso não tenha):
   ```bash
   npm install -g firebase-tools
   ```
2. Faça login na sua conta Google:
   ```bash
   firebase login
   ```
3. Inicialize ou vincule ao seu projeto Firebase:
   ```bash
   firebase use --add
   ```
4. Realize o deploy:
   ```bash
   firebase deploy --only hosting
   ```

---

## **Licença**

Disponibilizado para livre uso e adaptação em campanhas e projetos correlatos.
