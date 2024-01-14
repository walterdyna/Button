
Guia do Button e Formulário - GitHub

Este repositório é um guia simples e instrutivo sobre o uso de botões (<button>) e formulários (<form>) em HTML. Abaixo, você encontrará informações sobre os principais tipos de botões e suas funções associadas.


Tipos de Botões

Botões em Formulários

Em um formulário HTML, você pode usar botões para realizar ações específicas. Aqui estão alguns exemplos:

<form action="" method="get">
    <button type="submit">Enviar Dados do Formulário</button>
</form>

Este botão, dentro de um formulário, enviará os dados do formulário para o destino especificado na ação do formulário.


Resetar Dados do Formulário:

<form action="" method="get">
    <button type="reset">Resetar Dados do Formulário</button>
</form>

Este botão, dentro de um formulário, limpará todos os campos do formulário, resetando para os valores padrão.


Botões Independentes

Você também pode ter botões independentes sem a necessidade de formulários:


Botão Acionando Ação JavaScript:

<button type="button" onclick="executarAcaoJavaScript()">Ação JavaScript</button>

Este botão executa uma ação específica em JavaScript quando clicado. Substitua "executarAcaoJavaScript()" com a função JavaScript desejada.


Botão Desabilitado:

<button type="button" disabled>Botão Desabilitado</button>

Este botão está inicialmente desabilitado e não pode ser clicado. Você pode habilitá-lo através de JavaScript, por exemplo, quando certa condição for atendida.


Como Contribuir

Sinta-se à vontade para contribuir com este guia! Se você tiver sugestões de melhoria, correções ou adições, siga estes passos:

Faça um fork do repositório.
Crie uma branch para suas alterações: git checkout -b sua-branch
Faça as alterações desejadas.
Commit suas alterações: git commit -m 'Descrição das Alterações'
Faça push para a branch: git push origin sua-branch
Abra um pull request.
Obrigado por contribuir!