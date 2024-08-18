MARKDOWN:

# Cabeçalho

Negrito:

**Texto em negrito**

__Texto em negrito__


Itálico:

*Texto em itálico*

_Texto em itálico_


Tachado:

~Texto tachado~

Link:

[Google](https://www.google.com.br)

![Logo do GitHub](https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png)



Lista ordenada:

1. Workflows
2. Jobs
3. Steps


Sub tópicos:
1. Item 1
2. Item 2
   1. Subitem
   2. Subitem
3. Item 3


Blocos de código:

```python
def hello_world():
    print("Hello, world!")
```

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

```Dockerfile
FROM nginx:alpine
COPY ./html /usr/share/nginx/html
EXPOSE 80
```


```yaml
workflows:
  jobs:
    steps:
```



Citações:

> Está é uma citação importante

Tabelas:

| Coluna 1 | Coluna 2 | Coluna 3 |
| -------- | -------- | -------- |
| Celula 1 | Celula 2 | Celula 3 |
| Celula 4 | Celula 5 | Celula 6 |


Listas de Tarefas:

- [ ] Tarefa incompleta
- [x] Tarefa completa

Divisores Horizontais:

---
***
___

Referências Automáticas para Links e E-mails:

https://github.com
email@example.com

Ignorar caracteres:

\*Texto não itálico\*


<details>
  <summary>Clique para expandir</summary>
  
  Este texto está oculto até que você clique.
  
</details>
