#GridGen

Projeto criado durante o Hackathon Intel na Unicamp em 2012

Trata-se de um gerenciador de grade de horários para eventos e afins.

##Configurando
Para utilizá-lo basta alterar o arquivo assets/www/sample.xml, que segue a seguinte estrutura.
````
<event name="Intel Software Day 2012" dateBegin="05/12/2012" dateEnd="05/12/2012" db="intelsoftwareday">
    <session>
        <date>05/12/2012</date>
        <title>Registro Welcome Coffee</title>
        <description>Credenciamento dos Participantes e Café de boas vindas</description>
        <speaker>None</speaker>
        <location>Auditório principal</location>
        <begin>08:00</begin>
        <end>09:00</end>
    </session>
</event>
````

### Para iniciar modificamos os dos atributos da tag event:

- name (nome do evento)
- dateBegin (data de início)
- dateEnd (data de término)
- db (nome do banco de dados)

### Em seguida, incluir as tegs session de acordo com cada 'momento' do evento:
- date: Data em que ocorrerá a sessão
- title: Título que irá aparecer para o usuário na lista de eventos
- description: Descrição do assunto que será tratado
- speaker: Palestrante
- location: local do evento
- begin / end: horário de início e de término

## Rodando no Eclipse

O projeto já está todo configurado para ser executado no Eclipse, pasta abri-lo como projeto.


