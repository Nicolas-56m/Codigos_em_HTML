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

## FASE 1 - Exercícios (Básico-Intermediário)
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
```

### 8-) Imagem + lista. Pegue o exercício 7 e acrescente uma lista: Característica do animal. (Continuação do exercício 7)!.

```HTML
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

```HMTL

```

### 10-) Tabela. Crie uma tabela com 5 produtos. Ela deverá ter: Produto | Preço | Quantidade. Você precisará aprender: ```<table>```, ```<tr>```, ```<th>``` e ```<td>```.

```HTML

```