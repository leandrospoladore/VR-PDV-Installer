# Histórico de alterações — VR PDV Installer

Este documento registra a evolução do instalador do VR PDV, incluindo funcionalidades, correções e mudanças técnicas.

As alterações são documentadas conforme as informações e evidências disponíveis. Quando não há informações suficientes para confirmar uma mudança, ela não é atribuída a uma versão específica.

## [1.5.1] — Em testes

### Alterações
- Removida a verificação e ativação do .NET Framework 3.5.
- Removidas as chamadas associadas à instalação dos drivers de impressoras Elgin que acionavam essa etapa.

### Comportamento mantido
- Instalação interativa dos drivers de impressoras.
- Instalação e configuração dos componentes previstos pelo instalador, conforme as opções selecionadas.

### Status
Em fase de testes. Ainda não considerada uma versão estável.

## [1.4.9] — Teste em máquina física

### Validação
- Teste em máquina física concluído com resultado satisfatório.
- Foi identificada demora na etapa relacionada ao .NET Framework 3.5.

### Observação
Este registro documenta o resultado do teste. O conjunto completo de alterações introduzidas nesta versão ainda precisa ser recuperado.

## Versões anteriores

As alterações das versões anteriores ainda estão em processo de reconstrução. Os registros serão preenchidos quando houver informações suficientes para confirmar as funcionalidades introduzidas, as correções realizadas e as mudanças de comportamento.

## Convenções

- **Adicionado:** nova funcionalidade ou recurso.
- **Alterado:** modificação de um comportamento existente.
- **Corrigido:** correção de defeito.
- **Removido:** funcionalidade ou etapa retirada.
- **Testes:** validações executadas e respectivos resultados.

