# 💰 FinanSee

Sistema de controle financeiro pessoal com lançamentos, orçamentos, relatórios e um assistente de IA para ajudar a economizar

O FinanSee é uma aplicação web para organizar receitas e despesas do dia a dia. Ele mostra, em gráficos e tabelas, para onde o dinheiro está indo, avisa quando um orçamento está perto do limite e, com a ajuda de IA, sugere formas de economizar sem expor os lançamentos detalhados.

🌐 **Acesse o projeto**

[CLIQUE AQUI PARA ACESSAR O FINANSEE](https://finansee.up.railway.app/)

🔐 **Primeiro acesso**

Crie sua conta na tela de **Cadastrar-se**. Cada pessoa vê apenas os próprios dados.

✨ **Principais funcionalidades**

* 🔐 Cadastro e login com sessão protegida por token JWT.
* 🧾 Lançamentos de receitas e despesas, com edição e exclusão.
* 🏷️ Categorias padrão para despesas e receitas, cada uma com cor própria.
* 🎯 Orçamentos mensais por categoria, com alertas de "perto do limite" e "limite estourado".
* 📊 Dashboard com indicadores do mês, gráfico dos últimos 6 meses e despesas por categoria.
* 📈 Relatórios mensais com comparação entre meses e detalhamento por categoria.
* 🔁 Recorrências para lançamentos que se repetem, como aluguel ou assinaturas.
* 🧠 Análises calculadas a partir dos próprios lançamentos: variações, categorias de maior impacto, anomalias e projeção do saldo do mês.
* 🤖 Assistente de IA para tirar dúvidas sobre os gastos do mês e receber dicas de economia.

🛠️ **Tecnologias utilizadas**

* React, TypeScript, Vite e Tailwind CSS
* Recharts para os gráficos
* Java 21, Spring Boot e Spring Security
* PostgreSQL (Supabase), com migrações versionadas pelo Flyway
* JWT para autenticação
* Groq (API de IA) para o assistente
* Railway para hospedagem

🎯 **Objetivo do projeto**

Desenvolver uma aplicação financeira completa, do banco de dados à interface, com regras de negócio reais, segurança no acesso aos dados e uma integração com IA que respeita a privacidade do usuário, enviando apenas resumos e não os lançamentos detalhados.

Este projeto faz parte da minha evolução na área de Engenharia de Software e representa uma oportunidade de aplicar conhecimentos técnicos em uma aplicação real.

🔒 **Privacidade e segurança**

* Senhas são guardadas com BCrypt, nunca em texto puro.
* Todas as consultas são filtradas pelo usuário autenticado.
* Segredos e chaves ficam em variáveis de ambiente, fora do código.
* O assistente de IA recebe apenas totais por categoria e por mês, sem as descrições dos lançamentos.
