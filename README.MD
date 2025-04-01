# NAND2TETRIS HDL Implementations

Este repositorio contiene implementaciones en lenguaje HDL para los componentes del curso [Nand2Tetris](https://www.nand2tetris.org/). Los componentes implementados abarcan desde la puerta lógica AND hasta el contador de programa (PC).

## Estructura del Repositorio

Los archivos `.hdl` están organizados en carpetas según los capítulos y proyectos del curso. A continuación, se detalla la estructura y la ubicación de cada archivo:

```
├── 01-BasicGates/
│   ├── AND.hdl
│   ├── OR.hdl
│   ├── NOT.hdl
│   ├── XOR.hdl
│   ├── AND16.hdl
│   ├── NOT16.hdl
│   ├── OR8WAY.hdl
│   └── ...
├── 02-ALU/
│   ├── HalfAdder.hdl
│   ├── FullAdder.hdl
│   ├── ADD16.hdl
│   ├── ALU.hdl
│   ├── COMPLEMENTO2.hdl
│   └── ...
├── 03-Memory/
│   ├── RAM8.hdl
│   ├── RAM64.hdl
│   ├── RAM512.hdl
│   ├── RAM4K.hdl
│   ├── RAM16K.hdl
│   ├── Register.hdl
│   ├── BIT.hdl
│   ├── PC.hdl
│   └── ...
├── 04-Multiplexers/
│   ├── MUX.hdl
│   ├── MUX16.hdl
│   ├── MUX4.hdl
│   ├── MUX8.hdl
│   ├── MUX4WAY16.hdl
│   ├── MUX8WAY16.hdl
│   └── ...
├── 05-Demultiplexers/
│   ├── DEMUX.hdl
│   ├── DEMUX16.hdl
│   ├── DEMUX4WAY.hdl
│   ├── DEMUX8WAY.hdl
│   └── ...
```

## Componentes Implementados

### Puertas Lógicas Básicas
- **AND**: `01-BasicGates/AND.hdl` - Implementa la operación lógica AND.
- **OR**: `01-BasicGates/OR.hdl` - Implementa la operación lógica OR.
- **NOT**: `01-BasicGates/NOT.hdl` - Implementa la operación lógica NOT.
- **XOR**: `01-BasicGates/XOR.hdl` - Implementa la operación lógica XOR.
- **AND16**: `01-BasicGates/AND16.hdl` - Implementa la operación lógica AND para 16 bits.
- **NOT16**: `01-BasicGates/NOT16.hdl` - Implementa la operación lógica NOT para 16 bits.
- **OR8WAY**: `01-BasicGates/OR8WAY.hdl` - Implementa la operación lógica OR para 8 entradas.

### ALU (Unidad Aritmética Lógica)
- **HalfAdder**: `02-ALU/HalfAdder.hdl` - Suma dos bits y produce un bit de suma y un bit de acarreo.
- **FullAdder**: `02-ALU/FullAdder.hdl` - Suma tres bits y produce un bit de suma y un bit de acarreo.
- **ADD16**: `02-ALU/ADD16.hdl` - Suma dos números de 16 bits.
- **ALU**: `02-ALU/ALU.hdl` - Implementa operaciones aritméticas y lógicas según los bits de control.
- **COMPLEMENTO2**: `02-ALU/COMPLEMENTO2.hdl` - Calcula el complemento a 2 de un número.

### Memoria
- **RAM8**: `03-Memory/RAM8.hdl` - Memoria de 8 registros.
- **RAM64**: `03-Memory/RAM64.hdl` - Memoria de 64 registros.
- **RAM512**: `03-Memory/RAM512.hdl` - Memoria de 512 registros.
- **RAM4K**: `03-Memory/RAM4K.hdl` - Memoria de 4K registros.
- **RAM16K**: `03-Memory/RAM16K.hdl` - Memoria de 16K registros.
- **Register**: `03-Memory/Register.hdl` - Registro de 16 bits.
- **BIT**: `03-Memory/BIT.hdl` - Implementa un bit de almacenamiento.
- **PC (Program Counter)**: `03-Memory/PC.hdl` - Contador de programa que controla la dirección de la instrucción actual.

### Multiplexores
- **MUX**: `04-Multiplexers/MUX.hdl` - Multiplexor de 2 entradas.
- **MUX16**: `04-Multiplexers/MUX16.hdl` - Multiplexor de 16 bits.
- **MUX4**: `04-Multiplexers/MUX4.hdl` - Multiplexor de 4 entradas.
- **MUX8**: `04-Multiplexers/MUX8.hdl` - Multiplexor de 8 entradas.
- **MUX4WAY16**: `04-Multiplexers/MUX4WAY16.hdl` - Multiplexor de 4 entradas de 16 bits.
- **MUX8WAY16**: `04-Multiplexers/MUX8WAY16.hdl` - Multiplexor de 8 entradas de 16 bits.

### Demultiplexores
- **DEMUX**: `05-Demultiplexers/DEMUX.hdl` - Demultiplexor de 1 a 2 salidas.
- **DEMUX16**: `05-Demultiplexers/DEMUX16.hdl` - Demultiplexor de 16 bits.
- **DEMUX4WAY**: `05-Demultiplexers/DEMUX4WAY.hdl` - Demultiplexor de 1 a 4 salidas.
- **DEMUX8WAY**: `05-Demultiplexers/DEMUX8WAY.hdl` - Demultiplexor de 1 a 8 salidas.

## Progreso

| Componente       | Estado       |
|------------------|--------------|
| Puertas básicas  | ✅ Completado |
| ALU             | ✅ Completado |
| Memoria         | ✅ Completado |
| PC              | ✅ Completado |

## Recursos

- [Sitio oficial de Nand2Tetris](https://www.nand2tetris.org/)