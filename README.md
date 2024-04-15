# Sistema de Hospedagem - Desafio .NET

Este projeto faz parte da trilha .NET da DIO (Digital Innovation One) e consiste em um sistema de hospedagem para realizar reservas em um hotel.

## Descrição

O sistema de hospedagem permite que os usuários realizem reservas em um hotel, utilizando as classes `Pessoa`, `Suíte` e `Reserva` para gerenciar as informações relacionadas aos hóspedes, quartos e reservas.

## Funcionalidades

- Cadastrar hóspedes para uma reserva.
- Cadastrar uma suíte para uma reserva.
- Calcular o valor total da reserva, levando em consideração o número de dias reservados e possíveis descontos.

## Classes

### Pessoa

Representa um hóspede do hotel.

#### Atributos
- Nenhum atributo específico foi fornecido no código de exemplo.

### Suíte

Representa um quarto do hotel disponível para reserva.

#### Atributos
- Capacidade: Capacidade máxima de hóspedes que a suíte pode acomodar.
- ValorDiaria: Valor da diária da suíte.

### Reserva

Representa uma reserva de hospedagem no hotel.

#### Atributos
- Hospedes: Lista de hóspedes da reserva.
- Suite: Suíte reservada.
- DiasReservados: Número de dias da reserva.

#### Métodos
- CadastrarHospedes(List<Pessoa> hospedes): Cadastra os hóspedes na reserva.
- CadastrarSuite(Suite suite): Cadastra a suíte na reserva.
- ObterQuantidadeHospedes(): Retorna a quantidade total de hóspedes na reserva.
- CalcularValorDiaria(): Retorna o valor total da reserva, considerando o número de dias reservados e possíveis descontos.

## Diagrama de Classe

![Diagrama de classe do sistema de hospedagem](diagrama_classe_hotel.png)

## Como Contribuir

1. Faça um fork deste repositório.
2. Crie uma branch para sua feature (`git checkout -b feature/nova-feature`).
3. Faça commit de suas alterações (`git commit -am 'Adicionando nova feature'`).
4. Faça push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Autores

- [Seu Nome](https://github.com/seu-usuario) - Desenvolvedor
- [Nome do Colega](https://github.com/usuario-colega) - Colaborador

## Licença

Este projeto está licenciado sob a licença MIT - consulte o arquivo [LICENSE](LICENSE) para obter detalhes.
