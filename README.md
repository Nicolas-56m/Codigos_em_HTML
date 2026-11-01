# Códigos em HTML - Feitos por mim (para estudo)

## FASE 1 - Exercícios (Básico)
<img src="https://img.shields.io/badge/FEITO NO-VScode-red">

### 1-) Crie uma página HTML que mostre: Seu nome, sua idade e sua cidade.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Minha página</title>
</head>
<body>

  <h1>Meu nome é Nicolas</h1>
  
  <p>Tenho 16 anos</p>
  <p>Moro em Jaguariúna</p>
  
</body>
</html>
```

### 2-) Faça uma página com esses títulos: Meu site, sobre mim, meus estudos, e meus hobbies.

```HTML
<!DOCTYPE html>  
<html lang="pt-BR">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Minha página</title>  
</head>  
<body>    

  <h1>Meu site</h1>  
  <p>Minhas informações</p>  
  
  <h2>Sobre mim</h2>  
  <p>Estudo no Senai</p>   
  
  <h2>Meus Estudos</h2>  
  <p>Estudo programação</p>    
  
  <h2>Meus hobbies</h2>  
  <p>Gosto de andar de bicicleta</p> 

</body>  
</html>
```

### 3-) Crie uma página chamada "Meus hobbies". Faça uma lista com pelo menos 5 hobbies.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meus hobbies</title>
</head>
<body>

  <h1>Meus hobbies</h1>
  
  <ul>
    <li>Jogar</li>
    <li>Assistir séries</li>
    <li>Programar</li>
    <li>Soltar pipa</li>
    <li>Andar de bicicleta</li>
  </ul>

</body>
</html>
```

### 4-) Lista numerada. Crie uma página chamada "Minha rotina". Faça uma lista numerada com 5 coisas que você faz durante o dia.

```HTML
<!DOCTYPE html>  <html lang="pt-BR">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Minha rotina</title>  
</head>  
<body>    
  
  <h1>Minha rotina</h1>  
  
  <ol>
    <li>Acordo</li>
    <li>Tomo café</li>
    <li>Escovo os dentes</li>
    <li>Às vezes estudo</li>
    <li>Vou fazer algo</li>
  </ol>
  
</body>  
</html>
```

### 5-) Links. Crie uma página chamada "Meus sites". Coloque links para: Google, YouTube e GitHub.

```HTML
<!DOCTYPE html>  <html lang="pt-BR">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Meus sites</title>  
</head>  
<body>    
  
  <h1>Meus sites</h1>  
  
  <ul>
    <li><a href="https://www.google.com">Google</a></li>
    <li><a href="https://www.youtube.com">YouTube</a></li>
    <li><a href="https://github.com">GitHub</a></li>
  </ul>
  
</body>  
</html>
```

## FASE 2 - Exercícios (Básico-Intermediário)
<img src="https://img.shields.io/badge/FEITO NO-VScode-blue">

### 6-) Crie uma página chamada "Sobre mim". Ela deve ter um ```<h1>```, um parágrafo falando sobre você, um ```<h2>``` chamado "Meus hobbies". Uma lista com 5 hobbies. Um ```<h2>``` chamado "Meus estudos". Um parágrafo sobre seus estudos.

```HTML
<!DOCTYPE html>  
<html lang="pt-BR">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Sobre mim</title>  
</head>  
<body>    
  
  <h1>Sobre mim</h1>
  
  <p>Sou estudante do Senai e faço DS</p>
  
  <h2>Meus hobbies</h2>
  
  <ul>
    <li>Andar de bike</li>
    <li>Soltar pipa</li>
    <li>Programar</li>
    <li>Ouvir música</li>
    <li>Assistir filmes e séries</li>
  </ul>
  
  <h2>Meus estudos</h2>
  <p>Estudo programação e faço atividades</p>
  
</body>  
</html>
```

### 7-) Crie uma página sobre seu animal favorito. Ela deve ter: Título, imagem e um parágrafo explicando sobre o animal.

```HTML
<!DOCTYPE html>  
<html lang="pt-BR">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Animal favorito</title>  
</head>  
<body>    
  
  <h1>Animal favorito</h1>
  
  <img 
    src="https://media.istockphoto.com/id/1130682008/pt/foto/dog-in-a-field-os-flowers.jpg?s=612x612&w=0&k=20&c=zfX2COrv9IWuoP8uMxHi_RVs3uzADJXzV2GCrHUZzgE="
    alt="Um cachorro feliz"
    width="400">
  
  <p>Cachorro é um companheiro, dependendo da criação se torna um animal obediente e dócil.</p>
  
</body>
</html>
```

### 8-) Imagem + lista. Pegue o exercício 7 e acrescente uma lista: Característica do animal. (Continuação do exercício 7)!.

```HTML
<!DOCTYPE html>  
<html lang="pt-BR">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Animal favorito</title>  
</head>  
<body>    
  
  <h1>Animal favorito</h1>
  
  <img 
    src="https://media.istockphoto.com/id/1130682008/pt/foto/dog-in-a-field-os-flowers.jpg?s=612x612&w=0&k=20&c=zfX2COrv9IWuoP8uMxHi_RVs3uzADJXzV2GCrHUZzgE="
    alt="Um cachorro feliz"
    width="400">
  
  <p>Cachorro é um companheiro, dependendo da criação se torna um animal obediente e dócil.</p>

  <h2>Características do animal</h2>
  
  <ol>
    <li>Olfato superpoderoso</li>
    <li>Focinho único</li>
    <li>Leal e companheiro</li>
    <li>Inteligência e aprendizado</li>
    <li>Comunicação corporal</li>
  </ol>
  
</body>  
</html>
```
### 9-) Formatação de texto: Crie uma página explicando alguma coisa que você conhece. Você deverá utilizar  ```<strong>```, ```<em>``` e ```<mark>```.

```HTML
<!DOCTYPE html>  
<html lang="pt-BR">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Formatação de texto</title>  
</head>  
<body>    
  
  <h1>Computador</h1>
  
  <p>
    <strong>Memória RAM,</strong>
    <strong>Memória SSD,</strong>
  
    <em>Monitor Gamer,</em>
    <em>Gabinete,</em>
  
    <mark>Placa-Mãe,</mark>
    <mark>Processador.</mark>
  </p>
  
</body>  
</html>
```

### 10-) Tabela. Crie uma tabela com 5 produtos. Ela deverá ter: Produto | Preço | Quantidade. Você precisará aprender: ```<table>```, ```<tr>```, ```<th>``` e ```<td>```.

```HTML
<!DOCTYPE html>  
<html lang="pt-BR">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Tabela</title>  
</head>  
<body>    
  
  <h1>Tabela de produtos</h1>
  
  <table>
    <tr>
      <th>Produto</th>
      <th>Preço</th>
      <th>Quantidade</th>
    </tr>
    
    <tr>
      <td>Mouse</td>
      <td>R$ 50,00</td>
      <td>2</td>
    </tr>
     
    <tr>
      <td>Teclado</td>
      <td>R$ 80,00</td>
      <td>4</td>
    </tr>
     
    <tr>
      <td>Monitor</td>
      <td>R$ 500,00</td>
      <td>12</td>
    </tr>
     
    <tr>
      <td>Gabinete</td>
      <td>R$ 100,00</td>
      <td>18</td>
    </tr>
    
    <tr>
      <td>Processador</td>
      <td>R$ 700,00</td>
      <td>7</td>
    </tr>
  </table>
  
</body>  
</html>
```

### 11-) Tabelas de alunos. Crie uma tabela chamada "Notas dos alunos". Colunas: Nome | Nota 1 | Nota 2 | Média. Cadastre 5 alunos fictícios. Use a estrutura do ex 5.

```HTML
<!DOCTYPE html>  
<html lang="pt-BR">  
<head>  
  <meta charset="UTF-8">  
  <meta name="viewport" content="width=device-width, initial-scale=1.0">  
  <title>Tabela de alunos</title>  
</head>  
<body>    
  
  <h1>Notas dos alunos</h1>
  
  <table>
    <tr>
      <th>Nome</th>
      <th>Nota 1</th>
      <th>Nota 2</th>
      <th>Média</th>
    </tr>
    
    <tr>
      <td>Gabriel</td>
      <td>5</td>
      <td>4</td>
      <td>4,5</td>
    </tr>
     
    <tr>
      <td>Júlia</td>
      <td>9</td>
      <td>10</td>
      <td>9,5</td>
    </tr>
     
    <tr>
      <td>Rafaela</td>
      <td>10</td>
      <td>7</td>
      <td>8,5</td>
    </tr>
     
    <tr>
      <td>Mateus</td>
      <td>8</td>
      <td>2</td>
      <td>5</td>
    </tr>
    
    <tr>
      <td>Zézão</td>
      <td>10</td>
      <td>10</td>
      <td>10</td>
    </tr>
  </table>
  
</body>  
</html>
```

### 12-) Formulário Básico. Crie uma página chamada "Cadastro". Ela deve pedir: Nome, e-mail, senha e um botão enviar. Use ```<form>```, ```<label>```, ```<input>``` e ```<button>```.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cadastro</title>
</head>
<body>

  <h1>Cadastro</h1>

  <form>
    <label for="nome">Nome:</label>
    <input type="text" id="nome"><br><br>

    <label for="email">E-mail:</label>
    <input type="email" id="email"><br><br>

    <label for="senha">Senha:</label>
    <input type="password" id="senha"><br><br>

    <button type="submit">Enviar</button>
  </form>
  
</body>
</html>
```

### 13-) Formulário completo. Pegue o exercício 12 e acrescente idade, telefone, e data de nascimento. Descubra os ```<input>```. (Continuação do exercício 12)!. 

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cadastro</title>
</head>
<body>

  <h1>Cadastro</h1>

  <form>
    <label for="nome">Nome:</label>
    <input type="text" id="nome"><br><br>

    <label for="email">E-mail:</label>
    <input type="email" id="email"><br><br>

    <label for="senha">Senha:</label>
    <input type="password" id="senha"><br><br>

    <label for="idade">Idade:</label>
    <input type="number" id="idade" name="idade"><br><br>

    <label for="telefone">Telefone:</label>
    <input type="tel" id="telefone" name="telefone"><br><br>

    <label for="nascimento">Data de nascimento:</label>
    <input type="date" id="nascimento"><br><br>

    <button type="submit">Enviar</button>
  </form>
  
</body>
</html>
```

### 14-) Escolhas. Pegue o formulário do exercício 13 e acrescente: Sexo. Utilize rádio. Linguagens que você conhece: utilize checkbox,  estado: utilize um ```<select>``` com pelo menos 5 estados.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cadastro completo</title>
</head>
<body>

  <h1>Cadastro</h1>

  <form>
    <label for="nome">Nome:</label>
    <input type="text" id="nome"><br><br>

    <label for="email">E-mail:</label>
    <input type="email" id="email"><br><br>

    <label for="senha">Senha:</label>
    <input type="password" id="senha"><br><br>

    <label for="idade">Idade:</label>
    <input type="number" id="idade" min="0" max="100"><br><br>

    <label for="telefone">Telefone:</label>
    <input type="tel" id="telefone"><br><br>

    <label for="nascimento">Data de nascimento:</label>
    <input type="date" id="nascimento"><br>

    <p><strong>Sexo:</strong></p>

    <input type="radio" id="masculino" name="sexo" value="masculino">
    <label for="masculino">Masculino</label>

    <input type="radio" id="feminino" name="sexo" value="feminino">
    <label for="feminino">Feminino</label><br><br>

    <p><strong>Linguagens que você conhece:</strong></p>

    <input type="checkbox" id="html" name="linguagens" value="html">
    <label for="html">HTML</label>

    <input type="checkbox" id="css" name="linguagens" value="css">
    <label for="css">CSS</label>

    <input type="checkbox" id="js" name="linguagens" value="JavaScript">
    <label for="javascript">JavaScript</label>

    <input type="checkbox" id="python" name="linguagens" value="Python">
    <label for="python">Python</label><br><br>

    <label for="estado"><strong>Estado:</strong></label>

    <select id="estado" name="estado">
      <option value="">Selecione seu estado</option>
      <option value="sp">São Paulo</option>
      <option value="rj">Rio de Janeiro</option>
      <option value="mg">Minas Gerais</option>
      <option value="ba">Bahia</option>
      <option value="pr">Paraná</option>
      <option value="sc">Santa Catarina</option>
    </select><br><br>

    <button type="submit">Enviar</button>
  </form>

</body>
</html>
```

### 15-) Página do produto. Agora crie uma página para um produto, imagem, descrição, preço, lista com características, tabela com informações, link e botão. 

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Produto</title>
</head>
<body>

  <h1>Compra</h1>
  
  <h3>Gabinete Gamer</h3>

  <img
    src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcSYEKSWN1aWYCkgy5jM0AVtfdZC35ruvfI93QTacX2BRzqhH6Y8isRat1ZJvSjwRn5VNzMbcekw0kce2v8wjf17-EXyMqk0D1ebdR7HEkSke3yrtwkKBZfeoClFyzHHjfoNTRAfMDc0WQc&usqp=CAc"
    alt="Gabinete Gamer Branco"
    width="400">

  <p>Gabinete Gamer Branco para PC com 4 ventoinhas RGB (3 na frente e 1 atrás).</p>
  <p><em><strong>R$ 182,21</strong></em></p>

  <ul>
    <li>Gabinete Gamer</li>
    <li>Cor Branco</li>
    <li>L * 65cm, AL * 50cm</li>
    <li>Vidros laterais</li>
  </ul>

  <table>
    <tr>
      <th>Compartimento</th>
      <th>Garantia</th>
      <th>Recomendações</th>
    </tr>

    <tr>
      <td>Peças de largura de até *64cm. Peças de altura de até *30cm</td>
      <td>GamerTech</td>
      <td>Garantia de 24 meses para defeitos</td>
      <td>Não deixá-lo em lugar muito fechado</td>
    </tr>
  </table>

  <a href="https://www.mercadolivre.com.br/up/MLBU4912537356?matt_tool=38524122&pdp_filters=item_id:MLB7487386522&ua=ooNq45mCUm4zbQM82t26-AlAVykb1B8t710I5-Cfx_I_6Emi#origin=share&sid=share&wid=MLB7487386522&action=copy">Gabinete Gamer Branco</a><br><br>

  <button type="button">Adicionar no Carrinho</button>

</body>
</html>
```

### 16-) Página de filme. Crie uma página sobre um filme. Com título, imagem, descrição, ano, gênero, lista com personagens e link.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Filme</title>
</head>
<body>

  <h1>Filme</h1>
  <h2>Pânico 2</h2>

  <img
    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSZGjwvkYr8Oq9YtKwAbLYSLksrKaFBDOVQPGkd0n_7TA&s=10"
    alt="Capa do filme"
    width="400">

  <p>
    Pânico 2 é um filme de terror slasher lançado em 1997 dirigido por Wes Craven e escrito por Kevin Williamson.
  </p>

  <p><strong>Ano de lançamento:</strong> 1997</p>
  <p><strong>Gênero(s):</strong> Terror e Suspense</p>

  <ul>
    <li>Sidney Prescott <em>(Protagonista)</em></li>
    <li>Gale Weathers</li>
    <li>Dewey Riley</li>
    <li>Randy Meeks</li>
    <li>Cotton Weary</li>
  </ul>
  
  <form>
    <input type="radio" id="p" name="filme" value="p">
    <label for="p">Paramount</label>
    
    <input type="radio" id="pv" name="filme" value="pv">
    <label for="pv">Prime Video</label>
  </form><br>

  <a href="https://play.google.com/store/apps/details?id=com.cbs.ca">Paramount+</a>
  <a href="https://www.netflix.com/br/title/1181550?preventIntent=true&source=35&fromWatch=true">Netflix</a>
</body>
</html>
```

## FASE 3 - Exercícios (Básico-Difícil)
<img src="https://img.shields.io/badge/FEITO NO-VScode-orange">

### 17-) Página de jogo. Crie uma página sobre um jogo. Inclua: Nome, imagem, descrição, requisitos, listas de características, tabelas de informações e link para o site oficial.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sobre o Free Fire</title>
</head>
<body>

  <h1>Free Fire</h1>

  <img
    src="https://escolaeducacao.com.br/wp-content/uploads/2021/08/ff-capa.jpg"
    alt="Capa de carregamento antiga de jogo"
    width="400">

  <h4>Descrição do jogo</h4>
  <p>Jogo de batalha online para celular com partidas de aproximadamente 10 minutos, tendo de exemplo os modos de jogo com Battle Royale e Contra Squad.</p>

  <h4>Características</h4>
  
  <ol>
    <li>Battle Royale</li>
    <li>Contra Squad</li>
    <li>Partidas rápidas</li>
    <li>Personagens</li>
    <li>Free Fire MAX</li>
  </ol>

  <h4>Tabela de informações</h4>

  <table>
    <tr>
      <th>Informação</th>
      <th>Dado</th>
    </tr>
    
    <tr>
      <td>Desenvolvedora</td>
      <td>Garena</td>
    </tr>
    
    
    <tr>
      <td>Plataforma</td>
      <td>Android/IOS/PC</td>
    </tr>
    
    <tr>
      <td>Gênero</td>
      <td>Battle Royale</td>
    </tr>
    
    <tr>
      <td>Modelo</td>
      <td>Gratuito para jogar</td>
    </tr>
  </table><br>

  <a href="https://play.google.com/store/apps/details?id=com.dts.freefireth">Link Oficil do Jogo</a>

</body>
</html>
```

### 18-) Página de time. Crie uma página sobre um time de futebol. Inclua: Nome, escudo/imagem, descrição, títulos, jogadores, tabelas com informações e links.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Time de futebol</title>
</head>
<body>

  <h1>Clube de Regatas do Flamengo</h1>

  <img
    src="https://encrypted-tbn1.gstatic.com/shopping?q=tbn:ANd9GcQPAXiZ1Y77SwL-wwBsvSZhVJbTd9jgOs_ZiPLMo_0zChmHkPUv5F-4Gu7hfWrhuD2AFVLjFKhJwCY6CbR2dYsb_vZlBroCZHg9-sVkBPw1qqRok2SUNdmWuxbWf-JshzaztPuGb0XyfBw&usqp=CAc"
    alt="Escudo do Flamengo"
    width="400">

  <h3>Descrição</h3>
  
  <ul>
    <li>Clube brasileiro do Rio de Janeiro</li>
    <li>Fundado em 1895</li>
    <li>Conhecidos pelas cores <strong>vermelho e preto</strong></li>
    <li>Começou como clube de remo e posteriormente entrou no futebol</li>
  </ul>
  
  <h4>Títulos</h4>
  <ul>
    <li>Mundial Interclubes - <em>1981</em></li>
    <li>Campeonato Brasileiro - <em>8 títulos</em></li>
    <li>Libertadores - <em>1981, 2019, 2022 e 2025</em></li>
    <li>Copa do Brasil - <em>5 títulos</em></li>
    <li>Supercopa do Brasil - <em>2020 e 2021</em></li>
    <li>Campeonato Carioca - <em>38 títulos</em></li>
  </ul>
  
  <p>Os números acima vêm das páginas oficiais do Flamengo</p>

  <h2>Jogadores</h2>
  <p>O elenco oficial lista esses jogadores entre os atuais</p>
  
  <ol>
    <li>Rossi</li>
    <li>Varela</li>
    <li>Alex Sandro</li>
    <li>Léo Ortiz</li>
    <li>De La Cruz</li>
    <li>Luiz Lino</li>
    <li>De Arrascaeta</li>
    <li>Bruno Henrique</li>
    <li>Pedro</li>
    <li>Luiz Araújo</li>
  </ol>

  <table>
    <tr>
      <th>Informação</th>
      <th>Dado</th>
    </tr>
    
    <tr>
      <td>Nome</td>
      <td>Clube de Regatas do Flamengo</td>
    </tr>
    
    <tr>
      <td>Fundação</td>
      <td><em>1895</em></td>
    </tr>
    
    <tr>
      <td>Estádio</td>
      <td>Maracanã</td>
    </tr>
    
    <tr>
      <td>Apelidos</td>
      <td>Mengão/Rubo Negro</td>
    </tr>
  </table>

  <h5>Links</h5>

  <a href="https://www.flamengo.com.br/">Site oficial</a>
  <a href="https://www.flamengo.com.br/clube/titulos">Títulos</a>

</body>
</html>
```

### 19-) Página de restaurante. Crie uma página para um restaurante. Inclua: Nome, Imagem, descrição, cardápio, preços, tabela, endereço fictício e fórmula de reserva.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Restaurante</title>
</head>
<body>

  <h1>Restaurante Cantina Bella Massa</h1>

  <img
    src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRHgUnRQKKR0HUPvEldCkcsOHdehwAcWhjN2NdteiNslg&s=10"
    alt="Dentro do restaurante"
    width="400">

  <h3>Descrição</h3>

  <ul>
    <li>Criador: <strong>Marco Bellinu</strong></li>
    <li>Ano de criação: <strong><em>2018</em></strong></li>
    <li>Restaurante especializado em culinária italiana</li>
    <li>Pratos principais: massas, pizzas, e sobremesas</li>
    <li>Ambiente familiar e atendimento no local</li>
  </ul>
  
  <h3>Cardápio</h3>
  
  <table>
    <tr>
      <th>Prato</th>
      <th>Categoria</th>
      <th>Preço</th>
    </tr>
    
    <tr>
      <td>Pizza Margherita</td>
      <td>Pizza</td>
      <td>R$ 39,90</td>
    </tr>
    
    <tr>
      <td>Pizza Calabresa</td>
      <td>Pizza</td>
      <td>R$ 42,90</td>
    </tr>
    
    <tr>
      <td>Lasanha à Bolonhesa</td>
      <td>Massa</td>
      <td>R$ 38,90</td>
    </tr>
    
    <tr>
      <td>Espaguete à Bolonhesa</td>
      <td>Massa</td>
      <td>R$ 34,90</td>
    </tr>
    
    <tr>
      <td>Nhoque ao Molho</td>
      <td>Massa</td>
      <td>R$ 36,90</td>
    </tr>
    
    <tr>
      <td>Tiramisa</td>
      <td>Sobremesa</td>
      <td>R$ 18,90</td>
    </tr>
    
    <tr>
      <td>Pudim</td>
      <td>Sobremesa</td>
      <td>R$ 12,90</td>
    </tr>
  </table>
  
  <h4>Endereço</h4>
  <p><strong>Cidade:</strong> Campinas-SP, <strong>Bairro: </strong>Cambuí, <strong>Rua/AV:</strong> Avenida Coronel Silva Telles, 514, <strong>CEP: </strong>13024-001</p>


  <h2>Formulário de reserva</h2>

  <form>
    <label for="nome">Nome:</label>
    <input type="text" id="nome"><br><br>

    <label for="email">E-mail:</label>
    <input type="email" id="email"><br><br>

    <label for="tel">Telefone:</label>
    <input type="tel" id="tel"><br><br>

    <label for="dtr">Data de reserva:</label>
    <input type="date" id="dtr"><br><br>

    <label for="qdp">Quantidade de pessoas:</label>
    <input type="number" id="qdp"><br><br>
    
    <select id="mesa">
      <option value="">Selecionar mesa</option>
      <option value="mc">Mesa comum</option>
      <option value="mf">Mesa para família</option>
      <option value="ae">Área externa</option>
    </select><br><br>

    <button type="submit">Reservar mesa</button>
  </form>

</body>
</html>
```

### 20-) Página de loja. Crie uma página de uma loja. Inclua pelo menos 5 produtos. Cada produto deve possuir: nome, imagem, descrição, preço e botão.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Loja PixelZone</title>
</head>
<body>

  <h1>PixelZone</h1>
  <p><strong>Descrição da nossa loja: </strong>Loja de acessórios e periféricos para PC e gamers</p>

  <h3>Produtos</h3>

  <h6>Mouse Gamer</h6>
  
  <img src="https://m.media-amazon.com/images/I/51jXq6Nz2SL._AC_UF894,1000_QL80_FMwebp_.jpg" 
    alt="Mouse gamer"
    width="400">
  
  <p><strong>Descrição: </strong>Mouse iluminação RGB e 6 botões.</p>
  <p><strong>Preço: </strong>R$ 89,90</p>
  
  <button type="button">Adicionar no Carrinho</button><hr>
  
  <h6>Teclado Mecânico RGB</h6>
  
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSypQ5NdQs-uD0CdjdaKWb4lklD6ODbiqR9wiv8Atsaww&s=10" 
    alt="Teclado Mecânico RGB"
    width="400">
  
  <p><strong>Descrição: </strong>Teclado mecânico com iluminação RGB.</p>
  <p><strong>Preço: </strong>R$ 199,90</p>
  
  <button type="button">Adicionar no Carrinho</button><hr>
  
  <h6>Headset Gamer</h6>
  
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQtKp88YVrcHoSeXBx9--ZVaQjP1KF_A4cmJc3_OJeuFg&s=10" 
    alt="Headset Gamer"
    width="400">
  
  <p><strong>Descrição: </strong>Headset com microfone integrado e som estéreo.</p>
  <p><strong>Preço: </strong>R$ 149,90</p>
  
  <button type="button">Adicionar no Carrinho</button><hr>
  
  <h6>Mousepad Gamer Grande</h6>
  
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTOQ1k6tW_Ict1JAg9ITjnuzoeyJS9AgvfnzSnrcFPFZg&s=10" 
    alt="Mousepad Gamer Grande"
    width="400">
  
  <p><strong>Descrição: </strong>Mousepad grande para teclado e mouse.</p>
  <p><strong>Preço: </strong>R$ 79,90</p>
  
  <button type="button">Adicionar no Carrinho</button><hr>
  
  <h6>Webcam Full HD</h6>
  
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQhHcrQQsJ_lSBDEKxg37bSTAYXqosFSFSToDXcleRB9Q&s=10" 
    alt="Webcam Full HD"
    width="400">
  
  <p><strong>Descrição: </strong>Webcam com resolução Full HD para chamadas e gravações</p>
  <p><strong>Preço: </strong>R$ 169,90</p>
  
  <button type="button">Adicionar no Carrinho</button><hr>

</body>
</html>
```


### 21-) Página de cadastro de curso. Crie uma página para inscrição em um curso. O formulário deve pedir: nome, email, idade, telefone, data de nascimento, curso desejado, turno, linguagens que conhece e botão de envio.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cadastro de curso</title>
</head>
<body>

  <h1>Curso de Desenvolvimento de Sistemas</h1>
  <h3>Se inscreva no formulário abaixo</h3>
  <h4>Formulário</h4>

  <form>
    <label for="nome">Nome:</label>
    <input type="text" placeholder="Digite seu nome aqui" id="nome"><br><br>

    <label for="email">E-mail:</label>
    <input type="email" placeholder="Digite seu e-mail aqui" id="email"><br><br>

    <label for="idade">Idade:</label>
    <input type="number" id="idade"><br><br>

    <label for="tel">Telefone:</label>
    <input type="tel" id="tel"><br><br>

    <label for="dtn">Data de nascimento:</label>
    <input type="date" id="dtn"><br><br>

    <label for="cd"><strong>Curso desejado (Desenvolvimento de Sistemas):</strong></label>
    <input type="text" placeholder="Digite (Sim ou Não)" id="cd"><br><br>
    
    <p><strong>Linguagens que conhece:</strong></p>

    <input type="checkbox" id="html" value="html">
    <label for="html">HTML</label>

    <input type="checkbox" id="css" value="css">
    <label for="css">CSS</label>

    <input type="checkbox" id="js" value="JavaScript">
    <label for="js">JavaScript</label>

    <input type="checkbox" id="c#" value="c#">
    <label for="c#">C#</label><br>
    
    <p><strong>Escolha o turno</strong></p>

    <input type="radio" id="manha" name="turno">
    <label for="manha">Manhã</label>

    <input type="radio" id="tarde" name="turno">
    <label for="tarde">Tarde</label>

    <input type="radio" id="noite" name="turno">
    <label for="noite">Noite</label><br><br>

    <button type="submit">Enviar Cadastro</button>
  </form>

</body>
</html>
```

### 22-) Currículo. Crie uma página HTML representando um currículo. Inclua: nome, objetivo, formação, cursos, habilidades, conhecimentos, experiência e contato.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu currículo</title>
</head>
<body>

  <center>
    <h1><em>Currículo<br>Jovem Aprendiz</em></h1>
    <h2>Zé da Manga da Silva</h2>
    
    <h3>Objetivo Profissional (a disposição da empresa)</h3>
    <p>- Ser atendente, ajudante geral ou auxiliar de produção</p>
    
    <h3>Experiência</h3>
    <p>- Nenhuma experiência em mercado de trabalho</p>
    
    <h2>Formação</h2>
    <p>- Cursando o 2°ano do Ensino Médii a tarde (com a possibilidade da troca de horário).</p>
    
    <h3>Cursos/Habilidades/Conhecimentos</h3>
    
    <ul>
      <li>Pacote Office (Word, Excel, PowerPoint) - nível básico</li>
      <li>Inglês Básico</li>
      <li>Conhecimento Básico em Libras</li>
    </ul>
    
    <h3>Contato</h3>
    
    <ul>
      <li>19-989608960</li>
      <li>19-989604989</li>
      <li>84ng12z@gmail.com</li>
    </ul>
  </center>
  
</body>
</html>
```

### 23-) Página de escola. Crie uma página para uma escola fictícia. Inclua: nome da escola, apresentação, cursos, professores, horários, tabela, formulário de contato e links.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Escola Técnica</title>
</head>
<body>

  <h1>Escola Técnica Nova Geração</h1>
  <p><strong>Apresentação: </strong>A Escola Ténica Nova Geração oferece cursos voltados para tecnologia e preparação profissional dos alunos.</p>

  <h4>Cursos</h4>
  
  <ul>
    <li>Desenvolvimento de Sistemas</li>
    <li>Administração</li>
    <li>Eletrônica</li>
    <li>Redes de Computadores</li>
    <li>Design Gráfico</li>
  </ul>

  <h4>Professores</h4>
  
  <ol>
    <li>Carlos Oliveira - Desenvolvimento de Sistemas</li>
    <li>Mariana Santos - Administração</li>
    <li>João Pereira - Eletrônica</li>
    <li>Ana Costa - Redes de Computação</li>
    <li>Lucas Mendes - Design Gráfico</li>
  </ol>

  <h4>Horários</h4>
  
  <ul>
    <li>Desenvolvimento de Sistemas - 13:30 às 17:30</li>
    <li>Administração - 08:00 às 12:00</li>
    <li>Redes de Comoutadores - 13:30 às 17:30</li>
    <li>Eletrônica - 18:30 às 22:30</li>
    <li>Design Gráfico - 08:00 às 12:00</li>
  </ul>
  
  <h4>Tabela de cursos</h4>

  <table>
    <tr>
      <th>Curso</th>
      <th>Professor</th>
      <th>Horário</th>
      <th>Duração</th>
    </tr>
    
    <tr>
      <td>Desenvolvimento de Sistemas</td>
      <td>Carlos Oliveira</td>
      <td>13:30 - 17:30</td>
      <td>2 anos</td>
    </tr>
    
    <tr>
      <td>Administração</td>
      <td>Mariana Santos</td>
      <td>08:00 - 12:00</td>
      <td>1 ano e meio</td>
    </tr>
    
    <tr>
      <td>Eletrônica</td>
      <td>João Pereira</td>
      <td>18:30 - 22:30</td>
      <td>2 anos</td>
    </tr>
    
    <tr>
      <td>Redes de Computadores</td>
      <td>Ana Costa</td>
      <td>13:30 - 17:30</td>
      <td>2 anos</td>
    </tr>
    
    <tr>
      <td>Design Gráfico</td>
      <td>Lucas Mendes</td>
      <td>08:00 - 12:00</td>
      <td>1 ano</td>
    </tr>
  </table>

  <h4>Formulário de Contato</h4>

  <form>
    <label for="nome">Nome:</label>
    <input type="text" placeholder="Ex: João da Silva"id="nome"><br><br>

    <label for="email">E-mail:</label>
    <input type="email" placeholder="Ex: joão@email.com" id="email"><br><br>

    <label for="ass">Assunto:</label>
    <input type="text" placeholder="Informações sobre o curso de interesse" id="ass"><br><br>
    
    <label for="msg">Mensagem</label>
    <textarea id="mensagem"></textarea><br><br>
    
    <button type="submit">Enviar mensagem</button>
  </form>

  <h5><mark>Links</mark></h5>

  <a href="https://www.google.com/url?opi=89978449&q=https://www.instagram.com/senai_nacional/%3Fhl%3Dpt&sa=U&ved=2ahUKEwiYt7iuu-eXAxWhkJUCHUirB_4QFnoECCQQAQ&usg=AOvVaw1dx2sP4eL6PCzNOzLlNdXy">Instagram</a>
  <a href="https://www.google.com/url?opi=89978449&q=https://www.facebook.com/senainacional/&sa=U&ved=2ahUKEwiIjcLNu-eXAxWrpZUCHX6fLwEQFnoECGEQAQ&usg=AOvVaw2oGkjhh9xZuBtp8pg_mhZo">Facebook</a>
  
</body>
</html>
```

### 24-) Página completa. Crie uma página sobre qualquer assunto que você quiser. Usar todas as tags anteriores.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TechZone</title>
</head>
<body>

  <h1>TechZone</h1>
  <p>Tecnologia para jogar, estudar e trabalhar.</p>

  <h2>Sobre a TechZone</h2>

  <ul>
    <li>A TechZone vende computadores, peças e acessórios para jogos, estudos e trabalho.</li>
  </ul><hr>

  <h3>PC Gamer TechZone X1 em <mark>destaque</mark></h3>

  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRRcifdrwNZuCscE8_2HHlUUGaHkxINiS74NB61XBHt0w&s=10" 
    alt="PC Gamer"
    width="400">

  <p>
    <strong>Preço:</strong>
    <del>De: R$ 5.199,99</del><br>
    <strong>Por: </strong>R$ 4.599,00
  </p><hr>

  <h4>Componentes do PC</h4>

  <ul>
    <li>Ryzen 5 7600</li>
    <li>Radeon RX 7600</li>
    <li>16 GB de memória RAM</li>
    <li>Placa-mãe A620</li>
    <li>Fonte de 650W</li>
  </ul><hr>

  <h4>Como comprar</h4>

  <ol>
    <li>Escolha o produto</li>
    <li>Confira as especificações</li>
    <li>Preencha os dados</li>
    <li>Envie o pedido</li>
    <li>Aguarde a confirmação da loja</li>
  </ol><hr>

  <h4>Especificações do TechZone X1</h4>

  <table border="12">
    <tr>
      <th>Componentes</th>
      <th>Modelo</th>
      <th>Informação</th>
    </tr>

    <tr>
      <td>Processador</td>
      <td>Ryzen 5 7600</td>
      <td>6 núcleos/12 threads</td>
    </tr>

    <tr>
      <td>Placa de vídeo</td>
      <td>Radeon RX 7600</td>
      <td>8 GB</td>
    </tr>

    <tr>
      <td>Memória RAM</td>
      <td>DDR5</td>
      <td>16 GB</td>
    </tr>

    <tr>
      <td>Armazenamento</td>
      <td>SSD NVMe</td>
      <td>1 TB</td>
    </tr>

    <tr>
      <td>Placa-mãe</td>
      <td>A620</td>
      <td>AM5</td>
    </tr>

    <tr>
      <td>Fonte</td>
      <td>650W</td>
      <td>80 Plus</td>
    </tr>
  </table><hr>

  <h3>Outros produtos da loja</h3>

  <ul>
    <li>Monitor Gamer 24"</li>
    <li>Teclado mecânico</li>
    <li>Mouse Gamer</li>
    <li>Headset</li>
    <li>SSD NVMe</li>
    <li>Memória RAM</li>
  </ul><hr>

  <h3>Conheça mais sobre hardware</h3>

  <p>
    Consulte um site especializado em tecnologia e hardware.
    <strong>Link parceiro:</strong>
  </p>

  <a href="https://www.techtudo.com.br/">TechTudo</a><hr>

  <h3>Entre em contato conosco através do formulário abaixo:</h3>

  <form>
    <label for="nome"><strong>Nome:</strong></label>
    <input type="text" placeholder="Digite seu nome" id="nome"><br><br>

    <label for="email"><strong>E-mail:</strong></label>
    <input type="email" placeholder="Digite seu e-mail" id="email"><br><br>

    <strong>Produto de Interesse</strong><br><br>

    <input type="radio" name="p" id="pc" value="pc">
    <label for="pc">PC Gamer TechZone X1</label>

    <input type="radio" name="p" id="mg" value="mg">
    <label for="mg">Monitor Gamer 24"</label>

    <input type="radio" name="p" id="tm" value="tm">
    <label for="tm">Teclado mecânico</label>

    <input type="radio" name="p" id="mog" value="mog">
    <label for="mog">Mouse Gamer</label>

    <input type="radio" name="p" id="h" value="h">
    <label for="h">Headset</label>

    <input type="radio" name="p" id="ssd" value="ssd">
    <label for="ssd">SSD NVMe</label>

    <input type="radio" name="p" id="mr" value="mr">
    <label for="mr">Memória RAM</label><br><br>

    <button type="submit">Enviar mensagem</button>
  </form>

</body>
</html>
```

### 25-) Agora faça uma página inteira sozinho. De qualquer tema, com as tags utilizadas.

```HTML
<!DOCTYPE html>
<html lang="pt-BR">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mundo do Futebol</title>
</head>

<body>

  <h1>Mundo do Futebol</h1>

  <p>O futebol é um dos esportes mais populares do mundo. É praticado por milhões de pessoas e envolve técnica, estratégia e trabalho em equipe.</p>

  <img src="https://images.pexels.com/photos/12179593/pexels-photo-12179593.jpeg" 
    alt="Bola de futebol"
    width="400"><hr>

  <h2>Características do futebol:</h2>

  <ul>
    <li>Trabalho em equipe</li>
    <li>Estratégia</li>
    <li>Velocidade</li>
    <li>Comunicação</li>
  </ul><hr>

  <table border="8">
    <tr>
      <th>Competição</th>
      <th>Região</th>
      <th>Periodicidade</th>
    </tr>

    <tr>
      <td>Copa do Mundo</td>
      <td>Mundial</td>
      <td>4 anos</td>
    </tr>

    <tr>
      <td>Brasileirão</td>
      <td>Brasil</td>
      <td>Anual</td>
    </tr>

    <tr>
      <td>Libertadores</td>
      <td>América do Sul</td>
      <td>Anual</td>
    </tr>

    <tr>
      <td>Champions League</td>
      <td>Europa</td>
      <td>Anual</td>
    </tr>
  </table><br><hr>

  <h3>Links</h3>

  <a href="https://www.fifa.com/">FIFA</a>
  <a href="https://www.cbf.com.br/">CBF</a>
  <a href="https://www.uefa.com/">UEFA</a><br><br><hr>

  <h3>Formulário</h3>

  <form>
    <label for="nome">Nome:</label>
    <input type="text" placeholder="Digite seu nome" id="nome"><br><br>

    <label for="email">E-mail:</label>
    <input type="email" placeholder="Digite seu e-mail" id="email"><br><br>

    <strong>Time favorito:</strong><br><br>

    <input type="radio" name="t" id="p" value="p">
    <label for="p">Palmeiras</label>

    <input type="radio" name="t" id="am" value="am">
    <label for="am">Atlético Mineiro</label>

    <input type="radio" name="t" id="b" value="b">
    <label for="b">Bahia</label>

    <input type="radio" name="t" id="f" value="f">
    <label for="f">Flamengo</label>

    <input type="radio" name="t" id="s" value="s">
    <label for="s">Santos</label>

    <input type="radio" name="t" id="c" value="c">
    <label for="c">Corinthians</label><br><br>

    <strong>Competição favorita:</strong><br><br>

    <input type="checkbox" id="brasileirao" value="brasileirao">
    <label for="brasileirao">Brasileirão</label>

    <input type="checkbox" id="copa" value="copa">
    <label for="copa">Copa do Mundo</label>

    <input type="checkbox" id="cl" value="cl">
    <label for="cl">Champions League</label>

    <input type="checkbox" id="l" value="l">
    <label for="l">Libertadores</label><br><br>

    <button type="submit">Enviar opinião</button>
  </form>

</body>
</html>
```