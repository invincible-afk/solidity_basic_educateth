# Solidity Básico - Contrato Inteligente "Hola Mundo" 

Este repositorio contiene un contrato inteligente básico en Solidity que almacena y devuelve un mensaje de saludo: **"Hola Mundo"**. El proyecto sirve como una introducción práctica para aquellos que desean iniciarse en la programación de contratos inteligentes en la blockchain de Ethereum.

## Descripción

El contrato inteligente implementado en este repositorio está diseñado para mostrar cómo se pueden almacenar y recuperar datos de la blockchain. Es un ejemplo simple y directo de cómo funciona Solidity y cómo los contratos inteligentes interactúan con la red de Ethereum.

### Características:
- **Almacena un mensaje**: El contrato guarda un mensaje de saludo, que por defecto es "Hola Mundo".
- **Retorna el mensaje**: Permite la recuperación del mensaje almacenado.

Este ejemplo es ideal para principiantes que deseen entender los conceptos básicos de la programación de contratos inteligentes en Ethereum.

## Requisitos

Antes de ejecutar este proyecto, asegúrate de tener instalados los siguientes componentes:

- **Node.js**: [Descargar aquí](https://nodejs.org/)
- **Solidity**: Instalado mediante [Remix](https://remix.ethereum.org/) o cualquier otra herramienta para compilar y desplegar contratos inteligentes en Ethereum.

## Estructura del Contrato
--------------------------------------------------------------------------------------------------------
// SPDX-License-Identifier: MIT

pragma solidity 0.8.24; // en esta parte defino la versión del compilador

// a partir de acá coloco la logica de mi contrato
contract hola_mundo {

    string public saludo ="Hola desde Educateth 2.0"; // declarando el contenido de mi variable saludo

}
--------------------------------------------------------------------------------------------------------
### Explicación:
- **`constructor`**: Se ejecuta una vez al desplegar el contrato y establece el saludo por defecto como "Hola Mundo".
- **`obtenerSaludo`**: Es una función de solo lectura que retorna el mensaje de saludo almacenado.
- **`cambiarSaludo`**: Permite modificar el saludo almacenado en la blockchain.

## Uso

Puedes usar Remix IDE para probar el contrato en una red local o en la red de prueba de Ethereum. Sigue estos pasos para desplegar y probar el contrato:

1. **Abre Remix IDE**: [Remix](https://remix.ethereum.org/)
2. **Copia y pega el código en un nuevo archivo .sol** en Remix.
3. **Compila el contrato** utilizando la versión de Solidity `0.8.0` o superior.
4. **Despliega el contrato** en una red local o de prueba (puedes usar `Injected Web3` para Metamask o la opción de `JavaScript VM` para pruebas locales).
5. **Interactúa con el contrato**: Usa la función `obtenerSaludo` para obtener el mensaje y `cambiarSaludo` para modificarlo.

## Contribuciones

Este proyecto es simple y está diseñado para ayudar a los desarrolladores que están comenzando con Solidity. Si tienes ideas o mejoras, siéntete libre de enviar un Pull Request o abrir un Issue en este repositorio.

## Licencia

Este proyecto está licenciado bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

---

Este archivo `README.md` debería proporcionar una visión clara y fácil de seguir sobre el propósito del proyecto, cómo usarlo y cómo contribuir.
