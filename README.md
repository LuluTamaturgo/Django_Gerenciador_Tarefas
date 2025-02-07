<p align="center">
  <a href="https://skillicons.dev">
    <img loading="lazy" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/django/django-plain.svg" width="40" height="40"/>   <img src="https://skillicons.dev/icons?i=python" />
  </a>
</p>

# Gerenciador de Tarefas

 

Uma aplicação web Django para gerenciar suas tarefas de forma eficiente e organizada.

## Descrição

Este projeto é um gerenciador de tarefas desenvolvido com o framework Django. Ele permite criar, visualizar, editar, marcar como concluídas e excluir tarefas. A interface é responsiva e amigável, facilitando o uso em diversos dispositivos.

## Funcionalidades

* **Criação de tarefas:** Adicione títulos, descrições e alarmes para suas tarefas.
* **Listagem de tarefas:** Visualize todas as suas tarefas em uma lista organizada, com status de conclusão e data de criação.
* **Detalhes de tarefas:** Veja informações detalhadas de cada tarefa, incluindo descrição completa e alarme.
* **Edição de tarefas:** Modifique tarefas existentes para atualizar informações ou alterar o status de conclusão.
* **Conclusão de tarefas:** Marque tarefas como concluídas para acompanhar seu progresso.
* **Exclusão de tarefas:** Remova tarefas que não são mais necessárias.


## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

* **Nome do projeto:** `task_manager`
* **Nome da aplicação:** `tasks`
* **Templates:**
    * `base.html`: Template base para todas as páginas, contendo estrutura HTML comum e estilos CSS.
    * `task_detail.html`: Página de detalhes de uma tarefa específica.
    * `task_form.html`: Formulário para criar ou editar tarefas.
    * `task_list.html`: Lista de todas as tarefas.

## Tecnologias Utilizadas

* **Python:** Linguagem de programação principal.
* **Django:** Framework web para desenvolvimento rápido e escalável.
* **HTML:** Linguagem de marcação para estrutura da página.
* **CSS:** Folha de estilos para estilização da interface.

## Como Executar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/LuluTamaturgo/Django_Gerenciador_Tarefas.git](https://github.com/LuluTamaturgo/Django_Gerenciador_Tarefas.git)

2. **Crie um ambiente virtual (opcional, mas recomendado):**
```bash
  python -m venv .venv
````
3. **Ative o ambiente virtual:**
* No Windows:
```bash
.venv\Scripts\activate
````
* No macOS/Linux:
```bash
source .venv/bin/activate
````

4. **Instale as dependências:**
```bash
pip install -r requirements.txt  # Caso tenha um arquivo requirements.txt
```
5. **Migre o banco de dados:**
```bash
python manage.py migrate
```
6. **Execute o servidor de desenvolvimento:**
```bash
python manage.py runserver
```




