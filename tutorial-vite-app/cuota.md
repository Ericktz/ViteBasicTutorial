# Cuota

Antes de echar un vistazo a las otras funciones dentro de la aplicación Vite, tenemos que echar un vistazo rápido a las Cuotas. A diferencia de las otras blockchains, la moneda nativa de Vite no se utiliza como pago de las transacciones. En su lugar, VITE se utiliza para conseguir Cuota y la Cuota se consume para pagar las transacciones en Vite. Esto hace que las transacciones en Vite sean gratuitas, ya que el VITE bloqueado para Cuota puede ser recuperado sin pérdida alguna.

![](https://1133519882-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FKKudeTJkiGsCkY0t9EYC%2Fuploads%2F8khilyTJZKRUuuRrauPj%2F7.png?alt=media\&token=4459661b-132e-45a0-b575-4a3a676cc9f5)

Para facilitar esto, tendrá que bloquear VITE para la obtención de Cuota. Simplemente vaya a la pestaña VITE y haga clic en "Obtener Cuota". En la nueva pantalla, seleccione el beneficiario de la Cuota. Puedes obtener Cuota para ti o para otra dirección de Vite. A continuación, introduzca la cantidad de VITE que desea bloquear. Tenga en cuenta que el mínimo es de 134 VITE. A continuación, pulse el botón "Enviar para bloquear".&#x20;

El periodo mínimo de bloqueo de VITE es de 3 días. Los VITE bloqueados pueden desbloquearse en cualquier momento después del periodo de 3 días.

![](https://1133519882-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FKKudeTJkiGsCkY0t9EYC%2Fuploads%2FNkeY00pRerg8BbYypw5U%2F8.png?alt=media\&token=a1bb4c9a-d023-461a-a948-f040c15c6c63)

Para encontrar su VITE bloqueado, vaya a "Locking Record" (Registro de Bloqueo) de la parte superior derecha de la página "Obtener Cuota". El Registro de Bloqueo muestra cuánto VITE tienes bloqueado, quién es el beneficiario y cuándo es el momento disponible para desbloquear tu VITE.

![](https://1133519882-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FKKudeTJkiGsCkY0t9EYC%2Fuploads%2FbucCQU7ElcyPzq8phMLe%2F9.png?alt=media\&token=ca87aadf-b29b-4036-942f-02c9fb7b7e4a)

Cada transacción en la cadena Vite requiere Cuota. Se puede obtener Cuota bloqueando VITE como se ha descrito anteriormente, o ejecutando el "Proof of Work", también conocido como PoW y obtener la Cuota necesaria para esa transacción.&#x20;

Cuando los usuarios quieren enviar una transacción sin bloquear VITE o no tienen suficiente Cuota debido a que sólo una pequeña cantidad de VITE está bloqueada, la aplicación Vite tendrá una ventana emergente para notificarle que obtenga Cuota, ya sea ejecutando el PoW o bloqueando VITE. Puedes elegir cualquiera de las dos opciones. Sin embargo, hay un límite diario en el número de veces que un usuario puede ejecutar PoW. Cuando agote su límite (100 transacciones), tendrá que bloquear VITE para realizar más transacciones.

![](https://1133519882-files.gitbook.io/\~/files/v0/b/gitbook-x-prod.appspot.com/o/spaces%2FKKudeTJkiGsCkY0t9EYC%2Fuploads%2FHhCCRe6ZIsttLf7qfg7H%2F10.png?alt=media\&token=0b4559c8-dc47-4ec2-b57b-a78a11597759)

### Reglas de consumo de cuotas

La siguiente tabla enumera el consumo de cuotas de las transacciones más comunes:

| **Tipo de Transacción**                                        | **Cuota Consumida** | **Cantidad Mínima de Bloqueo （VITE）** |
| -------------------------------------------------------------- | ------------------- | ------------------------------------- |
| Enviar una transferencia sin comentarios                       | 1                   | 134                                   |
| Recibir una transacción                                        | 1                   | 134                                   |
| Crear un contrato inteligente                                  | 1.4762              | 267                                   |
| Registrar un SBP                                               | 8                   | 1067                                  |
| Actualizar la dirección de creación de bloques                 | 8                   | 1067                                  |
| Actualizar la dirección de recuperación de recompensas del SBP | 8                   | 1067                                  |
| Cancelar el registro del SBP                                   | 6                   | 534                                   |
| Recuperar las recompensas del SBP                              | 7                   | 934                                   |
| Votar                                                          | 4                   | 534                                   |
| Cancelar votación                                              | 2.5                 | 400                                   |
| Bloquear para Cuota                                            | 5                   | 667                                   |
| Cancelar Bloqueo                                               | 5                   | 667                                   |
| Bloquear para Cuota a través de callback                       | 5.5                 | 800                                   |
| Cancelar bloqueo para Cuota a través de  callback              | 5.5                 | 800                                   |
| Emitir un nuevo token                                          | 9                   | 1200                                  |
| Re-emitir una cantidad adicional de un token                   | 6                   | 800                                   |
| Quemar tokens                                                  | 5.5                 | 800                                   |
| Transferir la propiedad de un token                            | 6.5                 | 934                                   |
| Cambiar el tipo de token                                       | 5.5                 | 800                                   |
| Consultar la información del token.                            | 1.5                 | 267                                   |

Si está interesado en el cálculo de la Cuota, puede consultar este enlace [https://docs.vite.org/vite-docs/reference/quota.html](https://docs.vite.org/vite-docs/reference/quota.html)
