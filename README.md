# ChainCar 
Es una propuesta de Mejora para la compra y venta de Automoviles, dando una seguridad para las personas que necesitan comprar un automovil y no quieren ser estafados o engañados con los datos del Automovil

UNIVERSIDAD POLITECNICA DE PACHUCA
ESTANCIA I

-------------
## Herramientas a ocupar 
- Solidity
- Remix
- Ganache 
- React
- Hardhat


### 1. Instalacion de las Dependencias:
`$ npm install`

>> Para modificar los SmartContracts se recomienda hacerlo en Remix y pasarlo a el proyecto

### 2. Arranque de la Blockchain de desarrollo local:
`$ npx hardhat node`

### 3. Conectar las cuentas del blockchain de desarrollo a Metamask
- Copiar la clave privada de las direcciones e importarla a Metamask
- Conecta tu metamask al hardhat blockchain, 127.0.0.1:8545.

### 4. Migrar los Smart Contracts a Ganache
`npx hardhat run src/backend/scripts/deploy.js --network ganache`

### 5. Para Ejecutar los Tests
`$ npx hardhat test`

### 6. Lanzar el Frontend Con React
`$ npm run start`
