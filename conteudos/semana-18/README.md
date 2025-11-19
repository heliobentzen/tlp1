# Semana 18: Serialização e Listagem de Dados

Olá, turma!

Nesta semana, vamos aprender a serializar os dados do banco e criar o endpoint para listar os recursos disponíveis. Este é um passo fundamental para tornar os dados acessíveis via API.

---

## 🎯 Objetivos de Aprendizagem

Ao final desta semana, você será capaz de:

* Criar um `Serializer` para os `Models` definidos.
* Configurar uma `View` para listar os recursos disponíveis.
* Mapear a URL correspondente para acessar a lista de recursos.
* Testar o endpoint de listagem utilizando ferramentas como o Postman.

---

## 📖 Material de Estudo Principal

O notebook da aula guia você na criação do serializer e na configuração da view de listagem. Siga os passos com atenção!

**[➡️ Abrir o notebook da aula no Google Colab](https://colab.research.google.com/github/heliobentzen/tlp1/blob/main/conteudos/semana-18/aula_semana_18.ipynb)**

---

## 💻 Exercício da Semana: Criando o Endpoint de Listagem

O objetivo desta atividade é colocar em prática a criação de um `Serializer` e de uma `View` para listar os recursos.

### Instruções

1. Siga todos os passos do notebook da aula para criar o `Serializer` no arquivo `api/serializers.py`.
2. Adicione a `View` de listagem no arquivo `api/views.py`.
3. Atualize o arquivo `api/urls.py` para incluir a rota para a view de listagem.
4. Teste o endpoint utilizando o Postman ou a `Browsable API` do DRF.

### Entrega

Para comprovar a conclusão da atividade, você deve entregar **três capturas de tela (prints)**:

1. **Print 1:** Uma captura de tela mostrando o código completo do seu arquivo `api/serializers.py`, com o serializer criado.
2. **Print 2:** Uma captura de tela mostrando o código completo do seu arquivo `api/views.py`, com a view de listagem.
3. **Print 3:** Uma captura de tela da janela do seu navegador mostrando a `Browsable API` do DRF para o endpoint de listagem.

Crie um documento de texto ou PDF, cole os **três prints** solicitados e envie o arquivo na tarefa correspondente no **AVEA**.
