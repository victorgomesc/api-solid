# App 

GymPass style app.

## Requisitos funcionais

<lu>
    <li>[ ] - Deve ser possivel se cadastrar;</li>
    <li>[x] - Deve ser possivel se autenticar;</li>
    <li>[x] - Deve ser possivel obter um perfil de um usuario logado;</li>
    <li>[ ] - Deve ser possivel obter o numero de chekins realizado pelo o usuario logado;</li>
    <li>[ ] - Deve ser possivel se o usuario obter seu historico de chekins;</li>
    <li>[ ] - Deve ser possivel ser possivel o usuario buscar academias proximas;</li>
    <li>[ ] - Deve ser possivel ser possivel o usuario realizar chekin em uma academia;</li>
    <li>[ ] - Deve ser validar o chekin de um usuario;</li>
    <li>[ ] - Deve ser possivel cadastrar uma academia;</li>
</lu>

## Regras de negocio

<lu>
    <li>[ ] - O usuario nao pode se cadastrar com um email duplicado;</li>
    <li>[ ] - O usuario nao pode fazer chekin duas vezes no mesmo dia;</li>
    <li>[ ] - O usuario nao pode fazer chekin se nao estiver 100m perto da academia;</li>
    <li>[ ] - O chekin so pode ser validado ate 20 minutos apos criado;</li>
    <li>[ ] - O chekin so pode ser validado por adiministradores;</li>
    <li>[ ] - A cademia so pode ser cadastrada por adiminastradores;</li>
</lu>

## Requisitos nao funcionais

<lu>
    <li>[ ] - A senha do usuario precisa estar criptografada;</li>
    <li>[ ] - os dados da aplicação precisam estar persistindo em um banco de dados PostgreSQL;</li>
    <li>[ ] - toda as listas de dados precisam estar paginadas com 20 items por pagina;</li>
    <li>[ ] - O usuario deve ser identificado por um JWT (json web token);</li>
</lu>