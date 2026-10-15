FOLHA - PROJETO FRONT-END
Universidade Positivo | Desenvolvimento Front-End para Web | 2026

COMO ABRIR
1. Extraia toda a pasta do arquivo ZIP.
2. Abra o arquivo index.html com um navegador moderno (Chrome, Edge ou Firefox).
3. Mantenha as pastas css, js, img, audio, video e doc no mesmo local.
4. Para navegar, use o menu e os links do rodapé.

A maior parte das funções foi criada para rodar offline. O link externo "RHS" requer internet.
Os dados do meu jardim, favoritos, regas e mensagens de demonstração são guardados no armazenamento local do navegador. O comportamento do armazenamento em páginas file:// pode variar entre navegadores. Para conferir a persistência entre telas no mesmo endereço, também é possível executar um servidor estático local.

EXEMPLO DE SERVIDOR ESTÁTICO, CASO SEJA NECESSÁRIO
Abra um terminal na pasta Folha-Projeto-Web e execute:
python -m http.server 8000
Depois abra http://localhost:8000/ no navegador.
Isso não precisa de internet e não cria um servidor externo.

PÁGINAS
index.html - Início
plantas.html - Catálogo com filtros
planta.html - Ficha individual por ?id=nome
meu-jardim.html - Plantas cadastradas
favoritos.html - Favoritos
agenda.html - Acompanhamento de regas
guia.html - Guia para iniciantes (HTML/CSS/JS puro)
rega.html - Calculadora (HTML/CSS/JS puro)
galeria.html - Galeria
biblioteca.html - Biblioteca e vídeo
sobre.html - Sobre o projeto
contato.html - Formulário demonstrativo

DOCUMENTAÇÃO
Leia doc/Relatorio_Academico_Folha.docx.
Consulte doc/Roteiro_Defesa.txt para estudar a apresentação.

ANTES DE ENTREGAR
- Confirmar com o professor a possibilidade de entrega individual (o enunciado prevê duplas).
- Publicar esta pasta (descompactada) em um repositório público no GitHub.
- Conferir no cronograma da disciplina a data da entrega e da defesa.
- Abrir index.html e percorrer as páginas no computador que será usado na avaliação.

OBSERVAÇÕES
O formulário registra mensagens localmente; não envia e-mail.
A agenda e a calculadora fornecem datas aproximadas de rega, não um diagnóstico do solo.
