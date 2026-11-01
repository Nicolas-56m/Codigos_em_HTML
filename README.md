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
```

### 14-) Escolhas. Pegue o formulário do exercício 13 e acrescente: Sexo. Utilize rádio. Linguagens que você conhece: utilize checkbox,  estado: utilize um ```<select>``` com pelo menos 5 estados.

```HTML

```

### 15-) Página do produto. Agora crie uma página para um produto, imagem, descrição, preço, lista com características, tabela com informações, link e botão. 

```HMTL

```

### 16-) Página de filme. Crie uma página sobre um filme. Com título, imagem, descrição, ano, gênero, lista com personagens e link.

```HTML

```

## FASE 3 - Exercícios (Básico-Difícil)
<img src="https://img.shields.io/badge/FEITO NO-VScode-orange">