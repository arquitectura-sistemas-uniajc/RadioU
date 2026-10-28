# Documentación de la Cuenta AWS - Grupo 04

## Valores de referencia del grupo (Sección 15)
- **Nombre de la cuenta:** ASI-G04-RadioU
- **Alias de la cuenta:** asi-g04
- **Dirección de inicio de sesión:** https://asi-g04.signin.aws.amazon.com/console
- **Correo de la cuenta:** nyrodriguez@estudiante.uniajc.edu.co
- **Región de trabajo:** us-east-1 (US East - N. Virginia)
- **Nombre del presupuesto:** presupuesto-G04
- **Tema de notificación SNS:** alertas-costos-G04
- **Monitor de anomalías:** monitor-G04
- **Usuarios creados:** sebastian.rodas (y los demás integrantes)
- **Fecha de vencimiento de los créditos:** 21 de abril de 2027

## Notas técnicas y observaciones
- **Nota sobre CloudWatch (Procedimiento 7):** No fue posible crear las alarmas de facturación en CloudWatch (7.2 y 7.3) porque la nueva interfaz de AWS (2026) no permite habilitar la opción "Receive CloudWatch Billing Alerts" para publicar la métrica `EstimatedCharges`. Se documenta este bloqueo de la interfaz acogiéndonos a la modalidad de observación.
- **Nota sobre usuarios IAM (Procedimiento 4.4):** La interfaz actual de IAM no permitió habilitar el acceso a la consola para los usuarios. El usuario raíz conserva el MFA activo y las credenciales resguardadas.
