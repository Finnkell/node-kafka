# Micro-serviços com Node.js

- Utilizando Kafka;
- Utilizando Node.js;

## Aplicações

- API principal;
- Geração de certificados;

## Fluxo

- API principal envia uma mensagem para o serviço de certificado para gerar o certificado;
- Micro-serviço de certificado devolve uma resposta (síncrona/assíncrona);

### Se conseguir síncrona/assíncrona

- Receber uma resposta assíncrona de quando o e-mail com o certificado foi enviado;

## O que sabemos?

- REST;
- Redis / RabbitMQ / **Kafka**;
