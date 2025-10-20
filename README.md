# ☕ Café Aroma

Uma página web elegante e responsiva para apresentar a cafeteria **Café Aroma**, destacando seus produtos artesanais, ambiente acolhedor e localização.

---

## 🌐 Demonstração

Acesse o projeto localmente em seu navegador após abrir o arquivo `index.html`.  

OU 

Acesse o link da demonstração: [https://emersontlsd.github.io/Cafeteria-Com-Agente-IA/](https://emersontlsd.github.io/Cafeteria-Com-Agente-IA/)


---

## 🧩 Estrutura do Projeto

📂 projeto-cafe-aroma

┣ 📂 assets

┃     ┗ 📜 style.css

┣ 📂 images

    ┃ ┗ 🖼️ nathan-dumlao-6VhPY27jdps-unsplash.jpg
    
┗ 📜 index.html


---

## 🖥️ Tecnologias Utilizadas

- **HTML5** → Estrutura semântica da página  
- **CSS3** → Estilização moderna e responsiva  
- **Flexbox e Grid Layout** → Organização dos elementos  
- **Google Maps Embed** → Exibição da localização da cafeteria  

---

## 🧾 Descrição do Projeto

O **Café Aroma** é uma cafeteria fictícia que valoriza o sabor autêntico do café artesanal.  
A página foi projetada para destacar:

- **Identidade visual sofisticada** com tons terrosos e tipografia acolhedora  
- **Menu de cafés** com preços e descrições  
- **Mapa interativo** para localização  
- **Layout responsivo**, adaptando-se a qualquer dispositivo  

---

## 📸 Pré-visualização

A seção principal exibe uma imagem de fundo com sobreposição suave:

```css
.hero {
    background: linear-gradient(rgba(44,24,16,0.7), rgba(44,24,16,0.7)),
    url(images/nathan-dumlao-6VhPY27jdps-unsplash.jpg) center / cover;
}

📜 Código HTML Principal

<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="assets/style.css" />
    <title>Café Aroma</title>
  </head>
  <body>
    <header>
      <nav class="navbar">
        <div class="logo"><h1>Café Aroma</h1></div>
        <ul class="nav-links">
          <li><a href="#home">Início</a></li>
          <li><a href="#sobre">Sobre</a></li>
          <li><a href="#produtos">Produtos</a></li>
          <li><a href="#localizacao">Localização</a></li>
        </ul>
      </nav>
    </header>
    <main>
      <!-- Conteúdo das seções -->
    </main>
    <footer>
      <p>2025 Café Aroma - Todos os direitos reservados.</p>
    </footer>
  </body>
</html>

🎨 CSS Principal

body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    color: #333;
}

header {
    background-color: #2c1810;
    position: fixed;
    top: 0;
    width: 100%;
}

.hero {
    background: linear-gradient(rgba(44,24,16,0.7), rgba(44,24,16,0.7)),
    url(images/nathan-dumlao-6VhPY27jdps-unsplash.jpg) center / cover;
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}

🚀 Como Executar

1. Baixe o projeto ou clone o repositório:
    git clone https://github.com/Emersontlsd/Cafeteria-Com-Agente-IA.git

2. Abra a pasta do projeto:
    cd cafe-aroma

3. Execute o arquivo index.html em seu navegador.

📍 Autor

Desenvolvido com ☕ e 💻 por Emerson Souza
📧 emersontlsd@gmail.com

🪶 Licença
Este projeto é de uso livre para fins educacionais e de portfólio.
