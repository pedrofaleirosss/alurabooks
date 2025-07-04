# 📚 AluraBooks

Site front-end estiloso e responsivo para livraria de tecnologia, desenvolvido como projeto do curso de Front-End da Alura em 2023.  
Implementa carrossel interativo, menu hambúrguer responsivo, área de contato e rodapé completo.

🔗 [Veja a demonstração em GitHub Pages](https://pedrofaleirosss.github.io/alurabooks/)  
🔗 [Repositório no GitHub](https://github.com/pedrofaleirosss/alurabooks)

---

## 📌 Sobre o projeto

AluraBooks é um site de vitrine para livros de tecnologia com foco em experiência de usuário e responsividade.  
Inclui recursos como:

- Menu hambúrguer em telas mobile
- Carrossel de lançamentos e best sellers com **SwiperJS**
- Seção de “Talvez você também goste…”
- Seção de “Autor do mês”
- Seção de “Tópicos visitados recentemente”
- Formulário de contato e rodapé institucional com logos de instituições parceiras

### 📱 Responsivo e Mobile First

Desenvolvido com abordagem **mobile-first**, o layout se adapta perfeitamente para celulares, tablets e desktops.

---

## 🛠 Tecnologias utilizadas

- HTML5 semântico
- CSS3 modularizado (componentes divididos por área)
- Reset com `reset.css`
- [SwiperJS](https://swiperjs.com) para carrossel responsivo
- JavaScript minimal para inicializar o slider
- Google Fonts (Poppins, Josefin Sans)

---

## 🗂 Estrutura do projeto

```
alurabooks/
├── img/                  # Imagens usadas na interface
├── styles/               # Arquivos CSS por componente
│   ├── header.css
│   ├── banner.css
│   ├── carrossel.css
│   ├── topicos.css
│   ├── contato.css
│   └── footer.css
├── reset.css             # Reset CSS geral
├── style.css             # Import central dos estilos
├── index.html
└── README.md
```

---

## ▶️ Como executar localmente

1. Clone o repositório:
   ```
   git clone https://github.com/pedrofaleirosss/alurabooks.git
   ```
2. Acesse a pasta:
   ```
   cd alurabooks
   ```
3. Abra `index.html` no seu navegador.

---

## 🔄 Uso online (GitHub Pages)

O site está disponível online neste link:  
➡️ https://pedrofaleirosss.github.io/alurabooks/

---

## 🎞 Demonstrações

- **Modo desktop:**

![image](https://github.com/user-attachments/assets/a0c0a851-1d43-4c2c-9765-ec05768bf99a)
![image](https://github.com/user-attachments/assets/a09d4dd8-baa2-43e4-830d-57d93ce950fd)
![image](https://github.com/user-attachments/assets/f3506f27-e665-4edb-8466-1d88328ae946)
![image](https://github.com/user-attachments/assets/28f451aa-d79f-43f4-8524-ecf816bf6c37)
![image](https://github.com/user-attachments/assets/b3cc2e6a-5639-4982-bc83-ecf0452caa98)
  
- **Versão mobile:**

![image](https://github.com/user-attachments/assets/7eac5562-e0c0-4e03-ae0f-ec9cb2ed9289)
![image](https://github.com/user-attachments/assets/ed30571f-fb3c-4e98-99e3-3d0fe6c49e34)
![image](https://github.com/user-attachments/assets/489f227e-33f2-4e27-82f1-8818bfff05a6)

---

## ⚙️ SwiperJS – Carrossel

- Configuração no final de `index.html`:
  ```js
  const swiper = new Swiper('.swiper', {
    spaceBetween: 10,
    slidesPerView: 3,
    pagination: { el: '.swiper-pagination', type: 'bullets' },
    navigation: { nextEl: '.swiper-button-next', prevEl: '.swiper-button-prev' },
    autoplay: { delay: 5000 },
  });
  ```
- Carrossel automático, responsivo e navegável por gestos ou setas.

---

## ✅ Destaques do projeto

- Layout limpo e moderno com atenção à tipografia
- Arquitetura CSS modular
- Responsividade garantida com media queries
- Interatividade com SwiperJS

---

Desenvolvido com 💛 por [**Pedro Faleiros**](https://github.com/pedrofaleirosss)  
