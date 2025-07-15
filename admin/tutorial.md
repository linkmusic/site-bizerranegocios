### **Tutorial do Painel Administrativo – Bizerra Negócios**

Olá! Seja bem-vindo ao painel de controlo do seu site.

Este guia foi criado para o ajudar a gerir as informações e produtos da sua loja de forma fácil e rápida, sem precisar de mexer em nenhum código.

---

#### **1. Acesso e Secções do Painel**

* **Acesso:** Use o link [https://bizerra.shop/admin/](https://bizerra.shop/admin/) e as suas credenciais (e-mail e senha) para entrar.
* **Guia de Uso:** Onde você está agora.
* **Configurações Gerais:** Para editar informações, links e cores do site.
* **Produtos e Assinaturas:** Para gerir a sua lista de produtos.
* **Monetização (Google AdSense):** Para inserir os códigos de anúncio.

---

#### **2. Configurações Gerais**

Aqui, você pode alterar:
* **Título e Slogan:** O nome e a frase de efeito do seu site.
* **Cores do Tema:** Use a paleta para escolher as cores do site.
    * **Cor Principal:** Usada em destaques, botões e links.
    * **Cor de Fundo:** A cor escura de fundo do site.
    * **Cor do Texto:** A cor clara principal do texto.
* **Links de Suporte e Cupom de Desconto.**

Após qualquer alteração, clique sempre em **"Publicar"** no topo da página.

---

#### **3. Gestão de Produtos**

* **Editar:** Clique sobre um produto para alterar o seu Nome, Ícone, Preço, etc.
* **Adicionar:** Clique no botão "Adicionar novo" para criar um novo produto.
* **Remover:** Entre na edição de um produto e clique no botão "Excluir".

##### **Como Adicionar um Ícone ao Produto**
O campo "Ícone" usa a biblioteca Font Awesome. Para escolher um:
1.  Acesse a galeria: [**Font Awesome Free Icons**](https://fontawesome.com/v6/search?o=r&m=free)
2.  Procure pelo ícone que deseja (ex: "film", "tv", "spotify").
3.  Clique no ícone escolhido e copie o seu nome (ex: `fa-film`).
4.  Cole no campo "Ícone" do painel, adicionando `fas` ou `fab` na frente.
    * Ícones normais: `fas fa-film`
    * Ícones de marcas: `fab fa-spotify`

---

#### **4. Monetização com Google AdSense**

Para exibir anúncios, você precisa de uma conta aprovada no [Google AdSense](https://www.google.com/adsense/start/).

1.  No painel do seu site, vá para a aba **"Monetização (Google AdSense)"**.
2.  Você verá três campos para preencher:

##### **a) Script do Cabeçalho**
* No AdSense, após adicionar o seu site, a Google fornecerá um código de verificação. Ele começa com `<script...` e contém o seu ID de publicador (`ca-pub-xxxxxxxxxxxxxxxx`).
* Copie todo este código.
* Cole-o no campo **"Script do Cabeçalho (...)"** no seu painel.

##### **b) Códigos dos Blocos de Anúncios**
* No AdSense, vá para **Anúncios > Por bloco de anúncios** e crie um novo bloco (recomendamos "Anúncios de display").
* Configure o tamanho (ex: responsivo) e dê um nome a ele.
* Clique em "Criar". O AdSense irá gerar um código que também começa com `<script...`.
* Copie todo este código.
* Cole-o no campo **"Código do Bloco de Anúncios 1"** ou **"2"**. Você pode usar os dois para ter anúncios em locais diferentes do site.

3.  Após colar os códigos, clique em **"Publicar"**. Os anúncios podem levar algum tempo para começar a aparecer no site.