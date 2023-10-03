## Escrow (Deposito en garantia)
1. **El vendedor, para publicar su oferta, primero deposita los bitcoins que quiere vender en una dirección multisig 2 de 2. Los 2 firmantes son el mismo vendedor y Peach.**  
Peach pre-firma la transacción para liberar los fondos, así que los bitcoins puedan ser liberados por el vendedor, haciendo clic en "Pago recibido".  
2 **Después de 4320 bloques desde el depósito en garantía (alrededor de 30 días), la dirección 2 de 2 se transforma en una dirección de una sola firma controlada por Peach.**  
De esta manera, Peach puedes enviar los fondos al comprador en caso de una controversia con un vendedor malévolo.   
3. **Si la oferta de venta no ha iniciado ninguna correspondencia 15 días después de la financiación del depósito en garantía, la oferta se elimina y el vendedor puede iniciar el proceso de reembolso.**  
Si el vendedor no está disponible en iniciar el proceso de reembolso, Peach puede reembolsar automáticamente la oferta de venta vencida después de 30 días.

## Sistema de reputación
1. **Cada usuario de Peach tiene una calificación reputacional asociada a su cuenta.**  
La calificación reputacional se calcula agregando la calificación recibida desde cada socio comercial más las acciones dentro de la app.  
2. **Las acciones del usuario monitoreadas en la aplicación tienen diferentes pesos e impactos en su puntuación.**  
Ejemplos de acciones monitoreadas incluyen: cancelación de una oferta, cancelación de un match, velocidad a la que paga/confirma el pago, inicio de una disputa, pérdida/ganancia de una disputa. La puntuación general de los usuarios de Peach es de 1 a 5 y se ve reforzada por las etiquetas especial: #SuperTrader (usuario con mas de 20 compraventas), #TraderRapido y #Pioniero.  
3. **Peach puede expulsar a un usuario que se involucre en un comportamiento malicioso.**   
El usuario malintencionado será notificado de la prohibición.  
Peach almacenará el hash de su ID Dispositivo, hash de sus detalles de pago e historial de chat.  

## Uso de sus datos 
1. **La creación de una cuenta de Peach no requiere ninguna información personal.**
Su cuenta de Peach vive en su teléfono, y su contraseña es la clave para descifrar su cuenta. Peach no almacena su contraseña.  
¡Recuerda, sin tu contraseña, no hay aceso a la cuenta de Peach!  
Peach rastrea el hash del ID de dispositivo del usuario para garantizar que un usuario solo puede crear una cuenta de Peach por dispositivo.  
El ID del dispositivo es un identificador único diferente para cada teléfono y aplicación.  
Seguirá siendo el mismo incluso después de que la aplicación se elimine y se vuelva a instalar.  
Las funciones hash se crean para no descifrarse. Por lo tanto, no podemos vincular un ID de dispositivo a la identidad de un usuario, pero podemos sin embargo, asegúrese de que un dispositivo se utiliza para una sola cuenta de Peach y, a continuación, para un solo usuario de Peach.  
2. **Los detalles de pago y la información del chat están encriptados.**  
Solo su socio de intercambio puede leer los datos relevantes para el contrato de intercambio (por ejemplo: su IBAN, su ID de PayPal, etc.), a menos que haya una disputa.  
3. **Realizamos un seguimiento de los análisis para evaluar el rendimiento de la aplicación Peach.**  
Relacionado con el libro de pedidos (volumen, ofertas, intercambios, disputas, etc.)
Relacionado con la calificación reputacional del usuario (Calificación de socio comercial + Acciones del usuario en la aplicación).  
Firebase y Google Analytics. 
Utilizamos un proveedor externo, Zammad, para administrar el sistema de tickets y de disputas.  
