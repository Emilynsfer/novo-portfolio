
# Meu Portfólio Dockerizado

Este projeto é o resultado do desafio da **DIO** para criar e dockerizar uma aplicação web simples utilizando **Nginx** como servidor web.  

A aplicação consiste em um portfólio estático, servido diretamente dentro de um container Docker, garantindo portabilidade, facilidade de deploy e ambiente isolado.

---

## 🚀 Tecnologias e Conceitos Aplicados

- **Docker**: Containerização da aplicação, permitindo execução independente do ambiente local.
- **Nginx (Alpine)**: Servidor web leve e eficiente, ideal para servir conteúdo estático.
- **Dockerfile**: Configuração otimizada para copiar o conteúdo estático para o container.
- Exposição da porta 80 para acesso externo, mapeada para a porta local 8080.

---

## 💡 Como usar

1. Clone este repositório:

```bash
git clone <seu-repositorio-url>
cd <nome-da-pasta>
```

2. Construa a imagem Docker:

```bash
docker build -t meu-portfolio .
```

3. Execute o container:

```bash
docker run -d -p 8080:80 meu-portfolio
```

4. Acesse no navegador:

```
http://localhost:8080
```

---

## 🎯 Objetivo do Desafio

Demonstrar conhecimento prático em containerização com Docker, uso de imagens oficiais otimizadas e configuração básica de servidor web para aplicações estáticas.

---

## 📌 Pontos Fortes

- Simplicidade e eficiência na configuração
- Imagem leve baseada em `nginx:alpine`
- Fácil replicação e deploy em qualquer ambiente com Docker
- Documentação clara para rápida compreensão e uso

---

## 🔗 Links

- Docker Hub (caso subir imagem): [meu-portfolio](http://localhost:8080/)
- DIO: [https://dio.me](https://dio.me)

---

## Contato

Para dúvidas ou sugestões, entre em contato:  
[Linkedin](https://www.linkedin.com/in/emilynsfer013)
