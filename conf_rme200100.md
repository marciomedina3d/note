#### Configuração Básica CNC RME200100

Version 1.0.0

------

Após instalado o programa LinuxCNC realize as seguintes configurações:

Localize o icone 'Stepcon'

### `Configurando Stepconf`

[TOC]

#### 1. Primeira Tela : Inicie a configuração de sua máquina

Clique no botão: `Start`

#### 2. Segunda Tela: Criando atalhos

Marque as seguintes caixas de seleção:

- [x] Create a new configuration
- [x] Create a desktop shortcut (symlink) to configuration files.
- [x] Create simulated hardware configuration.

#### 3. Terceira Tela: Informações do equipamento

Altere apenas as configurações a seguir:

Machine Name: `RME200100`

Axis configuration: `XYZ`

Reset Default machine units: `MM`

Driver type: `Kelling 4030`

#### 4. Quarta Tela: Configurando as portas paralelas

Serão usados apenas os pino de 2 à 8:

| Outputs (PC to Mill): | Input (Mill to PC) |
| --------------------- | ------------------ |
| Pin 1: `Unused`       | Pin 10: `Unused`   |
| Pin 2: `X Step`       | Pin 11: `Unused`   |
| Pin 3: `X Direction`  | Pin 12: `Unused`   |
| Pin 4: `Y Step`       | Pin 13: `Unused`   |
| Pin 5: `Y Direction`  | Pin 15: `Unused`   |
| Pin 6: `Z Step`       |                    |
| Pin 7: `Z Direction`  |                    |
| Pin 8: `Unused        |                    |
| Pin 9: `Unused`       |                    |
| Pin 14: `Unused`      |                    |
| Pin 16: `Unused`      |                    |
| Pin 17: `Unused`      |                    |

#### 5. Quinta tela - Opções

Manter a configuração padrão

#### 6. Sexta tela -  Eixo X

Motor steps per revolutio: `200.0`

Driver Microstepping: `10.0`

Pulley teeth (Motor: Leadscrew): `25.0` : `35.0`

Leadscrew Pitch: `125.15` mm/rev

Maximum Velocity: `150.0` mm/s

Maximum Acceleration: `1000.0` mm/s²

Home location: `0.0`

Table travel: `-99999.0` to `99999.0`

#### 7. Sétima tela - Eixo Y

Motor steps per revolutio: `200.0`

Driver Microstepping: `10.0`

Pulley teeth (Motor: Leadscrew): `1.0` : `1.0`

Leadscrew Pitch: `20.04` mm/rev

Maximum Velocity: `100.0` mm/s

Maximum Acceleration: `1000.0` mm/s²

Home location: `0.0`

Table travel: `-99999.0` to `99999.0`

#### 8. Oitava tela - Eixo Z

Motor steps per revolutio: `200.0`

Driver Microstepping: `10.0`

Pulley teeth (Motor: Leadscrew): `12.0` : `35.0`

Leadscrew Pitch: `20.00` mm/rev

Maximum Velocity: `30.0` mm/s

Maximum Acceleration: `300.0` mm/s²

Home location: `0.0`

Table travel: `-99999.0` to `99999.0`

















