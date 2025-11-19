# Semana 13: DRF - Detalhando Recursos (GET por ID)

Olá, turma!

Nesta semana, vamos implementar a funcionalidade de detalhamento de recursos utilizando o método GET por ID. Isso permitirá que nossa API forneça informações específicas sobre um recurso solicitado.

---

## 🎯 Objetivos de Aprendizagem

Ao final desta semana, você será capaz de:

* Explicar o conceito de detalhamento de recursos em uma API REST.
* Implementar uma `View` para buscar um recurso específico pelo seu ID.
* Configurar a URL correspondente para acessar o recurso detalhado.
* Testar o endpoint de detalhe utilizando ferramentas como o navegador ou o Postman.

## 📖 Material de Estudo Principal

Todo o conteúdo aprofundado, com exemplos de código que você pode executar e modificar, está no notebook interativo da aula. Clique no link abaixo para abri-lo diretamente no Google Colab.

**[➡️ Abrir o notebook da aula no Google Colab](https://colab.research.google.com/github/heliobentzen/tlp1/blob/main/conteudos/semana-13/aula_semana_13.ipynb)**

---

## 💻 Exercício da Semana: Implementando o Endpoint de Detalhe

Agora que aprendemos a detalhar recursos, é hora de colocar a mão na massa. O objetivo deste exercício é criar um endpoint que retorna os detalhes de um recurso com base no ID fornecido na URL.

### Instruções

1. Crie um novo arquivo Python chamado `views.py` na sua aplicação Django.
2. Dentro deste arquivo, defina uma classe de view chamada `DetalheRecursoView`.
3. Configure a rota correspondente no arquivo `urls.py`.
4. Teste sua implementação utilizando o Postman ou Insomnia.

### Entrega

* Faça o upload do código completo no **AVEA**.