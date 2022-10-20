<!-- logo -->
<p align="center">
  <a href="https://starkscan.co">
    <img width='320' src="https://raw.githubusercontent.com/starkscan/starkscan-verifier/main/docs/logo.svg">
  </a>
</p>

<!-- primary badges -->
<p align="center">
  <a href="https://www.npmjs.com/package/starkscan">
    <img src='https://img.shields.io/npm/v/starkscan' />
  </a>
  <a href="https://www.npmjs.com/package/starkscan">
    <img src='https://img.shields.io/npm/dt/starkscan?color=blueviolet' />
  </a>
  <a href="https://github.com/starkscan/starkscan-verifier/blob/main/LICENSE/">
    <img src="https://img.shields.io/badge/license-MIT-black">
  </a>
  <a href="https://github.com/starkscan/starkscan-verifier/stargazers">
    <img src='https://img.shields.io/github/stars/starkscan/starkscan-verifier?color=yellow' />
  </a>
  <a href="https://starkware.co/">
    <img src="https://img.shields.io/badge/powered_by-StarkWare-navy">
  </a>
</p>

<p align="center">
  <img width="360" src="https://raw.githubusercontent.com/starkscan/starkscan-verifier/main/docs/demo.gif" alt="demo" />
</p>

# Nadai Cairo os deja la repo de Starkscan Oficial

Una gran herramienta y muy rápida de usar para verificar contratos.

## ¿Por qué verificar? 

Cualquiera puede cargar cualquier ABI en Starknet y los exploradores de bloques asumirán que es correcto cuando no tiene por qué serlo. La información es engañosa porque es posible cargar una ABI incorrecta. Esto podría potencialmente presentar un riesgo de seguridad al interactuar con contratos no verificados en Starknet. Este verificador te permite verificar el ABI de un contrato en Starknet y confirmar que es correcto. Jonathan Lei mencionó esto en una [publicación comunitaria aquí](https://community.starknet.io/t/remove-abi-from-contract-deployment-request-and-get-code-response/308).

### ¿Qué sucede después de verificar? 

- [Transacciones](https://starkscan.co/txs) y [Eventos](https://starkscan.co/events) se descodifican correctamente en funciones, entradas y salidas legibles por humanos. 
- Ejecutar operaciones de lectura y escritura en el estado del contrato de forma segura y precisa. 
- Los usuarios que miran sus contratos en Starkscan pueden confiar en que toda la información es correcta.

## Primeros pasos 

### Requisitos previos: 

- 🐍 Usuarios de Python que usan [Nile](https://github.com/OpenZeppelin/nile), activen su entorno virtual. 
- 🌟 Usuarios de Protostar, ejecuten `protostar install` antes de ejecutar esta herramienta. 


### Uso

###### npx

```bash
# En el directorio de su proyecto
npx starkscan
```

###### npm

```bash
npm install -g starkscan

# En el directorio de su proyecto
starkscan
```

## Ayuda

- Consultanos en [Twitter](https://twitter.com/starkscanco)

## Licencia

Copyright (c) 2022 Diamond Paws Inc

Licensed under the [AGPL](https://github.com/starkscan/starkscan-verifier/blob/main/LICENSE) license.

## Website

- [Starkscan](https://starkscan.co)
