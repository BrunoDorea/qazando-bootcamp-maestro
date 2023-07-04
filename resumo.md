# Bootcamp QA Mobile - Maestro

## Pq utilizar?

Tolerância incorpodada à descamação -> Os elementos da interface do usuário nem sempre estarão onde você espera, o toque na tela nem sempre passará, etc. O Maestro abraça a instabilidade dos aplicativos e dispositivos mobiles e tenta combatê-la

Tolerância incorpodada a atrasos -> Não há necessidade de apimentar seus testes com `sleep()` chamadas. O Maestro sabe que pode demorar para carregar o conteúdo (ou seja, pela rede) e o espera automaticamente (mas não mais do que o necessário)

Iteração incrivelmente rápida -> Os testes são interpretados, não há necessidade de compilar nada. O Maestro é capaz de monitorar continuamente seus arquivos de testes e executá-los novamente à medida que mudam.

Sintaxe declarativa, mas poderosa. Defina seus testes em um `.yaml`.

Configuração simples. Maestro é o único binário que funciona em qualquer lugar.

![Alt text](image.png)

## O Maestro tem seu próprio farm?

Maestro Cloud é a maneira mais fácil de executar seus Maestro Flows em CI.
Como seus Flows são executados na nuvem, não há necessidade de configurar nenhum simulador ou emulador de sua parte. Basta carregar seu aplicativo e fluxos por meio de uma de nossas integrações de CI.

### Características

- Suporte Maestro de primeira classe
- Simuladores de iOS gerenciados e emuladores de Android
- Integração de CI simples e inoperante
- Execução de Teste Paralelo
- Prevenção de descamação integrada
- Gravação de Tela
- Saída de Comando Maestro
- Registros de aplicativos

![Alt text](image-1.png)
