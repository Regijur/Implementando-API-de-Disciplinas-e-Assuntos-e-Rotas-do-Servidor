# Implementação de API e Rotas do Servidor

O intuito desse projeto foi o de implementar uma **API** que basicamente retorna para o usuário um **JSON** com algumas disciplinas e assuntos estudados nas mesmas, e o servidor com as implementações das rotas:
* **Get:**
    - No diretório padrão retorna o **JSON** completo
    - No diretório '/disciplines' retorna somente o nome das disciplinas cadastradas
    - No diretório '/:Nome_da_Disciplina' retorna os assuntos estudados pela disciplina passada como parâmetro

* **Post:**
    - No diretório padrão adiciona uma nova disciplina e seus assuntos, que devem ser passadas em um objeto pelo body, não é possível adicionar uma disciplina que já está cadastrada, nem uma disciplina sem passar os conteúdos

* **Put:**
    - No diretório padrão atualiza os assuntos de uma disciplina passada no body, caso a disciplina não exista é retornado um erro


* **Delete:**
    - No diretório '/:Nome_da_Disciplina' deleta a disciplina passada como parâmetro, caso a disciplina não esteja cadastrada retorna erro

Desenvolvido por **Reginaldo Mota (O Régis)**